# E-Commerce Platform

A full-stack e-commerce application inspired by large online marketplaces such as Amazon. The platform lets users discover products, manage shopping carts, place orders, and track payments through a React frontend and Spring Boot microservices backend.

## Features

- Browse and search products
- Filter products by category and availability
- User registration and login
- Product, category, and inventory management
- Shopping cart management
- Order placement and order-status updates
- Payment tracking
- Admin operations for managing products and orders
- Microservices-based backend architecture

## Architecture

```text
React Frontend
      |
API Gateway
      |
Eureka Service Discovery
      |
------------------------------------------------
| User Service | Catalog Service | Cart Service |
| Order & Payment Service                       |
------------------------------------------------
      |
   MongoDB
```

## Tech Stack

### Frontend

- React
- Vite
- React Router
- Axios

### Backend

- Java 17
- Spring Boot
- Spring Cloud Gateway
- Eureka Server
- OpenFeign
- Spring Data MongoDB
- Lombok

### Database

- MongoDB

## Services

| Service | Responsibility |
| --- | --- |
| User Service | Registration, login, and user-profile management |
| Catalog Service | Products, categories, attributes, and inventory |
| Cart Service | Add, update, and remove cart items |
| Order & Payment Service | Order placement, stock updates, and payment records |
| API Gateway | Single entry point for frontend API requests |
| Eureka Server | Service discovery for backend microservices |

## Getting Started

### Prerequisites

- Java 17+
- Node.js and npm
- MongoDB
- Maven

### Run the Frontend

```bash
cd frontend
npm install
npm run dev
```

### Run the Backend

Start MongoDB, then run the services in this order:

1. Eureka Server
2. API Gateway
3. User Service
4. Catalog Service
5. Cart Service
6. Order and Payment Service

## Project Attribution

This repository is my portfolio copy of a team e-commerce project.

Original team repository: https://github.com/Kuganes-Rathinam/ecomm_ip

### My Contributions

- [Add the features, modules, or design work you personally completed]
- [Add your frontend, backend, database, or API responsibilities]
- [Add testing, documentation, or deployment work you completed]
