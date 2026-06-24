<h1 align="center">S Nagarjuna</h1>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&pause=1000&color=6DB33F&center=true&vCenter=true&width=700&lines=Backend+Developer+-+Java+%7C+Spring+Boot;Scalable+Microservices;Kafka+%7C+Redis+%7C+PostgreSQL+%7C+Circuit+Breakers;MCP+Server+%7C+Spring+AI" alt="Typing SVG" />
</p>

<p align="center">
  Integrated MCA student at <strong>Amrita Vishwa Vidyapeetham</strong> · Building backend systems that handle real load.<br/>
  I focus on security, scalability, clean API design and I learn best by implementing things.
</p>

<p align="center">
  <a href="https://linkedin.com/in/s-nagarjuna">
    <img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white" />
</p>

---

## 🚀 Featured Projects

### 🔗 [ShortlyAI](https://github.com/SNagarjuna07/shortlyai) - Production-Grade URL Shortener Platform

> 6-service Spring Boot 4 microservices system built with Java 25, designed for production load and resilience.

| Service | Port | Responsibility |
|---------|------|----------------|
| `eureka-server` | 8761 | Service discovery |
| `api-gateway` | 8080 | JWT pre-validation · Redis rate limiting · routing |
| `auth-service` | 8081 | JWT · OAuth2 · BCrypt · refresh tokens |
| `url-service` | 8082 | Base62 shortening · Redis cache · Kafka producer |
| `analytics-service` | 8083 | Kafka consumer · click tracking · Bloom filter |
| `ai-service` | 8084 | Spring AI · ReAct agent · MCP server · classification |

**Architecture highlights:**
- **SAGA choreography** via Kafka with compensating transactions + Transactional Outbox DLQ (retries every 15 min)
- **Cache-aside pattern** - Redis → PostgreSQL fallback on every redirect
- **MCP Server** (Model Context Protocol) - Claude AI manages URLs via live tool calls with SHA-256 API key auth
- **Resilience4j** - Circuit Breaker → Retry → Bulkhead → Time Limiter on every inter-service call
- **Token-bucket rate limiting** via Redis Lua script (atomic, gateway-level)
- **ShedLock** distributed locks on all 6 scheduled jobs across services
- **Observability** - Prometheus + Grafana + Loki + Promtail + MDC trace IDs
- **CI/CD** - GitHub Actions parallel test matrix
- **Virtual Threads** - `spring.threads.virtual.enabled: true` across all services

**Load test results (k6, url-service, 0 cold cache):**
```
Peak RPS    :  1,576  @ 500 VUs
Sweet spot  :  1,332  @ 200 VUs
Requests    :  ~284,000 total
Failure rate:  0%  ← circuit breakers return fallbacks, not errors
```

`Java 25` `Spring Boot 4` `Spring Cloud Gateway` `Spring AI 2.0` `Kafka` `Redis` `PostgreSQL` `Resilience4j` `Docker` `GitHub Actions` `Prometheus` `Grafana` `Loki` `ShedLock` `MCP`

---

### 🍱 [Food Waste Management](https://github.com/SNagarjuna07/Food-Waste-Management) - Donation Workflow Backend

> Production-ready backend with async notifications, OAuth2, and Redis rate limiting.

**Key features:**
- JWT + Google OAuth2 authentication
- Kafka async notification pipeline
- Redis-backed rate limiting
- MongoDB persistence with Spring Data
- Spring Boot Actuator observability endpoints
- Profile-based environment configuration (dev/prod)

`Spring Boot` `Kafka` `Redis` `MongoDB` `JWT` `OAuth2` `Spring Security` `Actuator`

---

### 📊 [Finance Data Processing System](https://github.com/SNagarjuna07/Finance-Data-Processing-System) - RBAC Finance Backend

> Role-based access control finance dashboard with fine-grained authorization tiers.

**Key features:**
- Spring Security RBAC - VIEWER / ANALYST / ADMIN tiers
- JWT authentication with stateless session
- Paginated records with soft delete
- Swagger / OpenAPI documentation

`Spring Boot` `Spring Security` `JWT` `MySQL` `Spring Data JPA` `Swagger`

---

## 🛠️ Tech Stack

**Languages & Frameworks**

