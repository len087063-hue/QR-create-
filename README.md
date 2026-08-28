# QR Creator 1.0

Một công cụ tạo mã QR trực tuyến với giao diện hiện đại, hỗ trợ tạo QR từ nhiều loại nội dung và file.

## ✨ Tính năng

* 📝 Tạo QR từ văn bản hoặc URL
* 🖼️ Tạo QR từ hình ảnh
* 🎬 Tạo QR từ video
* 🎵 Tạo QR từ âm thanh
* 📁 Tạo QR từ các loại tệp
* 📤 Upload file trực tiếp
* 🖱️ Hỗ trợ kéo & thả file
* 👀 Xem trước nội dung trước khi tạo QR
* 🎨 Tùy chỉnh màu QR và màu nền
* 📐 Tùy chỉnh kích thước QR
* ↔️ Tùy chỉnh khoảng trắng QR
* 🔲 Tùy chỉnh kiểu góc QR
* ⚡ Giao diện có animation và hiệu ứng chuyển động
* 💾 Tải mã QR dưới dạng PNG
* 📱 QR có thể quét và sử dụng trên điện thoại

## 🛠️ Công nghệ

Project được xây dựng bằng:

* HTML5
* CSS3
* JavaScript
* QRCode.js
* Cloudinary
* GitHub Pages

## ☁️ Upload file

Đối với hình ảnh, video, âm thanh và tệp, QR Creator sử dụng Cloudinary để lưu trữ file và tạo URL công khai.

Luồng hoạt động:

```text
Chọn / kéo thả file
        ↓
Xem trước file
        ↓
Upload lên Cloudinary
        ↓
Nhận URL HTTPS
        ↓
Tạo mã QR
        ↓
Quét QR bằng điện thoại
        ↓
Mở file
```

## 🚀 Chạy project

### Cách 1: GitHub Pages

Repository có thể được triển khai trực tiếp bằng GitHub Pages.

Vào:

`Settings → Pages`

Sau đó chọn:

```text
Source: Deploy from a branch
Branch: main
Folder: / (root)
```

Sau khi GitHub hoàn tất deployment, mở URL GitHub Pages của repository.

### Cách 2: Chạy trực tiếp

Tải repository về máy và mở:

```text
index.html
```

bằng trình duyệt.

## 📦 Cấu trúc project

```text
QR-create-1.0/
│
├── index.html
└── README.md
```

## 🔐 Cloudinary

Project sử dụng Cloudinary Upload Preset dạng **Unsigned** để upload file từ trình duyệt.

Không đưa các thông tin bảo mật như:

* API Secret
* Mật khẩu tài khoản
* Private API credentials

vào mã nguồn công khai.

## 📱 Tương thích

QR Creator được thiết kế để sử dụng trên:

* 💻 Máy tính
* 📱 Điện thoại
* 📱 Máy tính bảng

Các trình duyệt hiện đại như Chrome, Edge, Firefox và Safari được khuyến nghị.

## 📄 License

Bạn có thể tự do sử dụng, chỉnh sửa và phát triển project này cho mục đích cá nhân.

---

## 🌐 Live Demo

**QR Creator 1.0**

https://len087063-hue.github.io/QR-create-1.0/
