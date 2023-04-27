# Bài 13 - DC Motor

## 💥 13.1 Giới thiệu

DC Motor là 2 động cơ để gắn 2 bánh xe vào Zoom:bit di chuyển

2 động cơ này chính là phần truyền động chính cho zoom:bit, phía trước zoom:bit có một hộp bi xoay đa hướng, giúp nó rẻ trái, phải và xuay đầu linh hoạt.


## 💥 13.2 Cách sử dụng

Để điều khiển được động cơ Servo Motor, trên MakeCode chúng ta cần cài thêm extensions mở rộng zoom:bit

Cài xong sẽ có thêm 2 modules Zoom:bit và reka:bit


## 💥 13.3 Đưa chương trình vào micro:bit

* Khởi động lên thì cho Servo xoay đầu phía trước, tức servo 90 độ
* Nhấn button A, thì xe rẻ trái đồng thời cho Servo xoay trái 45 độ
* Nhấn Button B, thì xe rẻ phải đồng thời cho Servo xoay phải 45 độ
* Nhấn A+B thì xe đi thẳng, đồng thời xoay Servo về trước


## 💥 13.4 Hoạt động học viên

### Hoạt động 1

Tạo chương trình điều khiển giúp zoom:bit di chuyển:

* Khởi động lên thì cho Servo xoay đầu phía trước, tức servo 90 độ. Màn hình LED hiển thị mặt cười. Bật âm thanh `power up`
* Nhấn button A, rẻ trái và Servo xoay trái 45 độ, màn hình LED hiển thị mũi trên hướng trái
* Nhấn Button B, rẻ phải và Servo xoay phải 45 độ, màn hình LED hiển thị mũi trên hướng phải
* Nhấn A+B, đi thẳng, Servo xoay về trước 90 độ, màn hình LED hiển thị mũi trên hướng lên


### Hoạt động 2 - Vượt chướng ngại vật

Cải tiến chương trình trên cho Hoạt động 2 này

Tạo ra một sa hình có bố trí chướng ngại vật giữa quảng đường di chuyển từ vạch xuất phát đến đích.

Tạo ra một chương trình cho zoom:bit di chuyển: 

* Khởi động lên thì cho Servo xoay đầu phía trước, tức servo 90 độ. Màn hình LED hiển thị mặt cười. Bật âm thanh `power up`
* Nhấn button A, rẻ trái và Servo xoay trái 45 độ, màn hình LED hiển thị mũi trên hướng trái, đèn trước bên trái nháy 3 lần, đèn RGB nháy 3 lần màu vàng
* Nhấn Button B, rẻ phải và Servo xoay phải 45 độ, màn hình LED hiển thị mũi trên hướng phải, đèn trước bên phải nháy 3 lần, đèn RGB nháy 3 lần màu vàng
* Nhấn A+B, đi thẳng, Servo xoay về trước 90 độ, màn hình LED hiển thị mũi trên hướng lên
