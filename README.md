<div align="center">

# 📚 Book Management API
### Scalable RESTful Service with Spring Boot & Docker

[![Spring Boot](https://img.shields.io/badge/Spring_Boot-3.x-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white)](https://spring.io/projects/spring-boot)
[![Java](https://img.shields.io/badge/Java-17+-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)](https://www.oracle.com/java/)
[![Docker](https://img.shields.io/badge/Docker-Ready-2496ED?style=for-the-badge&logo=docker&logoColor=white)](https://www.docker.com/)
[![MySQL](https://img.shields.io/badge/MySQL-Data-4479A1?style=for-the-badge&logo=mysql&logoColor=white)](https://www.mysql.com/)

</div>

---

## 📖 Overview
The **Book Management API** is a robust backend solution designed to handle digital library operations. Built with a focus on **Clean Architecture** and **Scalability**, this REST API allows for seamless management of book records, integrated with a persistent MySQL database and fully containerized for instant deployment.

---

## 🚀 Key Features

- ✅ **Full CRUD Lifecycle**: Create, Read, Update (Partial/Full), and Delete book records.
- 🐳 **Containerized Deployment**: Multi-container orchestration using Docker Compose.
- 🛠️ **RESTful Standards**: Follows standard HTTP methods and status codes.
- 🗃️ **Persistence Layer**: Structured data management using Spring Data JPA & MySQL.
- ⚡ **Optimized Performance**: Lightweight service with minimal overhead.

---

## 🛠️ Tech Stack

| Category | Technology |
| :--- | :--- |
| **Language** | Java 17+ |
| **Framework** | Spring Boot 3.x |
| **Persistence** | Spring Data JPA / Hibernate |
| **Database** | MySQL 8.0 |
| **DevOps** | Docker, Docker Compose |
| **Build Tool** | Maven |

---

## 🗺️ API Endpoints

### 📘 Book Management

| Action | Method | Endpoint | Description |
| :--- | :--- | :--- | :--- |
| **Create** | `POST` | `/api/books` | Register a new book in the database |
| **Read All** | `GET` | `/api/books` | Fetch all available books |
| **Read One** | `GET` | `/api/books/{id}` | Retrieve details of a specific book |
| **Update** | `PATCH` | `/api/books/{id}` | Partially update book details |
| **Delete** | `DELETE` | `/api/books/{id}` | Remove a book from the system |

---

## 📦 Getting Started

### 🐳 Running with Docker (Recommended)
No need to install Java or MySQL locally. Just run:

```bash
# Clone the repository
git clone [https://github.com/sahil-dev/bookstack-rest-api.git](https://github.com/sahil-dev/bookstack-rest-api.git)

# Build and start containers
docker-compose up --build
├── src/main/java/com/sahil/bookapi
│   ├── controller/   # REST Endpoints
│   ├── model/        # Database Entities
│   ├── repository/   # Data Access Layer
│   └── service/      # Business Logic
├── Dockerfile        # Container Config
└── docker-compose.yml # Service Orchestration
👤 Author
MD Sahil

💼 LinkedIn

🌐 Portfolio

📧 Email

<div align="center">

⭐ Star this repository if you find it useful!
</div>
