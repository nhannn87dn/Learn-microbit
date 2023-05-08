# Bài 8 - Cảm biến La Bàn

## 💥 8.1 Giới thiệu

La bàn (cũng gọi là Từ kế hay Kim chỉ Nam) là dụng cụ dùng để xác định phương hướng trong không gian nhất định. La bàn được ứng dụng nhiều trong các hoạt động đi biển, vào rừng, sa mạc, hướng bay của máy bay, tàu thủy, tàu ngầm, tên lửa, tàu vũ trụ,...

La bàn kỹ thuật số là một cảm biến đầu vào phát hiện từ trường. BBC micro:bit của bạn có một la bàn sẵn có có thể phát hiện hướng mà nó đang hướng tới.

Giải thích ký hiệu la bàn, cách định hướng trên là bàn

* Hướng gốc là N = Hướng Bắc = 0 độ
* Dựa vào la bàn ta biết được góc độ chênh lệch so với hướng gốc thì chúng ta biết hướng chúng ta đang ở đâu

  * Hướng Nam được kí hiệu là S.
  * Hướng Đông ký hiệu là E.
  * Hướng Bắc được kí hiệu là N.
  * Hướng Tây được kí hiệu là W.
  * Hướng Đông Bắc có kí hiệu là NE.
  * Hướng Đông Nam kí hiệu là SE.
  * Hướng Tây Nam kí hiệu là SW.
  * Hướng Tây Bắc kí hiệu là NW

## 💥 8.2 Sử dụng cảm biến La Bàn

**Bước 1 - Makecode**:

Dùng makecode soạn chương trình: hiển thị độ lệch la bàn

Sử dụng `compass heading (0)`

**Bước 2 - Chạy trên micro:bit**

Đưa chương trình vào micro:bit

## 💥 8.3 Hoạt động học viên


###  8.1 Công viên động vật hoang dã

Nhà trường tổ chức cho các bạn nhỏ hoạt động ngoài giờ, tham quan công viên động vật hoang dã. Hướng dẫn viên của công viên có giới thiệu rằng -  hướng 45 độ là nơi mấy bạn Gấu sinh sống. Vì vậy các bạn nhỏ không nên đến quá gần các bạn Gấu nhé !

Các bạn nhỏ tạo chương trình làm một La Bàn kỹ thuật số để xác định vị trí nơi mấy bạn Gấu ở.


- Nếu đúng hướng 45 độ thì tạo một biểu tượng Sonar nhấp nháy
- Các hướng còn lại hiển thị biểu tượng mặt cười để báo hiệu tình trạng an toàn
- Nếu Chạm vào logo thì hiển thị kết quả cảm biến đo được ra màn hình LED

Lưu ý: Soạn thuật toán trước khi thực hiện chương trình

###  8.2 Hòn Đảo Chứa Kho Báu

Theo truyền thuyết kể rằng tại một hòn đảo xa xôi tại một vùng biển hướng Đông Bắc từng có một chiếc thuyền chở đầy kho báu bị sóng biển đánh dạt vào bờ.

Có rất nhiều người đã đổ xô đi tìm nhưng vẫn chưa tìm ra vì họ không xác định đướng hướng đi đến hòn đảo trên biển khơi mênh mông.

Các bạn nhỏ hãy làm một chương trình La bàn để có thể giúp những người tìm kiếm kho báu xác định đúng hướng đi của mình.

* Sử dụng một biến compass để lưu trữ giá trị cảm biến đo được
* Nếu compass = 45 độ và thì hiển thị ra màn hình LED ký tự NE và phát ra âm thành bip bip để báo hướng đi đúng
* Nếu compass > 45 độ và < 135 độ và thì hiển thị ra màn hình LED ký tự E
* Nếu compass = 135 độ và thì hiển thị ra màn hình LED ký tự SE
* Nếu compass > 135 độ và < 225 độ và thì hiển thị ra màn hình LED ký tự S
* Nếu compass = 225 độ và thì hiển thị ra màn hình LED ký tự SW
* Nếu compass > 225 độ và < 315 độ và thì hiển thị ra màn hình LED ký tự W
* Nếu compass = 315 độ và thì hiển thị ra màn hình LED ký tự NW
* Khoảng còn lại là hướng Bắc thì hiển thị ra màn hình LED ký tự N

Lưu ý: Soạn thuật toán trước khi thực hiện chương trình