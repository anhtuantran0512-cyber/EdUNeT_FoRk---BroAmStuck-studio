# EdUNeT_FoRk

![version](https://img.shields.io/badge/version-3.9.0-informational)
![platform](https://img.shields.io/badge/platform-Tampermonkey-black)

Các bản EduNext cũ và bản thử nghiệm. Bản ổn định: [Edunext_fe](https://github.com/broamstuck-cybr/Edunext_fe).

## Cách hoạt động

Giống bản chính: đọc đề trong widget bài học, lấy câu trả lời từ mô hình ngôn ngữ, ghi vào ô soạn thảo, nộp và đọc phản hồi. Khác ở chỗ bản trong repo này ưu tiên tuyến cầu nối:

1. Script ghi đề vào `GM_setValue`.
2. Tab `gemini.google.com` đang mở đọc giá trị, chèn đề vào ô chat, gửi.
3. Script trong tab Gemini chờ phần tử trả lời xuất hiện, đọc text khi nội dung ngừng tăng.
4. Kết quả ghi lại storage, tab EduNext đọc ra và điền vào ô soạn thảo.

Tuyến API trực tiếp vẫn có, dùng khi không mở tab Gemini.

## Tệp

| Tệp | Ghi chú |
| --- | --- |
| `edunext_ULTRA.user.js` | Bản mới nhất trong repo, dùng cầu nối tab Gemini |
| `edunext_ULTRA_console.js` | Bản chạy trong DevTools Console |
| `eDuNeXt_FoRk_Prenium_V1.js` | Bản cũ, không cập nhật |
| `eDuNeXt_FoRk_liteV1.0.7.js` | Bản đầu tiên, lưu trữ |

## Cài đặt

1. Cài Tampermonkey hoặc Violentmonkey, bật Developer Mode.
2. Mở `edunext_ULTRA.user.js`, bấm **Raw**, bấm **Install**.
3. Mở EduNext, bấm `Ctrl + E`.
4. Mở thêm một tab `gemini.google.com` nếu dùng tuyến cầu nối.

`Ctrl + E` mở/đóng bảng điều khiển. `Ctrl + Shift + X` dừng khẩn cấp. `Esc` đóng bảng.

## Giới hạn

- Cũ hơn bản ở `Edunext_fe`; vài lỗi đã sửa ở đó nhưng chưa có ở đây.
- Cầu nối phụ thuộc DOM của `gemini.google.com` và trạng thái đăng nhập của tab đó.
- Đề là video hoặc cần thao tác ngoài khung chat: script dừng.
