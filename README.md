# 🏦 Banking Application using Java 8, Spring Boot, Spring Security, and H2 Database

A RESTful API backend built with Java and Spring Boot to simulate simple banking operations.

---

## 📋 Features

- 🔁 CRUD operations for customers and accounts
- 💰 Deposit and withdrawal functionalities
- 🔄 Internal account transfers (between a customer's own accounts)
- 🔐 Secure endpoints with Spring Security
- 🗂 In-memory H2 database for quick testing
- 📄 Swagger documentation for API testing

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/destrozzzzz/MyBankApp.git
cd MyBankApp
```

### 2. Enable Lombok in Your IDE

Lombok is used to reduce boilerplate code.

- Setup instructions: [https://projectlombok.org/setup/eclipse](https://projectlombok.org/setup/eclipse)

### 3. Import the Project into Your IDE

- Import as a **Maven Project**
- Run `mvn clean install`
- If using Spring Tool Suite (STS) or IntelliJ:
  - Run as **Spring Boot App**

### 4. Run the Application

The API runs on port `8989` by default.

---

## 🔧 Prerequisites

- Java 8+
- Spring Tool Suite 4 / IntelliJ / Eclipse
- Maven

---

## 📦 Maven Dependencies

```xml
spring-boot-starter-actuator  
spring-boot-starter-data-jpa  
spring-boot-starter-security  
spring-boot-starter-web  
spring-boot-devtools  
h2  
lombok  
springfox-swagger2  
springfox-swagger-ui  
spring-boot-starter-test  
spring-security-test  
```

---

## 📑 API Documentation (Swagger)

Access the Swagger UI for testing endpoints:

[http://localhost:8989/bank-api/swagger-ui.html](http://localhost:8989/bank-api/swagger-ui.html)

---

## 🗃️ H2 In-Memory Database

H2 console available at:

[http://localhost:8989/bank-api/h2-console](http://localhost:8989/bank-api/h2-console)

> JDBC URL: `jdbc:h2:mem:testdb`

If using a custom DB name, configure `application.yml` accordingly.

---

## 🧪 Testing the API

- Use Swagger UI for interactive API testing.
- Sample request payloads can be found in:  
  `src/test/resources/`

---

## 👨‍💻 Author

**Khamar Ali**  
GitHub: [destrozzzzz](https://github.com/destrozzzzz)

---
