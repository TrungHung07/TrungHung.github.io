# Portfolio Website

Một trang portfolio đơn giản, đẹp mắt được tạo bằng HTML, CSS, và JavaScript.

## ✨ Tính năng

- 🎨 Giao diện hiện đại với gradient đẹp
- 📱 Responsive (tương thích với mọi thiết bị)
- 📄 Modal hiển thị resume (PDF)
- 📧 Form liên hệ tích hợp
- 🔗 Liên kết mạng xã hội
- ⚡ Smooth animations

## 📝 Cách sử dụng

### 1. Tùy chỉnh thông tin cá nhân

**Trong file `index.html`:**

```html
<!-- Đổi tên của bạn -->
<h1 class="name">Your Name</h1>

<!-- Đổi vị trí công việc -->
<p class="title">Full Stack Developer</p>

<!-- Đổi bio -->
<p class="bio">
    Welcome to my portfolio! I'm passionate about creating amazing web experiences.
</p>

<!-- Đổi email -->
<a href="mailto:your@email.com" title="Email">
```

### 2. Thêm avatar

1. Đặt ảnh avatar với tên `avatar.jpg` trong cùng thư mục
2. Hoặc đổi tên file trong HTML:
   ```html
   <img src="your-image-name.png" alt="Avatar" class="avatar">
   ```

### 3. Thêm resume (PDF)

1. Đặt file PDF resume với tên `resume.pdf` trong cùng thư mục
2. Hoặc đổi tên file trong HTML:
   ```html
   <iframe id="resumeIframe" src="your-resume-name.pdf" type="application/pdf"></iframe>
   <a id="downloadLink" href="your-resume-name.pdf" download>
   ```

### 4. Cập nhật liên kết mạng xã hội

Tìm phần này trong `index.html`:

```html
<div class="social-links">
    <a href="https://github.com/your-username" target="_blank" title="GitHub">
    <a href="https://linkedin.com/in/your-profile" target="_blank" title="LinkedIn">
    <a href="mailto:your@email.com" title="Email">
```

## 🚀 Deploy bằng GitHub Pages

### Bước 1: Tạo repository GitHub

1. Đăng nhập vào **GitHub** (github.com)
2. Nhấn **New** để tạo repository mới
3. Đặt tên: `your-username.github.io`
   - VD: `john-doe.github.io`
4. Chọn **Public**
5. Nhấn **Create repository**

### Bước 2: Push code lên GitHub

Mở PowerShell/Terminal và chạy các lệnh sau:

```powershell
# Di chuyển vào thư mục portfolio
cd "c:\Users\admin\Desktop\New folder\astro-portfolio-template"

# Khởi tạo git (nếu chưa có)
git init

# Thêm tất cả file
git add .

# Commit
git commit -m "Initial portfolio commit"

# Thêm remote repository
git remote add origin https://github.com/your-username/your-username.github.io.git

# Push lên main branch
git branch -M main
git push -u origin main
```

### Bước 3: Kích hoạt GitHub Pages

1. Vào **Settings** của repository
2. Cuộn xuống tìm **Pages**
3. Chọn branch **main**
4. Chọn folder **/ (root)**
5. Nhấn **Save**

### Bước 4: Truy cập website

Sau vài giây, trang web sẽ có sẵn tại:
```
https://your-username.github.io
```

## 📂 Cấu trúc file

```
portfolio/
├── index.html      # File HTML chính
├── style.css       # File CSS (styling)
├── script.js       # File JavaScript (tương tác)
├── avatar.jpg      # Ảnh avatar của bạn
├── resume.pdf      # File resume PDF
└── README.md       # This file
```

## 🔄 Cập nhật sau khi deploy

Mỗi lần bạn thay đổi file:

```powershell
# Thêm thay đổi
git add .

# Commit
git commit -m "Update portfolio"

# Push lên GitHub
git push
```

Trang web sẽ tự động cập nhật trong vài giây!

## 🎨 Tùy chỉnh màu sắc

Bạn có thể thay đổi màu gradient trong `style.css`:

```css
body {
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
}
```

Đổi các mã màu hex (`#667eea`, `#764ba2`) với màu bạn thích.

## ⚙️ Màu tương thích

Dưới đây là một số gợi ý kết hợp màu:

- **Tím xanh (hiện tại)**: `#667eea` → `#764ba2`
- **Hồng cam**: `#f093fb` → `#f5576c`
- **Xanh dương**: `#4facfe` → `#00f2fe`
- **Xanh lá**: `#43e97b` → `#38f9d7`
- **Đỏ cam**: `#fa709a` → `#fee140`

## 📧 Hỗ trợ

Nếu có vấn đề, kiểm tra:
1. File `avatar.jpg` và `resume.pdf` có đúng vị trí không
2. Các link mạng xã hội có chính xác không
3. Email trong form có đúng không

## 📄 License

Tự do sử dụng cho mục đích cá nhân.

---

**Chúc bạn thành công với portfolio!** 🎉
