# 📦 SmartStock

> A modern inventory management system built with **Java 21**, **Spring Boot 3.5**, and **PostgreSQL**.

SmartStock is a backend application designed for small and medium-sized businesses to efficiently manage inventory, suppliers, purchases, sales, and stock movements. The project follows a layered architecture, SOLID principles, and Clean Code practices to ensure scalability, maintainability, and high code quality.

---

# 🚀 Tech Stack

| Technology | Version |
|------------|----------|
| Java | 21 |
| Spring Boot | 3.5 |
| Maven | 3.x |
| PostgreSQL | 17+ |
| Spring Data JPA | ✓ |
| Hibernate | ✓ |
| Lombok | ✓ |
| Bean Validation | ✓ |
| Git | ✓ |
| GitHub | ✓ |

---

# 🏗 Architecture

The project follows a layered architecture to improve maintainability and scalability.

```text
src/main/java/com/smartstock

├── authentication
├── category
├── common
├── config
├── exception
├── inventory
├── product
├── purchase
├── report
├── sale
├── security
├── supplier
├── user
└── util
```

Each business module contains:

```text
controller/
dto/
entity/
mapper/
repository/
service/
    └── impl/
```

---

# ✨ Features

## 👤 User Management

- User registration
- Authentication
- Role-based access
- User administration

### Roles

- Administrator
- Employee

---

## 📦 Product Management

- Product CRUD
- Barcode support
- Purchase price
- Selling price
- Current stock
- Minimum stock
- Category assignment
- Supplier assignment

---

## 🏷 Category Management

- Create categories
- Update categories
- Delete categories
- Retrieve categories

---

## 🚚 Supplier Management

- Complete CRUD operations

---

## 📊 Inventory Management

- Stock entries
- Stock exits
- Inventory movements
- Movement history

---

## 🛒 Purchase Management

- Register purchases
- Automatic stock updates

---

## 💰 Sales Management

- Register sales
- Automatic stock deduction

---

## 📈 Dashboard

- Total products
- Low stock alerts
- Daily sales
- Monthly purchases
- Best-selling products

---

## 📄 Reports

- Inventory reports
- Purchase reports
- Sales reports
- Out-of-stock products

---

# 🛠 Installation

## Clone the repository

```bash
git clone https://github.com/LauraDaheq/SmartStock.git
```

Enter the project directory

```bash
cd SmartStock
```

Build the project

```bash
mvn clean install
```

Run the application

```bash
mvn spring-boot:run
```

---

# 🗄 Database

Database Engine

- PostgreSQL

Database Name

```text
smartstock
```

---

# 📌 Project Status

🚧 **Currently under active development**

## ✅ Completed

- Spring Boot project setup
- Maven configuration
- Java 21 configuration
- PostgreSQL integration
- Modular project structure
- Initial backend architecture

## 🚧 In Progress

- User module
- Authentication
- Categories
- Products
- Inventory

## 📅 Planned

- Purchase module
- Sales module
- Dashboard
- Reports
- Spring Security
- JWT Authentication
- Swagger / OpenAPI
- Docker support
- Unit & Integration Tests
- CI/CD Pipeline

---

# 📍 Roadmap

- [x] Project setup
- [x] Spring Boot configuration
- [x] Maven configuration
- [x] PostgreSQL configuration
- [ ] User Management
- [ ] Authentication
- [ ] Category Management
- [ ] Supplier Management
- [ ] Product Management
- [ ] Inventory Management
- [ ] Purchase Module
- [ ] Sales Module
- [ ] Dashboard
- [ ] Reports
- [ ] Spring Security
- [ ] JWT Authentication
- [ ] Swagger / OpenAPI
- [ ] Docker
- [ ] Unit Testing
- [ ] Integration Testing
- [ ] CI/CD

---

# 🎯 Project Goals

- Develop a scalable RESTful API.
- Apply Layered Architecture principles.
- Follow SOLID principles.
- Write clean and maintainable code.
- Build a production-ready backend application.
- Showcase backend development best practices.

---

# 📖 Future Improvements

- Docker Compose deployment
- Flyway database migrations
- Redis caching
- Email notifications
- Audit logging
- API versioning
- Monitoring with Spring Boot Actuator
- Performance optimization

---

# 👩‍💻 Author

**Laura Hernández**

Electronic Engineer

Universidad Nacional de Colombia

GitHub

**https://github.com/LauraDaheq**

---

# ⭐ Support

If you find this project useful, consider giving it a **Star ⭐** on GitHub.
