# 🚀 Book My Bus – Bus Ticket Reservation System

<p align="center">
<img src="https://img.shields.io/badge/Java-17-blue?style=for-the-badge&logo=java&logoColor=white" alt="Java 17">
<img src="https://img.shields.io/badge/Spring%20Boot-3.x-brightgreen?style=for-the-badge&logo=springboot&logoColor=white" alt="Spring Boot 3.x">
<img src="https://img.shields.io/badge/JPA%20%2F%20Hibernate-red?style=for-the-badge" alt="JPA / Hibernate">
<img src="https://img.shields.io/badge/Spring Security-white?style=for-the-badge" alt="Spring Security">
<img src="https://img.shields.io/badge/MySQL-lightgrey?style=for-the-badge" alt="MySQL">
</p>

"Book My Bus is a backend-based bus ticket reservation system developed using Spring Boot, Spring Security, JPA/Hibernate, and MySQL.

The application provides a secure platform where administrators can manage buses, routes, and reservations while customers can register, search buses, book tickets, and manage their reservations.

Designed using layered architecture (Controller → Service → DAO → Entity) with emphasis on security, scalability, clean code, and data consistency."

---

# ✨ Features

## 👨‍💻 Admin Features

- 🔐 Secure Admin Login
- 🚌 Manage Bus Details (Add, Update, Delete)
- 🛣️ Manage Routes
- 📅 Schedule Bus Services
- 👥 View Registered Users
- 🎫 View All Reservations
- ❌ Cancel Reservations
- 📊 Manage Bus Availability

---

## 🧑‍💻 User Features

- 📝 User Registration
- 🔐 Secure Login
- 👤 Manage Profile
- 🔍 Search Available Buses
- 🛣️ Search by Source & Destination
- 📅 Search by Journey Date
- 🎟️ Book Bus Tickets
- ❌ Cancel Bookings
- 📜 View Booking History
- ⭐ Submit Feedback

---

# 🛠️ Tech Stack

| Layer | Technology |
|-------|------------|
| Backend | Java 17, Spring Boot |
| Security | Spring Security |
| ORM | Spring Data JPA / Hibernate |
| Database | MySQL |
| Build Tool | Maven |
| API Testing | Postman |

---

# 📁 Project Structure

```
project-root/
│── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/
│   │   │       ├── controller/
│   │   │       ├── service/
│   │   │       ├── dao/
│   │   │       ├── entity/
│   │   │       ├── exception/
│   │   │       ├── security/
│   │   │       └── config/
│   │   │
│   │   └── resources/
│   │       ├── application.properties
│   │       └── static/
│
│── README.md
│── pom.xml
│── .gitignore
```

---

# 🖥️ API Modules

## 🔐 Authentication

- Admin Login
- User Registration
- User Login

---

## 🚌 Bus Management

- Add Bus
- Update Bus
- Delete Bus
- View Bus Details

---

## 🛣️ Route Management

- Add Route
- Update Route
- Delete Route
- View Routes

---

## 🎟️ Reservation Module

- Book Ticket
- View Reservation
- Cancel Reservation
- Reservation History

---

## ⭐ Feedback Module

- Add Feedback
- View Feedback

---

# 🚀 How to Run the Project

## ✔️ Prerequisites

- Java 17+
- Maven
- MySQL
- IntelliJ IDEA / Eclipse / VS Code

---

## ✔️ Clone Repository

```bash
git clone https://github.com/yourusername/book-my-bus.git

cd Book-My-Bus
```

---

## ✔️ Configure Database

Update **application.properties**

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/bookmybus
spring.datasource.username=root
spring.datasource.password=yourpassword
```

---

## ✔️ Run Application

Run

```
BusTicketReservationSystemApplication.java
```

Application starts at

```
http://localhost:8080
```

---

# 🗄️ Database

- MySQL Database
- Spring Data JPA
- Hibernate ORM

---

# 🔮 Future Enhancements

- JWT Authentication
- Email Notifications
- Online Payment Gateway
- Seat Selection
- Live Bus Tracking
- REST API Documentation (Swagger)
- Redis Caching
- Docker Deployment
- Microservices Architecture
- React/Angular Frontend

---

# 👨‍💻 Author

**Tushar Patil**

🎓 Computer Engineering Graduate

💻 Java | Spring Boot | Spring Security | SQL | Hibernate | JPA | REST APIs

---

# ❤️ Final Note

Book My Bus is a backend-focused project built to demonstrate industry-level Java backend development skills using Spring Boot, Spring Security, JPA/Hibernate, and MySQL.

The project follows layered architecture, RESTful API design, secure authentication, exception handling, and clean coding principles. It can be extended into a production-ready online bus reservation platform by integrating payment gateways, JWT authentication, cloud deployment, Docker, Redis, and Microservices.

Happy Coding ❤️
