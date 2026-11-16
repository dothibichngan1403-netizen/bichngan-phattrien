# English Quest 8 — Hành trình tiếng Anh lớp 8 (Bản PWA v1)

App học tiếng Anh lớp 8 bằng giọng nói: nghe, nói, đọc, viết cùng giáo viên ảo
(Ms. Mia, Mr. Ethan, Ms. Sofia). 2 unit: Leisure Time và Life in the Countryside.

## Cài đặt 1 nút bấm

Mở link GitHub Pages bằng **Chrome** (điện thoại Android / máy tính) rồi bấm nút
**📲 Cài app về máy** ở đầu trang → **Cài đặt**. iPhone mở bằng Safari rồi làm
theo hướng dẫn trong hộp thoại cài đặt của app.

## File trong thư mục này

- `index.html` — app (một file duy nhất)
- `manifest.webmanifest` — khai báo PWA (tên, icon, màu, standalone)
- `sw.js` — service worker, cache `english-quest-8-v1` (mở nhanh, học offline)
- `icon-192.png`, `icon-512.png`, `icon-maskable-512.png` — icon PNG (Chrome
  bắt buộc có PNG mới hiện nút cài tự động)
- `apple-touch-icon-180.png` — icon khi thêm vào Màn hình chính trên iPhone
- `icon.svg` — icon vector dự phòng

## Lưu ý

- Ảnh giáo viên (`teachers/teacher-mia.jpg`, `teacher-ethan.jpg`,
  `teacher-sofia.jpg`) chưa có trong gói này. Khi chưa có ảnh thật, app tự hiện
  ảnh minh họa có chữ cái đầu tên giáo viên thay cho khung ảnh vỡ. Gửi thêm 3
  ảnh chân dung giáo viên để gắn ảnh thật vào app.
- Tiến độ học lưu riêng trên từng máy (localStorage `eq8_state_v1`).
