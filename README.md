# Phát triển bản thân cùng các tư tưởng lớn

**Biên soạn:** Jenifer_DoNa
**Định dạng:** Ứng dụng web một file HTML duy nhất, mở bằng trình duyệt là dùng ngay.
**Ngày tạo:** 13/11/2026

## Nội dung

Hành trình học 100 ngày, gồm:

- **10 chủ đề** phát triển bản thân
- **100 người thầy** (nhà tâm lý học, triết gia, giáo sư, chuyên gia hàng đầu thế giới)
- **1.000 tư tưởng tinh hoa**, mỗi tư tưởng gồm 3 phần: Tư tưởng gốc, Giải thích, Ứng dụng thực tế
- Mỗi bài học có thêm Đoạn tổng hợp và Triết lý đúc kết
- Bảng tổng kết và danh mục nguồn tham khảo xác thực cho từng chủ đề
- Phần tổng kết chung và Kế hoạch áp dụng thực tế trong 30 ngày

### 10 chủ đề

| Chủ đề | Nội dung | Ngày | Người thầy đại diện |
| --- | --- | --- | --- |
| 1 | Phát triển bản thân và kỷ luật | 1–10 | Jim Rohn |
| 2 | Sức mạnh của thói quen nhỏ | 11–20 | James Clear |
| 3 | Tư duy phát triển và niềm tin vào khả năng học hỏi | 21–30 | Carol S. Dweck |
| 4 | Làm chủ cuộc đời và quản lý ưu tiên | 31–40 | Stephen R. Covey |
| 5 | Giao tiếp và thấu hiểu con người | 41–50 | Dale Carnegie |
| 6 | Kiên trì và theo đuổi mục tiêu dài hạn | 51–60 | Angela Duckworth |
| 7 | Lòng can đảm và sống chân thành | 61–70 | Brené Brown |
| 8 | Thiết lập mục tiêu, quản lý thời gian và hành động hiệu quả | 71–80 | Brian Tracy |
| 9 | Niềm tin, động lực và hành động | 81–90 | Tony Robbins |
| 10 | Trí tuệ cảm xúc và làm chủ bản thân | 91–100 | Daniel Goleman |

## Cách sử dụng

1. Mở file `Phat-trien-ban-than-cung-cac-nha-tu-tuong-lon_Jenifer-DoNa.html` bằng bất kỳ trình duyệt nào (điện thoại hoặc máy tính). Không cần cài đặt, không cần mạng (trừ phông chữ hiển thị).
2. Học mỗi ngày một bài, 15–20 phút. Trang chủ luôn hiển thị bài tiếp theo chưa học.
3. Bấm vào ảnh để xem nguyên tấm ở chế độ toàn màn hình.
4. Cuối mỗi bài: đánh dấu đã học, thêm vào yêu thích, ghi 3 dòng chiêm nghiệm vào sổ tay.
5. Dùng mục Tìm kiếm để tra cứu tên người thầy, tư tưởng hoặc từ khóa (gõ không dấu vẫn tìm được).
6. Nút A− / A+ ở góc phải trên cùng để chỉnh cỡ chữ.

Tiến độ học, bài yêu thích và sổ tay được lưu trong trình duyệt của người dùng. Xóa dữ liệu trình duyệt sẽ mất các thông tin này.

## Quy tắc trình bày

- Ảnh chân dung hiển thị nguyên tấm, không cắt khung.
- Tên sách và từ quan trọng in đậm, tô màu nổi bật luân phiên: đỏ, cam, xanh dương, tím, xanh lá.
- Văn phong trong ứng dụng theo phong cách báo chí: ngắn gọn, trực diện, đúng chính tả tiếng Việt.
- Nội dung bài học xưng hô với độc giả là “bạn” (nói với từng người đọc) và “chúng ta” (nói chung). Các trường hợp giữ nguyên “chị”: “chị em” khi chỉ phụ nữ nói chung, “chị ấy” và “chị ơi” khi nhắc tới người thứ ba trong câu chuyện ví dụ.
- Nội dung 100 bài học giữ nguyên văn bản gốc. Mục “Triết lý đúc kết” vẫn ghi tên Jade_DoNa; trang bìa và tiêu đề ghi biên soạn Jenifer_DoNa.

## Nguồn và cách dựng lại

- **File nguồn nội dung:** `HANH_TRINH_10_CHU_DE_100_NGUOI_THAY_PHAT_TRIEN_BAN_THAN.md` (8.227 dòng, file gốc giữ nguyên xưng hô “chị”).
- **Ảnh chân dung:** 10 ảnh trong thư mục ảnh của người dùng (`h1`, `h3`–`h11`). Lưu ý: hai ảnh `h7` và `h10` trùng nhau (ảnh vest trắng ngồi ghế), nên chủ đề 5 và 9 đang dùng chung một ảnh.
- **Bộ công cụ dựng web** (trong thư mục làm việc `workspace/work/ptbt-build/`):
  - `parse.py` — đọc file nguồn, chuyển xưng hô, xuất `data.json` (đã kiểm tra: đủ 100 bài, 1.000 tư tưởng).
  - `template.html` — giao diện và logic ứng dụng.
  - `build.py` — ghép dữ liệu và ảnh (nén còn chiều rộng 760 px) thành file HTML hoàn chỉnh.
- Để cập nhật nội dung: sửa file nguồn, chạy lại `parse.py` rồi `build.py`.

## Lịch sử thay đổi

- **13/11/2026 — Bản đầu tiên:** đủ 100 bài, 1.000 tư tưởng; theo dõi tiến độ, yêu thích, sổ tay, tìm kiếm.
- **13/11/2026 — Bản chỉnh trình bày:** ảnh hiển thị nguyên tấm, bấm vào ảnh xem lớn; từ quan trọng in đậm, tô màu; chữ trong ứng dụng viết theo phong cách báo chí.
- **13/11/2026 — Bản đổi xưng hô:** “chị” chuyển thành “bạn/chúng ta” theo ngữ cảnh (5.167 chỗ) trong toàn bộ website.
