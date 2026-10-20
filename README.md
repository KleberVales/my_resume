# Professional Summary

<p align="justify">Java & Spring Software Engineer with solid experience in backend development, microservices architecture, and cloud-native applications. I specialize in building scalable, secure, and maintainable systems using Java, Spring Boot, Docker, and Kubernetes, following clean architecture principles and DevOps best practices.<p/>

<p align="justify">With a strong foundation in Computer Science and an MBA in Web Software Development, I combine technical depth with a strategic mindset for delivering high-quality software in collaborative environments. Certified in Java, DevOps, Scrum, and Generative AI, I continuously invest in improving my expertise in cloud infrastructure, CI/CD pipelines, and modern software engineering practices.<p/>


[View my resume](https://klebervales.github.io/my_resume/)

## Projects

[**Smart Sales Store**](https://github.com/KleberVales/smart-sales-store)

Automation and inventory control in stores

Smart Sales Store is a fullstack application for managing sales operations, developed by Kleber Vales as a practical of modern Java and Spring Boot backend engineering. The project emphasizes clean architecture, domain-driven design, modularity, and scalable backend development, with its architecture prepared to evolve into a distributed system. integrations, discovery 

```text
┌─────────────────────────────────────────────────────────┐
│                    API Gateway                          │
└────────────────────┬────────────────────────────────────┘
                     │
     ┌───────────────┼───────────────┐
     ▼               ▼               ▼
┌─────────┐    ┌─────────┐    ┌─────────┐
│  User   │    │ Sales   │    │ Product │
│ Service │    │ Service │    │ Service │
└────┬────┘    └────┬────┘    └────┬────┘
     │              │              │
     ▼              ▼              ▼
┌─────────┐    ┌─────────┐    ┌─────────┐
│PostgreSQL│   │PostgreSQL│   │PostgreSQL│
└─────────┘    └─────────┘    └─────────┘
```

**Technology Stack**

The application is built using Java 21 and Spring Boot 3.2.4, with a Gradle multi-module structure that allows new services to be added independently. The current implementation includes a User Service responsible for user-related operations, utilizing Spring Web for REST API development, Spring Data JPA for persistence, and PostgreSQL as the relational database. The project employs Lombok for boilerplate reduction and JUnit 5 for automated testing.

**Architecture Principles**

The project follows Clean Architecture principles, ensuring business rules remain independent from external frameworks, databases, and delivery mechanisms. The architecture is organized into distinct layers: Controllers handling REST API interactions, Application layer containing use cases, Domain layer housing business rules, and Infrastructure layer managing JPA and PostgreSQL persistence. This separation enables the system to be easily tested, maintained, refactored, and migrated to different infrastructure solutions.

**Microservices Evolution**

Smart Sales Store is designed to evolve toward a microservices architecture, where each business capability can become an independent service. The repository structure includes modules for API Gateway, authentication, users, customers, products, inventory, orders, payments, sales, notifications, reports, server, and configuration server. Each service can own its own data and business rules, reducing coupling between bounded contexts.

**Planned Capabilities**

The project roadmap includes user authentication, product and inventory management, sales processing, customer service, API gateway implementation, service-to-service communication, event-driven architecture, observability features, Docker containerization, CI/CD pipeline setup, and cloud deployment. This comprehensive plan reflects the project's goal of serving as a practical laboratory for studying backend architecture and distributed systems.

---

[**Nutrition Daily**](https://github.com/KleberVales/nutrition-daily)

The Home Data Platform is a smart-home data platform designed to centralize environmental and device information in a single application. It aims to collect, organize, and analyze data such as temperature, humidity, energy consumption, presence, and air quality, providing a unified view of home conditions and helping users identify patterns and unusual events.



<img width="600" height="382" alt="yyy" src="https://github.com/user-attachments/assets/a6ad1b08-b5b3-4c98-bb06-6e9edbc924c4" />


[topelectronics.gr](https://topelectronics.gr/smart-home/neo/smart-temperature-and-humidity-sensor-zigbee-neo-nas-th02b-tuya/?utm_source=chatgpt.com)

---

### ✉️ Contact

Email: klebervales.dev@gmail.com  
LinkedIn: www.linkedin.com/in/kleber-vales

### Kleber Vales

**Java & Spring Software Engineer**

| Cloud | DevOps | Generative AI | Methodologies | Architectures |
  
**Certifications**  
🏆 **Oracle Certified Associate – Java SE 7 Programmer**  
🏆 **Microsoft Technology Associate – Software Development Fundamentals**  
🏆 **Scrum Fundamentals Certified (SFC™)**  
🏆 **Oracle Cloud Infrastructure 2025 – DevOps Professional**  
🏆 **Oracle Cloud Infrastructure 2025 – Generative AI Professional**  
🏆 **Agentic AI Certified Fundations Associate**  
🏆 **OCI AI Foundations Associate**  

🎓 **Bachelor's Degree in Computer Science**  
🎓 **MBA in Web Software Development**


