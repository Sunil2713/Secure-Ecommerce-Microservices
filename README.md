# Secure E-Commerce Microservices

> A modern e-commerce platform with AI-powered security and microservices architecture

## Overview

This project demonstrates a complete e-commerce solution built with microservices, featuring advanced ML-based security to protect against NoSQL injection attacks. The architecture is designed for scalability, security, and maintainability.

## Key Features

- **AI Security**: BERT-based NoSQL injection detection
- **Microservices**: Scalable, independent service architecture
- **Real-time Protection**: Automatic threat filtering and blocking
- **Modern Stack**: React frontend with Node.js/Express backend
- **Containerized**: Docker-ready for easy deployment

## Quick Start

```bash
# Frontend
cd frontend && npm install && npm run dev

# Backend (requires Docker)
docker-compose up --build
```

## Architecture

```
Frontend (React) → NGINX Gateway → Microservices
                                    ├── Auth Service
                                    ├── Product Service  
                                    ├── Order Service
                                    └── ML Security Service
```

## Tech Stack

| Component | Technology |
|-----------|------------|
| Frontend | React, Vite |
| Backend | Node.js, Express |
| Security | FastAPI, BERT Model |
| Database | MongoDB |
| Cache | Redis |
| Container | Docker, Docker Compose |
| Gateway | NGINX |

## Project Structure

```
├── frontend/              # React application
├── ecomm-backend/
│   ├── auth-service/      # Authentication & authorization
│   ├── product-service/   # Product catalog management
│   ├── order-service/     # Order processing & cart
│   ├── ml-service/        # AI security (BERT)
│   ├── ml-filter-gateway/ # Threat filtering middleware
│   ├── api-gateway/       # NGINX configuration
│   └── shared-utils/      # Common utilities
└── docker-compose.yml     # Service orchestration
```

## Security Highlights

- **BERT Model Integration**: Advanced ML-based injection detection
- **Real-time Filtering**: Automatic malicious payload identification
- **JWT Authentication**: Secure session management
- **Redis Sessions**: High-performance session storage

## Contributors

- [@Sushant-Khot](https://github.com/Sushant-Khot)
- [@Sunil2713](https://github.com/Sunil2713) 
- [@keerthanasoms](https://github.com/keerthanasoms)

## Contact

**GitHub**: [@Sushant-Khot](https://github.com/Sunil2713)

---

*Built with modern technologies and security-first approach*

