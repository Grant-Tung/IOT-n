🔒 Dự án IOT-N: Hệ thống Vault Bảo mật (Secure Vault & Receiver)
Chào mừng bạn đến với kho lưu trữ mã nguồn của dự án IOT-N (Báo cáo môn học - Nhóm 15). Đây là một hệ thống thiết bị phần cứng IoT tập trung vào bảo mật, được xây dựng trên nền tảng vi điều khiển ESP32/Arduino nhằm mục đích mã hóa và lưu trữ an toàn các thông tin cá nhân nhạy cảm.

🌟 Tính năng nổi bật
Lưu trữ đa dạng: Hỗ trợ lưu trữ an toàn Thông tin đăng nhập (Logins), Thẻ tín dụng (Credit Cards), Ghi chú (Notes) và Số điện thoại (Phone Numbers).

Bảo mật đa lớp siêu cấp: Dữ liệu được mã hóa xếp chồng qua hàng loạt các thuật toán mạnh mẽ: AES-256, 3DES, Blowfish, Serpent kết hợp cùng hàm băm SHA-512 và thuật toán xác thực tính toàn vẹn HMAC-SHA256.

Giao tiếp không dây nội bộ: Sử dụng giao thức ESP-NOW để truyền dữ liệu đã mã hóa giữa thiết bị Vault và thiết bị nhận (Receiver) một cách tức thời, không phụ thuộc vào mạng Wi-Fi hay kết nối Internet bên ngoài.

Giao diện trực quan: Tích hợp màn hình hiển thị TFT trực tiếp, hỗ trợ menu đồ họa và thao tác nhập liệu độc lập thông qua núm xoay (Encoder) hoặc Serial Terminal/bàn phím.

Hệ thống tệp tin nhúng: Dữ liệu mã hóa được ghi trực tiếp vào bộ nhớ Flash của vi điều khiển thông qua hệ thống tệp SPIFFS/LittleFS.

📂 Cấu trúc Repository
/Firmware_for_vault/: Chứa mã nguồn gốc (.ino, .cpp, .h) của thiết bị Vault chính (quản lý giao diện hiển thị, nhận lệnh điều khiển, lưu trữ và thực thi các thuật toán mã hóa).

Vault Circuit Diagram.png: Sơ đồ nối dây mạch điện tử của toàn bộ hệ thống.

Reports_Group15_IOT.docx: Tệp tài liệu báo cáo đồ án chi tiết của Nhóm 15.

/extra/: Các tệp tài nguyên mở rộng, chẳng hạn như ảnh nền tĩnh dùng cho khóa màn hình (Dallas, Denver, Miami, v.v.).

/Untested RNG/: Công cụ tạo số ngẫu nhiên dự phòng hoặc đang trong quá trình thử nghiệm.

/Copyright Notices/ & LICENSE: Giấy phép và thông tin bản quyền của các thư viện mã nguồn mở được dùng trong dự án (như AES, Blowfish, DES, ESP-NOW tutorial, v.v.).
