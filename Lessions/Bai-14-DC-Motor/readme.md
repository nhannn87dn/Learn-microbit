# Bài 14 - DC Motor

## 💥 14.1 Giới thiệu

DC Motor là 2 động cơ để gắn 2 bánh xe vào Zoom:bit di chuyển

2 động cơ này chính là phần truyền động chính cho zoom:bit, phía trước zoom:bit có một hộp bi xoay đa hướng, giúp nó rẻ trái, phải và xuay đầu linh hoạt.


## 💥 14.2 Cách sử dụng

Để điều khiển được động cơ Servo Motor, trên MakeCode chúng ta cần cài thêm extensions mở rộng zoom:bit

Cài xong sẽ có thêm 2 modules Zoom:bit và reka:bit


## 💥 14.3 Đưa chương trình vào micro:bit

* Khởi động lên thì cho Servo xoay đầu phía trước, tức servo 90 độ
* Nhấn button A, thì xe rẻ trái đồng thời cho Servo xoay trái 45 độ
* Nhấn Button B, thì xe rẻ phải đồng thời cho Servo xoay phải 45 độ
* Nhấn A+B thì xe đi thẳng, đồng thời xoay Servo về trước


## 💥 14.4 Hoạt động học viên

### Xe cấp cứu phiên bản mới

Nâng cấp bài tập xe cấp cứu ở bài học trước, thêm phần di chuyển như sau:

* Khởi động lên thì cho Servo xoay đầu phía trước, tức servo 90 độ. Màn hình LED hiển thị mặt cười. Bật âm thanh `power up`
* Để tăng sự thu hút của mọi người và nhường đường để xe chạy, bạn có thể vừa cho đèn RGB LED nhấp nháy liên tục vừa phát ra tiếng còi báo động tò te to tè bằng block play melody

* Nhấn button A, rẻ trái và Servo xoay trái 45 độ, màn hình LED hiển thị mũi trên hướng trái
* Nhấn Button B, rẻ phải và Servo xoay phải 45 độ, màn hình LED hiển thị mũi trên hướng phải
* Nhấn A+B, đi thẳng, Servo xoay về trước 90 độ, màn hình LED hiển thị mũi trên hướng lên


### Hoạt động 2 - Xe buýt đến trường

Cải tiến chương trình trên cho Hoạt động 2 này

Tạo ra một sa hình có bố trí chướng ngại vật giữa quảng đường di chuyển từ vạch xuất phát đến đích.

Tạo ra một chương trình cho zoom:bit di chuyển: 

* Khởi động lên thì cho Servo xoay đầu phía trước, tức servo 90 độ. Màn hình LED hiển thị mặt cười. Bật âm thanh `power up`
* Nhấn button A, rẻ trái và Servo xoay trái 45 độ, màn hình LED hiển thị mũi trên hướng trái, đèn trước bên trái nháy 3 lần, đèn RGB nháy 3 lần màu vàng
* Nhấn Button B, rẻ phải và Servo xoay phải 45 độ, màn hình LED hiển thị mũi trên hướng phải, đèn trước bên phải nháy 3 lần, đèn RGB nháy 3 lần màu vàng
* Nhấn A+B, đi thẳng, Servo xoay về trước 90 độ, màn hình LED hiển thị mũi trên hướng lên

### Hoạt động 3 - Xe điều khiển từ xa

Áp dụng kiến thức đã học ở bài Radio để Lập trình điều khiển xe robot zoom:bit A bằng một bo mạch micro:bit B

* zoom:bit A là xe chạy
* micro:bit B là điều khiển từ xe

Yêu cầu:

* Nếu chạm và giữ vào Logo thì cho xe chạy tới, thả ra thì dừng
* Nhấn nút A thì rẻ phải
* Nhấn nút B thì rẻ trái
* Nhấn A+B thì đi lùi

Mở rộng bài này bằng cách sử dụng cảm biến gia tốc kế: Sử dụng khối lệnh on Shake / logo up/ logo down / sreen up / screen down / tilt left / tilt right ... để điều khiển.