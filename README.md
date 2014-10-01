screen-command-linux
====================

Hướng dẫn sử dụng lệnh screen trong Linux

### Giới thiệu

*Screen* hiểu nôm na là một câu lệnh cho phép chúng ta quản lý các kết nối SSH tới server Linux bằng các phím tắt trên cùng một cửa sổ console, đồng thời nó cũng cho phép giữ một cửa sổ (một câu lệnh) làm việc liên tục mặc cho việc kết nối từ SSH client bị ngắt.

Các chức năng của *screen*

- Quản lý các phiên làm việc từ xa (SSH)
- Không giới hạn các cửa sổ làm việc
- Copy, paste giữa các cửa sổ
- Phân chia các cửa sổ làm việc
- Khóa cửa sổ làm việc
- ...

### Cách sử dụng Screen

Để sử dụng lệnh screen ta có thể sử dụng trên chính terminal của máy chủ hoặc trên SSH client (Putty, Secure Crt,...)

Trên các terminal này ta sử dụng lệnh

    screen

Sau đó màn terminal sẽ vào *screen* mode, hình sau sẽ hiện ra

<img src=>

Lúc này ta có thể thao tác với các terminal bằng screen

