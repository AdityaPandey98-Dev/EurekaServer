# 🚀 Eureka Server
==================
A production-ready **Spring Cloud Netflix Eureka Server** built with **Spring Boot** for service discovery in a microservices architecture.

This project acts as the **Service Registry**, allowing microservices to dynamically register themselves and discover other services without hardcoding network locations.

## 📌 Features
===============
- Service Discovery using Netflix Eureka
- Centralized Service Registry
- Dynamic Registration of Microservices
- Eureka Dashboard
- Spring Boot 4
- Spring Cloud Netflix
- Maven Build
- Java 17
- Lightweight Configuration
- Ready for Microservices Architecture
- 
## 🛠 Tech Stack
===============
| Technology | Version |
|------------|---------|
| Java | 17 |
| Spring Boot | 4.1.0 |
| Spring Cloud | 2025.1.2 |
| Spring Cloud Netflix Eureka | Latest Compatible |
| Maven | 3.x |
| IntelliJ IDEA | Ultimate Edition |

## ⚙️ Configuration
====================
application.properties
---------------------
spring.application.name=EurekaServer
server.port=8761
eureka.client.register-with-eureka=false
eureka.client.fetch-registry=false

## ▶️ Run the Application
=========================
### Clone Repository

```bash
git clone https://github.com/your-username/eureka-server.git
```

### Navigate to Project

```bash
cd eureka-server
```

### Run

Using Maven Wrapper

```bash
./mvnw spring-boot:run
```

Windows

```bash
mvnw.cmd spring-boot:run
```

or

```bash
mvn spring-boot:run
```

---

## 🌐 Eureka Dashboard

After successful startup, open

```
http://localhost:8761
```

You should see the Eureka Dashboard.

> **Tip:** Add a screenshot of the dashboard inside a `screenshots/` folder and reference it here.

![Dashboard](screenshots/eureka-dashboard.png)

## 🏗 Architecture
==================
                   +----------------------+
                   |    Eureka Server     |
                   |      Port 8761       |
                   +----------+-----------+
                              ^
                              |
      -----------------------------------------------
      |                     |                       |
+-------------+      +---------------+      +---------------+
| User Service|      | Order Service |      | Product Service|
+-------------+      +---------------+      +---------------+


## 📦 Maven Dependencies added

- Spring Boot Starter Web
- Spring Cloud Netflix Eureka Server
- Spring Boot DevTools
- Lombok
- Spring Boot Test

## 🔮 Future Enhancements
- Docker Support
- Docker Compose
- Config Server Integration
- API Gateway Integration
- Spring Security
- Prometheus Monitoring
- Grafana Dashboard
- Kubernetes Deployment
- Distributed Tracing

---

# Aditya Pandey
# Java Full Stack Developer
- Java
- Spring Boot
- Microservices
- React
- AWS
- Docker

