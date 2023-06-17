# Bài 4 Conditions và Boolean

⛔ Chuẩn bị của Giáo Vụ

- In LED Planning cho mỗi bạn 1 tờ
- In mỗi bạn bài tập về nhà
- In mỗi bạn 1 file Thuat-toan-Planning-v1.docx (in 2 mặt)
- In mỗi bạn 1 file so-do-giai-thuat.docx

## 4.1 Xác định đầu ra

Giải thích cho học viên hiểu đầu ra là thế nào

* Lấy ví dụ: Tivi đóng vai trò là đầu ra, Chương trình tivi có rất nhiều kênh. Nếu bạn nhấn phím 1 thì ra VTV1, nhấn phím 2 nhảy sang kênh VTV2...

Như vậy khi bạn nhấn nút chuyển kênh ==> Chương trình đang tính toán để xác định đầu ra, và đưa hình ảnh ra màn hình cho bạn xem.

Trên màn hình LED của micro:bit cũng tương tự như vậy.

* Ví dụ 2: Bạn nào có Áo Xanh thì giơ tay lên, còn không thì đặt tay lên bàn.

Kết luận: Bạn đang đưa ra điều kiện để thực hiện một cái gì đó

## 4.2 Giới thiệu về if else - Lựa chọn

**Bước 1:**

* if bạn mặc áo xanh 
    giơ tay cao lên

* còn không: đặt tên lên bàn

**Lựa chọn** là khi một tập hợp các hành động được thực hiện khi một điều kiện nhất định được đáp ứng.

Lấy ví dụ về việc đi qua đường lối đi dành cho người đi bộ.

* Điều kiện gì cần phải được đáp ứng trước khi chúng ta có thể băng qua đường?

* Hành động nào nên được thực hiện khi 'đèn chuyển sang màu đỏ'?

**Bước 2: Sơ đồ thuật giải**

Giải quyết vấn đề trên bằng sơ đồ thuật giải

Cách mà bạn giải quyết vấn đề như trên gọi là thuật toán (algorithms)

## 4.3 Áp dụng lý thuyết

Chuẩn bị: bản in sơ đồ giải thuật, led giấy


Viết thuật toán thực hiện chương trình:

* Micro:bit khởi động thì hiển thị mặt buồn
* Nếu Nhấn button A thì hiển thị mặt cười

Dùng sơ đồ giải thuật kết hợp với led giấy để minh hoạt thuật toán chương trình

Sau đó triển khai thực tế lên Makecode

## 4.4 Hoạt động học sinh

Lưu ý: Viết thuật toán trước khi thao tác trên Makecode

###  Hoạt động 1

* Micro:bit khởi động thì hiển thị mặt buồn
* Nếu Nhấn button A thì hiển thị mặt cười
* Nếu nhấn Button A+B hiển thị mặt mếu
* Lắc hiển thị mặt khóc
* Nhấn button B thì hiển thị cười mỉm

###  Hoạt động 2

Cho biến X = 2
Cho biến Y = 4

* Nếu phím A được nhấn thì hiển thị kết quả X+Y ra LED
* Nếu phím B được nhấn thì hiển thị kết quả Y-X ra LED
* Nếu phím A+B được nhấn thì hiển thị kết quả XxY ra LED

###  Hoạt động 2

Tạo một biến có tên là rank

*  Khi nhấn nút A, thì rank = 1
*  Khi nhấn B thì rank = 2
*  Khi chạm Logo thì rank = 3. 

Đồng thời Kiểm tra rank:

*  Nếu rank =1 thì hiển thị chữ GOLD tượng trưng cho huy chương vàng. 
* Nếu rank =2 thì hiển thị chữ SILVER tượng trưng cho huy chương bạc. 
*  Nếu rank =3 thì hiển thị chữ BRONZE tượng trưng cho huy chương đồng. Còn lại không có huy chương
