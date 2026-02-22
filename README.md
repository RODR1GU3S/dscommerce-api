# DSCommerce System – Spring Boot E-Commerce Backend

A professional backend application built with **Java** and **Spring Boot**, implementing a simplified e-commerce domain model with ORM mapping, relational database integration, and clean layered architecture.

This project demonstrates real-world backend concepts including domain modeling, entity relationships, JPA/Hibernate integration, and structured service architecture.

---

## 🚀 Features

- Domain-driven design for e-commerce systems
- User, Order, Product, and Payment modeling
- Entity relationships:
  - Many-to-One
  - One-to-One
  - Many-to-Many
  - Association class (composite key)
- JPA and Hibernate ORM mapping
- H2 in-memory database for development
- Data seeding
- Clean layered architecture (Controller → Service → Repository)

---

## 🛠 Technologies Used

- Java 11+
- Spring Boot
- Spring Data JPA
- Hibernate
- H2 Database
- Maven

---

## 📁 Project Structure

```
src/
└── main/
    └── java/
        └── com.devsuperior.dscommerce
            ├── controllers
            ├── services
            ├── repositories
            ├── entities
            ├── dto
            └── config
```

The project follows a layered architecture to ensure:

- Separation of concerns  
- Maintainability  
- Scalability  
- Clean code organization  

---

## 🗃 Domain Model Overview

The system models a simplified e-commerce environment including:

- Users
- Orders
- Products
- Categories
- Payments

Relationships implemented:

- User → Orders (One-to-Many)
- Order → Payment (One-to-One)
- Product ↔ Category (Many-to-Many)
- Order ↔ Product (Many-to-Many with association class)

---

## ⚙️ How to Run the Project

### 1️⃣ Clone the repository

```bash
git clone https://github.com/RODR1GU3S/Project---DSCommerce-System
```

### 2️⃣ Navigate to the project folder

```bash
cd Project---DSCommerce-System
```

### 3️⃣ Run the application

```bash
mvn spring-boot:run
```

The application will start at:

```
http://localhost:8080
```

---

## 🗄 H2 Database Console

Since the project uses H2 for development, you can access the database console:

```
http://localhost:8080/h2-console
```

Default configuration:

- JDBC URL: `jdbc:h2:mem:testdb`
- Username: `sa`
- Password: (leave blank)

---

## 🧠 Key Backend Concepts Demonstrated

- Relational database modeling
- ORM with JPA/Hibernate
- Entity mapping strategies
- Composite primary keys
- Association class implementation
- Clean service-layer separation
- Repository abstraction with Spring Data JPA

---

## 🎯 Purpose of This Project

This project was developed to practice and demonstrate backend system modeling for an e-commerce domain, focusing on:

- Correct entity relationship mapping
- Clean architectural patterns
- Real-world business logic representation
- Scalable backend design

---

## 👨‍💻 Author

Ronaldo Rodrigues  
Backend Java & Spring Boot Developer
