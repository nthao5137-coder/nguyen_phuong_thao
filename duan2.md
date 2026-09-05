# 📐 Dự Án Nghiên Cứu: Ứng Dụng Của Vectơ & Hệ Thức Lượng Trong Thực Tiễn (Toán Lớp 10)

Chào mừng bạn đến với kho lưu trữ dự án học tập và nghiên cứu chuyên đề **Hình học** trong chương trình Toán lớp 10. Đây là nơi quản lý toàn bộ quá trình nghiên cứu, đề cương chi tiết, mã nguồn trình bày bằng Typst và các bài toán thực tế.

---

## 📌 1. Thông Tin Chung
* **Chủ đề:** Vectơ, hệ thức lượng trong tam giác và các ứng dụng thực tiễn trong đo đạc, vật lý, kỹ thuật.
* **Mục tiêu:** Vận dụng linh hoạt các quy tắc vectơ, định lý cô-sin, định lý sin để giải quyết các bài toán đo đạc thực tế không thể đo trực tiếp và bài toán tổng hợp lực.
* **Định dạng đầu ra:** File tài liệu biên dịch bằng Typst / PDF.

---

## 🗺️ 2. Đề Cương Chi Tiết Bài Báo Cáo

### Mở Đầu
* Lý do chọn đề tài (Vai trò của vectơ và hình học tọa độ trong việc giải quyết các bài toán thực tiễn).
* Mục đích và nhiệm vụ nghiên cứu.
* Đối tượng và phạm vi nghiên cứu.

### Chương 1: Hệ Thống Hóa Kiến Thức Cơ Bản
* Khái niệm vectơ, các phép toán vectơ (tổng, hiệu, tích với một số).
* Các hệ thức lượng trong tam giác: Định lý cô-sin, định lý sin.
* Các công thức tính diện tích tam giác và ứng dụng giải tam giác.

### Chương 2: Các Mô Hình Hình Học Trong Thực Tiễn
* **Trong Trắc địa & Đo đạc:** Tính khoảng cách giữa hai điểm bị cản trở bởi chướng ngại vật (hồ nước, thung lũng) sử dụng định lý cô-sin và định lý sin.
* **Trong Vật lý & Cơ học:** Tổng hợp và phân tích lực trong các hệ thống cân bằng, xác định vận tốc thực tế của chuyển động dưới tác động của dòng chảy hoặc gió.

### Chương 3: Bài Tập Minh Họa Và Lời Giải Chi Tiết
* Xây dựng các bài toán thực tế tiêu biểu ở cấp độ lớp 10.
* Giải chi tiết bằng phương pháp hình học kết hợp đại số hóa vectơ.

---

## 📈 3. Kế Hoạch & Tiến Độ Thực Hiện

- [ ] **Tuần 1:** Ôn tập lý thuyết vectơ và hệ thức lượng, tìm kiếm các bài toán đo đạc thực tế.
- [ ] **Tuần 2:** Hoàn thành phần Mở đầu và Chương 1 (Hệ thống kiến thức nền tảng).
- [ ] **Tuần 3:** Viết nội dung trọng tâm ở Chương 2 (Xây dựng các mô hình trắc địa và lực học).
- [ ] **Tuần 4:** Giải quyết các bài toán minh họa (Chương 3), viết phần Kết luận và trình bày tài liệu tham khảo.
- [ ] **Tuần 5:** Kiểm tra lại định dạng trình bày bằng Typst, rà soát lỗi tính toán và hoàn thiện sản phẩm.

---

## 💻 4. Mã Nguồn Typst Cho Báo Cáo

Dưới đây là mã nguồn Typst chuẩn xác để bạn copy và biên dịch thành file PDF:

```typst
#set page(paper: "a4", margin: (x: 2.5cm, y: 2.5cm))
#set text(font: "Liberation Serif", size: 12pt, lang: "vi")
#set par(justify: true, leading: 0.8em, first-line-indent: 1.5em)

#align(center)[
  #text(size: 16pt, weight: "bold")[BÁO CÁO CHUYÊN ĐỀ HÌNH HỌC 10] \
  #v(0.5em)
  #text(size: 14pt, fill: rgb("#1a5fb4"))[ỨNG DỤNG HỆ THỨC LƯỢNG VÀ VECTƠ TRONG THỰC TIỄN]
  #v(1cm)
]

= 1. Đặt vấn đề
Trong chương trình Hình học lớp 10, vectơ và hệ thức lượng trong tam giác cung cấp công cụ toán học mạnh mẽ để giải quyết các bài toán đo đạc trắc địa và cơ học mà các phương pháp hình học thuần túy gặp nhiều khó khăn.

= 2. Bài toán đo đạc khoảng cách thực tế
Để đo khoảng cách giữa hai điểm $A$ và $B$ bị ngăn cách bởi một hồ nước, ta chọn một điểm $C$ nhìn rõ cả $A$ và $B$. Đo khoảng cách $AC = b$, $BC = a$ và góc $C$. Áp dụng định lý cô-sin trong tam giác $ABC$:
$AB = sqrt(a^2 + b^2 - 2ab \cos C)$
Công thức này cho phép xác định chính xác khoảng cách cần tìm mà không cần đo trực tiếp qua mặt nước.

= 3. Kết luận
Việc ứng dụng các hệ thức lượng trong tam giác giúp học sinh kết nối tri thức toán học vào các bài toán đo đạc thực tế đời sống một cách trực quan và khoa học.
