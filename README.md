# FS-EMPLOYEE-MANAGEMENT
Full stack web development project 2 using java
Employee Management System

Description

The Employee Management System is a web application that allows administrators to manage employee details efficiently. It provides functionalities such as adding, editing, and deleting employees. The frontend is built using HTML, CSS, JavaScript, and Bootstrap 5.3, while the backend is powered by Java Spring Boot and MySQL.

Features

User Authentication (Login & Signup)

JWT Token-Based Security

Password Hashing with BCrypt

Role-Based Access (Admin & Employee)

Admin Panel with CRUD Operations for Employee Management

Employee Search & Sorting

Export Options (CSV, PDF, Excel)

Technologies Used

Frontend:

HTML

CSS

JavaScript

Bootstrap 5.3

Backend:

Java Spring Boot

MySQL

Hibernate (JPA)

JWT Authentication

Installation & Setup

1. Clone the Repository

git clone https://github.com/yashrajesh/employee-management-system.git

2. Setup the Backend

Navigate to the backend folder:

cd backend

Configure application.properties in src/main/resources/

spring.datasource.url=jdbc:mysql://localhost:3306/employeedb
spring.datasource.username=root
spring.datasource.password=info123
spring.jpa.hibernate.ddl-auto=update

Run the Spring Boot application:

mvn spring-boot:run

3. Setup the Frontend

Navigate to the frontend folder:

cd frontend

Open index.html in a browser or use a live server extension.

API Endpoints

Authentication

POST /api/auth/signup - User Registration

POST /api/auth/login - User Login

Employee Management

GET /api/employees - Fetch All Employees

POST /api/employees - Add New Employee

PUT /api/employees/{id} - Update Employee Details

DELETE /api/employees/{id} - Delete Employee

Usage

Login as an admin to access employee management.

Add, edit, or remove employees from the dashboard.

Export employee data in CSV, PDF, or Excel format.

Logout securely after managing employees.

Contributors

Yash Rajesh - GitHub | LinkedIn

License

This project is licensed under the MIT License.



