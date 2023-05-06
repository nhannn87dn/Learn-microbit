# Bài 7 - Cảm biến Ánh Sáng

## 💥 7.1 Giới thiệu

Cảm biến ánh sáng là một thiết bị đầu vào đo mức độ ánh sáng. Micro:bit BBC của bạn sử dụng đèn LED để cảm nhận mức độ ánh sáng và cho phép bạn lập trình micro:bit của mình làm cảm biến ánh sáng.


## 💥 7.2 Sử dụng cảm biến ánh sáng

**Bước 1**

Sử dụng MakeCode để tạo một chương trình thu thập chường độ ánh sáng phòng 

Ví dụ 1: 

* Sử dụng block Show number + Light level
* Giải thích cho học viên là cảm biến sánh sáng sẽ trả về giá trị là một con số

Ví dụ 2: 

Dựa vào con số đó chúng ta có thể phân tích được môi trường ánh sáng hiện tại:

* Nếu cường độ ánh sáng > 100 thì là ban ngày
* Nếu cường độ ánh sáng < 100 thì là ban đêm

Có thể dùng `micro:bit simulator` trình mô phỏng trên Makcode để minh họa khi không dùng đến micro:bit

**Bước 2 - Chạy trên micro:bit**

Chuyển chương trình lên micro:bit

## 💥 7.3 Hoạt động học viên

### 7.3.1 Cột đèn thông minh

Đèn đường là một phương tiện chiếu sáng công cộng giúp mọi người có thể quan sát để hoạt động vào trời tối. Tuy nhiên Điện Lực địa phương đang gặp phải một khó khăn là phải cử người tắt khi trời sáng và bật đèn lên khi trời sắp tối.

Bạn có thể giúp họ giải quyết vấn đề trên hay không ?

Gợi ý:

* Dùng micro:bit đo cường độ ánh sáng
* Nếu ban ngày thì hiển thị màn hình LED biểu tượng mặt trời
* Nếu là ban đêm thì hiển thị biểu tượng mặt trăng
* Viết thuật toán trước khi làm

### 7.3.2 Đèn Cảnh Báo An Toàn

Lucy có một người bạn tên là Jack không may bị tai nạn giao thông và bị thương đôi chân không đi lại được. Bạn ấy phải di chuyển bằng xe lăn. Jack rất thích đi dạo công viên mỗi buổi tối, công viên thì đông người qua lại, có cả những người đi xe đạp.

Bạn có thể giúp Jack tạo một đèn cánh báo vào ban đêm để bạn ấy gắn lên xe lăn không ?

Yêu cầu là:

* Khi micro:bit bật lên thì hiển thị icon trái tim
* Khi nhấn Button A, micro:bit dựa vào cường độ ánh sáng để nhận biết làm ban đêm để bật LED và tắt LED.
* Nếu là ban đêm thì bật cả 25 đèn LED, rồi tắt bật liên tục để tạo hiệu ứng đèn LED nháy cảnh báo.
* Khi nhấn phím B thì tắt chương trình

Gới ý:

* Tạo một biến để lưu lại trạng thái tắt, bật chương trình
* Tạo một biến để lưu lại trạng thái hiển thị LED, lúc đầu là tắt LED
* Dùng if else kết hợp với biến để kiểm tra trạng thái chương trình tắt, bật và trạng thái môi trường để tắt mở LED để tạo hiệu ứng nháy