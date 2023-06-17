# Bài 13 - Servo Motor

⛔ Chuẩn bị của Giáo Vụ
- In mỗi bạn bài tập về nhà
- In mỗi bạn 1 file Thuat-toan-Planning-v2.docx (in 2 mặt)

## 💥 13.1 Giới thiệu

Đầu của Zoom bit được gắn động cơ Servo 180 độ. Giải thích động cơ Servo là gì, chỉ rõ nằm ở đâu trên xe.

Chức năng Servo: điều khiển để Zoom:bit có thể nhìn thẳng về phía trước, quay đầu sáng trái, phải hoặc xoay sang góc mong muốn.

## 💥 13.2 Cách sử dụng

Để điều khiển được động cơ Servo Motor, trên MakeCode chúng ta cần cài thêm extensions mở rộng zoom:bit

Cài xong sẽ có thêm 2 modules Zoom:bit và reka:bit

Vào Module reka:bit --> Tại mục Servos chọn Block `set servo S1 position to 90 degrees`

## 💥 13.3 Đưa chương trình vào micro:bit

Tạo một chương trình:

* Khởi động lên thì cho Servo xoay đầu phía trước, tức servo 90 độ
* Nhấn button A, xoay trái 45 độ
* Nhấn Button B, xoay phải 45 độ
* Nhấn A+B thì xoay về trước 90 độ

## 💥 13.4 Hoạt động học viên

**Xe Cánh Sát Zoom:bit**

* Khởi động lên thì cho Servo xoay đầu phía trước, tức servo 90 độ. Màn hình LED hiển thị mặt cười. Bật âm thanh `power up`
* Nhấn button A, đầu xoay trái 45 độ, màn hình LED hiển thị mũi trên hướng phải
* Nhấn Button B, đầu xoay trái 45 độ, màn hình LED hiển thị mũi trên hướng trái

* Chạm Logo thì đầu xoay về trước, màn hình LED hiển thị mũi trên hướng lên
* Nhấn thì Button A+B đầu xoay về trước, màn hình LED hiển thị mũi trên lùi

Để tăng sự thu hút của mọi người và nhường đường để xe chạy, bạn có thể vừa cho đèn RGB LED nhấp nháy liên tục 2 màu Xanh Đỏ vừa phát ra tiếng còi báo động bằng các khối âm thanh
