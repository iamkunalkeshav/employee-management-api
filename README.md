# 🧩 Employee Management API

A simple Spring Boot REST API for managing employees (create, read, update, delete).

---

## 🚀 Tech Stack
- Java 17  
- Spring Boot 3.x  
- Maven  
- Docker & Docker Compose  

---

## ⚙️ Setup (Local)

```bash
git clone https://github.com/iamkunalkeshav/employee-management-api.git
cd employee-management-api
mvn spring-boot:run
App runs on 👉 http://localhost:8080


🐳 Run with Docker
docker-compose up --build

This will start:

Spring Boot app on port 8080

MySQL container on port 3306

| Method | Endpoint          | Description       |
| ------ | ----------------- | ----------------- |
| GET    | `/employees`      | Get all employees |
| POST   | `/employees`      | Add new employee  |
| PUT    | `/employees/{id}` | Update employee   |
| DELETE | `/employees/{id}` | Delete employee   |


👨‍💻 Author

Kunal Keshav
🔗 github.com/iamkunalkeshav
