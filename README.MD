# EdUNeT_FoRk

Chỗ tôi để các bản EduNext cũ và bản đang thử. Đây không phải bản nên cài.

Bản ổn định và có tài liệu đầy đủ nằm ở repo [Edunext_fe](https://github.com/broamstuck-cybr/Edunext_fe).

## Tệp trong repo

| Tệp | Tình trạng |
|---|---|
| `edunext_ULTRA.user.js` | Bản mới nhất trong repo này, nối sang tab Gemini đang mở |
| `edunext_ULTRA_console.js` | Cùng bản trên, dạng dán vào DevTools Console |
| `eDuNeXt_FoRk_Prenium_V1.js` | Bản cũ, giữ lại để tham khảo, không còn cập nhật |
| `eDuNeXt_FoRk_liteV1.0.7.js` | Bản đầu tiên, chỉ để xem lại |

## Nó làm gì

- Đọc đề trong bài học trên EduNext, kể cả đề là ảnh vẽ trên canvas.
- Chuyển đề sang một tab `gemini.google.com` đang mở, đọc câu trả lời từ tab đó, hoặc gọi API bằng key bạn dán vào.
- Gõ câu trả lời vào ô soạn thảo và bấm nộp, sau đó đọc phản hồi của hệ thống.
- Ghi từng bước ra console để bạn theo dõi và dừng khi cần.

## Cài đặt

1. Cài Tampermonkey hoặc Violentmonkey, bật Developer Mode trong trang quản lý tiện ích.
2. Mở `edunext_ULTRA.user.js`, bấm **Raw**, bấm **Install**.
3. Vào EduNext (`fsc-edunext.fpt.edu.vn` hoặc `edunext.fpt.edu.vn`), mở một bài học.
4. Bấm `Ctrl + E` để mở bảng điều khiển.

Phím tắt: `Ctrl + E` mở/đóng bảng, `Ctrl + Shift + X` dừng khẩn cấp, `Esc` đóng bảng đang mở.

## Giới hạn

- Bản trong repo này cũ hơn bản ở `Edunext_fe`, có lỗi đã sửa ở đó mà chưa sửa ở đây.
- Cách nối sang tab Gemini phụ thuộc giao diện Gemini, Google đổi là hỏng.
- Đề là video hoặc cần thao tác ngoài khung chat thì script dừng, không tự xử lý.

## Liên hệ

- Tác giả: Trần Anh Tuấn
- Facebook: <https://github.com/broamstuck-cybr/Edunext_fe>

Tôi không bán các tệp này và không nhận làm bài hộ. Dùng thế nào là việc của bạn, kèm theo quy chế của nhà trường.
