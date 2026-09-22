# 🛒 ShopSphere - Full Stack E-Commerce Web Application

ShopSphere is a full-stack e-commerce web application built with **Spring Boot, ReactJS, MySQL, and JWT Authentication**. The application provides an online shopping workflow with secure authentication, product management, shopping cart functionality, order management, and an admin dashboard.

---

## 🚀 Features

### 👤 User Features

* User Registration & Login
* JWT Authentication
* Role-Based Authorization
* Browse Products
* Search Products
* View Product Details
* Add Products to Cart
* User-specific Shopping Cart
* Increase / Decrease Product Quantity
* Remove Products from Cart
* Checkout
* Place Orders
* View Order History
* Responsive UI
* Toast Notifications

### 👨‍💼 Admin Features

* Admin Login
* Dashboard Overview
* Add New Products
* Update Existing Products
* Delete Products
* Search Products
* Inventory Management
* View All Orders
* Update Order Status
* Product Stock Management

---

## 🛠️ Tech Stack

### Frontend

* ReactJS
* React Router DOM
* Axios
* Bootstrap 5
* React Toastify

### Backend

* Spring Boot
* Spring Security
* Spring Data JPA
* Hibernate
* JWT Authentication
* REST APIs

### Database

* MySQL

### Tools

* Eclipse IDE
* VS Code
* Postman
* Git
* GitHub
* Maven

---

## ✨ Modules

### Authentication Module

* User Registration
* User Login
* JWT Token Authentication
* Role-Based Authorization

### Product Module

* Add Product
* Update Product
* Delete Product
* Search Product
* View Products

### Cart Module

* Add to Cart
* Remove from Cart
* Update Quantity
* Grand Total Calculation
* User-specific Cart

### Checkout Module

* Delivery Address
* Payment Method
* Order Summary
* Place Order

### Order Module

* Create Orders
* User Order History
* Admin Order Management
* Order Status Update

### Admin Dashboard

* Product Management
* Inventory Management
* Dashboard Statistics
* Order Management

---

## 🔐 Authentication

The application uses **JWT-based authentication** with Spring Security.

### Roles

* `USER`
* `ADMIN`

Protected APIs are secured using Spring Security and role-based authorization.

---

## 📁 Project Structure

```text
ShopSphere/
│
├── shopsphere-frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── services/
│   │   ├── App.js
│   │   └── index.js
│   └── package.json
│
├── backend/
│   ├── controller/
│   ├── service/
│   ├── repository/
│   ├── entity/
│   ├── security/
│   └── config/
│
└── README.md
```

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/Akanksha-k2/ShopSphere_E-Commerce_Web_Application.git

cd ShopSphere_E-Commerce_Web_Application
```

### 2. Backend Setup

Navigate to the backend directory and install the Maven dependencies:

```bash
mvn clean install
```

Run the Spring Boot application:

```bash
mvn spring-boot:run
```

The backend runs on:

```text
http://localhost:8080
```

### 3. Frontend Setup

Navigate to the frontend directory:

```bash
cd shopsphere-frontend
```

Install dependencies:

```bash
npm install
```

Start the application:

```bash
npm start
```

The frontend runs on:

```text
http://localhost:3000
```

---

## 🗄️ Database Setup

Create a MySQL database:

```sql
CREATE DATABASE shopsphere;
```

Update the database credentials in the application's `application.properties` file.

Do not commit real database passwords or API credentials to GitHub.

---

## 📡 REST APIs

### Authentication

| Method | Endpoint             |
| ------ | -------------------- |
| POST   | `/api/auth/register` |
| POST   | `/api/auth/login`    |

### Products

| Method | Endpoint             |
| ------ | -------------------- |
| GET    | `/api/products`      |
| GET    | `/api/products/{id}` |
| POST   | `/api/products`      |
| PUT    | `/api/products/{id}` |
| DELETE | `/api/products/{id}` |

### Cart

| Method | Endpoint                    |
| ------ | --------------------------- |
| GET    | `/api/cart/{userId}`        |
| POST   | `/api/cart`                 |
| PUT    | `/api/cart/{id}/{quantity}` |
| DELETE | `/api/cart/{id}`            |

### Orders

| Method | Endpoint                    |
| ------ | --------------------------- |
| POST   | `/api/orders`               |
| GET    | `/api/orders`               |
| GET    | `/api/orders/user/{userId}` |
| PUT    | `/api/orders/{id}/{status}` |

---

## 📸 Screenshots

Screenshots can be added to document the application's interface.

Suggested screenshots:

```text
screenshots/
├── Login.png
├── Register.png
├── Products.png
├── Cart.png
├── Checkout.png
├── Orders.png
└── AdminDashboard.png
```

---

## 📈 Future Enhancements

* Wishlist
* Product Reviews & Ratings
* Online Payment Integration
* Coupon & Discount System
* Email Notifications
* Product Categories
* Pagination
* Product Filters
* Sales Analytics Dashboard

---

## 🎯 Learning Areas

This project provides practical experience with:

* Spring Boot REST APIs
* Spring Security
* JWT Authentication
* Hibernate & JPA
* MySQL Integration
* React Hooks
* React Router
* Axios API Integration
* Bootstrap
* CRUD Operations
* Role-Based Access Control
* Full-Stack Web Application Development

---

## 👩‍💻 Repository

**GitHub:**
https://github.com/Akanksha-k2/ShopSphere_E-Commerce_Web_Application

---

## ⭐ Support

If you find the project useful, consider giving the repository a star on GitHub.
