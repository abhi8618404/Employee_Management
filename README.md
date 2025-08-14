# 🧑‍💼 Employee Management System

![Java](https://img.shields.io/badge/Java-007396.svg?&logo=java&logoColor=white) 
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F.svg?&logo=springboot&logoColor=white) 
![React](https://img.shields.io/badge/React-61DAFB.svg?&logo=react&logoColor=black) 
![MySQL](https://img.shields.io/badge/MySQL-4479A1.svg?&logo=mysql&logoColor=white) 
![REST API](https://img.shields.io/badge/REST_API-000000.svg?&logo=fastapi&logoColor=white)  

A **full-stack Employee Management System** that allows HR/Admins to manage employee records efficiently with CRUD operations, authentication, and state management.  
Built using **Spring Boot (Backend)**, **React (Frontend)**, and **MySQL (Database)**.

---

## ✨ Features

- 👨‍💼 Add, update, delete, and view employee details.
- 🔐 Authentication & Authorization (JWT ready).
- 📊 Search and filter employees.
- 💾 Persistent data storage with MySQL.
- 🌐 RESTful APIs for integration.

---

## 🛠 Tech Stack

### Backend:
- **Java 17**
- **Spring Boot**
- **Spring Data JPA**
- **Hibernate ORM**
- **MySQL**
- **Maven**

### Frontend:
- **React.js**
- **Axios**
- **Bootstrap**

---

## 📂 Project Structure

```
Employee_Management/
│
├── backend/               # Spring Boot Backend
│   ├── src/main/java
│   ├── src/main/resources
│   └── pom.xml
│
├── frontend/              # React Frontend
│   ├── src
│   ├── public
│   └── package.json
│
└── README.md
```

---

## ⚡ Installation & Setup

### 1️⃣ Clone the repository
```bash
git clone https://github.com/abhi8618404/Employee_Management.git
cd Employee_Management
```

### 2️⃣ Backend Setup
```bash
cd backend
mvn clean install
mvn spring-boot:run
```

### 3️⃣ Frontend Setup
```bash
cd frontend
npm install
npm start
```

---

## 🔗 API Endpoints

| Method | Endpoint           | Description              |
|--------|-------------------|--------------------------|
| GET    | /employees        | Get all employees        |
| GET    | /employees/{id}   | Get employee by ID       |
| POST   | /employees        | Add a new employee       |
| PUT    | /employees/{id}   | Update employee details  |
| DELETE | /employees/{id}   | Delete employee          |

---

## 📸 Screenshots

> *Add your application screenshots here*

---

## 📜 License
This project is licensed under the MIT License.

---

## 🤝 Contributing
Pull requests are welcome. For significant changes, please open an issue first to discuss the proposed changes.
