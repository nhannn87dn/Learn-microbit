# Bài 13 - Maker Line Sensor

## 💥 13.1 Giới thiệu

Giới thiệu về bo mạch Maker Line Sensor được gắn bên dưới phía trước xe zoom:bit

 Với bộ 5 cảm biến IR, nó có thể dò đường có chiều rộng từ 13mm đến 30mm. Màu sắc của đường có thể chọn màu sáng ( trắng ) hoặc màu tối ( đen).

## 💥 13.2 Cách sử dụng

## 💥 13.2.1 - Hiệu chuẩn

Để zoom:bit có thể dò theo đường đi trước hết chúng ta cần chỉ cho nó biết là đi theo cái gì ? Bằng cách dạy nó nhận biết.

Bước 1: Nhấn nút Calibrate (hiệu chuẩn) trong 5 giây đến khi 5 đèn LED đỏ lên để vào chế độ hiệu chuẩn

Bước 2:  Quét 5 cảm biến IR lần lượt qua vạch line 2 lần mà chúng ta muốn zoom:bit lần theo.

Bước 2: Nhấn nút Calibrate (hiệu chuẩn) để thoát chế độ hiệu chuẩn


Dữ liệu hiệu chuẩn được lưu lại trong EPROM và nó vẫn không thay đổi ngay khi cảm biến đã tắt nguồn. Hiệu chuẩn chỉ cần thực hiện một lần trừ khi có thay đổi chiều cao hoặc màu nền.

## 💥 13.2.1 - Vận hành

Để nhận được thông tin từ cảm biến Maker Line sensor, trên MakeCode chúng ta cần cài thêm extensions mở rộng zoom:bit

Cài xong sẽ có thêm 2 modules Zoom:bit và reka:bit

Bạn sẽ tìm thấy Maker Line trong module zoom:bit


Demo chương trình cho zoom:bit chạy theo sa hình bằng giấy đi kèm bộ kít zoom:bit, hoặc lấy băng keo đen tạo đường đi.


## 💥 13.3 Đưa chương trình vào micro:bit


## 💥 13.4 Hoạt động học viên

Hoạt động thi nhóm: tạo không khi tranh đua sôi nỗi

Tạo chương trình cho zoom:bit đi theo đường đi được vạch sẵn. 
Nếu đội nào đi đúng hướng và xa nhất sẽ là đội thắng.

 Lưu ý: zoom:bit không thể đo quảng đường đã đi, nhưng chúng ta có thể dùng biến. Nếu cảm biến phát hiện ngã rẽ thì tại đó chúng ta có thể gắn biến để lưu lại.

 Qua đó chúng ta biết zoom:bit đã đi được đến đâu