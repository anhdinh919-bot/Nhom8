# Nhom8
Sử dụng Sympy để giải quyết các bài toán về ma trận
# Sử dụng SymPy để giải quyết các bài toán về ma trận 🧮🐍

Dự án này ứng dụng thư viện **SymPy** trong ngôn ngữ lập trình Python để mô phỏng, tính toán và giải quyết các bài toán cơ bản đến nâng cao trong Đại số tuyến tính, cụ thể là lý thuyết ma trận và hệ phương trình tuyến tính. Dự án giúp tự động hóa quá trình tính toán, hiển thị kết quả chính xác (dưới dạng phân số/ký hiệu toán học) và hỗ trợ kiểm chứng kết quả làm tay.

---

## 👥 Thông tin dự án

- **Môn học:** Tích hợp CNTT trong dạy học toán
- **Giảng viên hướng dẫn:** Thầy Nguyễn Đăng Minh Phúc
- **Lớp:** Toán 4A
- **Nhóm thực hiện:** Nhóm 8
- **Thành viên:**
  1. Đinh Thị Kim Anh
  2. Phạm Thị Bích Ngân
  3. Trần Yến Vi
  4. Yn Lân

---

## ✨ Các chức năng chính (Nội dung bài toán)

Dự án sử dụng Python và SymPy để triển khai các bài toán sau:
- **Khởi tạo và truy xuất ma trận:** Khai báo ma trận, tạo ma trận không, ma trận đơn vị.
- **Phép toán cơ bản:** Cộng, trừ, nhân hai ma trận, nhân ma trận với một số vô hướng.
- **Đặc trưng của ma trận:** Tìm ma trận chuyển vị ($A^T$), tính định thức ($\det(A)$), tìm ma trận nghịch đảo ($A^{-1}$).
- **Biến đổi sơ cấp trên hàng:** 
  - Đổi chỗ 2 hàng.
  - Nhân một hàng với số khác $0$.
  - Cộng một bội của hàng này vào hàng khác.
- **Dạng bậc thang:** Đưa ma trận về dạng bậc thang và bậc thang rút gọn (RREF).
- **Hạng của ma trận:** Xác định hạng của ma trận ($\operatorname{rank}(A)$).
- **Hệ phương trình tuyến tính:** 
  - Áp dụng định lý Rouché-Capelli để biện luận số nghiệm.
  - Giải hệ phương trình bằng phương pháp Gauss-Jordan.
  - Giải hệ phương trình tổng quát (nghiệm duy nhất, vô số nghiệm, vô nghiệm) bằng `linsolve`.

---

## 🛠 Cài đặt môi trường

Dự án yêu cầu máy tính của bạn đã cài đặt sẵn **Python** (phiên bản 3.x).

Để chạy được mã nguồn, bạn cần cài đặt thư viện `sympy`. Mở Terminal (hoặc Command Prompt) và chạy lệnh sau:

```bash
pip install sympy
