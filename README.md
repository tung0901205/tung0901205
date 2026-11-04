Xin chào, mình là Nguyễn Văn Tùng 👋

👨‍💻 Java Backend / Fullstack Developer

Sinh viên năm 4 ngành Kỹ thuật Phần mềm tại Đại học Công nghiệp Hà Nội (HaUI). Định hướng phát triển chuyên sâu về xây dựng hệ thống Backend chất lượng, kiến trúc Microservices và xử lý các bài toán nghiệp vụ phức tạp với Java & Spring Boot.

🙋‍♂️ Giới thiệu về mình

🎓 Học vấn: Đại học Công nghiệp Hà Nội (HaUI) - GPA: 3.43 / 4.0 (2 lần đạt Học bổng KKHT)

💼 Kinh nghiệm: Cựu Java Backend Intern tại Công ty Cổ phần Lạc Long Quân (08/2026 - 11/2026)

🏆 Nghiên cứu khoa học:

Giải Nhì NCKH cấp Trường (2024 - 2025) & Giải Ba NCKH cấp Trường (2025 - 2026)

🎯 Mục tiêu: Tìm kiếm cơ hội vị trí Intern/Fresher Java Backend hoặc Fullstack Developer

🛠️ Công nghệ & Kỹ năng (Tech Stack)

Backend & Frameworks

Frontend & Web

Database, Message Broker & Cache

DevOps, Tools & AI Integration

🚀 Dự án tiêu biểu

1. 📦 Quản lý Kho Đồ Điện Tử

Vai trò: Java Backend Developer (10/2026)

Tech Stack: Java, Spring Boot, Spring Data JPA, Spring Security, RESTful API, MySQL 8.4, Redis, JWT, JUnit 5, Mockito, Swagger/OpenAPI, Docker.

Xác thực & Bảo mật: Triển khai JWT (HS256) kết hợp Access Token / Refresh Token; lưu trữ bằng HttpOnly Cookie và tích hợp Redis Blacklist (TTL) phục vụ thu hồi token tức thì khi đăng xuất hoặc thay đổi mật khẩu.

Tìm kiếm & Phân trang: Xây dựng bộ lọc tìm kiếm động linh hoạt theo tên, mã, danh mục, trạng thái và khoảng giá bằng Spring Data JPA Specification.

Phân quyền (RBAC): Thiết lập phân quyền truy cập chi tiết cho 3 vai trò Admin, Nhân viên kho và Kế toán, kiểm soát chặt chẽ các API và nghiệp vụ.

Giao dịch & Đồng thời: Bảo đảm tính nguyên tử cho thao tác nhập/xuất kho bằng @Transactional; giải quyết xung đột dữ liệu khi cập nhật tồn kho bằng Optimistic Locking (@Version).

Cơ sở dữ liệu & Tối ưu: Thiết kế lược đồ MySQL tối ưu với khóa chính, khóa ngoại, Indexing; viết unit test với JUnit 5 / Mockito và áp dụng Redis Cache giúp giảm tải truy vấn DB.

2. 📄 Hệ thống Quản lý Văn bản

Vai trò: Backend Developer (Đồ án chuyên ngành - 05/2026 – 10/2026)

Tech Stack: Spring Boot, Spring Cloud Gateway, Spring Security, JWT, Apache Kafka, PostgreSQL (pgvector), Gemini API, Docker Compose.

Kiến trúc Microservices: Tách biệt hệ thống thành 5 dịch vụ độc lập (Authentication, Document, Workflow, Notification, AI); sử dụng Spring Cloud Gateway làm cổng định tuyến API Gateway tập trung.

Quy trình Phê duyệt (Workflow): Xây dựng luồng phê duyệt văn bản nhiều bước (Trình duyệt ➔ Phê duyệt ➔ Từ chối ➔ Ký ➔ Ban hành), kiểm soát trạng thái văn bản theo phân quyền Admin, Chuyên viên, Lãnh đạo.

Xử lý Bất đồng bộ: Sử dụng Apache Kafka theo mô hình Producer-Consumer để truyền nhận event giữa các service và phát thông báo realtime khi văn bản đổi trạng thái.

Tích hợp AI & Tìm kiếm Ngữ nghĩa: Tích hợp Gemini API để tự động tóm tắt và phân loại văn bản; lưu trữ Vector Embedding vào PostgreSQL (pgvector) hỗ trợ tìm kiếm ngữ nghĩa và mô hình RAG.

Triển khai: Đóng gói toàn bộ các service và cơ sở dữ liệu bằng Docker Compose.

3. 🛡️ Quản lý Tham số PMH (Maker-Checker)

Vai trò: Backend & Frontend Developer (Thực tập / Luyện tập - 09/2026 – Nay)

Tech Stack: Spring Boot, Spring Security (JWT), Spring Data JPA, Angular, TypeScript, Oracle Database, Swagger.

Nghiệp vụ Phê duyệt 2 cấp (Maker-Checker): Xây dựng hệ thống quản lý tham số cấu hình doanh nghiệp (Group Category, Components) với cơ chế kiểm soát rủi ro nghiêm ngặt.

Phân tách trách nhiệm:

Maker: Khởi tạo, chỉnh sửa cấu hình và gửi yêu cầu phê duyệt.

Checker: Kiểm tra, phê duyệt hoặc từ chối kèm lý do, hỗ trợ hủy duyệt khi cần.

Lưu vết & Bảo mật (Audit Log): Phân quyền vai trò Admin / Maker / Checker và ghi nhận chi tiết lịch sử thao tác hệ thống (Thông tin người dùng, IP, Timestamp).

📊 Thống kê GitHub

📬 Thông tin liên hệ

📱 Điện thoại: 0345040243

📧 Email: tung0901205@gmail.com

🐙 GitHub: github.com/tung0901205
