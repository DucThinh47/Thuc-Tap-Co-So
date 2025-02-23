# Cài đặt, cấu hình Ubuntu Server

- Cài đật dịch vụ ssh, sau khi cài đặt kiểm tra dịch vụ đang hoạt động: 

![img](https://github.com/DucThinh47/Thuc-Tap-Co-So/blob/main/images/image42.png?raw=true)

- Cài đặt chương trình Putty trên máy trạm Windows. Sử dụng chương trình này để truy cập vào máy ubuntu server thông qua ssh.

Chương trình Putty trên máy Windows 7: 

![img](https://github.com/DucThinh47/Thuc-Tap-Co-So/blob/main/images/image43.png?raw=true)

- Trên máy windows 7, nhập login và password và kết nối với máy Ubuntu: 

![img](https://github.com/DucThinh47/Thuc-Tap-Co-So/blob/main/images/image44.png?raw=true)

- Cài đặt và cấu hình dịch vụ chia sẻ file Samba trên máy Ubuntu. 

    *Samba là một phần mềm mã nguồn mở cho phép chia sẻ tập tin và thư mục giữa các hệ thống khác nhau*

![img](https://github.com/DucThinh47/Thuc-Tap-Co-So/blob/main/images/image45.png?raw=true)

- Thêm user mới có tên pdt1: 

![img](https://github.com/DucThinh47/Thuc-Tap-Co-So/blob/main/images/image46.png?raw=true)

- Ánh xạ tên user Samba sang tên user hệ thống: 

![img](https://github.com/DucThinh47/Thuc-Tap-Co-So/blob/main/images/image47.png?raw=true)

- Chia sẻ folder (sharing samba) của user tạo được: 

Cấu hình samba: 

![img](https://github.com/DucThinh47/Thuc-Tap-Co-So/blob/main/images/image48.png?raw=true)

- Truy cập từ máy trạm Windows 7 vào folder tạo được: 

![img](https://github.com/DucThinh47/Thuc-Tap-Co-So/blob/main/images/image49.png?raw=true)

File bên máy Ubuntu: 

![img](https://github.com/DucThinh47/Thuc-Tap-Co-So/blob/main/images/image50.png?raw=true)

SELinux (Security-Enhanced Linux) là một cơ chế bảo mật tích hợp vào nhân Linux, được phát triển bởi NSA (Cơ quan An ninh Quốc gia Hoa Kỳ) cùng với các cộng tác viên mã nguồn mở. Nó cung cấp một lớp bảo mật bổ sung bằng cách áp dụng các chính sách kiểm soát truy cập bắt buộc (MAC - Mandatory Access Control) trên hệ thống.

- Cài đặt và cấu hình SELinux: 

![img](https://github.com/DucThinh47/Thuc-Tap-Co-So/blob/main/images/image51.png?raw=true)

![img](https://github.com/DucThinh47/Thuc-Tap-Co-So/blob/main/images/image52.png?raw=true)

![img](https://github.com/DucThinh47/Thuc-Tap-Co-So/blob/main/images/image53.png?raw=true)

Các chế độ hoạt động của SELinux:

- Enforcing: Chế độ mặc định, SELinux áp dụng các chính sách và từ chối các hành động vi phạm.

- Permissive: SELinux ghi nhận các vi phạm chính sách nhưng không từ chối chúng. Chế độ này hữu ích cho việc gỡ lỗi.

- Disabled: SELinux bị vô hiệu hóa hoàn toàn.

Cấu hình SELinux: 

![img](https://github.com/DucThinh47/Thuc-Tap-Co-So/blob/main/images/image54.png?raw=true)

Sử dụng semanage thêm giao thức TCP chạy trên cổng 992 và cổng dịch vụ FTP: 

![img](https://github.com/DucThinh47/Thuc-Tap-Co-So/blob/main/images/image55.png?raw=true)

Bên máy Windows 7: 

![img](https://github.com/DucThinh47/Thuc-Tap-Co-So/blob/main/images/image56.png?raw=true)

