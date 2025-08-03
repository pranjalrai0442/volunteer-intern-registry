# Volunteer / Intern Registry (Spring Boot)

## 📋 Description
A backend service to:
- Register users (interns or volunteers)
- Allow admin-only access to view registered users

Built using **Spring Boot**, **Spring Security (OAuth2 with Google Login)**, and **PostgreSQL**.

---

## 🔧 Tech Stack
- Java 17+
- Spring Boot
- Spring Security (OAuth2 Login)
- PostgreSQL
- Maven

---

## 📁 Endpoints

| Method | Endpoint     | Access        | Description                      |
|--------|--------------|---------------|----------------------------------|
| POST   | `/register`  | Public        | Register a new intern/volunteer  |
| GET    | `/viewlist`  | Admin-only    | View registered users (secure)   |

---

## 🚀 Getting Started

### ✅ 1. Clone the repository
```bash
git clone https://github.com/your-username/volunteer-intern-registry.git
cd volunteer-intern-registry
