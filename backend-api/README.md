# 🔌 EcoConnect - Backend Services

> **Internship Project** | **API & Data Processing**

This repository houses the backend logic for the EcoConnect ecosystem, serving both the Zalo Mini App (Volunteers) and the Admin Dashboard.

> 🔒 **Note:** *Source code is private due to NDA.*

## 🏗 System Architecture
The backend follows a **Monolith architecture**, focusing on scalability and data synchronization.

## 🛠 Tech Stack
* **Runtime:** Node.js.
* **Framework:** Express.js 
* **Database:** MongoDB (Flexible schema for event data).

## 💡 My Contributions
### 1. RESTful API Development
* Designed and implemented APIs for `Event Management` (CRUD) and `Volunteer Registration`.
* Ensured API security using JWT Authentication and Middleware validation.

### 2. Zalo API Gateway
* Developed a middleware to validate Zalo Access Tokens, ensuring requests genuinely originate from the Zalo Mini App.

## 📊 Database Schema (Simplified)
* **Users:** Linked with Zalo ID.
* **Events:** Main events created by other Volunteers.
* **Reviews:** User's review of an specific event.
* **Tickets:** Represents user's complaints about an event or another volunteer.