![Java](https://img.shields.io/badge/Java%2025%20%2B%20Virtual%20Threads-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot%204-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring%20Security-%236DB33F.svg?style=for-the-badge&logo=springsecurity&logoColor=white)
![Spring Cloud](https://img.shields.io/badge/Spring%20Cloud%20Gateway-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white)
![Spring Data JPA](https://img.shields.io/badge/Spring%20Data%20JPA-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white)
![Spring AI](https://img.shields.io/badge/Spring%20AI%202.0-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white)
![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)

**Auth & Security**

![JWT](https://img.shields.io/badge/JWT-%23000000.svg?style=for-the-badge&logo=jsonwebtokens&logoColor=white)
![OAuth2](https://img.shields.io/badge/OAuth2%20Google-%23EB5424.svg?style=for-the-badge&logo=auth0&logoColor=white)
![BCrypt](https://img.shields.io/badge/BCrypt-%23004088.svg?style=for-the-badge&logo=letsencrypt&logoColor=white)
![API Key Auth](https://img.shields.io/badge/API%20Key%20Auth%20SHA--256-%23333.svg?style=for-the-badge&logo=keycdn&logoColor=white)

**Databases & Migrations**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL%2016-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis%207%20%2B%20RedisBloom-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)
![Liquibase](https://img.shields.io/badge/Liquibase-%232962FF.svg?style=for-the-badge&logo=liquibase&logoColor=white)

**Messaging & Events**

![Apache Kafka](https://img.shields.io/badge/Apache%20Kafka-000?style=for-the-badge&logo=apachekafka)
![Kafka SAGA](https://img.shields.io/badge/SAGA%20Choreography-%23000000.svg?style=for-the-badge&logo=apachekafka&logoColor=white)
![DLQ](https://img.shields.io/badge/Dead%20Letter%20Queue-%23B22222.svg?style=for-the-badge&logo=apachekafka&logoColor=white)

**Resilience**

![Resilience4j](https://img.shields.io/badge/Resilience4j-%23006400.svg?style=for-the-badge&logo=java&logoColor=white)
![Circuit Breaker](https://img.shields.io/badge/Circuit%20Breaker-%23B22222.svg?style=for-the-badge&logo=statuspage&logoColor=white)
![Retry](https://img.shields.io/badge/Retry-%23FF8C00.svg?style=for-the-badge&logo=statuspage&logoColor=white)
![Bulkhead](https://img.shields.io/badge/Bulkhead-%23708090.svg?style=for-the-badge&logo=statuspage&logoColor=white)
![Time Limiter](https://img.shields.io/badge/Time%20Limiter-%234B0082.svg?style=for-the-badge&logo=statuspage&logoColor=white)
![Rate Limiting](https://img.shields.io/badge/Rate%20Limiting%20Redis%20Lua-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white)
![ShedLock](https://img.shields.io/badge/ShedLock-%23006400.svg?style=for-the-badge&logo=spring&logoColor=white)

**API & Docs**

![REST API](https://img.shields.io/badge/REST%20API-%23007396.svg?style=for-the-badge&logo=fastapi&logoColor=white)
![Swagger](https://img.shields.io/badge/Swagger%20%2F%20OpenAPI%203-%2385EA2D.svg?style=for-the-badge&logo=swagger&logoColor=black)
![MCP Server](https://img.shields.io/badge/MCP%20Server-%23A259FF.svg?style=for-the-badge&logo=anthropic&logoColor=white)

**Infrastructure & DevOps**

![Docker](https://img.shields.io/badge/Docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![Docker Compose](https://img.shields.io/badge/Docker%20Compose-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white)
![Eureka](https://img.shields.io/badge/Eureka%20Service%20Discovery-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white)

**Observability**

![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=Prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-%23F46800.svg?style=for-the-badge&logo=grafana&logoColor=white)
![Loki](https://img.shields.io/badge/Loki-%23F5A623.svg?style=for-the-badge&logo=grafana&logoColor=white)
![Promtail](https://img.shields.io/badge/Promtail-%23F5A623.svg?style=for-the-badge&logo=grafana&logoColor=white)
![Micrometer](https://img.shields.io/badge/Micrometer-%23117AC9.svg?style=for-the-badge&logo=spring&logoColor=white)
![SLF4J](https://img.shields.io/badge/SLF4J%20%2F%20Logback-%23333.svg?style=for-the-badge&logo=java&logoColor=white)

**Testing & Load**

![JUnit 5](https://img.shields.io/badge/JUnit%205-%2325A162.svg?style=for-the-badge&logo=junit5&logoColor=white)
![Mockito](https://img.shields.io/badge/Mockito-%2325A162.svg?style=for-the-badge&logo=java&logoColor=white)
![k6](https://img.shields.io/badge/k6%20Load%20Testing-%237D64FF.svg?style=for-the-badge&logo=k6&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)

**Tools**

![Maven](https://img.shields.io/badge/Maven%20Multi--Module-%23C71A36.svg?style=for-the-badge&logo=apachemaven&logoColor=white)
![IntelliJ IDEA](https://img.shields.io/badge/IntelliJ%20IDEA-%23000000.svg?style=for-the-badge&logo=intellij-idea&logoColor=white)
![Git](https://img.shields.io/badge/Git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=SNagarjuna07&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true&rank_icon=github" height="165" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=SNagarjuna07&theme=tokyonight&hide_border=true&layout=compact&langs_count=6" height="165" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=SNagarjuna07&theme=tokyonight&hide_border=true" />
</p>

---

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=SNagarjuna07&theme=tokyonight&no-frame=true&row=1&column=6" />
</p>

---

<p align="center">
  <i>"Write code that survives production, not just interviews."</i>
</p>
