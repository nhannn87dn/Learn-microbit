# Bài 10 - Radio

⛔ Chuẩn bị của Giáo Vụ
- In LED Planning cho mỗi bạn 1 tờ
- In mỗi bạn bài tập về nhà
- In mỗi bạn 1 file Thuat-toan-Planning-v2.docx (in 2 mặt)

## 💥 10.1 Giới thiệu

Radio là một cách gửi và nhận tin nhắn và BBC micro:bits có thể sử dụng sóng radio để liên lạc với nhau.

## 💥 10.2 Cách sử dụng

### 10.2.1 Lập trình với Makecode

**Bước 1 - Thiết lập Nhóm Radio**

Sử dụng block `radio set group` trong nhóm Radio để tạo một Nhóm, có thể đánh số từ 0 đến 255.

Nhóm Radio giống như Kênh tín hiệu vậy. Bất kỳ micro:bit nào có cùng kênh thì có thể nhận và gửi tín hiệu cho nhau.

**Bước 2 - Gửi và nhận tín hiệu**

Radio chỉ gửi được tín hiệu bằng ký tự số, chữ và một biến dạng name = key
Radio nhận cũng chỉ nhận được các giá trị tương ứng từ radio gửi đi do vậy nó có các khối block gửi và nhận tương ứng.

Ngoài ra bạn có thể xem thêm trong Radio -> More

**Bước 3 - Demo**

Gửi text `duck` và nhận 'hình con vịt`


### 10.2.2 Đưa chương trình vào micro:bit


## 💥 10.3 Hoạt động học viên

### Đáp án bí mật

Cùng rủ thêm một người bạn thân chơi trò hói đáp đúng sai. Ví dụ bạn A hỏi còn bạn B trả lời và phải bí mật không để người khác nghe thấy đáp án.

* Nếu trả lời đúng thì bạn B dùng micro:bit gửi tín hiệu yes, còn sai thì gửi no
* Bạn A nhận được tín hiệu yes thì hiển thị icon check, còn no thì hiển thị icon chéo
* Lưu ý phải thiết lập nhóm kênh trước nhé !

### Tín hiệu ngọn hải đăng

Đi đảm bảo an toàn khi ra khơi, các ngọn hải đăng thường phát một tín hiệu radio cho các tàu thuyền đang hoạt động ngoài biển.

Dựa vào tín hiệu radio, các tàu thuyền có thể xác định mình đã đi xa bờ đến đâu. Gần thì tín hiệu mạnh, xa thì tín hiệu yếu đi

Một bạn có thể đóng vai trò là người quản lí hải đăng phát tính hiệu và các bạn khác đóng vai trò là chủ thuyền dùng micro:bit để nhận tín hiệu radio từ hải đăng

Tạo chương trình thể hiện việc gửi và nhận tín hiệu như đã nói trên

**Gợi ý thực hiện:**

* Hải đăng thiết lập cường độ tín hiệu mạnh hay yếu bằng cách set từ 0 - 9. Block này nằm trong Radio -> ...More

* Hải đăng diên tục gửi tín hiệu đi bằng khối forever

* Tàu thuyền nhận cường độ tín hiệu bằng block này. Block này nằm trong Radio

* Bạn cần tạo một biến để giữ lại cường độ hiệu rồi kết hợp với 2 block trên để tạo ra một biểu đồ biến động cao hay thấp.

* Tín hiệu signal nhận được là con số - 95 là yếu nhất, - 42 là mạnh nhất
Chúng ta sử dụng block map nói trên để convert sang khoảng 0 – 9 để có thể đưa vào block plot bar graph of x tup to y




