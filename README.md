# 💍 Thiệp Cưới Online: Gia Huy 11 & Phương Anh 11

> **Ngày thành hôn:** 11:11 30/11/2026  
> **Gói xuất bản:** Tự động tạo bởi Hệ thống Quản trị Thiệp Cưới Online (LS-Wedding).

Gói mã nguồn này đã được tối ưu hóa toàn bộ thành **Static Site (HTML/CSS/JS thuần)**, không phụ thuộc vào bất kỳ máy chủ PHP hay cơ sở dữ liệu MySQL nào. Bạn có thể mở offline trên máy tính hoặc tải lên GitHub Pages miễn phí hoàn toàn.

---

## 🚀 HƯỚNG DẪN SỬ DỤNG

### CÁCH 1: Xem trực tiếp Offline trên máy tính cá nhân
1. Giải nén file `.zip` vào một thư mục bất kỳ.
2. Click đúp vào file **`index.html`** để mở trên bất kỳ trình duyệt nào (Google Chrome, Microsoft Edge, Safari, Firefox).
3. *(Tùy chọn)* Nếu bạn dùng VS Code, bạn có thể click chuột phải vào `index.html` và chọn **Open with Live Server**.

---

### CÁCH 2: Xuất bản lên GitHub Pages (Miễn phí vĩnh viễn)

Chỉ với 3 bước đơn giản dưới đây, bạn sẽ có ngay một trang web thiệp cưới online dạng `https://<ten-github>.github.io/<ten-repo>/`:

#### Bước 1: Tạo Repository trên GitHub
1. Đăng nhập vào tài khoản [GitHub](https://github.com/).
2. Nhấn vào nút **New** (Tạo mới Repository) hoặc truy cập [github.com/new](https://github.com/new).
3. Đặt **Repository name** (ví dụ: `test` hoặc `dam-cuoi`).
4. Chọn chế độ **Public**.
5. Nhấn nút **Create repository**.

#### Bước 2: Tải toàn bộ mã nguồn lên GitHub
- **Cách giao diện web (Đơn giản nhất):**
  1. Trong trang repository vừa tạo, nhấn vào liên kết **uploading an existing file**.
  2. Kéo thả **tất cả các file và thư mục** trong gói giải nén này (bao gồm file `index.html`, `404.html`, `.nojekyll`, thư mục `template...`, `js`, `storage`, v.v.) vào trình duyệt.
  3. Chờ các file tải lên hoàn tất, sau đó nhấn nút xanh **Commit changes**.
- **Cách dùng lệnh Git (Dành cho lập trình viên):**
  ```bash
  git init
  git add .
  git commit -m "Phát hành thiệp cưới Gia Huy 11 & Phương Anh 11"
  git branch -M main
  git remote add origin https://github.com/<tai-khoan-cua-ban>/test.git
  git push -u origin main
  ```

#### Bước 3: Kích hoạt GitHub Pages
1. Tại repository của bạn trên GitHub, nhấn vào tab **Settings** (Cài đặt).
2. Ở thanh menu bên trái, tìm và nhấn vào mục **Pages** (mục con của Code and automation).
3. Tại phần **Build and deployment**:
   - **Source**: Chọn `Deploy from a branch`.
   - **Branch**: Chọn nhánh `main` (hoặc `master`), thư mục chọn `/(root)`.
   - Nhấn nút **Save**.
4. Chờ khoảng 1 - 2 phút, GitHub Pages sẽ cấp cho bạn một đường dẫn công khai:
   👉 `https://<tai-khoan-cua-ban>.github.io/test/`

---

### CÁCH 3: Cài đặt Tên Miền Riêng (Custom Domain - ví dụ: `tuan-linh.wedding`)
Nếu bạn đã mua tên miền riêng và muốn gán vào GitHub Pages:
1. Trong trang quản lý DNS của tên miền (Cloudflare, Nhà đăng ký tên miền...), thêm 4 bản ghi `A` trỏ về IP của GitHub:
   - `185.199.108.153`
   - `185.199.109.153`
   - `185.199.110.153`
   - `185.199.111.153`
2. Thêm 1 bản ghi `CNAME` cho `www` trỏ về `<tai-khoan-cua-ban>.github.io`.
3. Vào lại mục **Settings -> Pages** trên GitHub, nhập tên miền vào ô **Custom domain** rồi nhấn **Save**.
4. Tích chọn **Enforce HTTPS** để kích hoạt chứng chỉ bảo mật SSL miễn phí.

---

## 💌 VỀ TÍNH NĂNG LỜI CHÚC & XÁC NHẬN THAM DỰ (RSVP)
- **Khi xem offline:** Danh sách lời chúc đã được lưu sẵn dạng bản chụp (snapshot) trong file `data/wishes.json` và nhúng sẵn vào trang.
- **Khi chạy trên GitHub Pages:** Nếu thiết bị có kết nối Internet, mọi lời chúc hoặc xác nhận tham dự (RSVP) của khách mời sẽ tự động đồng bộ về hệ thống quản trị trung tâm để cô dâu & chú rể tiện theo dõi!

---
*Chúc hai bạn trăm năm hạnh phúc! ❤️*