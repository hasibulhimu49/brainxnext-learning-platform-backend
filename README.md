# BrainXNext Learning Platform - Backend API

A scalable and secure RESTful API for the BrainXNext Learning Platform built with Spring Boot. The backend provides authentication, user management, course management, lessons, quizzes, enrollments, and other core LMS functionalities.

---

## 🚀 Features

- JWT Authentication & Authorization
- Role-Based Access Control (Admin, Instructor, Student)
- User Management
- Course Management
- Lesson Management
- Quiz & Assignment APIs
- Enrollment Management
- Progress Tracking
- RESTful API Design
- Input Validation
- Global Exception Handling
- Pagination & Sorting
- API Documentation (Swagger/OpenAPI)
- Database Migration (Flyway)
- Optimized Database Queries
- Secure Password Encryption
- CORS Configuration

---

## 🛠️ Tech Stack

- Java 21
- Spring Boot
- Spring Security
- Spring Data JPA
- PostgreSQL
- Hibernate
- JWT Authentication
- Flyway
- Maven
- Lombok
- Swagger / OpenAPI

---

## 📁 Project Structure

```text
src/
├── controller/
├── service/
├── repository/
├── entity/
├── dto/
├── mapper/
├── config/
├── security/
├── exception/
├── specification/
├── util/
└── resources/
    ├── db/migration/
    ├── application.yml
    └── application.properties
```

---

## ⚙️ Prerequisites

- Java 21+
- Maven 3.9+
- PostgreSQL

---

## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/your-username/brainxnext-learning-platform-backend.git
```

Navigate to the project:

```bash
cd brainxnext-learning-platform-backend
```

Configure your database in `application.yml` or `application.properties`.

---

## 🗄️ Database Configuration

Example:

```properties
spring.datasource.url=jdbc:postgresql://localhost:5432/brainxnext
spring.datasource.username=postgres
spring.datasource.password=your_password

spring.jpa.hibernate.ddl-auto=validate
spring.jpa.show-sql=true

spring.flyway.enabled=true

jwt.secret=your-secret-key
jwt.expiration=86400000
```

---

## ▶️ Run the Application

```bash
mvn spring-boot:run
```

or

```bash
./mvnw spring-boot:run
```

The API will start on:

```
http://localhost:8080
```

---

## 📚 API Documentation

Swagger UI:

```
http://localhost:8080/swagger-ui/index.html
```

OpenAPI Docs:

```
http://localhost:8080/v3/api-docs
```

---

## 🔑 Authentication

This API uses **JWT (JSON Web Token)** authentication.

After logging in, include the token in every protected request:

```http
Authorization: Bearer <your_jwt_token>
```

---

## 📜 Available Maven Commands

| Command | Description |
|---------|-------------|
| `mvn clean install` | Build the project |
| `mvn test` | Run tests |
| `mvn spring-boot:run` | Start the application |
| `mvn clean package` | Generate JAR file |

---

## 🧪 Testing

Run all tests:

```bash
mvn test
```

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Mohammad Hasibul Hasan**

Java Backend Developer

**Tech Stack:** Java • Spring Boot • Spring Security • PostgreSQL • Hibernate • JWT • Flyway • REST API

---

⭐ If you found this project useful, please give it a star!
