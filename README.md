# bookstore-api-backend


This Spring Boot application implements a RESTful API for managing a bookstore. It includes CRUD operations for books, pagination, sorting, and role-based access control with Basic Authentication.

## Features
- **CRUD Operations**: Create, read, update, and delete books.
- **Pagination and Sorting**: Retrieve books with pagination and sorting (e.g., by `title`, `price`).
- **Role-Based Access Control**:
  - `USER` role: Can perform `GET` requests (read-only).
  - `ADMIN` role: Can perform `POST`, `PUT`, and `DELETE` requests (full access).
- **Basic Authentication**:
  - Username: `admin`, Password: `admin123` (Role: `ADMIN`)
  - Username: `user`, Password: `user123` (Role: `USER`)
- **H2 In-Memory Database**: Uses H2 for data storage with a web console for easy access.

## Prerequisites
- **Java 17**: Ensure you have Java 17 installed.
- **Maven**: Maven is used for dependency management and building the project.
- **Postman**: For testing the API endpoints.

## How to Run the Application
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/Book_store-api.git
   cd Book_store-api
