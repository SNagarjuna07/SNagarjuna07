<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1e293b,100:334155&height=120&section=header&text=S%20Nagarjuna&fontSize=26&fontColor=ffffff&fontAlignY=38&desc=Backend%20Engineer%20in%20progress%0A-%20Distributed%20Systems%20%C2%B7%20Java%2FSpring%20Boot%20%C2%B7%20AI%20Infrastructure&descSize=14&descAlignY=58&animation=fadeIn" width="95%"/>

<a href="https://readme-typing-svg.demolab.com">
  <img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&size=20&pause=1500&color=38BDF8&center=true&vCenter=true&width=650&lines=I+build+backend+systems+and+break+them+on+purpose.;Java+%2F+Spring+Boot+%2F+Redis+%2F+Distributed+Systems.;Currently%3A+AI+agents%2C+MCP%2C+resilience+engineering." alt="Typing SVG" />
</a>

<a href="https://linkedin.com/in/s-nagarjuna"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="mailto:srinivasnagarjuna04@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>

</div>

## About

Integrated MCA student at Amrita Vishwa Vidyapeetham. I don't build demos - I build systems, then find out how they fail under real load, real concurrency, and real network partitions, and fix what I find before anyone else has to. Most recently: a 6-service microservices platform with an AI agent and a native MCP server, benchmarked to ~168,000 requests with zero failures.

Currently deep in resilience engineering, event-driven architecture, and applied AI infra (tool-calling agents, RAG, MCP).

## Featured Work

**[shortlyai](https://github.com/SNagarjuna07/shortlyai)** - Production-grade distributed URL-shortening platform built as a 6-service Spring Boot microservices system. Kafka SAGA choreography, transactional outbox, dual-layer circuit breakers, full Prometheus/Grafana/Loki/Tempo observability, an AI agent, and a native MCP server.

### Performance

![k6 Load Test](https://img.shields.io/badge/k6%20Load%20Test-1%2C325%20req%2Fs-7D64FF?style=flat-square&logo=k6&logoColor=white)
![Avg](https://img.shields.io/badge/Avg-~7ms-16A34A?style=flat-square)
![P95](https://img.shields.io/badge/P95-16.84ms-7C3AED?style=flat-square)
![Requests](https://img.shields.io/badge/Requests-167%2C966-0891B2?style=flat-square)
![Failures](https://img.shields.io/badge/Failures-0%25-16A34A?style=flat-square)
![VUs](https://img.shields.io/badge/VUs-200-F59E0B?style=flat-square)

> **1,325 req/s · ~7ms average · 16.84ms p95 · 167,966 requests · 0 failures · 200 concurrent users**

---

**[spring-ai-rag-service](https://github.com/SNagarjuna07/spring-ai-rag-service)** · **[spring-ai-chat-service](https://github.com/SNagarjuna07/spring-ai-chat-service)** · **[spring-ai-task-manager](https://github.com/SNagarjuna07/spring-ai-task-manager)** · **[spring-ai-mcp-server](https://github.com/SNagarjuna07/spring-ai-mcp-server)** - four separate Spring AI services, each isolating one architectural pattern (streaming chat, scoped tool-calling, RAG, MCP) instead of one monolithic AI demo. All four enforce a human-in-the-loop safety boundary on destructive operations - the AI proposes, it never executes unilaterally.

---

**[Food-Waste-Management](https://github.com/SNagarjuna07/Food-Waste-Management)** - Load-tested to 8,000 requests / 100 concurrent users / 0.00% error rate, designed explicitly around cache-outage and async-failure edge cases, not just the happy path.

## Stack

**Core** <br />
![Java](https://img.shields.io/badge/Java%2025-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot%204-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Spring Cloud](https://img.shields.io/badge/Spring%20Cloud-6DB33F?style=flat-square&logo=spring&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring%20Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white)
![Eureka](https://img.shields.io/badge/Netflix%20Eureka-6DB33F?style=flat-square&logo=spring&logoColor=white)

**Auth & Security**  <br />
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)
![OAuth2](https://img.shields.io/badge/OAuth2-EB5424?style=flat-square&logo=auth0&logoColor=white)
![BCrypt](https://img.shields.io/badge/BCrypt-004088?style=flat-square&logo=letsencrypt&logoColor=white)

**Data & Messaging**  <br />
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![Liquibase](https://img.shields.io/badge/Liquibase-2962FF?style=flat-square&logo=liquibase&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Kafka](https://img.shields.io/badge/Apache%20Kafka-000000?style=flat-square&logo=apachekafka)
![Dead Letter Queue](https://img.shields.io/badge/Kafka%20DLQ-231F20?style=flat-square&logo=apachekafka&logoColor=white)

**Resilience & Observability**  <br />
![Resilience4j](https://img.shields.io/badge/Resilience4j-006400?style=flat-square&logo=java&logoColor=white)
![ShedLock](https://img.shields.io/badge/ShedLock-006400?style=flat-square&logo=spring&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Loki](https://img.shields.io/badge/Loki-F5A623?style=flat-square&logo=grafana&logoColor=white)
![Tempo](https://img.shields.io/badge/Tempo-F5A623?style=flat-square&logo=grafana&logoColor=white)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-black?style=flat-square&logo=opentelemetry)
![Micrometer](https://img.shields.io/badge/Micrometer-117AC9?style=flat-square&logo=spring&logoColor=white)

**AI**  <br />
![Spring AI](https://img.shields.io/badge/Spring%20AI-6DB33F?style=flat-square&logo=spring&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-A259FF?style=flat-square&logo=anthropic&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-6B4FBB?style=flat-square&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-F55036?style=flat-square)
![Tavily](https://img.shields.io/badge/Tavily%20Search-336791?style=flat-square)

**API & Testing**  <br />
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)
![Swagger](https://img.shields.io/badge/Swagger%20%2F%20OpenAPI-85EA2D?style=flat-square&logo=swagger&logoColor=black)
![JUnit 5](https://img.shields.io/badge/JUnit%205-25A162?style=flat-square&logo=junit5&logoColor=white)
![Mockito](https://img.shields.io/badge/Mockito-25A162?style=flat-square&logo=java&logoColor=white)
![k6](https://img.shields.io/badge/k6-7D64FF?style=flat-square&logo=k6&logoColor=white)

**Infra & Tools**  <br />
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Docker Compose](https://img.shields.io/badge/Docker%20Compose-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2671E5?style=flat-square&logo=githubactions&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

## GitHub Stats

<table align="center">
<tr>
<td><img src="https://github-readme-stats-fast.vercel.app/api?username=SNagarjuna07&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" height="165"/></td>
<td><img src="https://streak-stats.demolab.com/?user=SNagarjuna07&theme=tokyonight&hide_border=true" height="165"/></td>
</tr>
</table>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:334155,100:1e293b&height=100&section=footer" width="100%"/>
