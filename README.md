# BÁO CÁO BÀI THI THỰC HÀNH - KỲ THI 2026
**Môn thi:** Phát triển ứng dụng Web (HTML/CSS/JS & ReactJS)  
**Ca thi:** Ca 1

---

## 👤 THÔNG TIN SINH VIÊN
* **Họ và tên:** Lê Minh Triết
* **Mã sinh viên:** 2451170952
* **Ngày sinh:** 03/03/2005
* **Trường:** Đại học Thủy Lợi (TLU)
* **Khoa/Ngành:** Công nghệ thông tin

---

## 📁 CẤU TRÚC THƯ MỤC DỰ ÁN (ĐÃ TUÂN THỦ)
Dự án được tổ chức chính xác theo yêu cầu cấu trúc của đề thi `EXAM2026_CaX`:

```text
EXAM2026_CaX/
├── html/
│   ├── index.html          # Giao diện gốc chuẩn hóa Bootstrap
│   ├── css/style.css       # Custom styles bổ sung cho giao diện
│   ├── js/app.js           # Xử lý logic phần HTML thuần (nếu có)
│   └── data/data.js        # Mảng dữ liệu mẫu (5 bản ghi sản phẩm)
├── reactjs/
│   ├── package.json        # Cấu hình dự án và dependencies của React
│   └── src/
│       ├── main.jsx        # Điểm khởi chạy cấu hình ứng dụng
│       ├── App.jsx         # Component gốc quản lý State tổng thể (Danh sách sản phẩm)
│       ├── components/
│       │   ├── Header.jsx       # Component hiển thị Tiêu đề ứng dụng
│       │   ├── ProductForm.jsx  # Component Form thêm mới (Xử lý State biểu mẫu)
│       │   ├── ProductTable.jsx # Component bảng chứa danh sách sản phẩm
│       │   └── ProductRow.jsx   # Component render từng dòng sản phẩm (Nhận props từ Table)
│       ├── data/data.js    # Khởi tạo dữ liệu giả lập cho ứng dụng React
│       └── styles/app.css  # Styles cho ứng dụng React
└── README.md               # Tài liệu hướng dẫn và thông tin sinh viên