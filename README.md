<div align="center">

# S Nagarjuna

**Backend Engineer** - Distributed Systems · Java / Spring Boot · AI Infrastructure

[LinkedIn](https://linkedin.com/in/s-nagarjuna)

<img src="https://img.shields.io/badge/Open%20to-Summer%202027%20SDE%20Internships-brightgreen?style=for-the-badge" />

</div>

---

## About

I build backend systems and load-test them until they fail, on purpose, so I know exactly how they degrade. Integrated MCA student at Amrita Vishwa Vidyapeetham, seeking a **Summer 2027 Software Engineering Internship**. Focus: microservices architecture, resilience engineering, and applied AI infrastructure (RAG, tool-calling agents, MCP).

---

## Highlights

- Designed and load-tested a 6-service microservices platform to **1,576 req/s peak, 0% failure rate across 284,485 requests** - circuit breakers degrade latency under overload instead of dropping requests. [`shortlyai`](https://github.com/SNagarjuna07/shortlyai)
- Built distributed transaction handling with **Kafka SAGA choreography** - no central orchestrator, failed events persisted and retried via ShedLock instead of relying on a managed DLQ. [`shortlyai`](https://github.com/SNagarjuna07/shortlyai)
- Shipped **4 independent Spring AI services** covering streaming chat, scoped tool-calling, Retrieval-Augmented Generation (RAG), and Model Context Protocol (MCP) - each isolating one architectural pattern rather than one monolithic AI demo. [`spring-ai-chat-service`](https://github.com/SNagarjuna07/spring-ai-chat-service) · [`spring-ai-task-manager`](https://github.com/SNagarjuna07/spring-ai-task-manager) · [`spring-ai-rag-service`](https://github.com/SNagarjuna07/spring-ai-rag-service)
- Enforced a **human-in-the-loop safety boundary** for destructive operations across two unrelated architectures (direct tool-calling and MCP) - AI can propose an action, never execute one. [`spring-ai-task-manager`](https://github.com/SNagarjuna07/spring-ai-task-manager)
- Load-tested a second backend to **8,000 requests, 100 concurrent users, 0.00% error rate**, designed explicitly around cache-outage and async-failure edge cases, not just the happy path. [`Food-Waste-Management`](https://github.com/SNagarjuna07/Food-Waste-Management)

---

## Stack

**Languages & Frameworks**

![Java](https://img.shields.io/badge/Java%2025-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot%204-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring%20Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white)
![Spring Cloud](https://img.shields.io/badge/Spring%20Cloud%20Gateway-6DB33F?style=flat-square&logo=spring&logoColor=white)
![Spring Data JPA](https://img.shields.io/badge/Spring%20Data%20JPA-6DB33F?style=flat-square&logo=spring&logoColor=white)
![Python](https://img.shields.io/badge/Python-3670A0?style=flat-square&logo=python&logoColor=ffdd54)

**AI / LLM**

![Spring AI](https://img.shields.io/badge/Spring%20AI-6DB33F?style=flat-square&logo=spring&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-A259FF?style=flat-square&logo=anthropic&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-336791?style=flat-square)
![Groq](https://img.shields.io/badge/Groq%20Llama%203.3-F55036?style=flat-square)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square)

**Auth & Security**

![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)
![OAuth2](https://img.shields.io/badge/OAuth2-EB5424?style=flat-square&logo=auth0&logoColor=white)
![BCrypt](https://img.shields.io/badge/BCrypt-004088?style=flat-square&logo=letsencrypt&logoColor=white)
![API Key Auth](https://img.shields.io/badge/API%20Key%20Auth%20SHA--256-333333?style=flat-square&logo=keycdn&logoColor=white)

**Data & Caching**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![pgvector](https://img.shields.io/badge/pgvector-336791?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![H2](https://img.shields.io/badge/H2-0000BB?style=flat-square)
![Liquibase](https://img.shields.io/badge/Liquibase-2962FF?style=flat-square&logo=liquibase&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=flat-square&logo=mongodb&logoColor=white)

**Messaging & Resilience**

![Kafka](https://img.shields.io/badge/Apache%20Kafka-000000?style=flat-square&logo=apachekafka)
![SAGA](https://img.shields.io/badge/SAGA%20Choreography-000000?style=flat-square&logo=apachekafka&logoColor=white)
![DLQ](https://img.shields.io/badge/Dead%20Letter%20Queue-B22222?style=flat-square&logo=apachekafka&logoColor=white)
![Resilience4j](https://img.shields.io/badge/Resilience4j-006400?style=flat-square&logo=java&logoColor=white)
![Circuit Breaker](https://img.shields.io/badge/Circuit%20Breaker-B22222?style=flat-square&logo=statuspage&logoColor=white)
![Retry](https://img.shields.io/badge/Retry-FF8C00?style=flat-square&logo=statuspage&logoColor=white)
![Bulkhead](https://img.shields.io/badge/Bulkhead-708090?style=flat-square&logo=statuspage&logoColor=white)
![Time Limiter](https://img.shields.io/badge/Time%20Limiter-4B0082?style=flat-square&logo=statuspage&logoColor=white)
![ShedLock](https://img.shields.io/badge/ShedLock-006400?style=flat-square&logo=spring&logoColor=white)
![Eureka](https://img.shields.io/badge/Netflix%20Eureka-6DB33F?style=flat-square&logo=spring&logoColor=white)

**API & Docs**

![REST API](https://img.shields.io/badge/REST%20API-007396?style=flat-square&logo=fastapi&logoColor=white)
![Swagger](https://img.shields.io/badge/Swagger%20%2F%20OpenAPI-85EA2D?style=flat-square&logo=swagger&logoColor=black)
![Jakarta Validation](https://img.shields.io/badge/Jakarta%20Validation-D91404?style=flat-square)

**Observability**

![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Loki](https://img.shields.io/badge/Loki-F5A623?style=flat-square&logo=grafana&logoColor=white)
![Promtail](https://img.shields.io/badge/Promtail-F5A623?style=flat-square&logo=grafana&logoColor=white)
![Micrometer](https://img.shields.io/badge/Micrometer-117AC9?style=flat-square&logo=spring&logoColor=white)
![SLF4J](https://img.shields.io/badge/SLF4J%20%2F%20Logback-333333?style=flat-square&logo=java&logoColor=white)

**Testing & Load**

![JUnit 5](https://img.shields.io/badge/JUnit%205-25A162?style=flat-square&logo=junit5&logoColor=white)
![Mockito](https://img.shields.io/badge/Mockito-25A162?style=flat-square&logo=java&logoColor=white)
![k6](https://img.shields.io/badge/k6-7D64FF?style=flat-square&logo=k6&logoColor=white)
![JMeter](https://img.shields.io/badge/Apache%20JMeter-D22128?style=flat-square&logo=apachejmeter&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)

**Infra & Tools**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Docker Compose](https://img.shields.io/badge/Docker%20Compose-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2671E5?style=flat-square&logo=githubactions&logoColor=white)
![Maven](https://img.shields.io/badge/Maven%20Multi--Module-C71A36?style=flat-square&logo=apachemaven&logoColor=white)
![Lombok](https://img.shields.io/badge/Lombok-BC0A5E?style=flat-square&logo=java&logoColor=white)
![IntelliJ IDEA](https://img.shields.io/badge/IntelliJ%20IDEA-000000?style=flat-square&logo=intellij-idea&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05033?style=flat-square&logo=git&logoColor=white)
