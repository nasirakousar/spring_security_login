# Spring Security Login System

A secure authentication and authorization application built using **Spring Boot**, **Spring Security**, **Spring Data JPA**, **MySQL**, and **Thymeleaf**. This project demonstrates user login, registration, role-based access control, password encryption, and secure session management.

---

## Features

- User Registration
- User Login
- Password Encryption using BCrypt
- Spring Security Authentication
- Role-Based Authorization
- Secure Session Management
- MySQL Database Integration
- Form Validation
- Responsive UI with HTML, CSS, and JavaScript
- MVC Architecture

---

## Tech Stack

### Backend
- Java 21
- Spring Boot
- Spring Security
- Spring Data JPA
- Hibernate

### Frontend
- HTML5
- CSS3
- JavaScript
- Thymeleaf

### Database
- MySQL

### Build Tool
- Maven

### IDE
- Visual Studio Code
- IntelliJ IDEA (Optional)

---

## Project Structure

```
spring_security_login
│
├── src
│   ├── main
│   │   ├── java
│   │   │   └── com.example.springsecuritylogin
│   │   │       ├── controller
│   │   │       ├── entity
│   │   │       ├── repository
│   │   │       ├── security
│   │   │       ├── service
│   │   │       └── SpringSecurityLoginApplication.java
│   │   │
│   │   ├── resources
│   │       ├── static
│   │       ├── templates
│   │       └── application.properties
│
├── pom.xml
└── README.md
```

---

## Prerequisites

Before running the project, install:

- Java 21 or above
- Maven
- MySQL
- Visual Studio Code or IntelliJ IDEA

---

## Database Configuration

Create a MySQL database.

```sql
CREATE DATABASE spring_security_db;
```

Update `application.properties`:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/spring_security_db
spring.datasource.username=root
spring.datasource.password=your_password

spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
```

---

## Clone the Repository

```bash
git clone https://github.com/nasirakousar/spring_security_login.git
```

Move into the project directory:

```bash
cd spring_security_login
```

---

## Run the Application

Using Maven:

```bash
mvn spring-boot:run
```

Or run the main class from your IDE.

---

## Application URLs

| Page | URL |
|-------|-----|
| Home | http://localhost:8080 |
| Login | http://localhost:8080/login |
| Register | http://localhost:8080/register |
| Dashboard | http://localhost:8080/dashboard |

---

## Authentication Flow

1. User registers with username and password.
2. Password is encrypted using BCrypt.
3. User logs in.
4. Spring Security authenticates the credentials.
5. User is redirected to the dashboard.
6. Unauthorized users cannot access protected pages.

---

## Security Features

- BCrypt Password Encoding
- Authentication Manager
- Authorization Rules
- CSRF Protection
- Session Management
- Secure Login
- Protected Endpoints

---

## Future Enhancements

- JWT Authentication
- Email Verification
- Forgot Password
- OTP Login
- OAuth2 Login (Google/GitHub)
- Remember Me Authentication
- Admin Dashboard
- User Profile Management

---

## Screenshots

Add screenshots of:

- Home Page
- Login Page
- Registration Page
- Dashboard
- Database Tables

---

## Author

**Shaik Naira Kousar Begum**

GitHub: https://github.com/nasirakousar

---

## License

This project is created for educational and learning purposes.
