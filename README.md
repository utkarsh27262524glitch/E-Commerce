# 🛒 E-Commerce Platform

### Developed by Team ByteCode 💻

A full-stack Java web application featuring Admin, Seller, and Buyer dashboards with e-commerce functionality, including product management, inventory control, shopping carts, order processing, and checkout.

**Team Name:** ByteCode
**Project Type:** Full-Stack Web Application
**Technologies:** Java 11+, Servlets 4.0, JSP, MySQL 8.0, Bootstrap 5.3, Apache Tomcat 9.x

---

## 👥 About Team ByteCode

We are **Team ByteCode**, and this project is our effort to build a functional e-commerce platform using Java web technologies.

Through this project, we aim to apply our programming knowledge to a practical application while learning about backend development, database management, frontend integration, and software architecture.

## ✨ Features

### 👨‍💼 Admin Dashboard

* User Management — Create, edit, and delete user accounts.
* Product Management — Manage product listings.
* Order Management — Track and update order statuses.
* System Overview — Monitor users, products, orders, and revenue.

### 🏪 Seller Dashboard

* Product Listing — Add, edit, and delete products with images.
* Inventory Management — Monitor stock levels and low-stock products.
* Order Processing — View and fulfill customer orders.
* Sales Analytics — Track sales and revenue.

### 🛍️ Buyer Dashboard

* Product Browsing — Search and filter products by category.
* Shopping Cart — Add, update, and remove items.
* Wishlist — Save favorite products.
* Checkout — Available payment options include COD, UPI, cards, and net banking.
* Order Tracking — View order progress through a status timeline.
* Flash Sale Timer — Display discount countdowns.
* Cookie Consent — Display a cookie consent popup.

## 🛠️ Tech Stack

| Layer                 | Technology                  |
| --------------------- | --------------------------- |
| Programming Language  | Java 11+                    |
| Web Framework         | Java Servlets 4.0           |
| View Technology       | JSP                         |
| Database              | MySQL 8.0                   |
| Database Connectivity | JDBC                        |
| JDBC Driver           | MySQL Connector/J           |
| Server                | Apache Tomcat 9.x           |
| Frontend              | HTML, CSS, JavaScript       |
| UI Framework          | Bootstrap 5.3               |
| Icons                 | Bootstrap Icons             |
| Fonts                 | Playfair Display, Poppins   |
| Architecture          | MVC (Model-View-Controller) |

## 📂 Project Structure

```text
ecommerce-platform/
├── database/
│   └── schema.sql
├── images/
├── jsp/
│   ├── admin/
│   │   ├── dashboard/
│   │   ├── users/
│   │   ├── products/
│   │   └── orders/
│   ├── seller/
│   │   ├── dashboard/
│   │   ├── products/
│   │   ├── orders/
│   │   └── inventory/
│   ├── buyer/
│   │   ├── dashboard/
│   │   ├── products/
│   │   ├── cart/
│   │   ├── checkout/
│   │   ├── orders/
│   │   └── wishlist/
│   └── common/
├── src/
│   └── com/ecommerce/
│       ├── model/
│       ├── dao/
│       ├── servlet/
│       ├── filter/
│       └── util/
├── WEB-INF/
│   ├── classes/
│   ├── lib/
│   └── web.xml
├── index.jsp
└── README.md
```

*Note: This is a representative structure. Update it to match the actual repository files.*

## ⚙️ Installation and Setup

### Prerequisites

* Java JDK 11 or later
* MySQL 8.0
* Apache Tomcat 9.x
* MySQL Connector/J
* An IDE such as VS Code, Eclipse, or IntelliJ IDEA

### 1. Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

Replace the placeholder with the actual repository URL.

### 2. Set Up the Database

Run the SQL script in MySQL:

```sql
SOURCE path/to/database/schema.sql;
```

### 3. Configure Database Credentials

Update the database connection settings in:

```text
src/com/ecommerce/util/DBConnection.java
```

Do not commit real passwords or sensitive credentials to GitHub.

### 4. Configure the JDBC Driver

Ensure MySQL Connector/J is available to the application at runtime.

### 5. Deploy the Application

Deploy the web application to Apache Tomcat 9.x, ensuring the directory structure and deployment configuration are correct.

### 6. Run the Application

Open the following address in your browser:

```text
http://localhost:8080/ecommerce-platform/
```

## 🌐 Live Demo

**Live Website:**
https://whisking-update-drank.ngrok-free.dev/ecommerce-platform/

*The live demo is accessible only while the hosting environment and ngrok tunnel are active.*

## 🧠 Java Concepts Used

| Concept            | Implementation                               |
| ------------------ | -------------------------------------------- |
| OOP                | Encapsulation and object-oriented models     |
| Enums              | User roles and order statuses                |
| Generics           | GenericDAO interface                         |
| Collections        | ArrayList and List                           |
| Interfaces         | DAO interfaces and filters                   |
| Exception Handling | try-with-resources                           |
| Singleton Pattern  | Database connection utility, if implemented  |
| DAO Pattern        | Separation of database operations            |
| MVC Architecture   | Separation of models, views, and controllers |
| JDBC               | Prepared statements and transactions         |
| Servlets           | Request processing                           |
| Session Management | User authentication sessions                 |

## 🎯 Project Objectives

* Build a practical full-stack Java web application.
* Understand MVC architecture and the DAO pattern.
* Implement database connectivity using JDBC and MySQL.
* Develop role-based dashboards for Admin, Seller, and Buyer.
* Apply Java programming concepts to a real-world application.
* Collaborate as a team on software development.

## 👨‍💻 Our Team

**Team Name: ByteCode**

**Team Members:**

* Utkarsh Kumar Singh
* [Abhiraj Sharma]
* [Trapti Srivastava]
* [Anshu]
* [Add the remaining team members]

*Replace the placeholders with the actual names of all team members.*

## 🚀 Future Improvements

* Enhanced authentication and authorization.
* Improved product search and filtering.
* Integration with a payment gateway.
* Better mobile responsiveness.
* Deployment to a stable hosting platform.
* Additional reporting and analytics features.

---

### Built with 💻 by Team ByteCode

*Learning, building, and growing together through code.*
