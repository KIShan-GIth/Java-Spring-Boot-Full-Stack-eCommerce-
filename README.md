# EcommerceHub: Enterprise Multi-Vendor E-Commerce Platform

A production-grade, full-stack multi-vendor e-commerce marketplace application built using **Spring Boot** and **React**, featuring role-based access control, secure payment processing, and real-time order management.

---

## 🚀 Key Features

*   **Multi-Portal Architecture:** Separate functionalities and dashboards for **Customers**, **Sellers**, and **Admins**.
*   **Secure Authentication & Authorization:** Enterprise-level security implemented using **Spring Security** with **JWT (JSON Web Tokens)** and Role-Based Access Control (RBAC).
*   **Payment Gateway Integration:** Secure online payment processing integrated via the **Stripe API**.
*   **Advanced Catalog Management:** Robust product search, sorting, and pagination capabilities backed by **JPA/Hibernate**.
*   **Scalable Backend & Responsive Frontend:** Built with high-throughput REST APIs on the backend and a sleek, modern UI on the frontend using React, Redux, and Tailwind CSS.

---

## 🛠️ Tech Stack

### Backend
*   **Java & Spring Boot** (REST APIs, Spring Data JPA)
*   **Spring Security & JWT** (Authentication & Authorization)
*   **PostgreSQL** (Relational Database)
*   **Maven** (Build & Dependency Management)

### Frontend
*   **React & Redux** (State Management & UI Components)
*   **Tailwind CSS** (Styling)

### Deployment & Tools
*   **Git & GitHub** (Version Control)
*   **Postman** (API Testing)

---

## 📁 Project Structure

```text
Java-Spring-Boot-Full-Stack-eCommerce/
│
├── spring-boot-main/        # Spring Boot REST API Backend
│   ├── src/
│   └── pom.xml
│
└── react-main/              # React Frontend Application
    ├── src/
    └── package.json
