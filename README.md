# Open-ViERP 🚀

> **Giải pháp ERP mã nguồn mở tinh gọn, hiệu năng cao và thuần Việt dành cho doanh nghiệp vừa và nhỏ.**

Open-ViERP là một hệ thống quản trị doanh nghiệp (ERP) mã nguồn mở được thiết kế và tối ưu riêng cho các doanh nghiệp tại Việt Nam. Dự án tập trung vào tính linh hoạt, tốc độ xử lý vượt trội, cấu trúc mô-đun hóa dễ mở rộng và khả năng tùy biến 100% theo quy trình thực tế.

---

## 💡 Tại sao chọn Open-ViERP?

- **Thuần Việt & Chuẩn hóa:** Tích hợp sẵn quy trình quản lý doanh nghiệp, nghiệp vụ tài chính, kế toán, thu chi và quản lý nhân sự theo tiêu chuẩn Việt Nam.
- **Tối ưu hiệu năng:** Kiến trúc tinh gọn, khả năng xử lý mượt mà cho hệ thống hàng chục người dùng đồng thời và hàng nghìn dữ liệu khách hàng/chứng từ.
- **Tự chủ dữ liệu 100%:** Dễ dàng triển khai trên hạ tầng VPS/Server riêng (Self-hosted), không lo phụ thuộc nhà cung cấp dịch vụ hay phí bản quyền theo người dùng.
- **Mã nguồn mở & Dễ mở rộng:** Kiến trúc Modular architecture giúp các nhà phát triển dễ dàng viết thêm plugin, module hoặc tích hợp qua RESTful API / GraphQL.

---

## ✨ Tính năng cốt lõi (Core Features)

### 💰 1. Quản lý Tài chính & Thu Chi (Finance & Accounting)
- Quản lý sổ quỹ, dòng tiền thu - chi theo thời gian thực.
- Theo dõi công nợ phải thu của khách hàng và công nợ phải trả cho nhà cung cấp.
- Quản lý hóa đơn, chứng từ và xuất báo cáo tài chính định kỳ.

### 👥 2. Quản lý Nhân sự & Chấm công (HRM & Payroll)
- Quản lý hồ sơ nhân viên, hợp đồng lao động, lịch sử công tác.
- Hệ thống chấm công, tích hợp dữ liệu từ máy chấm công hoặc ứng dụng di động.
- Tính lương tự động theo ca, thưởng, phạt và các khoản đóng bảo hiểm.

### 🤝 3. Quản lý Khách hàng & Bán hàng (CRM & Sales)
- Lưu trữ & phân loại dữ liệu 1.000+ khách hàng, đối tác.
- Theo dõi lịch sử giao dịch, cơ hội bán hàng và chăm sóc khách hàng.
- Quản lý đơn hàng, báo giá và hợp đồng kinh doanh.

### 📦 4. Quản lý Kho & Tồn kho (Inventory Management)
- Quản lý danh mục hàng hóa, nhập - xuất - tồn kho.
- Kiểm kê kho tự động, cảnh báo ngưỡng tồn kho tối thiểu.

---

## 🛠 Tech Stack

- **Backend:** PHP / Laravel Framework (Tương thích tốt với các engine tối ưu hiệu năng cao)
- **Frontend:** Vue.js / React / Tailwind CSS
- **Database:** MySQL / PostgreSQL / Redis Cache
- **API:** RESTful API & GraphQL support

---

## 🚀 Hướng dẫn Cài đặt (Quick Start)

### Yêu cầu hệ thống
- PHP >= 8.1
- Composer >= 2.0
- MySQL >= 8.0 / PostgreSQL >= 13
- Node.js >= 18.x & NPM/Yarn

### Các bước cài đặt

1. **Clone repository:**
   ```bash
   git clone [https://github.com/puleeno/Open-ViERP.git](https://github.com/puleeno/Open-ViERP.git)
   cd Open-ViERP

```

2. **Cài đặt các gói phụ thuộc (Dependencies):**
```bash
composer install
npm install

```


3. **Cấu hình môi trường (`.env`):**
```bash
cp .env.example .env
php artisan key:generate

```


*Cập nhật thông tin kết nối CSDL trong file `.env`.*
4. **Chạy Migration & Seed dữ liệu mẫu:**
```bash
php artisan migrate --seed

```


5. **Biên dịch Frontend & Khởi chạy server:**
```bash
npm run build
php artisan serve

```


Truy cập ứng dụng tại: `http://localhost:8000`

---

## 🤝 Đóng góp (Contributing)

Mọi đóng góp từ cộng đồng đều được trân trọng! Hãy giúp **Open-ViERP** ngày càng hoàn thiện hơn bằng cách:

1. Fork dự án
2. Tạo nhánh feature mới (`git checkout -b feature/AmazingFeature`)
3. Commit các thay đổi (`git commit -m 'Add some AmazingFeature'`)
4. Push lên nhánh (`git push origin feature/AmazingFeature`)
5. Mở một **Pull Request**

---

## 📄 Giấy phép (License)

Dự án được phát hành dưới giấy phép [MIT License](https://www.google.com/search?q=LICENSE). Bạn hoàn toàn tự do sử dụng, chỉnh sửa và phân phối cho mục đích cá nhân hoặc thương mại.

---
