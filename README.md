# Bài tập 3: So sánh Markdown và HTML trong hệ thống GreenTech
## Phần 1. Phân tích bài toán
- Token là đơn vị nhỏ mà AI sử dụng để chia văn bản thành các phần xử lý. Một từ có thể tương ứng với số lượng token nhất định
- Markdown thường ngắn gọn hơn HTML vì sử dụng ít kí tự định dạng hơn. Ví dụ, để in đậm chữ "độ ẩm", Markdown sử dụng cú pháp ** ___ ** còn HTML cần <strong> ___ </strong>
- Văn bản ngắn gọn thường giúp token đầu vào giảm, từ đó giảm chi phí xử lý và thời gian truyền tải dữ liệu. Tuy nhiên, số Token thực tế còn phụ thuộc vào cách mã hóa token xử lí nội dung
## Phần 2. so sánh và đánh giá
| Tiêu chí | Markdown | HTML |
|---|---|---|
| Cú pháp in đậm | ** __ ** | <strong>  __ </strong> |
| Số ký tự ví dụ | 11 kí tự | 27 kí tự |
| Độ dễ đọc | Ngắn gọn dễ hiểu | Nhiều thẻ định dạng |
| Số token | Thường ít hơn với nội dung tương đương | Có thể nhiểu hơn do thẻ mở và đóng |
| Khả năng định dạng | Phù hợp tài liệu, tiêu đề, danh sách, bảng | Định dạng giao diện chi tiết, linh hoạt |
| Xử lý bằng AI | Thuận tiện với văn bản và dữ liệu đơn giản | Có thể cần xử lý thêm các thẻ HTML |
| Ứng dụng | Prompt AI, tài liệu hướng dẫn, báo cáo | Website, giao diện web |

Giải pháp cho GreenTech
GreenTech nên ưu tiên sử dụng Markdown để truyền các câu hỏi và câu trả lời về nông nghiệp cho AI.
Lý do:
- Tiết kiệm dữ liệu đầu vào khi nội dung tương đương được biểu diễn bằng ít Token hơn.
- Giúp AI dễ nhận biết tiêu đề, danh sách và các ý chính.
- Giúp lập trình viên dễ đọc, chỉnh sửa và bảo trì nội dung.
- Có thể chuyển Markdown thành HTML khi cần hiển thị câu trả lời trên websit
