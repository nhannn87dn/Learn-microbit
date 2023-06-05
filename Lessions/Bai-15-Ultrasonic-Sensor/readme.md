# Bài 13 - Ultrasonic Sensor

⛔ Chuẩn bị của Giáo Vụ
- In LED Planning cho mỗi bạn 1 tờ
- In mỗi bạn bài tập về nhà
- In mỗi bạn 1 file Thuat-toan-Planning-v2.docx (in 2 mặt)

## 💥 13.1 Giới thiệu

**Ultrasonic Sensor** là phần cảm biến siêu âm được gắn vào phần đầu của zoom:bit

**Ultrasonic Sensor** đóng vai trò như con mắt của zoom:bit, nó có thể cảm nhận được chướng ngại vật và tự biết lùi lại, hay rẻ trái, phải tùy vào cách mà chúng ta lập trình hướng xử lý cho nó.


## 💥 13.2 Cách sử dụng

Để điều khiển được động cơ Servo Motor, trên MakeCode chúng ta cần cài thêm extensions mở rộng zoom:bit

Cài xong sẽ có thêm 2 modules Zoom:bit và reka:bit

Vào Module Zoom:bit --> Tại mục Ultrasonic ta tấy có block `Ultrasonic distance (cm)`

Block này chứa thông tin cảm biến siêu âm thu thập được. Dựa vào đó chúng ta ra quyết định tương ứng.


## 💥 13.3 Đưa chương trình vào micro:bit

Lập trình một chương trình cho zoom:bit tự chạy

* Khởi động lên màn hình LED show hình trái tim, đồng thời bật âm thanh `power up`

* Nếu cảm biến siêu âm đo được khoảng cách với chướng ngại vật < 10 cm thì cho zoom:bit đi lùi lại.

* Nếu cảm biến siêu âm đo được khoảng cách với chướng ngại vật < 20 cm thì
  * Phanh lại
  * Nếu nhấn phìm A thì rẻ trái, Nhấn phìm B thì rẻ phải
* Còn không thì cứ đi thẳng

## 💥 13.4 Hoạt động học viên

### Hoạt động 1

Cho học viên lập trình lại chương trình trên

Kết hợp thêm đèn, âm thanh, show biểu tượng ra màn hình LED...


### Hoạt động 2: Vượt chướng ngại vật

Tạo ra một sa hình có bố trí chướng ngại vật giữa quảng đường di chuyển từ vạch xuất phát đến đích.

Tạo ra một chương trình cho zoom:bit di chuyển: yêu cầu chỉ sử dụng cảm biến siêu âm và các lệnh rẻ trái, phải (Lưu ý không dùng đến inputs) để di chuyển về đích.


Cho học viên thực hiện và đặt vấn đề cái khó khi gặp phải là chương trình rất dài do phải rẻ trái và phải nhiều lần. Lặp lại các phần lệnh khi rẻ trái, phải liên tục.

Cách tối ưu : tạo function để rút gọn code