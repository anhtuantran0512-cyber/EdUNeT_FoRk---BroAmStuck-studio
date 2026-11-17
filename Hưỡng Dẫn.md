# Hướng dẫn cài

## 1. Cài Tampermonkey

- Cài Tampermonkey (bản thường hoặc bản beta) trên trình duyệt.
- Bật Developer Mode trong trang quản lý tiện ích (`chrome://extensions` với Chrome, `brave://extensions` với Brave).
- Bấm vào icon Tampermonkey, chọn **Create a new script**.
- Xoá hết nội dung mặc định, dán code vào, bấm **Save**.

Mở EduNext, nếu không thấy bảng điều khiển thì bấm `Ctrl + E`.

## 2. Lấy API key

- Vào Google AI Studio, đăng nhập tài khoản Google.
- Tạo một API key, dán vào ô trong bảng điều khiển của script.

Tài khoản miễn phí có hạn mức theo ngày và theo phút. Key tạo từ cùng một tài khoản dùng chung hạn mức đó, nên tạo thêm key không làm tăng hạn mức. Hết hạn mức thì phải chờ, script sẽ ghi lý do vào console.

Cách thứ hai là mở một tab `gemini.google.com` song song để script chuyển đề sang đó. Cách này không cần key, nhưng phụ thuộc giao diện Gemini nên dễ hỏng hơn khi Google cập nhật.

## 3. Câu hỏi hay gặp

**Đang giải thì dừng, báo lỗi?**

Phần lớn là hết hạn mức hoặc bị chặn tạm thời từ phía nhà cung cấp AI, không phải lỗi script. Đợi vài phút rồi chạy lại. Nếu vẫn lỗi, mở console trong script xem dòng cuối cùng ghi gì.

**Dán code vào Tampermonkey mà không thấy gì?**

Kiểm tra Developer Mode đã bật chưa. Sau đó bấm `Ctrl + E`. Nếu trang không nhận phím, thử `Ctrl + Shift + E`.

**Dùng bao nhiêu key là đủ?**

Một key là đủ cho nhu cầu bình thường. Muốn dùng nhiều key thì phải có nhiều tài khoản riêng, mỗi tài khoản có hạn mức riêng.

## 4. Góp ý

Lỗi hoặc góp ý: mở issue trong repo, hoặc nhắn qua Facebook ở phần liên hệ trong README.
