# Cài đặt, cấu hình Windows Server

Việc nâng cấp Windows Server thành Domain Controller giúp:

- Tạo một hệ thống quản lý tập trung, bảo mật và hiệu quả.

- Đơn giản hóa việc quản lý người dùng, thiết bị và tài nguyên mạng.

- Cung cấp tính sẵn sàng cao và khả năng mở rộng cho hệ thống mạng.

- Hỗ trợ các dịch vụ nâng cao và tuân thủ các yêu cầu pháp lý.

=> Nâng cấp Windows Server thành Domain Controller:

Chuyển sang sử dụng IP tĩnh: 

![img](https://github.com/DucThinh47/Thuc-Tap-Co-So/blob/main/images/image57.png?raw=true)

Add Roles and Features Wizard trong Sever Manager:

![img](https://github.com/DucThinh47/Thuc-Tap-Co-So/blob/main/images/image58.png?raw=true)

Chọn máy chủ đích:

![img](https://github.com/DucThinh47/Thuc-Tap-Co-So/blob/main/images/image59.png?raw=true)

Chọn Active Directory Domain Services:

![img](https://github.com/DucThinh47/Thuc-Tap-Co-So/blob/main/images/image60.png?raw=true)

Cài đặt role cho phép nâng cấp thành Domain Controller:

![img](https://github.com/DucThinh47/Thuc-Tap-Co-So/blob/main/images/image61.png?raw=true)

Đặt tên Root domain name là PDT181.it:

![img](https://github.com/DucThinh47/Thuc-Tap-Co-So/blob/main/images/image62.png?raw=true)

Đặt mật khẩu: 

![img](https://github.com/DucThinh47/Thuc-Tap-Co-So/blob/main/images/image63.png?raw=true)

Đặt tên cho NetBIOS domain:

![img](https://github.com/DucThinh47/Thuc-Tap-Co-So/blob/main/images/image64.png?raw=true)

Cài đặt: 

![img](https://github.com/DucThinh47/Thuc-Tap-Co-So/blob/main/images/image65.png?raw=true)

Nâng cấp Domain thành công:

![img](https://github.com/DucThinh47/Thuc-Tap-Co-So/blob/main/images/image66.png?raw=true)

=> Cấu hình máy trạm Windows7 gia nhập vào domain vừa tạo được

Máy Windows 7 gia nhập domain: 

![img](https://github.com/DucThinh47/Thuc-Tap-Co-So/blob/main/images/image67.png?raw=true)

=> Cài đặt Web Server và FTP Server

Truy cập Add Roles and Features Wizard trên Windows Server: 

![img](https://github.com/DucThinh47/Thuc-Tap-Co-So/blob/main/images/image68.png?raw=true)

Cài đặt thành công Web Server (IIS):

![img](https://github.com/DucThinh47/Thuc-Tap-Co-So/blob/main/images/image69.png?raw=true)

Chọn FTP Server trong Web Sever:

![img](https://github.com/DucThinh47/Thuc-Tap-Co-So/blob/main/images/image70.png?raw=true)

Mở IIS Manager: 

![img](https://github.com/DucThinh47/Thuc-Tap-Co-So/blob/main/images/image71.png?raw=true)

Thêm FTP Site: 

![img](https://github.com/DucThinh47/Thuc-Tap-Co-So/blob/main/images/image72.png?raw=true)

Cấu hình FTP Site: 

![img](https://github.com/DucThinh47/Thuc-Tap-Co-So/blob/main/images/image73.png?raw=true)

![img](https://github.com/DucThinh47/Thuc-Tap-Co-So/blob/main/images/image74.png?raw=true)

Tạo file tên ftpsharing trên Windows Server:

![img](https://github.com/DucThinh47/Thuc-Tap-Co-So/blob/main/images/image75.png?raw=true)

=> Máy Windows 7 truy cập được vào file ftpsharing:

![img](https://github.com/DucThinh47/Thuc-Tap-Co-So/blob/main/images/image76.png?raw=true)

=> Cài đặt Remote Desktop Users

Trên Windows Server, cài đặt Remote Desktop Services: 

![img](https://github.com/DucThinh47/Thuc-Tap-Co-So/blob/main/images/image77.png?raw=true)

Enabled thành công Remote Desktop:

![img](https://github.com/DucThinh47/Thuc-Tap-Co-So/blob/main/images/image78.png?raw=true)

Điều khiển Windows Server thành công từ máy Windows 7:

![img](https://github.com/DucThinh47/Thuc-Tap-Co-So/blob/main/images/image79.png?raw=true)

PsTools là một bộ công cụ mạnh mẽ giúp quản trị viên quản lý, giám sát và khắc phục sự cố trên các hệ thống Windows cục bộ và từ xa. Nó đặc biệt hữu ích trong các môi trường mạng lớn, nơi cần tự động hóa và quản lý tập trung.

=>  Cài đặt Pstools

Cài đặt pstools vào ổ C máy Windows 7:

![img](https://github.com/DucThinh47/Thuc-Tap-Co-So/blob/main/images/image80.png?raw=true)

Kết nối thành công từ windows 7 sang windows sever:

![img](https://github.com/DucThinh47/Thuc-Tap-Co-So/blob/main/images/image81.png?raw=true)

Xem systeminfo bên máy windows 7:

![img](https://github.com/DucThinh47/Thuc-Tap-Co-So/blob/main/images/image82.png?raw=true)

Xem systeminfo bên máy windows sever:

![img](https://github.com/DucThinh47/Thuc-Tap-Co-So/blob/main/images/image83.png?raw=true)







