# Cài đặt, cấu hình Windows Server

Việc nâng cấp Windows Server thành Domain Controller giúp:

- Tạo một hệ thống quản lý tập trung, bảo mật và hiệu quả.

- Đơn giản hóa việc quản lý người dùng, thiết bị và tài nguyên mạng.

- Cung cấp tính sẵn sàng cao và khả năng mở rộng cho hệ thống mạng.

- Hỗ trợ các dịch vụ nâng cao và tuân thủ các yêu cầu pháp lý.

=> Nâng cấp Windows Server thành Domain Controller:

Chuyển sang sử dụng IP tĩnh: 

![img](57)

Add Roles and Features Wizard trong Sever Manager:

![img](58)

Chọn máy chủ đích:

![img](59)

Chọn Active Directory Domain Services:

![img](60)

Cài đặt role cho phép nâng cấp thành Domain Controller:

![img](61)

Đặt tên Root domain name là PDT181.it:

![img](62)

Đặt mật khẩu: 

![img](63)

Đặt tên cho NetBIOS domain:

![img](64)

Cài đặt: 

![img](65)

Nâng cấp Domain thành công:

![img](66)

=> Cấu hình máy trạm Windows7 gia nhập vào domain vừa tạo được

Máy Windows 7 gia nhập domain: 

![img](67)

=> Cài đặt Web Server và FTP Server

Truy cập Add Roles and Features Wizard trên Windows Server: 

![img](68)

Cài đặt thành công Web Server (IIS):

![img](69)

Chọn FTP Server trong Web Sever:

![img](70)

Mở IIS Manager: 

![img](71)

Thêm FTP Site: 

![img](72)

Cấu hình FTP Site: 

![img](73)

![img](74)

Tạo file tên ftpsharing trên Windows Server:

![img](75)

=> Máy Windows 7 truy cập được vào file ftpsharing:

![img](76)

=> Cài đặt Remote Desktop Users

Trên Windows Server, cài đặt Remote Desktop Services: 

![img](77)

Enabled thành công Remote Desktop:

![img](78)

Điều khiển Windows Server thành công từ máy Windows 7:

![img](79)

PsTools là một bộ công cụ mạnh mẽ giúp quản trị viên quản lý, giám sát và khắc phục sự cố trên các hệ thống Windows cục bộ và từ xa. Nó đặc biệt hữu ích trong các môi trường mạng lớn, nơi cần tự động hóa và quản lý tập trung.

=>  Cài đặt Pstools

Cài đặt pstools vào ổ C máy Windows 7:

![img](80)

Kết nối thành công từ windows 7 sang windows sever:

![img](81)

Xem systeminfo bên máy windows 7:

![img](82)

Xem systeminfo bên máy windows sever:

![img](83)







