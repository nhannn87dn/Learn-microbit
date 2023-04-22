
## Bài 2. Inputs - Đầu ra

### 2.1 Giới thiệu về inputs

**Bước 1**

* Giải thích cho học sinh hiểu: Khi nhấn Buttons thì có thể yêu cầu micro:bit thực hiện một lệnh nào đó.

* Giải thích mối liên hệ giữa Buttons trên micro:bit và Blocks Input trên MakeCode

■ on button A pressed - Button A

■ on button B pressed - Button B

■ on button A+B pressed - Buttons A and B

**Bước 2 - Chương trình đầu tiên**

* Sử dụng [makecode.microbit.org](https://makecode.microbit.org/) để tạo chương trình. Click "New Project" sau đó đặt tên Project

* Giải thích các thành phần trên phần mềm MakeCode
  * A - Programming Blocks =  Danh sách Blocks Code
  * B - Workspace = Vùng tạo chương trình
  * C - micro:bit simulator = Mô phỏng kết quả hiển thị lên micro:bit thật


* Ví dụ 1: Tạo chương trình Emotion badge - Nhấn Button A show mặt cười, nhấn phím B thì show mặt buồn

Có thể cải tiến ví dụ trên thành Flash Emotion badge (nhấp nháy)

* Ví dụ 2: Name badge

**Bước 3 - Giới thiệu thêm**

Ngoài các inputs nhấn, micro:bit còn trang bị các inputs là cảm biến

■ on shake - Accelerometer (Cảm biến gia tốc kế)

■ on Touch Logo - Cảm biến Chạm

■ Cảm biến nhiệt độ - temperature sensor

■ Cảm biến la bàn - Compass

■ Cảm biến cường độ ánh sáng - light sensor


Demo `on shake` và `Touch Logo` thì đổi hình

### 2.2. Giới thiệu về Biến - Variables

**Bước 1:**

Giải thích biến là gì, dùng để làm gì, cách đặt tên biến

* Đếm lớp mình có bao nhiêu bạn ?
==> Sĩ số: 20

Sĩ số: là tên biến
20 : là giá trị biến là value

* Tên của bạn là gì ?

Tên: Tâm An

Tên: là tên của biến
Tâm An: là giá trị của biến là value



**Bước 2:**

Cặt đặt biến trong MakeCode và tương tác với Buttons để thay đổi giá trị biến


**Bước 3:**

Chúng ta có thể tạo ra một biến với giá trị ngẩu nhiên.


### 2.3 Hoạt động học viên

**Nhiệm vụ 1**

Tạo một chương trình 

* Nhấn Button A thì hiển thị một ra màn hình LED

* Nhấn Button B hiển thị tên bạn ra màn hình LED

* Nhấn Button A + B hiển thị icon và tên ra màn hình LED

* Lắc một cái Hiển thị ký tự đầu tiên của tên bạn ra màn hình LED

* Chạm vào Logo show icon mặt cười ra màn hình LED



**Nhiệm vụ 2 - Săn Rác**

Tình huống một tổ chức môi trường địa phương đang lo ngại vấn đề ô nhiễm rác tại khu vực sinh sống. Họ nghe nói micro:bit có thể lưu trữ thông tin, và họ hỏi là liệu bạn có thể thiết kế cho họ một chường trình:

* Đếm số lượng rác thải có thể tái chế
* Đếm số lượng rác thải không thể tái chế

Yêu cầu thêm:

* Khởi động lên show hình trái tim
* Lắc một cái để xem số lượng rác thải tái chế và không tái chế đã đếm được.