# 🏛 E-Commerce System Architecture

This repository serves as the central architecture documentation hub for the E-Commerce system.

It documents:

- System architecture
- Technology stack comparison
- Event-driven design
- Deployment strategies
- Links to all implementation repositories

---

# 🔗 Implementation Repositories

| Layer | Technology | Repository |
|-------|------------|------------|
| 🎨 Frontend | React | https://github.com/wenbo2978/eShop-frontend |
| ☕ Backend | Spring Boot | https://github.com/wenbo2978/eShopsBackendSpring |
| 🧱 Backend | ASP.NET Core | https://github.com/wenbo2978/EShopBackendCSharp |
| 🐍 Backend | Django | in process |

---

# 🏗 System Architecture Overview

Frontend ➜ REST API ➜ Service Layer ➜ Database  
                        ↘ RabbitMQ (Async Messaging)

---

# 📦 Core Components

- User Management
- Product Management
- Cart & Orders
- Asynchronous Order Events
- Authentication & Authorization

---

# 🔄 Event Flow (RabbitMQ)

Order Created ➜ Publish Event ➜ Inventory Update ➜ Email Notification

---

# ☁️ Deployment Strategy

- Dockerized services
- Docker Compose orchestration
- AWS EC2 deployment
- Environment-based configuration

---

# 📐 Design Goals

- Modular architecture
- Framework-agnostic design
- Clear separation of concerns
- Reproducible deployments
- Scalable service design
