# Bài 6 - Âm thanh

⛔ Chuẩn bị của Giáo Vụ
- In mỗi bạn bài tập về nhà
- In mỗi bạn 1 file Thuat-toan-Planning-v1.docx (in 2 mặt)

## 💥 6.1 Giới thiệu

Micro:bit có loa tích hợp, giúp bạn dễ dàng thêm âm thanh vào dự án của mình. Bạn có thể cho micro:bit phát nhạc, bạn cũng có thể thể hiện bản thân bằng một số âm thanh: làm cho micro:bit của bạn cười khúc khích, chào bạn hoặc cho bạn biết khi nó buồn ngủ hoặc buồn.


Micro:bit BBC của bạn có thể được lập trình để tạo ra nhiều loại âm thanh khác nhau - từ các nốt đơn, âm sắc và nhịp cho đến các tác phẩm âm nhạc của riêng bạn.


Nếu có đủ phụ kiện thì bạn có thể dùng micro:bit như một chiếc máy MP3 để phát nhạc ra tai nghe, headphones...bằng cách kết nối với các chân Pin


## 💥 6.2 Sử dụng

**Bước 1 - Makecode**

Tìm hiểu các thành phần của component Music

* Melody: Âm thanh có giai điệu
* Tone: là âm theo nốt nhạc
* Tempo: Nhịp độ nhanh hay chậm
* Volume: điều khiển âm lượng


**Demo 1 -  Chơi một giao điệu sẵn có**

* Sử dụng block Music: `play melody`
* Sử dụng block Music: `play sound`

**Demo 2 -  Bạn có thể sáng tạo một giai điệu cho riêng mình**

* Sử dụng block Music: `play tone`
* Giải thích beat nhạc là gì

Tạo giao điệu Happy birthday


**Bước 2 - Chạy trên micro:bit**

Đưa chương trình vào micro:bit

## 💥 6.3 Hoạt động học viên

### 6.3.1 Giai điệu em thích

Tạo chương trình chơi 5 giai điệu có sẵn mà bạn thích.

Yêu cầu: 

* Nhấn Button A thì chạy giai điệu 1
* Nhấn Button B thì chạy giai điệu 2
* Nhấn Button A+B thì chạy giai điệu 3
* Chạm Logo thì chạy giai điệu 4
* Lắc micro:bit thì chạy giai điệu 5


### 6.3.2 Countdown - Chúc Mừng Năm Mới

Tạo chương trình đếm ngược thời khắc chuyển giao năm mới từ 10 - 1 với yêu cầu như sau:

* Nhấn phím A thì khởi động chương trình và phát âm thanh bật nguồn `power up`
* Nhấn phím B thì tắt chương trình, phát âm thanh bật nguồn `power down`
* Chạm vào Logo thì bắt đầu chương trình đếm ngược. Mỗi giây thì hiển thị số ra màn hình LED, đồng thời phát âm thamh middle G.
* Đếm đến 0 thì phát âm thanh `happy`, đồng thời cho LED trình diễn animations pháo hoa liên tục cho đến tắt thì thôi


### 6.3.3 Giai điệu giáng sinh

Dùng Makecode soạn 1 đoạn giai điệu trong bài hát `Jingle Bells` nổi tiếng.
Với yêu cầu:

* Touch Logo để phát, nhấn A + B để tắt
* Nhấn A để giảm âm lượng, B để giảm âm lượng
* Hiển thị ra LED biểu tượng bông tuyết khi nhạc đang phát