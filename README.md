# Employee Management System

A comprehensive employee and user management system built with modern Java technologies.

---

## Overview

This project is a **Spring Boot** based web application for managing employees and users. It supports secure user authentication and authorization with **JWT tokens** and **Spring Security**. The system provides CRUD operations for employees and user management features such as registration, password change, and role-based access control.

---

## Technologies Used

- **Spring Boot** - Framework for building Java web applications.
- **Spring Security** - Provides authentication and authorization.
- **JWT (JSON Web Token)** - For stateless secure user authentication.
- **Spring Data JPA** - Simplifies data access with ORM.
- **Hibernate** - JPA implementation.
- **MySQL** - Relational database for data storage.
- **BCrypt** - Password hashing.
- **Maven** - Dependency management and build automation.
- **Java 17** (or specify your Java version)
- **REST API** - For communication with frontend or API clients like Postman.

---

## Features

- User registration and login with JWT authentication.
- Role-based access control: ADMIN and USER roles.
- CRUD operations for employees (Add, Update, Delete, List).
- Secure password storage with BCrypt.
- Password change functionality for users and admins.
- Token-based stateless authentication with JWT.
- CORS configuration for cross-origin requests.
- Validation of user inputs.
- Clear and meaningful error handling.
- Swagger UI integration for API documentation (if added).

---

## Project Structure

- **controller** - REST API controllers for handling HTTP requests.
- **service** - Business logic layer.
- **repository** - Database access layer using Spring Data JPA.
- **model** - Entity classes representing database tables.
- **dto** - Data Transfer Objects to shape API responses.
- **security** - JWT utilities and Spring Security configuration.
- **exception** - Custom exception handling (optional).

---

## Getting Started

### Prerequisites

- Java JDK 17 or higher installed
- MySQL database up and running
- Maven installed

### Setup

1. Clone the repository:

```bash
git clone https://github.com/abdularahman1243/employee-management-system.git
cd employee-management-system
