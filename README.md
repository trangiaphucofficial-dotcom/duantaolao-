# Bó Hoa Tulip & Bầu Trời Sao — Web Tương Tác

Dự án web tĩnh tương tác (HTML5 Canvas + Web Audio API) dành cho các dịp lễ kỷ niệm, ngày tri ân (20/10, 20/11) được tối ưu hóa để chạy trực tiếp trên GitHub Pages.

## Link Demo / Truy cập trực tiếp
👉 `https://trangiaphucofficial-dotcom.github.io/duantaolao-/`

---

## Cấu trúc và Tính năng
- **Bầu trời đêm & sao băng:** Vẽ bằng HTML5 Canvas, hiệu ứng ánh sáng động và đom đóm bay.
- **Bó hoa Tulip:** Vẽ vector trực tiếp qua Canvas với hiệu ứng hoa nở và rung rinh theo gió.
- **Hộp quà & Bìa thư tương tác:** Chạm mở phong bì thư phong cách vintage với hiệu ứng typewriter.
- **Âm thanh nền (BGM):** Tạo nhạc piano lãng mạn trực tiếp bằng Web Audio API, không cần tải file MP3 ngoài.
- **Zero-dependency:** Chạy trực tiếp 100% trên trình duyệt (hỗ trợ mobile & desktop).

---

## Prompt Template để tái sử dụng lần sau

Khi cần tạo hoặc tùy biến một dự án tương tự, sử dụng mẫu prompt sau:

```text
Tạo một trang web tĩnh tương tác chạy trực tiếp trên GitHub Pages bằng 1 file index.html duy nhất (HTML5, Tailwind CSS qua CDN, Canvas API, Web Audio API):
- Chủ đề: [Nhập sự kiện: 20/10, 20/11, sinh nhật...]
- Đối tượng nhận: [Gửi bạn bè, thầy cô, người yêu...]
- Hiệu ứng: Mở phong bì thư vintage, hoa nở/pháo hoa canvas, nhạc du dương Web Audio.
- Tự động setup git repository cục bộ và hướng dẫn push lên GitHub Pages.
```

---

## Cách triển khai nhanh cho dự án mới
```bash
# 1. Khởi tạo repo
git init
git add index.html
git commit -m "feat: initial release"
git branch -M main

# 2. Đẩy lên GitHub
git remote add origin https://github.com/<username>/<repo-name>.git
git push -u origin main

# 3. Kích hoạt GitHub Pages
# Vào GitHub Repo -> Settings -> Pages -> Chọn nhánh 'main' và thư mục '/ (root)' -> Save.
```
