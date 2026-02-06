📚 **Book Management System – Spring Boot CRUD**
📌** Project Description**

A Spring Boot REST API that performs CRUD operations on a Book entity using Java, Spring Data JPA (CrudRepository), and MySQL. The project follows a layered architecture with Controller, Service, and Repository.

**🛠 Tech Stack**

Java

Spring Boot

Spring Data JPA

MySQL

REST APIs

Maven

Eclipse IDE

🧱 **Project Architecture**

Controller Layer – Handles HTTP requests

Service Layer – Contains business logic

Repository Layer – Manages database operations using CrudRepository

📘 **Book Entity Fields**

id (int)

name (String)

author (String)

price (float)

**🔗 API Endpoints**

| Method | Endpoint           | Description    |
| ------ | ------------------ | -------------- |
| GET    | `/getAllBooks`     | Get all books  |
| GET    | `/getBook/{id}`    | Get book by ID |
| POST   | `/addBook`         | Add new book   |
| PUT    | `/updateBook/{id}` | Update book    |
| DELETE | `/deleteBook/{id}` | Delete book    |

**⚙️ How to Run**

Clone the repository

Configure MySQL in application.properties

Run the project as Spring Boot App

Test APIs using Postman


**🎯 Purpose**

To understand CRUD operations, REST APIs, and database integration using Spring Boot and Spring Data JPA.
