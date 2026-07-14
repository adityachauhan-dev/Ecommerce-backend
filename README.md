# 🛒 Spring Boot E-Commerce Backend REST API

A secure and scalable E-Commerce Backend REST API built using Java, Spring Boot, Spring Security, JWT Authentication, Spring Data JPA, Hibernate, MySQL, and Swagger/OpenAPI.

---

# 📌 Overview

This project provides a complete backend solution for an E-Commerce application. It includes secure authentication, product management, shopping cart, order processing, payment management, reviews, and address management using REST APIs.

---

# ✨ Features

- 🔐 JWT Authentication & Authorization
- 👤 User Registration & Login
- 🛍️ Product Management
- 📂 Category Management
- 🏷️ Brand Management
- 🛒 Shopping Cart
- 📦 Order Management
- 💳 Payment Management
- ⭐ Product Reviews & Ratings
- 📍 Address Management
- 📄 Swagger API Documentation
- ⚠️ Global Exception Handling
- 📁 DTO Architecture
- 🗄️ MySQL Database Integration

---

# 🛠 Tech Stack

### Backend
- Java
- Spring Boot
- Spring Security
- Spring Data JPA
- Hibernate
- REST API
- JWT Authentication
- Swagger / OpenAPI

### Database
- MySQL

### Build Tool
- Maven

### Tools
- Eclipse IDE
- Postman
- Git & GitHub

---

# 🏗 Project Architecture

Controller
      │
      ▼
Service
      │
      ▼
Repository
      │
      ▼
MySQL Database

---

# 📂 Project Structure

src
 ├── controller
 ├── service
 ├── repository
 ├── entity
 ├── dto
 ├── security
 ├── config
 ├── exception
 ├── enums
 └── resources

---

# 🔐 Authentication

- Register User
- Login User
- JWT Token Generation
- Role-Based Authorization
- Secure API Access

---


## 🔐 Authentication APIs

| Method | Endpoint       |
| ------ | -------------- |
| POST   | /auth/register |
| POST   | /auth/login    |

---

## 📦 Product APIs

| Method | Endpoint       |
| ------ | -------------- |
| GET    | /products      |
| GET    | /products/{id} |
| POST   | /products      |
| PUT    | /products/{id} |
| DELETE | /products/{id} |

---

## 📂 Category APIs

| Method | Endpoint         |
| ------ | ---------------- |
| GET    | /categories      |
| POST   | /categories      |
| PUT    | /categories/{id} |
| DELETE | /categories/{id} |

---

## 🏷️ Brand APIs

| Method | Endpoint     |
| ------ | ------------ |
| GET    | /brands      |
| POST   | /brands      |
| PUT    | /brands/{id} |
| DELETE | /brands/{id} |

---

## 🛒 Cart APIs

| Method | Endpoint   |
| ------ | ---------- |
| GET    | /cart      |
| POST   | /cart      |
| DELETE | /cart/{id} |

---

## 📦 Order APIs

| Method | Endpoint     |
| ------ | ------------ |
| GET    | /orders      |
| POST   | /orders      |
| GET    | /orders/{id} |

---

## 💳 Payment APIs

| Method | Endpoint  |
| ------ | --------- |
| GET    | /payments |
| POST   | /payments |

---

## ⭐ Review APIs

| Method | Endpoint |
| ------ | -------- |
| GET    | /reviews |
| POST   | /reviews |

---

## 📍 Address APIs

| Method | Endpoint        |
| ------ | --------------- |
| GET    | /addresses      |
| POST   | /addresses      |
| PUT    | /addresses/{id} |
| DELETE | /addresses/{id} |

---

## ⚙️ Setup Instructions

### Clone Repository


git clone https://github.com/adityachauhan-dev/Ecommerce-backend.git

### Navigate to Project

cd Ecommerce-backend

### Configure Application

Copy:

application-example.properties

to

application.properties

Update the following values:

* Database URL
* Database Username
* Database Password
* JWT Secret

### Run Project

mvn spring-boot:run

---

## 📘 API Documentation

Swagger UI

http://localhost:8080/swagger-ui/index.html

OpenAPI JSON

http://localhost:8080/v3/api-docs

---


## 👨‍💻 Author

**Aditya Chauhan**

GitHub:
https://github.com/adityachauhan-dev

---

## ⭐ If you like this project, give it a Star.
