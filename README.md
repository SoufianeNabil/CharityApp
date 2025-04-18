# CharityApp

CharityApp is a charity action management application that allows users and organizations to create, track, and participate in charitable initiatives.

## 🌟 Main Features

### Organization Management
- **Register organizations** (name, legal address, tax number, etc.).

### Charity Action Management
- **Create, modify, and archive actions**.
- Add **descriptions**, **locations**, **dates**, **financial goals**, **images**, and **videos**.

### Participation & Donations
- **Register for actions**.
- **Secure online donations**.

---

## 🏗️ Technical Architecture

### Backend:
- **Frameworks**: Spring Boot 3.x, Spring MVC, Spring Data JPA, Spring Security.
- **Database**: MySQL (phpMyAdmin).
- **Project Management**: Maven.

### Frontend:
- **Template Engine**: Thymeleaf.
- **CSS Framework**: Bootstrap.

### Tools Used:
- IntelliJ IDEA
- Postman
- Git

---

## 🚀 Quick Start

### Prerequisites
- **Java** 17+
- **Maven**
- **Database**: MySQL (phpMyAdmin)

### Launch the Application

1. **Clone the repository**:
   ```bash
   git clone https://github.com/SoufianeNabil/CharityApp.git
   cd CharityApp
   ```

2. **Configure the database** in `application.properties`:
   ```properties
   spring.datasource.url=jdbc:mysql://localhost:3306/charitydb
   spring.datasource.username=root
   spring.datasource.password=
   ```

3. **Run the project using Maven**:
   ```bash
   ./mvnw spring-boot:run
   ```

4. **Access the application**:
   http://localhost:8080/

---

## 🗄️ Database

- **MySQL**: Used in production.

---

## 📚 Documentation

- [Spring Boot - Official Documentation](https://spring.io/projects/spring-boot)
- [Thymeleaf - Documentation](https://www.thymeleaf.org/documentation.html)
- [MySQL Connector/J Documentation](https://dev.mysql.com/doc/connector-j/)

---

## ✍️ Author

- **Soufiane Nabil**  
  [GitHub](https://github.com/SoufianeNabil)
