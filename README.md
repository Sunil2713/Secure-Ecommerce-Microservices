# 🛒 Secure E-Commerce Microservices

A comprehensive e-commerce platform built with microservices architecture and ML-powered security features.

## ✨ Features

- **🔐 Secure Authentication** - JWT-based user management
- **🤖 ML Security** - BERT-based NoSQL injection detection
- **🛡️ Threat Filtering** - Real-time malicious payload blocking
- **📦 Product Management** - Complete product catalog system
- **🛒 Order Processing** - Cart and checkout functionality
- **🐳 Docker Ready** - Containerized microservices
- **⚡ Redis Caching** - High-performance session storage

## 🚀 Quick Start

### Prerequisites
- Node.js & npm
- Docker & Docker Compose

### Frontend
```bash
cd frontend
npm install
npm run dev
```

### Backend Services
```bash
docker-compose up --build
```

## 🏗️ Architecture

```
┌─────────────────┐    ┌─────────────────┐    ┌─────────────────┐
│   React Frontend│    │   NGINX Gateway │    │   Microservices │
│                 │◄──►│                 │◄──►│                 │
│   - User UI     │    │   - API Routing │    │   - Auth Service│
│   - Shopping    │    │   - Load Balance│    │   - Product Svc │
│   - Cart        │    │   - Security    │    │   - Order Svc   │
└─────────────────┘    └─────────────────┘    │   - ML Security │
                                              └─────────────────┘
```

## 🛠️ Tech Stack

- **Frontend**: React, Vite
- **Backend**: Node.js, Express
- **ML Security**: FastAPI, BERT Model
- **Database**: MongoDB
- **Cache**: Redis
- **Container**: Docker, Docker Compose
- **Gateway**: NGINX

## 📁 Project Structure

```
├── frontend/                 # React application
├── ecomm-backend/
│   ├── auth-service/         # User authentication
│   ├── product-service/      # Product management
│   ├── order-service/        # Order processing
│   ├── ml-service/           # ML security (BERT)
│   ├── ml-filter-gateway/    # Threat filtering
│   ├── api-gateway/          # NGINX configuration
│   └── shared-utils/         # Common utilities
└── docker-compose.yml        # Service orchestration
```

## 🔒 Security Features

- **BERT-based Injection Detection**: AI-powered NoSQL injection prevention
- **Real-time Threat Filtering**: Automatic malicious payload blocking
- **JWT Authentication**: Secure user sessions
- **Session Management**: Redis-backed session storage

## 👥 Contributors

- [@Sushant-Khot](https://github.com/Sushant-Khot)
- [@Suhas-30](https://github.com/Suhas-30)
- [@keerthanasoms](https://github.com/keerthanasoms)

## 📬 Contact

- **GitHub**: [@Sunil2713](https://github.com/Sunil2713)

