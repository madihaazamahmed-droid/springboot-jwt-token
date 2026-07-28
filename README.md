# Spring Boot JWT Token

A Spring Boot application that demonstrates secure authentication and authorization using JSON Web Tokens (JWT) with Spring Security.

## 🚀 Features

- User Registration
- User Login Authentication
- JWT Token Generation
- JWT Token Validation
- Spring Security Configuration
- BCrypt Password Encryption
- Role-Based Authorization (ADMIN & USER)
- Protected REST APIs
- Global Exception Handling
- MySQL Database Integration

## 🛠️ Tech Stack

- Java 21
- Spring Boot
- Spring Security
- JWT (JSON Web Token)
- Spring Data JPA
- Hibernate
- MySQL
- Maven
- Postman

## 📁 Project Structure

```
src
 ├── controller
 ├── service
 ├── repository
 ├── entity
 ├── config
 ├── security
 ├── exception
 └── resources
```

## 🔑 API Endpoints

### Public APIs
- POST `/save` – Register a new user
- POST `/login` – Authenticate user and generate JWT token

### Protected APIs
- GET `/admin` – Accessible only by ADMIN
- GET `/user` – Accessible by authenticated users

## ▶️ Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/madihaazamahmed-droid/springboot-jwt-token.git
   ```

2. Configure your MySQL database in `application.properties`.

3. Build and run the application:
   ```bash
   mvn spring-boot:run
   ```

4. Test the endpoints using Postman.

## 📌 Key Concepts

- JWT Authentication
- Spring Security
- Role-Based Access Control
- Password Encryption using BCrypt
- RESTful API Development
- Exception Handling

## 👩‍💻 Author

**Madiha Azam Ahmed**

If you found this project helpful, consider giving it a ⭐.
