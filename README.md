# Employee Management System

This project is a Spring Boot application for managing employees and users.

## Features

- User registration and login with JWT authentication.
- Role-based authorization (ADMIN and USER).
- Employee CRUD operations.
- Password encryption with BCrypt.
- Password change functionality for users and admins.

## Project Structure

- **AuthController**: Handles login and registration.
- **AdminController**: Manages users and employees for admins.
- **UsersController**: User-specific operations like password changes.
- **Models**: Users, Employee, DTOs.
- **Security**: JWT utilities and Spring Security configuration.
- **Services**: Business logic for users and employees.

## How to Run

1. Clone the repository
2. Configure your database in `application.properties`
3. Run the Spring Boot application
4. Use Postman or any API client to test endpoints

## Author

- Name: Abdul Rahman "Bahadurzai"
- Date: 2025-06-25

