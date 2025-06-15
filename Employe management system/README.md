# Employee Management System

A full-stack web application built with Java, Spring Boot, Hibernate, MySQL, and a responsive HTML/Bootstrap frontend. It allows users to perform CRUD operations on employee records.

## Features

- Add, view, update, and delete employees
- RESTful API backend
- Responsive Bootstrap frontend

## Technologies Used

- Java 17
- Spring Boot 3
- Spring Data JPA (Hibernate)
- MySQL
- Bootstrap 5
- JavaScript (Fetch API)

## Setup Instructions

### 1. Clone the repository

```
git clone <repo-url>
cd employee-management-system
```

### 2. Configure MySQL

- Create a database named `ems_db` in MySQL.
- Update `src/main/resources/application.properties` with your MySQL username and password.

### 3. Build and Run the Application

```
mvn spring-boot:run
```

The backend will start at `http://localhost:8080`.

### 4. Access the Frontend

Open your browser and go to:

```
http://localhost:8080/index.html
```

## API Endpoints

- `GET /api/employees` - List all employees
- `GET /api/employees/{id}` - Get employee by ID
- `POST /api/employees` - Add new employee
- `PUT /api/employees/{id}` - Update employee
- `DELETE /api/employees/{id}` - Delete employee

## License

MIT
