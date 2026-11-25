# ASP.NET Core Web API – Authentication & CRUD Operations

## About the Project

This project is a C# ASP.NET Core Web API application developed to practice backend development concepts, including CRUD operations, user authentication, authorization, and JWT-based token management.

The main goal of this project is to understand how to build secure RESTful APIs and manage user authentication using modern ASP.NET Core technologies.

## Features

### 1. CRUD Operations
- Create records
- Read and retrieve records
- Update existing records
- Delete records

### 2. Authentication
- User registration
- User login
- Password hashing
- Credential validation
- Secure authentication

### 3. JWT Token Management
- Generate JWT Access Tokens
- Generate Refresh Tokens
- Validate JWT tokens
- Token expiration management
- Refresh expired access tokens

### 4. Authorization
- Protect API endpoints
- Authenticate users using JWT Bearer tokens
- Control access to protected resources

## Technologies Used

- C#
- ASP.NET Core Web API
- Entity Framework Core
- PostgreSQL
- JWT (JSON Web Tokens)
- BCrypt Password Hashing
- RESTful API
- Dependency Injection

## Authentication Flow

1. User creates an account.
2. Password is securely hashed.
3. User logs in using email and password.
4. Server validates user credentials.
5. Server generates an Access Token and Refresh Token.
6. Client uses the Access Token to access protected endpoints.
7. When the Access Token expires, the Refresh Token can be used to obtain a new token.

## API Operations

| Method | Operation |
|---|---|
| POST | Create User |
| GET | Get Users |
| GET | Get User By ID |
| PUT | Update User |
| DELETE | Delete User |
| POST | Register |
| POST | Login |
| POST | Refresh Token |

## Project Structure

```text
Project/
├── Controllers/
├── Models/
├── DTOs/
├── Data/
├── Repositories/
├── Services/
├── Middleware/
├── Migrations/
└── Program.cs
```

## Learning Objectives

Through this project, I gained practical experience in:

- Building RESTful APIs using ASP.NET Core.
- Implementing CRUD operations.
- Working with Entity Framework Core.
- Connecting applications to PostgreSQL.
- Implementing user authentication.
- Understanding JWT Access and Refresh Tokens.
- Securing API endpoints.
- Applying dependency injection.
- Organizing backend applications using layered architecture.

## Author

**Hamse Abdi**

GitHub: [Hamse-abdi202](https://github.com/Hamse-abdi202)
