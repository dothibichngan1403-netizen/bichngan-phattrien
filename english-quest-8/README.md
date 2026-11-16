# English Quest 8 — Hành trình tiếng Anh lớp 8 (Bản PWA v1.1)

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

- Ảnh 3 giáo viên (Ms. Mia, Mr. Ethan, Ms. Sofia) đã nhúng sẵn trong `index.html`
  (base64, giữ nguyên 100% file gốc chị gửi ngày 16/11/2026). File gốc giữ trong
  thư mục `teachers/` kèm theo để đối chiếu.
- Tiến độ học lưu riêng trên từng máy (localStorage `eq8_state_v1`).
