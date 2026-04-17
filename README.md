🛒 Full-Stack E-Commerce System

A full-stack web application built using **Spring Boot** that allows users to browse products, manage carts, and place orders. The system also includes an **Admin Panel** to manage products, users, and orders.

---

 🌐 Live Demo

🚀 Frontend:https://ecommerce-frontend-xliv.onrender.com

⚙️ Backend API:https://ecommerce-backend-5rta.onrender.com





📌 Project Overview

This project simulates a real-world e-commerce platform with two roles:

* 👤 **User** – Browse products, add items to cart, and place orders
* 
* 🛠️ **Admin** – Manage products, users, and orders

It demonstrates full-stack development with REST APIs, database integration, and role-based functionality.



🛠️ Tech Stack

### Backend

* Java
* Spring Boot
* Spring Data JPA
* Hibernate
* Spring Security

### Frontend

* HTML
* CSS
* JavaScript

### Database

* PostgresSQL



## ⚙️ Features

### 👤 User Features

* User registration and login
  
* Browse products
  
* Add to cart
  
* Place orders

 🛠️ Admin Features

* Add / update / delete products
  
* View all users
  
* Manage orders
  
* Monitor system data



 📂 Project Structure

backend/
├── controller/
├── service/
├── repository/
├── entity/
└── application.properties

frontend/
├── index.html
├── style.css
└── script.js



⚙️ How to Run

### 1. Clone the repository

git clone https://github.com/your-username/full-stack-ecommerce-system

### 2. Configure PostgresSQL

spring.datasource.url=jdbc:mysql://localhost:3306/ecommerce_db

spring.datasource.username=root

spring.datasource.password=your_password

spring.jpa.hibernate.ddl-auto=update

### 3. Run backend

Start Spring Boot application

### 4. Run frontend

Open `index.html` in browser



 🔗 API Endpoints

### User

* GET /products
* GET /products/{id}
* POST /cart
* POST /orders

### Admin

* POST /admin/products
* PUT /admin/products/{id}
* DELETE /admin/products/{id}
* GET /admin/orders



 📸 Screenshots



 🚀 Future Enhancements

* JWT authentication
* Payment gateway integration
* Advanced search & filters
* Cloud deployment


 👨‍💻 Author

**Majjari Chenna Keshava**
https://github.com/123chenna
keshavachenna330@gmail.com
8639588635



## ⭐ Support

If you like this project, give it a ⭐ on GitHub!
