# Lab 01 Answers
## CIA & Risk: Hệ thống lưu điểm

**Họ và tên:** Mạc Đức Thắng    

**MSV:** 1871020530

**Lớp:** CNTT 18-01

---

## 1. Assets
Liệt kê ít nhất 2 assets cần bảo vệ.

- Asset 1: Dữ liệu điểm số của sinh viên.
- Asset 2: Thông tin tài khoản đăng nhập của giảng viên và sinh viên.
- Asset 3: Hệ thống và cơ sở dữ liệu lưu trữ điểm.

---

## 2. Mapping CIA
Ghép từng sự cố với CIA.

- Sự cố A -> Availability
- Sự cố B -> Integrity
- Sự cố C -> Confidentiality

---

## 3. Phân tích sự cố B
- Threat: Một người dùng trái phép hoặc nội bộ độc hại sửa đổi dữ liệu điểm số.
- Vulnerability: Kiểm soát truy cập yếu và thiếu cơ chế xác minh thay đổi dữ liệu.
- Mitigation: Áp dụng kiểm soát truy cập chặt chẽ, xác thực đa yếu tố cho người dùng có quyền sửa điểm và ghi nhật ký audit để phát hiện thay đổi bất thường.

---

## 4. Reflection
Sự cố B cho thấy Integrity rất quan trọng trong hệ thống lưu điểm, vì thay đổi dữ liệu sai có thể ảnh hưởng trực tiếp đến kết quả học tập của sinh viên. Tôi sẽ ưu tiên xử lý các lỗ hổng về kiểm soát truy cập và xác thực trước, rồi mới xử lý các vấn đề khác. Việc ghi nhật ký audit và kiểm tra phân quyền sẽ giúp phát hiện sớm và khôi phục dữ liệu khi cần. Từ bài lab, tôi hiểu rõ hơn cách phân biệt CIA và cách chọn mitigation phù hợp cho mỗi sự cố.

---

## 5. Bonus Flag
`FIT4012{A-A-B-I-C-C}`

Flag của em: FIT4012{A-A-B-I-C-C}

