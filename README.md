# ⚙️ Microservices Configuration Server

A **centralized configuration server** built using **Spring Cloud Config Server** to manage and provide configuration properties for all microservices from a single location.

### 🚀 Tech Stack

* ☕ Java 17 + Spring Boot
* ☁️ Spring Cloud Config Server
* 📁 Git-based Configuration
* 🔧 Maven

### ✨ Key Features

* ⚙️ Centralized `application.properties` for all services
* 🔄 Externalized configuration management
* 📦 Git-based configuration repository
* 🔐 Keeps service configurations separate from application code
* 🚀 Easy configuration updates across microservices
* 🧩 Supports multiple microservices in a distributed system

### 🏗️ Architecture

```text
Config Repository
       ↓
Config Server
       ↓
 ┌─────┼─────┐
 ↓     ↓     ↓
User  Hotel  Booking
Service Service Service
```

💻 **Built with Spring Boot & Spring Cloud by Manthan**

⭐ Feel free to explore the repository!
