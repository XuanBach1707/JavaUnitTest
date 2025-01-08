BIT220021 - Hà Xuân Bách
Mô tả bài tập kiểm thử đơn vị với Java

Bài tập này yêu cầu bạn kiểm thử các phương thức trong một lớp Java đơn giản có tên Calculator.
Lớp này thực hiện các phép toán cơ bản như cộng, trừ, nhân, và chia.
Mục tiêu chính của bài tập là giúp thực hành JUnit.


Nội dung lớp Calculator
Lớp Calculator bao gồm 4 phương thức cơ bản:

add(int a, int b): Trả về tổng của hai số nguyên.
subtract(int a, int b): Trả về hiệu của hai số nguyên.
multiply(int a, int b): Trả về tích của hai số nguyên.
divide(int a, int b):
Chia số nguyên a cho b.
Nếu b = 0, ném ngoại lệ IllegalArgumentException.
Mục tiêu của bài tập
Kiểm thử đơn vị cho từng phương thức:

Đảm bảo kết quả đúng khi nhập các đầu vào hợp lệ.
Xử lý đúng các trường hợp đặc biệt như chia cho 0.
Kiểm tra với nhiều kiểu giá trị đầu vào: số dương, số âm, và 0.
Sử dụng thư viện JUnit:

Áp dụng các phương pháp kiểm thử trong JUnit như assertEquals để so sánh kết quả mong đợi và kết quả thực tế.
Sử dụng assertThrows để kiểm tra ngoại lệ (trường hợp chia cho 0).
