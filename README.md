![bandicam 2025-09-05 10-39-59-870](https://github.com/user-attachments/assets/ed74c987-f30c-42a9-a60f-cb746bc76f7e)# SFML Code::blocks

## Dowload
- [link web](https://www.sfml-dev.org/download/sfml/2.6.2/)
- Chọn WinLibs MSVCRT 13.1.0 (64-bit) và GCC 13.1.0 MinGW (SEH) - 64-bit
- Nếu link chết thì tải ở WinLibs MSVCRT [ở đây](https://www.mediafire.com/file/vtvwodyvrixfkqs/SFML-2.6.2-windows-gcc-13.1.0-mingw-64-bit.zip/file) và GCC MinGW (SEH) [ở đây](https://www.mediafire.com/file/mkqeqp5nymzxwxv/winlibs-x86_64-posix-seh-gcc-13.1.0-mingw-w64msvcrt-11.0.0-r5.7z/file)

## Setup
- Cài codeblocks, sau đó giải nén 2 file:

![bandicam 2025-09-05 09-46-16-118](https://github.com/user-attachments/assets/a61f62a3-6503-4063-963b-d6b0ae8fc5c5)

- Giải nén xong sẽ như này:

 ![bandicam 2025-09-05 09-48-13-638](https://github.com/user-attachments/assets/aa7181e1-95cc-4367-9bb1-096e467219a3)

- Mở codeblocks lên, khi tạo 1 project mới, lướt xuống dưới sẽ thấy:

![bandicam 2025-09-05 09-53-03-625](https://github.com/user-attachments/assets/3e2dd9c8-e7ef-42e8-b6b8-41ba812e814f)

- Mình sẽ không chọn cái này vì nó là bản lỗi thời rồi, không có nhiều cái hỗ trợ như bản trên, vậy nên cứ tạo 1 project mới như bình thường:

![bandicam 2025-09-05 09-56-03-655](https://github.com/user-attachments/assets/ba647f9c-f670-420e-b759-d2ac36298498)

- Hãy chắc chắn rằng chương trình mặc định build + compiler thành công:

![bandicam 2025-09-05 10-03-08-154](https://github.com/user-attachments/assets/3800eb7a-520e-4e50-9a8f-3dc6132afe91)

- Sau đó vào setting:

![bandicam 2025-09-05 10-20-04-452](https://github.com/user-attachments/assets/787e8d81-99f7-4bb3-b58e-6007f3c3bfd2)

- Sau đó chọn:

![bandicam 2025-09-05 10-21-17-860](https://github.com/user-attachments/assets/feecb7e0-9470-4db6-b54b-e14b4af930f6)

- Sau đó chọn

![bandicam 2025-09-05 10-22-48-819](https://github.com/user-attachments/assets/c33424ac-a3a7-4111-a3a7-fb0b7626beaf)

- Sau đó chọn thay đổi lại đường dẫn cho mingw64 rồi nhấn ok:

![bandicam 2025-09-05 10-24-02-279](https://github.com/user-attachments/assets/454d8d40-8113-46e1-9445-e4b1c131fb76)

- Sau đó build + run lại để xác nhận ok:

![bandicam 2025-09-05 10-26-25-622](https://github.com/user-attachments/assets/a062c105-cb1e-4f36-b052-bec24010b17c)

- Sau đó chú ý đến tên project ở dưới workspace:

![bandicam 2025-09-05 10-28-01-890](https://github.com/user-attachments/assets/96b205ef-e456-4896-85d2-59aa157cf0ed)

- Tiếp đó chọn Build options...

![bandicam 2025-09-05 10-29-20-022](https://github.com/user-attachments/assets/5aaa52fe-15d4-4788-bc66-5fd5caaf8ae5)

- Mặc định nó sẽ ở mục debug:

![bandicam 2025-09-05 10-30-46-546](https://github.com/user-attachments/assets/d647fd93-a91a-43d6-917e-de4362b930c1)

- Giờ sẽ chuyển sang mục bao quát nhất cho cả 2 thằng này là mục trên cùng:

![bandicam 2025-09-05 10-32-09-124](https://github.com/user-attachments/assets/d6d0c90f-33b8-414b-a82e-0c4c23913b3a)

- Sau đó chọn mục Search directories

![bandicam 2025-09-05 10-32-37-879](https://github.com/user-attachments/assets/ea26562b-5881-479b-ba0c-7924a2ce580b)

- Sau đó, chỉnh sửa lại đường dẫn cho mục compiler, chọn mục include:

![bandicam 2025-09-05 10-35-08-727](https://github.com/user-attachments/assets/db93ba4a-ba38-4d25-b48b-4575baf7a425)

- Tiếp:

![bandicam 2025-09-05 10-35-57-887](https://github.com/user-attachments/assets/be09a164-0dce-441f-a12b-5e4bc5879f2c)

- Tiếp đó chọn no rồi ok, ok...

![bandicam 2025-09-05 10-37-05-858](https://github.com/user-attachments/assets/e89c3bc2-9a22-40c7-a3f3-81c4f745548e)

- Tương tự với linker bên cạnh nhưng chọn mục lib:

![bandicam 2025-09-05 10-38-54-129](https://github.com/user-attachments/assets/22103cd4-2b3a-4f01-b8a9-a3a4bb3a0359)

- Ok, giờ chuyển sang mục debug:

![bandicam 2025-09-05 10-39-59-870](https://github.com/user-attachments/assets/b237f425-061c-4314-b3f7-57997094d314)

- Tiếp tục với mục này thì vào phần linker setting, thêm các mục sau vào rồi nhấn ok (nhớ gõ phải đúng từng ký tự):

![bandicam 2025-09-05 10-41-51-515](https://github.com/user-attachments/assets/bd951c70-adf9-4843-853c-6791e1be3c2a)

- Nếu có cả release thì thêm như này:

![bandicam 2025-09-05 10-42-54-275](https://github.com/user-attachments/assets/4a63860a-53c6-42ee-ad16-2dd778eabbbe)

- Sau đó, bước cuối cùng để chạy được đồ họa thì cần phải chạy được các phần hỗ trợ cho chương trình hoạt động về đồ họa:

![bandicam 2025-09-05 10-44-41-349](https://github.com/user-attachments/assets/d2ed28d3-1a9c-4fd2-8dcf-77b5c6ac491d)

- Sau đó, copy toàn bộ:

![bandicam 2025-09-05 10-45-19-986](https://github.com/user-attachments/assets/eb0e5401-6b17-4abe-8ce9-36e942debf15)

- Sau đó vào mục có chứa file .exe:

![bandicam 2025-09-05 10-46-10-333](https://github.com/user-attachments/assets/c5afb602-dd7e-422f-a137-f3d471911db0)

- Paste vào:

![bandicam 2025-09-05 10-47-01-441](https://github.com/user-attachments/assets/2793af1a-3f3a-45df-a6b4-ae4ff16d3b41)

- Cuối cùng chạy thử với code test mẫu sau:

```cpp
#include <SFML/Graphics.hpp>

int main()
{
    sf::RenderWindow window(sf::VideoMode(200, 200), "SFML works!");
    sf::CircleShape shape(100.f);
    shape.setFillColor(sf::Color::Green);

    while (window.isOpen())
    {
        sf::Event event;
        while (window.pollEvent(event))
        {
            if (event.type == sf::Event::Closed)
                window.close();
        }

        window.clear();
        window.draw(shape);
        window.display();
    }

    return 0;
}

```

![bandicam 2025-09-05 10-48-41-205](https://github.com/user-attachments/assets/e154f4fe-b135-4e9f-844b-c2f133313552)




