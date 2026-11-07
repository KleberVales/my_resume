# Presentation

## 🚀 Journey

<p align="justify">My path in technology began in 2007, when I started customizing websites and managing domains and hosting on my own, purely out of curiosity. In 2010, I took a one-year technology course, and in 2014 I entered college to study Computer Science. During college, I had an entrepreneurial experience that taught me responsibility, business acumen, and organization, skills that still shape how I approach software projects today.</p>

<p align="justify">After graduating, I worked on a data collection project in industrial environments to monitor inventory. In 2019, I joined a project to automate bookstores, which gave me hands-on experience building solutions for real retail operations. In 2024, I joined a new company as a Java Developer and began a postgraduate degree in Software Development. In 2025, I earned three certifications, including two Oracle Professional certifications (DevOps and Generative AI), strengthening my foundation in cloud, DevOps, and Agile.</p>

## 🛠️ Projects

[**SMART SALE STORE**](https://github.com/KleberVales/smart-sales-store)

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

<p align="justify">The application is built using Java 21 and Spring Boot 3.2.4, with a Gradle multi-module structure that allows new services to be added independently. The current implementation includes a User Service responsible for user-related operations, utilizing Spring Web for REST API development, Spring Data JPA for persistence, and PostgreSQL as the relational database. The project employs Lombok for boilerplate reduction and JUnit 5 for automated testing.</p>

**Architecture Principles**

<p align="justify">The project follows Clean Architecture principles, ensuring business rules remain independent from external frameworks, databases, and delivery mechanisms. The architecture is organized into distinct layers: Controllers handling REST API interactions, Application layer containing use cases, Domain layer housing business rules, and Infrastructure layer managing JPA and PostgreSQL persistence. This separation enables the system to be easily tested, maintained, refactored, and migrated to different infrastructure solutions.</p>

**Microservices Evolution**

<p align="justify">Smart Sales Store is designed to evolve toward a microservices architecture, where each business capability can become an independent service. The repository structure includes modules for API Gateway, authentication, users, customers, products, inventory, orders, payments, sales, notifications, reports, server, and configuration server. Each service can own its own data and business rules, reducing coupling between bounded contexts.</p>

**Planned Capabilities**

<p align="justify">The project roadmap includes user authentication, product and inventory management, sales processing, customer service, API gateway implementation, service-to-service communication, event-driven architecture, observability features, Docker containerization, CI/CD pipeline setup, and cloud deployment. This comprehensive plan reflects the project's goal of serving as a practical laboratory for studying backend architecture and distributed systems.</p>

---

[**NUTRITION DAILY**](https://github.com/KleberVales/nutrition-daily)

<p align="justify">The Home Data Platform is a smart-home data platform designed to centralize environmental and device information in a single application. It aims to collect, organize, and analyze data such as temperature, humidity, energy consumption, presence, and air quality, providing a unified view of home conditions and helping users identify patterns and unusual events.</p>

<p align="justify">The project combines backend development, data persistence, cloud storage, IoT integration, and data visualization to explore how modern software architectures can transform raw sensor readings into useful insights.</p>

<img width="600" height="382" alt="yyy" src="https://github.com/user-attachments/assets/a6ad1b08-b5b3-4c98-bb06-6e9edbc924c4" />

Green Custard & Tiger Data | AWS IoT Migration & Real-Time Analytics

</br>

**Architecture and technologies**

<p align="justify">The proposed architecture uses a Java 21 and Spring Boot backend to expose APIs and coordinate access to application data. A React frontend provides dashboards and charts, while PostgreSQL stores structured information. AWS S3 is intended for image storage, and AWS IoT supports sensor and device integration. These components establish a foundation for organizing data flows between physical devices, cloud services, and the user interface.&#x20;</p>

<img width="600" height="382" alt="uuu" src="https://github.com/user-attachments/assets/70a31df0-40e2-446c-9594-7ba7f2f41dc2" />  

Green Custard & Tiger Data | AWS IoT Migration & Real-Time Analytics

</br>

**Dashboard and data visualization**

<p align="justify">The dashboard is intended to be the main entry point for exploring home data. Through charts, summary indicators, and historical views, users can gain a clearer understanding of environmental conditions and energy usage. The React interface and Spring Boot API provide a separation between presentation and business logic, supporting a modular approach to future development.</p> 

<img width="600" height="382" alt="rrr" src="https://github.com/user-attachments/assets/639e676a-58f8-49c4-8bfc-83204e3c5725" />  

### [Home Data Platform](https://github.com/KleberVales/home-data-platform)

**Smart Home Data Management and Analytics Platform**

<p align="justify">Home Data Platform is a cloud-oriented application designed to centralize and manage household data, providing a foundation for monitoring environmental conditions, device information, and historical data analysis.</p>

**Architecture and Technology Stack**

<p align="justify">The backend is built with Java 21 and Spring Boot, exposing REST APIs and organizing business logic into a modular service. PostgreSQL provides relational data persistence, while the React frontend is intended to provide dashboards and data visualization. The project also explores AWS integration for cloud storage and IoT device connectivity.</p>

**Backend Engineering and Deployment**

- Developed a Spring Boot backend service for family data management, exposing REST endpoints.
- Integrated PostgreSQL for persistent data storage.
- Containerized the application using Docker and Docker Compose.
- Deployed the backend application to AWS EC2, validating API accessibility and database connectivity.

**Technologies:** Java 21, Spring Boot, Gradle, REST APIs, PostgreSQL, Docker, Docker Compose, AWS EC2, React.

## 🎓 Education

**Bachelor's Degree in Computer Science**  

<p align="justify">My undergraduate studies were a period of significant, in-depth learning. Throughout the program, I developed semester-long practical projects that went beyond theory, requiring me to plan, design, and deliver working software while applying the concepts covered in class.</p>

<p align="justify">Beyond the classroom, I participated in science fairs, where I presented and defended my work, and in coding challenges that sharpened my problem-solving skills and my ability to write efficient code under pressure. These experiences built a strong technical foundation and a habit of continuous learning that I still carry into my professional work.</p>

**Postgraduate in Web Software Development**

<p align="justify">I started this postgraduate program in 2024, while working as a Java Developer, which let me apply what I learned directly to real projects. The program deepened my knowledge of modern web application development, covering software architecture, backend and frontend integration, databases, and good engineering practices for building scalable, maintainable systems.</p>

<p align="justify">Studying while working professionally connected theory and practice, strengthening my skills in clean architecture, REST APIs, and cloud-oriented development. It also supported the growth reflected in my 2025 certifications and in personal projects like Smart Sales Store and Home Data Platform.</p>

## 🏆 Certifications

**Oracle Certified Associate, Java SE 7 Programmer**

<p align="justify">The Oracle Certified Associate (OCA) Java SE 7 Programmer certification is an entry-level credential offered by Oracle that validates a candidate's fundamental knowledge of the Java programming language and object-oriented concepts. It is obtained by passing the Java SE 7 Programmer I exam (1Z0-803), </p>

**Oracle Cloud Infrastructure Certified AI Foundations Associate**

<p align="justify">The Oracle Cloud Infrastructure (OCI) AI Foundations certification is designed to introduce learners to the fundamental concepts of artificial intelligence (AI) and machine learning (ML), with a specific focus on the practical application of these technologies within the Oracle Cloud Infrastructure. This course is ideal for beginners and provides an accessible entry point for those looking to enhance their understanding of AI and ML without the requirement of prior extensive technical experience.</p>





