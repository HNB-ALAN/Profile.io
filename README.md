# ALAN — Hoàng Văn Bắc · CV

## 👨‍💻 AI / Backend Engineer
Microservices & AI-driven Products

---

## 📞 Liên hệ
- **Điện thoại:** 0971 932 296
- **Email:** hoangbac.hnb@outlook.com
- **Sinh:** 09/03/1993
- **Địa điểm:** TP. Hồ Chí Minh / Hà Nội

---

## 🎓 Học vấn
**Đại học FPT – TP.HCM**  
- Công nghệ thông tin
- Trí tuệ nhân tạo & Khoa học dữ liệu
- 05/2022 – 06/2025

---

## 💼 Mục tiêu nghề nghiệp
Làm tốt công việc ứng tuyển, hướng tới tạo ra giá trị mới trong lĩnh vực **tiền kỹ thuật số**. Tập trung phát triển sản phẩm AI/backend chất lượng production: microservices, pipeline dữ liệu, và tích hợp AI vào sản phẩm thực tế.

---

## 🚀 Dự án nghiên cứu & phát triển cá nhân

### 1. Alu-vivu — AI Event Networking Platform
🔗 [aluvivu.com](https://aluvivu.com)

**Tech Stack:** Next.js 14 · Flutter · NestJS · FastAPI · LangGraph · PostgreSQL + pgvector · Redis · AWS ECS/SQS/RDS · Prisma · OpenTelemetry · Jest · pytest

**Mô tả:**  
Nền tảng networking cho sự kiện alumni, ứng dụng AI để gợi ý kết nối phù hợp thay vì networking ngẫu nhiên. Tham gia xây dựng các microservice backend (NestJS + Fastify, Prisma), tích hợp AI Onboarding (LangGraph agent), Smart Matching Engine (hybrid scoring: embedding + rule-based), Face Recognition (on-device TFLite + server-side pgvector similarity search), và Icebreaker Engine (RAG + LLM).

**Highlights:**
- Xây dựng và vận hành các service Node.js (Auth, User, Event, Connection, Realtime Suggestion) trên NestJS + Fastify
- Triển khai vector search bằng pgvector (HNSW index) cho profile embeddings (1536-dim) và face embeddings (512-dim)
- Thiết kế hàng đợi bất đồng bộ với AWS SQS và cache/session bằng Redis (AWS ElastiCache)
- Đóng góp phần realtime: WebSocket, polling, Server-Sent Events fallback
- Triển khai hạ tầng trên AWS ECS (Fargate), ALB, RDS Proxy, Secrets Manager

---

### 2. VINA-too — AI-powered ATS (Career Management Platform)

**Tech Stack:** Next.js · NestJS + Fastify · Prisma · PostgreSQL · Redis · BullMQ · FastAPI · LangChain · OpenAI API · Playwright · Jest · Turborepo/pnpm

**Mô tả:**  
Hệ thống ATS (Applicant Tracking System) nội bộ tích hợp AI, hỗ trợ quy trình tuyển dụng end-to-end: đăng tin, quản lý ứng viên, sinh nội dung JD/email bằng AI. Trực tiếp làm việc trên module Candidates: tách các service tập trung (candidate processor, orchestration service, dashboard cache, bulk actions), viết unit test và property test đảm bảo chuẩn production.

**Highlights:**
- Thiết kế lại kiến trúc module Candidates theo hướng service nhỏ, gọn, giảm coupling
- Xây dựng background processor xử lý pipeline ứng viên với Jest spec + property-based test
- Làm việc với API backend NestJS, Prisma ORM, BullMQ, Redis cache, RBAC
- Phối hợp với AI service (FastAPI + LangChain/OpenAI) sinh JD, email tuyển dụng tự động
- Đảm bảo chất lượng qua verify-readiness script và production-contract-check

---

### 3. USC Platform — 24-Microservice Rust Backend

**Tech Stack:** Rust · Tonic (gRPC) · Tokio · ScyllaDB · Kafka · Redis Cluster · ClickHouse · Qdrant · InfluxDB · Kubernetes · OpenTelemetry · Flutter · Next.js

**Mô tả:**  
Hệ sinh thái backend quy mô lớn gồm 24 microservice viết bằng Rust (Gateway, Auth, User, Blockchain Core, Wallet, Social, Commerce, AI, Video, Search, Recommendation, Advertising, Jobs Grab, World/Metaverse...), giao tiếp qua gRPC, kiến trúc Clean Architecture (Porto Pattern) đồng nhất, phục vụ cho các app Flutter (mobile) và Next.js (web) trong hệ thống APPS-W.

**Highlights:**
- Xây dựng service theo Clean Architecture (api/grpc → application → infrastructure)
- Làm việc với hạ tầng dữ liệu đa dạng: ScyllaDB, Redis Cluster, ClickHouse, Qdrant, InfluxDB
- Triển khai event-driven architecture qua Kafka (KRaft mode, 3 brokers)
- Tham gia các service nghiệp vụ: Blockchain Core, Wallet, Jobs Grab, AI
- Đảm bảo chất lượng qua cargo fmt → clippy → test → build pipeline

---

## 💼 Kinh nghiệm làm việc

### Vin Smart Future
**Product Lead** — Từ thiết kế đến triển khai sản phẩm  
📅 25/05/2026 – 01/07/2026

- Đảm nhận vai trò lead sản phẩm xuyên suốt vòng đời: từ thiết kế (UX/UI, product design) đến định hướng kỹ thuật và triển khai thực tế
- Phối hợp giữa đội thiết kế và đội phát triển để đảm bảo sản phẩm bám sát yêu cầu

---

### FPT Software — Quy Nhơn
**Nhân viên — Data / ETL**  
📅 2023 – 2024

- Làm việc với Apache Airflow, xây dựng pipeline lấy dữ liệu từ hệ thống này chuyển sang hệ thống khác (ETL)

---

### Online Jobs (Freelance)
**Backend Developer**  
📅 2020 – Hiện tại

- Nhận yêu cầu và xây dựng các microservices backend sử dụng Rust và Golang
- Hợp tác với nhiều freelancer khác theo từng dự án để hoàn thiện sản phẩm end-to-end

---

### Nhóm bạn bán hàng chung
**Bán hàng**  
📅 2015 – 2019

- Tạo kênh nội dung trên các nền tảng mạng xã hội, chạy quảng cáo, mua bán hàng

---

## 🎯 Hoạt động

### Câu lạc bộ AbangB — Đại học FPT
**Người sáng lập / Trưởng nhóm tình nguyện**  
📅 2020

- Thành lập và dẫn dắt câu lạc bộ tình nguyện AbangB tại Đại học FPT
- Tổ chức tập hợp quà và phân phát tới người vô gia cư; quyên góp hỗ trợ người khó khăn trong mùa dịch Covid-19

---

## 🛠️ Kỹ năng chi tiết

### AI / Research
**Core:** Python · PyTorch · FastAPI · LangGraph/LangChain · OpenAI API (RAG, Embeddings) · pgvector

🔗 [github.com/HNB-ALAN/MODEL_BB](https://github.com/HNB-ALAN/MODEL_BB.git)

---

### Backend / Microservices
**Technologies:** Golang · Rust · Tonic/gRPC · Tokio · NestJS (Fastify/Express) · Prisma · PostgreSQL · ScyllaDB · ClickHouse · Qdrant · Redis/Redis Cluster · Kafka · BullMQ/SQS

🔗 [github.com/HNB-ALAN/demo-Rust-microservice](https://github.com/HNB-ALAN/demo-Rust-microservice.git)  
🔗 [github.com/HNB-ALAN/demo-Golang-cosmos-microservice](https://github.com/HNB-ALAN/demo-Golang--cosmos-microservice.git)

---

### Mobile / Web App
**Technologies:** Flutter · Next.js · React · TypeScript

🎥 [Demo video](https://www.youtube.com/watch?v=GH4irC1B9AA)

---

### Hạ tầng & Công cụ
Git · Docker · Kubernetes · AWS (EC2, S3, ECS, SQS, RDS) · Railway · Vercel · Apache Airflow (ETL) · Cursor/Copilot

---

### Quản lý dự án / Production
Quản lý production · Agile · Notion

---

### Nền tảng khác
Marketing & Tài chính doanh nghiệp

---

## 🌐 Ngôn ngữ
- Tiếng Việt
- Tiếng Anh

---

## 💪 Kỹ năng mềm
- Giải quyết vấn đề
- Lập kế hoạch

---

## 🎨 Sở thích
- Thiện nguyện
- Xem phim

---

## 📄 Xem CV đầy đủ
👉 Mở file `index.html` để xem CV với giao diện đẹp mắt và đầy đủ thông tin!
