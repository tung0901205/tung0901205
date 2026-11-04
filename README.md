# 👋 Xin chào, mình là Nguyễn Văn Tùng

<h3 align="center">🚀 Java Backend Developer Or Full Stack | Spring Boot | Microservices</h3>

<p align="center">
  Sinh viên năm 4 ngành Kỹ thuật Phần mềm tại <b>Đại học Công nghiệp Hà Nội</b>.<br/>
  Định hướng phát triển các hệ thống Backend ổn định, có khả năng mở rộng với Java và Spring Boot.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/GPA-3.43%2F4.00-blue?style=flat-square" />
  <img src="https://img.shields.io/badge/Java_Backend-Intern%2FFresher-orange?style=flat-square" />
  <img src="https://img.shields.io/badge/Location-Hanoi%2C_Vietnam-red?style=flat-square" />
</p>

---

## 🙋‍♂️ Giới thiệu bản thân

- 🎓 **Học vấn:** Sinh viên năm 4 ngành Kỹ thuật Phần mềm – Đại học Công nghiệp Hà Nội (HAUI). GPA: **3.43/4.00**.
- 💼 **Kinh nghiệm:** Java Backend Intern tại **Công ty Cổ phần Lạc Long Quân** (08/2026 – 11/2026).
- 🏆 **Thành tích:** Giải Nhì (2024) và Giải Ba (2025) cuộc thi Nghiên cứu Khoa học cấp Trường; 2 lần nhận Học bổng Khuyến khích học tập.
- 💡 **Quan tâm:** Java Backend Development, Full Stack, Database Design, Microservices và Event-Driven Architecture.
- 🎯 **Định hướng:** Phát triển chuyên sâu Java Backend, hướng tới xây dựng các hệ thống có tính ổn định, bảo mật và khả năng mở rộng.

## 🛠️ Tech Stack

**Backend Development**

<p>
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white"/>
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white"/>
  <img src="https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white"/>
  <img src="https://img.shields.io/badge/Spring_Data_JPA-59666C?style=for-the-badge&logo=spring&logoColor=white"/>
  <img src="https://img.shields.io/badge/Hibernate-59666C?style=for-the-badge&logo=hibernate&logoColor=white"/>
</p>

**Database & Caching**

<p>
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white"/>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white"/>
</p>

**Message Broker & Architecture**

<p>
  <img src="https://img.shields.io/badge/Apache_Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white"/>
  <img src="https://img.shields.io/badge/Microservices-2496ED?style=for-the-badge&logo=icloud&logoColor=white"/>
  <img src="https://img.shields.io/badge/RESTful_API-009688?style=for-the-badge"/>
</p>

**Tools & Technologies**

<p>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
  <img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white"/>
  <img src="https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black"/>
</p>

---

## 🚀 Dự án tiêu biểu

### 📦 [Hệ thống Quản lý Kho Đồ Điện Tử](https://github.com/tung0901205/electronics-warehouse)

<sub>**Vai trò:** Java Backend Developer | **Công nghệ:** Java, Spring Boot, Spring Security, MySQL, Redis, JWT, Docker</sub>

Hệ thống quản lý kho hàng hỗ trợ các nghiệp vụ nhập kho, xuất kho, kiểm soát tồn kho và quản lý người dùng theo vai trò.

- **Xác thực & Bảo mật:** Triển khai JWT với cặp Access Token và Refresh Token; sử dụng Redis Blacklist để thu hồi token, tăng cường bảo mật phiên đăng nhập.
- **Quản lý phân quyền:** Xây dựng cơ chế RBAC với 3 vai trò Admin, Kế toán và Nhân viên; kiểm soát quyền truy cập theo chức năng.
- **Xử lý giao dịch:** Sử dụng `@Transactional` đảm bảo tính nguyên tử của các nghiệp vụ nhập/xuất kho.
- **Đồng bộ dữ liệu:** Áp dụng Optimistic Locking (`@Version`) để phát hiện và ngăn chặn xung đột khi nhiều người dùng đồng thời cập nhật tồn kho.
- **Tối ưu hiệu năng:** Tích hợp Redis Cache và Spring Data JPA Specification hỗ trợ tìm kiếm, lọc dữ liệu động.

### 📄 [Hệ thống Quản lý Văn bản và Điều hành tác nghiệp](https://github.com/tung0901205/Document_Management_System)

<sub>**Vai trò:** Backend Developer | **Công nghệ:** Spring Boot, Microservices, Spring Cloud Gateway, Kafka, PostgreSQL, pgvector, Gemini API</sub>

Hệ thống quản lý văn bản và điều hành tác nghiệp thông minh, hỗ trợ luân chuyển văn bản, xử lý quy trình phê duyệt và khai thác thông tin bằng AI.

- **Kiến trúc hệ thống:** Thiết kế kiến trúc Microservices gồm 5 dịch vụ độc lập, định tuyến tập trung thông qua Spring Cloud Gateway.
- **Xử lý bất đồng bộ:** Tích hợp Apache Kafka để trao đổi sự kiện giữa các dịch vụ và gửi thông báo theo thời gian thực khi trạng thái văn bản thay đổi.
- **Quản lý quy trình:** Xây dựng Workflow xử lý văn bản nhiều bước, phân quyền theo 3 nhóm người dùng: Admin, Chuyên viên và Lãnh đạo.
- **Ứng dụng AI:** Tích hợp Gemini API hỗ trợ tóm tắt nội dung văn bản.
- **Tìm kiếm ngữ nghĩa:** Sử dụng PostgreSQL kết hợp pgvector để lưu trữ Vector Embedding, hỗ trợ Semantic Search và triển khai mô hình RAG.

---

## 📊 Thống kê GitHub

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=tung0901205&show_icons=true&theme=github_dark&hide_border=true&count_private=true" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=tung0901205&layout=compact&theme=github_dark&hide_border=true" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=tung0901205&theme=github-dark-blue&hide_border=true" />
</p>

---

## 📬 Liên hệ

<p align="center">
  <a href="mailto:tung0901205@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
  <a href="https://github.com/tung0901205">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
  </a>
</p>

<p align="center">
  📧 <b>Email:</b> tung0901205@gmail.com<br/>
  📱 <b>Điện thoại:</b> 0345040243
</p>

<p align="center">
  <i>Cảm ơn bạn đã ghé thăm GitHub Profile của mình! ❤️</i>
</p>
