# Employee Management System

A full-stack web application to manage employees — built with Java (Spring Boot) for the backend and React for the frontend.

---

## 🚀 Features

- Add, update, and delete employee records
- View employee details
- Search employees
- RESTful API integration
- Frontend + backend separation

---

## 🛠 Tech Stack

### Backend:
- Java 17
- Spring Boot
- Spring Data JPA
- MySQL / H2 (choose your DB)
- Maven

### Frontend:
- React
- Axios
- Bootstrap / TailwindCSS

---

## 📂 Project Structure

```bash
Employee_Management/
├── backend/
│   ├── src/
│   └── pom.xml
├── frontend/
│   ├── src/
│   └── package.json
└── README.md


1. Clone the Repo


git clone https://github.com/abhi8618404/Employee_manager_clean.git
cd Employee_manager_clean

2. Start Backend (Spring Boot)

cd backend
./mvnw spring-boot:run

3.Start Frontend (React)
cd frontend
npm install
npm start


# 🧰 Employee Management System – Backend (Spring Boot)

This is the **backend** of the Employee Management System, built using **Spring Boot**. It provides a REST API for managing employee data and can be consumed by any frontend client (like Angular, React, etc.).

---

## 🔧 Tech Stack

- Java 17  
- Spring Boot  
- Spring Data JPA  
- MySQL / H2 Database  
- Maven  

---

## 📂 Project Structure

backend/
├── src/
│ ├── main/
│ │ ├── java/
│ │ │ └── com.example.employeemanagement/
│ │ │ ├── controller/
│ │ │ ├── model/
│ │ │ ├── repository/
│ │ │ ├── service/
│ │ │ └── EmployeeManagementApplication.java
│ │ └── resources/
│ │ ├── application.properties
│ │ └── data.sql
└── pom.xml


---

## 🧪 API Endpoints

| Method | Endpoint         | Description              |
|--------|------------------|--------------------------|
| GET    | /api/employees   | Get all employees        |
| GET    | /api/employees/{id} | Get employee by ID  |
| POST   | /api/employees   | Add new employee         |
| PUT    | /api/employees/{id} | Update employee     |
| DELETE | /api/employees/{id} | Delete employee     |

---

## 🚀 How to Run

### Prerequisites:
- Java 17
- Maven
- MySQL (or use H2)

### Steps:

```bash
cd backend
./mvnw spring-boot:run

spring.datasource.url=jdbc:mysql://localhost:3306/your_db
spring.datasource.username=root
spring.datasource.password=your_password
spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true


