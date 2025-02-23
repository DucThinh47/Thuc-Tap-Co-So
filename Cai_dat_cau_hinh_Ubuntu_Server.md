# Cài đặt, cấu hình Ubuntu Server

- Cài đật dịch vụ ssh, sau khi cài đặt kiểm tra dịch vụ đang hoạt động: 

![img](42)

- Cài đặt chương trình Putty trên máy trạm Windows. Sử dụng chương trình này để truy cập vào máy ubuntu server thông qua ssh.

Chương trình Putty trên máy Windows 7: 

![img](43)

- Trên máy windows 7, nhập login và password và kết nối với máy Ubuntu: 

![img](44)

- Cài đặt và cấu hình dịch vụ chia sẻ file Samba trên máy Ubuntu. 

    *Samba là một phần mềm mã nguồn mở cho phép chia sẻ tập tin và thư mục giữa các hệ thống khác nhau*

![img](45)

- Thêm user mới có tên pdt1: 

![img](46)

- Ánh xạ tên user Samba sang tên user hệ thống: 

![img](47)

- Chia sẻ folder (sharing samba) của user tạo được: 

Cấu hình samba: 

![img](48)

- Truy cập từ máy trạm Windows 7 vào folder tạo được: 

![img](49)

File bên máy Ubuntu: 

![img](50)

- Cài đặt và cấu hình SELinux: 

![img](51)

![img](52)

![img](53)

Cấu hình SELinux: 

![img](54)

Sử dụng semanage thêm giao thức TCP chạy trên cổng 992 và cổng dịch vụ FTP: 

![img](55)

Bên máy Windows 7: 

![img](56)




