# 📚 Book Management System

A complete Spring Boot web application for managing library books with role-based authentication.

https://img.shields.io/badge/Java-17%252B-orange
https://img.shields.io/badge/Spring%2520Boot-3.1%252B-brightgreen
https://img.shields.io/badge/MySQL-8.0%252B-blue
https://img.shields.io/badge/License-MIT-green
https://img.shields.io/badge/Build-Maven-yellow

📖 Overview
The Book Management System is a web-based application for managing books in a library or personal collection. It allows users to add, update, delete, and view books efficiently, providing a simple and organized way to track book inventory with role-based access control.

✨ Features
User Authentication & Authorization - Role-based access (Admin/User)

CRUD Operations - Add, view, update, and delete books

Book Search - Filter books by title, author, or genre

Responsive UI - Works on desktop and mobile devices

Database Persistence - MySQL database integration

RESTful API - Clean API design for book management

🛠️ Technologies Used
Backend: Java 17+, Spring Boot 3.1+, Spring Security, Spring Data JPA

Frontend: HTML5, CSS3, JavaScript, Thymeleaf, Bootstrap 5

Database: MySQL 8.0+

Build Tool: Maven

Version Control: Git & GitHub

🚀 Quick Start
Prerequisites
Java 17 or higher

MySQL 8.0 or higher

Maven 3.6 or higher

Installation & Setup
Clone the repository

bash
git clone https://github.com/your-username/book-management.git
cd book-management
Configure Database

Create a MySQL database named book_management

Update database credentials in application.properties:

properties
# src/main/resources/application.properties
spring.datasource.url=jdbc:mysql://localhost:3306/book_management
spring.datasource.username=your_db_username
spring.datasource.password=your_db_password
spring.jpa.hibernate.ddl-auto=update
spring.sql.init.mode=always
Build and Run the Application

bash
mvn clean install
mvn spring-boot:run
Access the Application

Open your browser and navigate to: http://localhost:8080

Register a new account or use default admin credentials


