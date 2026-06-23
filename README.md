<h1 align="center">S Nagarjuna</h1>

<p align="center">
  <a href="https://readme-typing-svg.demolab.com">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&pause=1000&color=6DB33F&center=true&vCenter=true&width=650&lines=Backend+Engineer+%E2%80%94+Java+%26+Spring+Boot;Production-Grade+Microservices;Event-Driven+Systems+%7C+Kafka+%7C+Redis+%7C+PostgreSQL;Security+%7C+Resilience+%7C+Observability+%7C+MCP" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  Integrated MCA student at <strong>Amrita Vishwa Vidyapeetham</strong> · Building backend systems that handle real load.<br/>
  I focus on security, scalability, and clean API design and I learn best by implementing things.
</p>

<p align="center">
  <a href="https://linkedin.com/in/s-nagarjuna">
    <img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="https://www.instagram.com/_nagarjun07_">
    <img src="https://img.shields.io/badge/Instagram-%23E4405F.svg?style=for-the-badge&logo=Instagram&logoColor=white" />
  </a>
  <img src="https://komarev.com/ghpvc/?username=SNagarjuna07&style=for-the-badge&color=6DB33F&label=PROFILE+VIEWS" />
</p>

---

## 🚀 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 🔗 [ShortlyAI](https://github.com/SNagarjuna07/shortlyai) — URL Shortener Platform

Production-grade **6-service microservices system** built on Java 25 + Spring Boot 4.

**Architecture highlights:**
- Spring Cloud Gateway — JWT pre-validation, Redis token-bucket rate limiting
- SAGA choreography via Kafka with compensating transactions + DLQ
- MCP server (Model Context Protocol) — Claude AI can manage URLs via tool calls
- Resilience4j circuit breakers, retries, bulkheads, time limiters
- Prometheus + Grafana + Loki observability stack
- GitHub Actions CI/CD → GHCR image registry

**Load test results (k6, 500 VUs):**
```
Peak RPS:       1,576
Sweet-spot RPS: 1,332 @ 200 VUs
Total requests: ~284,000
Failure rate:   0%  ← zero-failure graceful degradation
```

`Java 25` `Spring Boot 4` `Kafka` `Redis` `PostgreSQL` `Spring AI` `Docker`

</td>
<td width="50%" valign="top">

### 🍱 [Food Waste Management](https://github.com/SNagarjuna07/Food-Waste-Management)

Production-ready **donation workflow backend** with full auth and async notifications.

**Key features:**
- JWT + Google OAuth2 authentication
- Redis-backed rate limiting
- Kafka async notification pipeline
- MongoDB persistence
- Spring Boot Actuator observability
- Profile-based environment config

`Spring Boot` `Kafka` `Redis` `MongoDB` `OAuth2`

---

### 📊 [Finance Data Processing System](https://github.com/SNagarjuna07/Finance-Data-Processing-System)

Role-based **finance dashboard backend** with fine-grained access control.

**Key features:**
- Spring Security RBAC — VIEWER / ANALYST / ADMIN tiers
- JWT authentication
- Paginated records with soft delete
- Swagger UI documentation

`Spring Boot` `Spring Security` `JWT` `MySQL` `Swagger`

</td>
</tr>
</table>

---

## 🛠️ Tech Stack

**Languages & Frameworks**

![Java](https://img.shields.io/badge/Java%2025-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot%204-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring%20Security-%236DB33F.svg?style=for-the-badge&logo=springsecurity&logoColor=white)
![Spring Cloud](https://img.shields.io/badge/Spring%20Cloud-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white)
![Spring AI](https://img.shields.io/badge/Spring%20AI-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white)
![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)

**Auth & Security**

![JWT](https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens)
![OAuth2](https://img.shields.io/badge/OAuth2-%23EB5424.svg?style=for-the-badge&logo=auth0&logoColor=white)
![BCrypt](https://img.shields.io/badge/BCrypt-%23004088.svg?style=for-the-badge&logo=letsencrypt&logoColor=white)

**Databases & Messaging**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Apache%20Kafka-000?style=for-the-badge&logo=apachekafka)
![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)
![Liquibase](https://img.shields.io/badge/Liquibase-%232962FF.svg?style=for-the-badge&logo=liquibase&logoColor=white)

**Resilience & API**

![Resilience4j](https://img.shields.io/badge/Resilience4j-%23006400.svg?style=for-the-badge&logo=java&logoColor=white)
![Circuit Breaker](https://img.shields.io/badge/Circuit%20Breaker-%23B22222.svg?style=for-the-badge&logo=statuspage&logoColor=white)
![Rate Limiting](https://img.shields.io/badge/Rate%20Limiting-Redis%20Lua-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white)
![REST](https://img.shields.io/badge/REST%20API-%23007396.svg?style=for-the-badge&logo=fastapi&logoColor=white)
![Swagger](https://img.shields.io/badge/Swagger%20%2F%20OpenAPI-%23Clojure?style=for-the-badge&logo=swagger&logoColor=white)

**Infrastructure & Observability**

![Docker](https://img.shields.io/badge/Docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=Prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-%23F46800.svg?style=for-the-badge&logo=grafana&logoColor=white)
![Loki](https://img.shields.io/badge/Loki-%23F5A623.svg?style=for-the-badge&logo=grafana&logoColor=white)
![Micrometer](https://img.shields.io/badge/Micrometer-%23117AC9.svg?style=for-the-badge&logo=spring&logoColor=white)
![Eureka](https://img.shields.io/badge/Eureka%20%2F%20Service%20Discovery-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white)

**Tools**

![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![IntelliJ IDEA](https://img.shields.io/badge/IntelliJ%20IDEA-000000.svg?style=for-the-badge&logo=intellij-idea&logoColor=white)
![Git](https://img.shields.io/badge/Git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-%23C71A36.svg?style=for-the-badge&logo=apachemaven&logoColor=white)

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
