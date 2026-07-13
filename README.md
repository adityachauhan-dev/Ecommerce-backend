# 🛒 E-Commerce Backend APP

A robust RESTful E-Commerce Backend built using **Spring Boot**, **Spring Security**, **JWT Authentication**, **Spring Data JPA**, and **MySQL**. The project provides secure authentication and complete APIs for managing users, products, categories, carts, orders, payments, reviews, and addresses.

---

## 🚀 Features

* JWT Authentication & Authorization
* User Registration & Login
* Role-Based Security
* Product Management (CRUD)
* Category Management
* Brand Management
* Shopping Cart
* Order Management
* Payment Management
* Product Reviews & Ratings
* User Address Management
* Global Exception Handling
* DTO-Based Request & Response
* Swagger API Documentation
* Spring Data JPA & Hibernate
* MySQL Database Integration

---

## 🛠️ Tech Stack

### Backend

* Java 21
* Spring Boot
* Spring Security
* JWT
* Spring Data JPA
* Hibernate
* Maven

### Database

* MySQL

### Documentation

* Swagger / OpenAPI

### Tools

* Eclipse IDE
* Git
* GitHub
* Postman

---

## 📂 Project Structure

src
 ├── config
 ├── controller
 ├── dto
 │    ├── request
 │    ├── response
 │    └── auth
 ├── entity
 ├── enums
 ├── exception
 ├── repository
 ├── security
 ├── service
 └── resources

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

```
## 📸 Screenshots

Add screenshots such as:

* Swagger UI
* Login API
* Register API
* Product APIs
* Category APIs
* MySQL Database Tables
* Postman Collection
```

---

## 👨‍💻 Author

**Aditya Chauhan**

GitHub:
https://github.com/adityachauhan-dev

---

## ⭐ If you like this project, give it a Star.
