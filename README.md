# 🧠 Urban Estate – Backend Services

## Overview
The Urban Estate backend provides **scalable, microservice-based APIs** to support authentication, property management, favorites, feedback, and real-time chat for the rental platform.

The backend is designed using **service-oriented architecture**, supports **real-time communication**, and is **containerized using Docker**.

---

## Services
- **Account Service** – User authentication & role management  
- **Property Service** – Property listing, add/view/manage  
- **Favorite Service** – Favorite property handling  
- **Feedback Service** – Reviews & feedback  
- **Chat Service** – Real-time messaging  
- **API Gateway** – Centralized request routing  

---

## Tech Stack
- Backend Framework: (ASP.NET)
- REST APIs & WebSockets
- Docker (containerization)
- API Gateway pattern
- Role-based access (Admin / Owner / Tenant)

---

## Architecture
- Microservices-based design  
- Independent service deployment  
- Gateway-driven communication  

---

## Run (Docker)
```bash
docker-compose up
