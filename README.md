# 🚀 Saranya Ganesan — Senior Java Backend Engineer Portfolio

Welcome to the source repository for my interactive single-file portfolio website. This repository showcases my enterprise backend experience across high-scale distributed systems, event-driven architectures, and federated API gateways in the airline, financial services, telecom, and startup domains.

---

## 🛠️ Key Technical Competencies

- **Languages & Frameworks:** Java 21, Spring Boot 3.x, Spring MVC, WebClient, Spring Data JPA/Hibernate, Node.js, Express.js
- **APIs & Distributed Architecture:** Microservices, GraphQL, Apollo Federation/Router, Stateless Aggregation, Service Orchestration, REST
- **Messaging & Event Streaming:** Apache Kafka, Kafka Connect, Avro, JSON
- **Databases & Persistence:** PostgreSQL, Liquibase, Native SQL, MariaDB, MySQL, Snowflake
- **Cloud & DevOps Platform:** AWS (S3), Kubernetes, OpenShift, Docker, Helm, IBM Cloud/KPaaS, Vault, Apigee, Akamai
- **Security & Delivery:** OAuth2, JWT, IBM Cloud Secrets Manager, GitHub Actions, Trident CI/CD, JaCoCo
- **Testing & Observability:** JUnit, Mockito, WireMock, Embedded PostgreSQL, Contract Testing, Apollo Studio, Dynatrace, Mezmo, Instana, Kibana

---

## 🌟 Featured System Architectures Highlighted

1. **Airline ReAccommodation Engine (American Airlines / Cognizant)**
   - Greenfield stateless orchestration service built with **Java 21, Spring Boot, and Apollo Federation**.
   - Handles **~418 RPM dual-region production traffic** with strict reactive `Spring WebClient` timeout controls.
   - Reduced schema composition downtime by implementing automated pre-composition schema quality gates in CI/CD pipelines.

2. **Financial Collections Decisioning Engine (Discover Financial Services / Capgemini)**
   - High-availability payment assistance microservice (`coll-pre-d`) using **Java 21, Spring Boot 3.1.2, and PostgreSQL**.
   - Event-driven Kafka streams with `@RetryableTopic` backoff strategies, Avro payloads, and Dead-Letter Topics (DLQ).
   - Upgraded framework legacy code from Spring Boot 2.x to 3.x (Jakarta EE) while sustaining **80%+ unit/integration test coverage**.

3. **LifePilot — AI Multi-Agent Personal Planner**
   - Multi-agent autonomous system built using **Google Gemini AI**, vector memory/embeddings, and dynamic task routing.
   - Containerized with Docker and deployed serverless on **Google Cloud Run** with Streamlit UI integration.

---

## 📁 Repository Structure

```text
.
├── index.html        # Complete standalone interactive portfolio page (HTML5, Tailwind CSS, Alpine.js)
└── README.md         # Repository overview and setup documentation
