# 📘 Dự Án: Ứng Dụng Của Hàm Số & Đồ Thị Trong Thực Tiễn (Toán Lớp 10)


## 📌 1. Thông Tin Chung
* **Chủ đề:** Hàm số, đồ thị bậc nhất, hàm số bậc hai và các ứng dụng thực tiễn trong đời sống, kinh tế, vật lý.
* **Mục tiêu:** Vận dụng linh hoạt khái niệm hàm số, bảng biến thiên và đồ thị Parabol để giải quyết các bài toán tối ưu hóa và mô hình hóa các hiện tượng thực tế.
* **Định dạng đầu ra:** File tài liệu biên dịch bằng Typst / PDF.

---

## 🗺️ 2. Đề Cương Chi Tiết Bài Báo Cáo

### Mở Đầu
* Lý do chọn đề tài (Vai trò của hàm số như "ngôn ngữ của sự thay đổi" trong tự nhiên và xã hội).
* Mục đích và nhiệm vụ nghiên cứu.
* Đối tượng và phạm vi nghiên cứu.

### Chương 1: Hệ Thống Hóa Kiến Thức Cơ Bản Về Hàm Số
* Khái niệm hàm số, tập xác định, tập giá trị.
* Tính đồng biến, nghịch biến của hàm số (Chiều biến thiên).
* Tổng quan về hàm số bậc nhất $y = ax + b$ ($a \neq 0$) và hàm số bậc hai $y = ax^2 + bx + c$ ($a \neq 0$).
* Ý nghĩa thực tiễn của đỉnh Parabol và trục đối xứng.

### Chương 2: Các Mô Hình Hàm Số Trong Thực Tiễn
* **Trong Kinh tế (Bài toán tối ưu lợi nhuận):** Xây dựng hàm doanh thu, hàm chi phí và hàm lợi nhuận; tìm mức giá hoặc sản lượng để đạt lợi nhuận tối đa dựa vào đỉnh Parabol.
* **Trong Vật lý & Kỹ thuật (Chuyển động & Kiến trúc):** Mô tả quỹ đạo chuyển động của vật thể bị ném ngang/xiên; thiết kế cổng vòm parabol, cầu treo.
* **Trong Đời sống & Tự nhiên:** Dự báo sự tăng trưởng dân số, mô hình tiêu thụ nhiên liệu theo vận tốc xe.

### Chương 3: Bài Tập Minh Họa Và Lời Giải Chi Tiết
* Xây dựng các bài toán thực tế tiêu biểu ở cấp độ lớp 10.
* Giải chi tiết bằng phương pháp lập hàm số, khảo sát bảng biến thiên và ứng dụng cực trị của hàm số bậc hai.

---

## 📈 3. Kế Hoạch & Tiến Độ Thực Hiện

- [ ] **Tuần 1:** Ôn tập lý thuyết hàm số lớp 10, tìm kiếm các bài báo/tình huống thực tế sử dụng hàm số bậc hai.
- [ ] **Tuần 2:** Hoàn thành phần Mở đầu và Chương 1 (Hệ thống kiến thức nền tảng).
- [ ] **Tuần 3:** Viết nội dung trọng tâm ở Chương 2 (Xây dựng các mô hình tối ưu hóa kinh tế và vật lý).
- [ ] **Tuần 4:** Giải quyết các bài toán minh họa (Chương 3), viết phần Kết luận và trình bày tài liệu tham khảo.
- [ ] **Tuần 5:** Kiểm tra lại định dạng trình bày bằng Typst, rà soát lỗi tính toán và hoàn thiện sản phẩm.

---

## 💻 4. Mã Nguồn Typst Cho Báo Cáo

Dưới đây là mã nguồn Typst mẫu để bạn biên dịch thành file báo cáo đẹp mắt:

```typst
#set page(paper: "a4", margin: (x: 2.5cm, y: 2.5cm))
#set text(font: "Liberation Serif", size: 12pt, lang: "vi")
#set par(justify: true, leading: 0.8em, first-line-indent: 1.5em)

#align(center)[
  #text(size: 16pt, weight: "bold")[BÁO CÁO CHUYÊN ĐỀ TOÁN HỌC] \
  #v(0.5em)
  #text(size: 14pt, fill: rgb("#1a5fb4"))[ỨNG DỤNG CỦA HÀM SỐ BẬC HAI TRONG THỰC TIỄN]
  #v(1cm)
]

= 1. Đặt vấn đề
Trong chương trình Toán lớp 10, hàm số và đồ thị là một trong những nội dung trọng tâm. Đặc biệt, hàm số bậc hai $y = ax^2 + bx + c$ ($a \neq 0$) với đồ thị là một Parabol không chỉ mang ý nghĩa lý thuyết thuần túy mà còn xuất hiện xuyên suốt trong các bài toán tối ưu hóa thực tế.

= 2. Bài toán tối ưu hóa kinh tế
Giả sử một doanh nghiệp sản xuất một loại sản phẩm với hàm chi phí và hàm doanh thu phụ thuộc vào số lượng sản phẩm $Q$. Lợi nhuận của doanh nghiệp được cho bởi hàm số bậc hai:
$Pi(Q) = -a Q^2 + b Q - c \quad (a > 0)$
Để tìm mức sản lượng $Q$ nhằm đạt lợi nhuận tối đa, ta đi tìm tọa độ đỉnh của Parabol:
$Q_max = -b / (2a)$

= 3. Kết luận
Việc ứng dụng mô hình hàm số giúp học sinh lớp 10 kết nối tri thức toán học vào đời sống thực tế một cách trực quan và sinh động nhất.
