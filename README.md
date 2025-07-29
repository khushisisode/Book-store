Here’s a professionally edited and simplified version of your *Online Book Store* project README:

---

# 📚 Online Book Store

A full-featured Online Book Store web application built with *Spring Boot, **Thymeleaf, and supports **both MySQL and H2 databases*. Users can register, browse, search, purchase, rate, and review books.

---

## ✨ Features

* 🔐 User Registration & Login
* 🧑‍💼 Role-Based Views (Admin & User)
* 📘 Add, Edit, Delete & View Books
* ⭐ Book Ratings & Reviews
* 🛒 Order Management
* 💬 SweetAlert2 for Stylish Alerts
* 🔄 Dual DB Support (MySQL & H2)

---

## 🛠 Tech Stack

* *Java 17*
* *Spring Boot 3.1.3*
* *Spring Data JPA*
* *Thymeleaf*
* *MySQL* / *H2 Database*
* *SweetAlert2*
* *Eclipse* / *VS Code*

---

## ⚙ Setup Instructions

### 🔍 Prerequisites

* Java JDK 17
* Maven
* MySQL (Optional – for persistent DB)

---

### 📥 Clone the Project

bash
git clone https://github.com/SLoharkar/Online-Book-Store.git


### 💻 Open in IDE

* Import the project as a *Maven project* into *Eclipse* or *VS Code*

---

### 🗄 Configure Database

Choose one of the following setups in application.properties:

#### ✅ MySQL (Persistent)

properties
spring.datasource.url=jdbc:mysql://localhost:3306/bookstore
spring.datasource.username=root
spring.datasource.password=yourpassword
spring.jpa.hibernate.ddl-auto=update


#### 🧪 H2 (In-Memory for testing)

properties
spring.datasource.url=jdbc:h2:mem:testdb
spring.datasource.driverClassName=org.h2.Driver
spring.datasource.username=sa
spring.datasource.password=
spring.h2.console.enabled=true


---

### ▶ Run the Application

bash
mvn spring-boot:run


Access the site at: [http://localhost:8080](http://localhost:8080)

---

## 🎞 Demo

🔗 [Watch the Project Walkthrough](https://github.com/SLoharkar/Online-Book-Store/assets/68845746/6cfab389-498e-42ad-82d2-2c26738284f8)

---

## 🖼 UI Screenshots

Find 40+ UI screenshots in the Screenshots/ folder:

* Login & Registration
* Dashboards (User/Admin)
* Book Listings & Details
* Order Management
* Alerts & Modals

---

## 📁 Project Structure


online-book-store/
├── src/main/java/              # Java Source Files
├── src/main/resources/
│   ├── templates/              # Thymeleaf Templates
│   └── application.properties
├── Screenshots/                # UI Images
├── pom.xml                     # Maven Config
└── README.md                   # Project Info


---

## 📄 License

This project is licensed under the *MIT License*.

---

Let me know if you'd like to add a *Contributors* section, *API details, or **deployment steps*.
