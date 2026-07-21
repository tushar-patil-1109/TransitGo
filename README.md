# 🚀 TransitGo – Bus Ticket Reservation System


<p align="center">
<img src="https://img.shields.io/badge/Java-17-blue?style=for-the-badge&logo=java&logoColor=white" alt="Java 17">
<img src="https://img.shields.io/badge/Spring%20Boot-3.x-brightgreen?style=for-the-badge&logo=springboot&logoColor=white" alt="Spring Boot 3.x">
<img src="https://img.shields.io/badge/JPA%20%2F%20Hibernate-red?style=for-the-badge" alt="JPA / Hibernate">
<img src="https://img.shields.io/badge/Spring Security-lightgrey?style=for-the-badge" alt="Spring Security">
<img src="https://img.shields.io/badge/MySQL-lightgrey?style=for-the-badge" alt="MySQL">
</p>


- ### deploy link: https://melodious-cassata-4c43f9.netlify.app/
- TransitGo is a full-stack portfolio project demonstrating a clear separation of concerns between a RESTful Java backend and a Vanilla JavaScript frontend.
- The platform provides a reliable environment where administrators can manage bus schedules, routes, and user details, while passengers can securely book tickets, cancel reservations, and submit feedback.
- Designed using a layered backend architecture (Controller → Service → Repository → Model) with dedicated exception handling and session management to ensure security, scalability, and seamless data flow.

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

```text
project-root/
│
├── Book-My-Bus-Backend/
│   ├── .mvn/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/
│   │   │   │   └── com/masai/
│   │   │   │       ├── controller/              # REST Controllers
│   │   │   │       ├── exception/              # Global Exception Handling
│   │   │   │       ├── model/                  # Entity Classes
│   │   │   │       ├── repository/             # JPA Repositories
│   │   │   │       ├── service/                # Business Logic
│   │   │   │       └── BusTicketReservationSystemApplication.java
│   │   │   │
│   │   │   └── resources/
│   │   │       ├── application.properties
│   │   │       ├── application-dev.properties
│   │   │       └── application-prod.properties
│   │   │
│   │   └── test/
│   │
│   ├── pom.xml
│   ├── mvnw
│   └── mvnw.cmd
│
├── Bus-Reservation-System-Frontend/
│   ├── Admin_section/
│   │   ├── images/
│   │   ├── scripts/
│   │   │   ├── AddBus.js
│   │   │   ├── Admin_Home.js
│   │   │   ├── route.js
│   │   │   └── ...
│   │   ├── styles/
│   │   │   ├── AddnewBusStyle.css
│   │   │   ├── bus.css
│   │   │   └── ...
│   │   ├── AddBus.html
│   │   ├── Admin_Home.html
│   │   ├── Admin_User_Details.html
│   │   ├── bus.html
│   │   └── route.html
│   │
│   └── User-Side/
│       ├── images/
│       ├── bookTicket.html
│       ├── cancelTicket.html
│       ├── feedback.html
│       └── ...
│
├── README.md
└── .gitignore
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
git clone https://github.com/tushar-patil-1109/transitgo.git

cd TransitGo
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

<a href="https://wa.me/+91 8378990863">
<img src="https://img.shields.io/badge/WhatsApp-Chat%20Now-green?style=for-the-badge&logo=whatsapp" >
</a>

- 🎓 Computer Engineering Graduate

- 💻 Java | Spring Boot | Spring Security | SQL | Hibernate | JPA | REST APIs

---

# ❤️ Final Note

TransitGo is a backend-focused project built to demonstrate industry-level Java backend development skills using Spring Boot, Spring Security, JPA/Hibernate, and MySQL.

The project follows layered architecture, RESTful API design, secure authentication, exception handling, and clean coding principles. It can be extended into a production-ready online bus reservation platform by integrating payment gateways, JWT authentication, cloud deployment, Docker, Redis, and Microservices.

---

<p align="center">
<strong>Happy Coding ❤️</strong>
</p>

