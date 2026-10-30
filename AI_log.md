# AI LOG – BUỔI 7, TIẾT 3

> Điền vào `[ ... ]`, tích `[x]` vào lựa chọn phù hợp. Ghi đúng việc đã làm; chưa kiểm tra thì ghi “Chưa kiểm tra”. Không cần chép toàn bộ cuộc trò chuyện AI.

## Thông tin sinh viên

- Họ và tên: [ Vũ Văn Thuận ]
- Mã sinh viên – Lớp: [2071020174 ]
- Ngày thực hiện: [ 30/10/2026]
- Link repository: [https://github.com/vuvanthuan952008-dotcom/k20_Portfolio_CNTT20_02/commits?author=vuvanthuan952008-dotcom]
- URL website: [https://vuvanthuan952008-dotcom.github.io/k20_Portfolio_CNTT20_02/]
- Tình huống: [Sai link liên kết với trang css] Website của tôi  [https://github.com] Repo luyện của giảng viên

## 1. Nhận định của tôi trước khi hỏi AI

- Trang/thao tác gặp lỗi: [HTML,không có sự liên kết giữa css và html ]
- Mong muốn và hiện tượng thực tế: [Mong muốn có sự kiên kết giữa htmlvaf css,]
- Dữ kiện đã kiểm tra (cấu trúc tệp, Request URL, Status…): [https://vuvanthuan952008-dotcom.github.io/k20_Portfolio_CNTT20_02/], cấu trúc [main],https://vuvanthuan952008-dotcom.github.io/k20_Portfolio_CNTT20_02, Status [(failed]. 
- Tôi nghi nguyên nhân là: [ Sai đường dẫn liên kết file CSS trong thẻ ]
- Vì sao tôi nhận định như vậy: [ vì chưa có sự liên kết  ]

## 2. Tôi hỏi AI và nhận được gợi ý

- Nguồn: [x] Công cụ AI: [Gemini]  [ ] Phản hồi mẫu của giảng viên
- Câu hỏi/prompt tôi đã gửi (hoặc tình huống của phản hồi mẫu):

  [Tôi có URL [https://vuvanthuan952008-dotcom.github.io/k20_Portfolio_CNTT20_02/], cấu trúc [main].
Network: Request URL [https://vuvanthuan952008-dotcom.github.io/k20_Portfolio_CNTT20_02/], Status [(failed].
Tôi dự đoán [Sai Css].
Hãy nêu giả thuyết, dữ kiện cần kiểm tra và bản sửa tối thiểu.
Chỉ tư vấn, không sửa tệp. Không kết luận đã sửa thành công]

- Gợi ý chính của AI:

  [ AI hướng dẫn kiểm tra lại thuộc tính href trong thẻ <link>. Với GitHub Pages (dạng project site), nên sử dụng đường dẫn tương đối bắt đầu bằng ]

## 3. Quyết định của tôi

- [x] Chấp nhận gợi ý
- [ ] Chỉnh sửa gợi ý rồi áp dụng
- [ ] Bác bỏ gợi ý

- Tôi quyết định làm gì: [ Cập nhật lại đường dẫn file CSS trong thẻ <link> của file index.html theo dạng đường dẫn tương đối chuẩn ./css/style.css ]
- Lý do, dựa trên dữ kiện nào: [ Dựa trên lỗi 404 và gợi ý chuẩn hóa đường dẫn tương đối của AI để phù hợp với môi trường hosting trên GitHub Pages]

## 4. Thực hiện và kiểm chứng

- Tệp/vị trí đã sửa (không sửa thì ghi rõ): [ index.html (thẻ <link> phần <head>) ]
- Nội dung thay đổi hoặc cách xử lý khác: [Sửa thành <link rel="stylesheet" href="./css/style.css">]
- Commit của bản sửa, nếu có: [ CSS stylesheet link path for GitHub Pages deployment]
- Bản sửa đã deploy: [x] Có  [ ] Chưa  [ ] Không phát sinh bản sửa

| Nội dung kiểm tra | Trước xử lý | Sau xử lý/thử lại |
| Request URL và Status của tài nguyên liên quan| Giao diện/chức năng trên URL website| 
| Request URL và Status của tài nguyên liên quan | [(https://vuvanthuan952008-dotcom.github.io/k20_Portfolio_CNTT20_02/) ]  |
| Giao diện/chức năng trên URL website | [ ttps://vuvanthuan952008-dotcom.github.io/k20_Portfolio_CNTT20_02/] 

- Cách thử lại và kết quả thực tế: [Push code lên GitHub, đợi vài phút cho GitHub Actions/Pages deploy lại, sau đó truy cập lại URL website, nhấn F12 kiểm tra tab Network không còn lỗi tài nguyên ]
- Căn cứ để đối chiếu (URL tệp, commit, đường dẫn ảnh chụp hoặc dữ kiện quan sát): URL tệp, commit, đường dẫn ảnh chụp hoặc dữ kiện quan sát: [ Commit history trên GitHub repository và giao diện trực tiếp trên GitHub Pages]

## 5. Kết luận
- Điều tôi rút ra hoặc việc cần làm tiếp: [Khi đưa website lên GitHub Pages, cần chú ý sử dụng đúng đường dẫn tương đối (có tiền tố ./) và kiểm tra kỹ tab Network (F12) để phát hiện sớm các lỗi 404 tài nguyên tĩnh như CSS, hình ảnh, JavaScript ]

---

*Tệp là minh chứng MC2 để nhận định mức đạt của tiết học; không tính điểm MC2 riêng. Nếu có tình huống khác, sao chép mục 1–5 để ghi thêm.*
