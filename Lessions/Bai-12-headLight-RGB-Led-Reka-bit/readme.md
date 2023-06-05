# Bài 12 - Head Light và RGB LED trên reka:bit

⛔ Chuẩn bị của Giáo Vụ
- In LED Planning cho mỗi bạn 1 tờ
- In mỗi bạn bài tập về nhà
- In mỗi bạn 1 file Thuat-toan-Planning-v2.docx (in 2 mặt)

Để điều khiển được các thành phần trên bộ kit Zoom:bit bạn cần cài thêm một thư viện mở rộng Extentions từ Cytron

## 💥 12.1 Cài đặt Extentions

Trong MakeCode --> Chọn Component Extentions -> Sau đó tìm với từ khóa zoom:bit 

Bạn sẽ thấy kết quả tìm kiếm trả về có extention mang tên zoombit (Cytron ZOOM:bit Robot Car Kit for micro:bit)

Click chọn nó để cài.

Đợi một chút Make sẽ thêm vào 2 module nữa là Zoom:bit và Reka:bit


## 💥 12.2 Giới thiệu reka:bit

Giới thiệu chi tiết các thành phần có trên reka:bit


reka:bit là bo mạch để khiển các thành phần 

* DC Motors
* Servos
* RGB LED


## 💥 12.3 RGB LED

-  	Clear all RGB pixel: tắt tất cả các đèn
-  	Set GRB pixels brightness to: thay đổi độ sáng các đèn (nằm trong khoảng 0 -255)
-  	Set all RGB pixel to: đặt các đèn sang màu đã chọn
-  	Set RGB pixel to: đặt đèn vị trí 0 hoặc 1 với màu chọn

Demo cách điều khiển đèn LED RGB

## 💥 12.4 Head Light Zoom:bit

Là 2 đèn được gắn phía trước của Zoom:bit

Demo cách điều khiển đèn Head Light

## 💥 12.5 Hoạt động học viên

### 12.5.1 Xe cứu thương

Dùng zoom:bit giả lập một xe cấp cứu với yêu cầu như sau:


* Nhấn nút A thì bắt đầu nháy 2 đền LED RGB với màu Đỏ
* Để tăng sự thu hút của mọi người và nhường đường để xe chạy, bạn có thể vừa cho đèn RGB LED nhấp nháy liên tục vừa phát ra tiếng còi báo động tò te to tè bằng các khối âm thanh
* Nhấn nút B để tắt đèn và âm thanh


### 12.5.1 Lái xe an toàn

Để đảm bảo an toàn khi tham gia giao thông, bạn hãy lập trình cho zoom:bit:

* Tự động Bật 2 đèn trước lên khi trời tối
* Rẻ trái hay phải thì bật và nháy đèn RGB LED bên tương ứng với màu Cam
* Có thể thêm âm thanh khi rẻ trái hay phải