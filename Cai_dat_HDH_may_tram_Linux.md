# Cài đặt hệ điều hành máy trạm Linux

**Làm quen một số lệnh cơ bản sau khi cài đặt máy trạm**: 

- ***sudo***: dùng để thực thi một lệnh với quyền root (superuser):

![img](https://github.com/DucThinh47/Thuc-Tap-Co-So/blob/main/images/image16a.png?raw=true)

- ***update***: cập nhật thông tin về các gói phần mềm mới nhất:

![img](https://github.com/DucThinh47/Thuc-Tap-Co-So/blob/main/images/image17.png?raw=true)

- ***upgrade***: nâng cấp các gói phần mềm đang cài đặt lên phiên bản mới nhất:

![img](https://github.com/DucThinh47/Thuc-Tap-Co-So/blob/main/images/image18.png?raw=true)

- ***pwd***: Hiển thị đường dẫn thư mục hiện tại (print working directory):

![img](https://github.com/DucThinh47/Thuc-Tap-Co-So/blob/main/images/image19.png?raw=true)

- ***ls***: Liệt kê các file và thư mục trong thư mục hiện tại (list):

![img](https://github.com/DucThinh47/Thuc-Tap-Co-So/blob/main/images/image20.png?raw=true)

- ***man***: Hiển thị hướng dẫn sử dụng một số lệnh cụ thể, ví dụ xem hướng dẫn sử dụng lệnh cp: 

![img](https://github.com/DucThinh47/Thuc-Tap-Co-So/blob/main/images/image21.png?raw=true)

- ***PS1***: biến môi trường để cấu hình định dạng của dấu nhắc lệnh, format lệnh: 

    ***PS1="\[\033[màu trc\]\u@\h:\w\$\[\033[màu sau\]"***

![img](https://github.com/DucThinh47/Thuc-Tap-Co-So/blob/main/images/image22.png?raw=true)

- ***mkdir***: Tạo một thư mục mới (make directory), ví dụ tạo thư mục Thinh181:

![img](https://github.com/DucThinh47/Thuc-Tap-Co-So/blob/main/images/image23.png?raw=true)

- ***cd***: Di chuyển đến thư mục khác:

![img](https://github.com/DucThinh47/Thuc-Tap-Co-So/blob/main/images/image24.png?raw=true)

- ***cp***: Sao chép một file hoặc thư mục sang một vị trí khác (copy), ví dụ copy thư mục Thinh181 sang /home/ptit: 

![img](https://github.com/DucThinh47/Thuc-Tap-Co-So/blob/main/images/image25.png?raw=true)

- ***mv***: Di chuyển hoặc đổi tên một file hoặc thư mục (move), ví dụ đổi tên thư mục Thinh181 thành Helo: 

![img](https://github.com/DucThinh47/Thuc-Tap-Co-So/blob/main/images/image26.png?raw=true)

Hoặc di chuyển thư mục Helo sang thư mục cntt: 

![img](https://github.com/DucThinh47/Thuc-Tap-Co-So/blob/main/images/image27.png?raw=true)

-  ***rm***: Xóa một file (thư mục), ví dụ xóa thư mục Helo:

![img](https://github.com/DucThinh47/Thuc-Tap-Co-So/blob/main/images/image28.png?raw=true)

- ***rmdir***: Xóa một thư mục trống (remove directory):

![img](https://github.com/DucThinh47/Thuc-Tap-Co-So/blob/main/images/image29.png?raw=true)

- ***cat***: Hiển thị nội dung của một file (concatenate):

![img](https://github.com/DucThinh47/Thuc-Tap-Co-So/blob/main/images/image30.png?raw=true)

- ***more***: hiển thị nội dung của một file trang từng trang. Ctrl + C để thoát:

![img](https://github.com/DucThinh47/Thuc-Tap-Co-So/blob/main/images/image31.png?raw=true)

- ***head***: Hiển thị nội dung đầu tiên của một file, ví dụ, hiển thị 5 dòng đầu của file test.txt: 

![img](https://github.com/DucThinh47/Thuc-Tap-Co-So/blob/main/images/image32.png?raw=true)

- ***tail***: Hiển thị nội dung cuối của một file, ví dụ hiển thị 5 dòng cuối của file test.txt: 

![img](https://github.com/DucThinh47/Thuc-Tap-Co-So/blob/main/images/image33.png?raw=true)

- ***grep***: Tìm kiếm các dòng trong một file chứa một chuỗi cụ thể, ví dụ hiển thị dòng chứa chuỗi "1": 

![img](https://github.com/DucThinh47/Thuc-Tap-Co-So/blob/main/images/image34.png?raw=true)

- ***wc***: Đếm số lượng dòng, ký tự, byte trong một file (word count):

![img](https://github.com/DucThinh47/Thuc-Tap-Co-So/blob/main/images/image35.png?raw=true)

- ***clear***: Xóa màn hình hiển thị:

![img](https://github.com/DucThinh47/Thuc-Tap-Co-So/blob/main/images/image36.png?raw=true)

- ***echo***: Hiển thị một thông điệp trên màn hình:

![img](https://github.com/DucThinh47/Thuc-Tap-Co-So/blob/main/images/image37.png?raw=true)

- ***>***: Chuyển hướng đầu ra của một lệnh sang một file mới hoặc ghi đè lên file đã tồn tại:

![img](https://github.com/DucThinh47/Thuc-Tap-Co-So/blob/main/images/image38.png?raw=true)

- ***>>***: ghi thêm đầu ra của một lệnh vào cuối file đã tồn tại: 

![img](https://github.com/DucThinh47/Thuc-Tap-Co-So/blob/main/images/image39.png?raw=true)

- ***sort***: Sắp xếp nội dung của 1 file theo thứ tự tăng dần hoặc giảm dần. Để sắp xếp giảm dần, có thể sử dụng tùy chọn “-r”: 

![img](https://github.com/DucThinh47/Thuc-Tap-Co-So/blob/main/images/image40.png?raw=true)

- ***uniq***: loại bỏ các dòng trùng lặp liên tiếp trong 1 file:

![img](https://github.com/DucThinh47/Thuc-Tap-Co-So/blob/main/images/image41.png?raw=true)











