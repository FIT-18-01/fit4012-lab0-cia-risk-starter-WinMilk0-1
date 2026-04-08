# FIT4012 - Report 1 Page
## Lab 01 - CIA & Risk: Hệ thống lưu điểm

### 1. Mục tiêu bài lab
- Nhận diện tài sản cần bảo vệ trong một hệ thống thông tin đơn giản.
- Phân biệt Confidentiality, Integrity, Availability.
- Xác định threat, vulnerability, mitigation.
- Thực hành workflow GitHub cơ bản để nhận và nộp bài.

### 2. Cách làm
- Đọc bối cảnh và xác định các thành phần quan trọng của hệ thống.
- Phân tích từng sự cố theo bộ ba CIA.
- Chọn sự cố B để phân tích sâu hơn theo threat - vulnerability - mitigation.
- Hoàn thiện bài làm trong repo và commit/push lên GitHub.

### 3. Kết quả chính
**Assets:**
- Dữ liệu điểm số của sinh viên.
- Thông tin đăng nhập của giảng viên và sinh viên.

**CIA mapping:**
- Sự cố A -> Availability
- Sự cố B -> Integrity
- Sự cố C -> Confidentiality

**Phân tích sự cố B:**
- Threat: Người dùng trái phép hoặc nội bộ độc hại sửa đổi điểm số.
- Vulnerability: Kiểm soát truy cập yếu và thiếu cơ chế xác nhận các thay đổi dữ liệu.
- Mitigation: Thiết lập xác thực mạnh, phân quyền rõ ràng cho việc sửa điểm và ghi nhật ký audit để phát hiện thay đổi bất thường.

### 4. Kết luận ngắn
Bài lab giúp tôi hiểu rõ hơn cách phân tích sự cố an toàn thông tin bằng mô hình CIA. Phần khó nhất là xác định đúng loại threat và vulnerability vì chúng có thể xuất phát từ cả yếu tố kỹ thuật và con người. Em cần chú ý rằng mỗi sự cố cần giải pháp mitigation riêng, đồng thời cần kết hợp kiểm soát truy cập và giám sát hệ thống.
