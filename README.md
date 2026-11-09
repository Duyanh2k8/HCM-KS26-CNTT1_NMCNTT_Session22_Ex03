# Bài 3 : Sử dụng AI an toàn khi xử lý lỗi phần mềm
## 1. Báo cáo phân tích theo mô hình IPO
<kbd>INPUT</kbd> **Đầu vào**
- Câu trả lời của AI về cách sửa lỗi `Path not found` khi cài đặt Python.
- Một câu lệnh Terminal do AI đề xuất nhưng chưa rõ nguồn gốc và mức độ an toàn.
- Thông tin về hệ điều hành và phiên bản Python đang sử dụng.

<kbd>PROCESS</kbd> **Quy trình xử lý và kiểm chứng**
1. Không chạy ngay câu lệnh do AI cung cấp.
2. Phân tích từng thành phần của câu lệnh để hiểu chức năng.
3. Sử dụng Google với toán tử tìm kiếm:
```text
site:stackoverflow.com "Path not found" Python
```
4. Kiểm tra tài liệu chính thức của Python tại [https://www.python.org/] và tài liệu Windows tại [https://learn.microsoft.com/].
5. Đối chiếu câu lệnh với hệ điều hành, phiên bản Python và mục đích sử dụng.
6. Kiểm tra xem lệnh có quyền quản trị, xóa dữ liệu hoặc thay đổi cấu hình hệ thống hay không.

<kbd>OUTPUT</kbd> **Đầu ra**
## 2. Thiết kế Prompt hỏi ngược lại AI
```text
Bạn vừa đề xuất cho tôi câu lệnh Terminal để sửa lỗi "Path not found" khi cài đặt Python.

Trước khi tôi thực thi, hãy phân tích và kiểm chứng độ an toàn của câu lệnh theo các yêu cầu:
1. Giải thích chức năng của từng thành phần trong câu lệnh.
2. Cho biết câu lệnh có yêu cầu quyền Administrator hay không.
3. Câu lệnh có thể xóa dữ liệu, thay đổi Registry, biến môi trường PATH hoặc ảnh hưởng đến hệ điều hành không?
4. Kiểm tra câu lệnh có phù hợp với Windows 11 và phiên bản Python tôi đang sử dụng không.
5. Đưa ra nguồn tài liệu chính thức từ Python hoặc Microsoft để xác minh.
6. Nếu câu lệnh không an toàn hoặc không cần thiết, hãy đề xuất phương án sửa lỗi khác an toàn hơn.

Không được khẳng định câu lệnh an toàn nếu chưa có đủ căn cứ kiểm chứng. Hãy nêu rõ những điểm chưa chắc chắn và cảnh báo trước khi đề xuất thực thi.
```
