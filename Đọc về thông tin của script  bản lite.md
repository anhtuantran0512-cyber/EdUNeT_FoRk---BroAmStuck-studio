# EdUNeT_FoRk---BroAmStuck-studio

Hi toi là T đây là 1 dự án nhỏ của tôi :V 
- Thật ra tôi không có ý tưởng nên thử làm 1 client riêng cho wed edunext thôi mục đích tạo tiền đề cho dự án lớn thôi :))
- Gửi những người đã đọc được script này : Script chỉ mang tính chất tham khảo,học thuật,giả lập hành vi và vận dụng script vào việc can thiệp wed nhằm thu thập dữ liệu dụng( chỉ là học hỏi và học tập )
+ Mọi hành vi gian lận , sử dụng script ngoài mục đích học tập và test được xem là vi phạm pháp luật và vi phạm nội quy nhà trường 
+ Mọi hành vi gian lận , lợi dụng , học vẹt học sinh ,sinh viên tận dụng phải tự CHỊU TRÁCH NHIỆM CHO HÀNH VI của mình khi sử dụng script thiệp
+ Sẽ ngừng hỗ trợ từ bản 1.0.7 
- **Edufork_lite v1.0.7 :** 

**Sơ lược :**  
 **Liên kết chính chủ: Facebook:** 
 - Liên hệ nế có vấn đề : https://www.facebook.com/TuanNotTun/
 • Phạm vi hoạt động (@match):
 • https://fsc-edunext.fpt.edu.vn/* (Trang học EduNext FSC)
 • https://edunext.fpt.edu.vn/* (Trang học EduNext chính)
 • https://gemini.google.com/* (Tab cầu nối AI Cross-Tab Bridge)

   Mở khóa thao tác (inputUnblocker): Gỡ bỏ hoàn toàn các rào cản chặn copy, paste, cut,
  contextmenu mà trang web EduNext thiết lập, trả lại quyền chuột phải và dán phím tắt tự do
  cho người dùng.
- **Log :** Ghi lại toàn bộ dữ liệu của wed,file wed cung cấp ( dựa vào auth_token trick discord :V )
- **Giả lập sự kiện focus** 
  • Trích xuất văn bản câu hỏi: Sử dụng bộ lọc loại bỏ thẻ rác, định vị thẻ chứa bài tập (.
  exercise-question-block) hoặc tin nhắn mới nhất của trợ lý bot EduNext.
  • Trích xuất ảnh (extractImages): Tự động quét toàn bộ thẻ <img>, cú pháp hình ảnh Markdown
  và các thẻ đồ thị <canvas>. Các ảnh được tải về dưới dạng nhị phân thông qua
  GM_xmlhttpRequest và chuyển đổi sang chuỗi Base64 (data:image/png;base64,...) để cấp trực
  tiếp cho mô hình thị giác AI.
  • Ngữ cảnh tài liệu & dữ kiện phụ trợ: Tự động đọc nội dung bài đọc ở khung bên trái
  (extractLessonContext) và ghi chú dữ kiện nằm bên dưới khung chat (extractBottomContext) để
  đưa vào prompt tham chiếu.
  • Hệ thống được thiết kế theo mô hình kiến trúc hướng đối tượng đan chéo máy trạng thái hữu hạn
  (Finite State Machine - FSM) khép kín, hoạt động hoàn toàn tự trị mà không can thiệp thô bạo
  vào server ( vi phạm nếu cố tình khai thác thêm )
  • Thiết kế : Thiết kế này broamstuck lấy ý tưởng từ hyperland và dymamic island , hex phối màu gồm aura 
- **Thông tin bản pre :** 
+ Tích hợp api toàn bộ cho các loại ai khác nhau , api không bị delay hay nỗi do spam quota , nâng giới hạn swap lên vô hạn ( lite chỉ có hỗ trợ gemini và cơ bản)
+ Thiết kế riêng về chuỗi tự động hóa , tự train ai , machine learing giả lập học sinh học hành vi thao tác 
+ Không giới hạn api và 25+ tính năng riêng  ,............... ( ib để biết thêm về bản đại cập nhật pre fork )
+ Mọi Hành vi leak file,can thiệp ,scan web, tái cấu trúc scipt để tận dụng làm việc xấu sẽ bị nghiêm cấm và mọi thông tin về sự thay đổi, người thay đổi của script sẽ được gửi thẳng về chính chủ 
      🛡️ BẢN QUYỀN SỞ HỮU TRÍ TUỆ THUỘC VỀ BROAMSTUCK (đừng có táy máy gì đấy )
