# 🌟 Link Bio Cá Nhân - Sẵn sàng deploy Netlify

Trang Link-in-Bio đẹp, hiện đại, responsive, tối ưu cho mobile.

## 📁 Cấu trúc file
```
link-bio/
├── index.html   ← File chính (chỉ cần file này là đủ)
└── README.md
```

## ✏️ Cách chỉnh sửa thông tin cá nhân

Mở file `index.html` bằng bất kỳ trình soạn thảo nào (VS Code, Notepad++, ... ) và thay đổi các phần sau:

### 1. Tên & Bio
Tìm đoạn:
```html
<h1>Nguyễn Văn A</h1>
<p class="username">@nguyenvana</p>
<p class="bio">...</p>
```

### 2. Ảnh đại diện
Hiện đang dùng ảnh mặc định từ DiceBear.  
Bạn có thể:
- Đặt file `avatar.jpg` cùng thư mục rồi đổi `src="avatar.jpg"`
- Hoặc dán link ảnh online (Google Drive, Imgur, Cloudinary...)

### 3. Icon mạng xã hội
Sửa các link trong phần `.socials`:
- Facebook, Instagram, TikTok, YouTube, X...

### 4. Các nút liên kết chính
Sửa trong phần `.links`:
- Thay `href` và text cho từng nút
- Có thể thêm / bớt nút dễ dàng

## 🚀 Cách đưa lên Netlify (rất dễ)

### Cách 1: Drag & Drop (nhanh nhất)
1. Vào https://app.netlify.com
2. Đăng nhập / tạo tài khoản
3. Kéo **cả thư mục** `link-bio` (hoặc chỉ file `index.html`) thả vào vùng "Drag and drop your site output folder here"
4. Xong! Netlify sẽ cho bạn link dạng `https://random-name.netlify.app`

### Cách 2: Kết nối GitHub (khuyên dùng)
1. Đẩy thư mục lên GitHub repo
2. Vào Netlify → "Add new site" → "Import an existing project"
3. Chọn repo → Deploy

### Tùy chỉnh domain
Sau khi deploy, bạn có thể:
- Đổi tên site (Site settings → Domain management)
- Gắn domain riêng (ví dụ: links.yourname.com)

## 💡 Tips
- Ưu tiên link quan trọng nhất lên đầu
- Chỉ nên có 5–7 link chính
- Cập nhật link thường xuyên để tăng click

Chúc bạn có trang Link Bio thật đẹp! ✨
