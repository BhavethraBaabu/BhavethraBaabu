# Hi, I'm Bhavethra Baabu

### Backend Software Engineer | Java • Spring Boot • Python • AWS • Distributed Systems

I build backend systems, APIs, and cloud-native services with a focus on **reliability, scalability, and clean architecture**.

Currently working across **Java/Spring Boot, Python, TypeScript, PostgreSQL, AWS, and distributed systems**, while building AI-powered applications using **RAG, vector search, and LLMs**.

Previously, I worked as a Software Engineer at **LTIMindtree**, building backend services and enterprise financial workflows with Java and Spring Boot.

---

## What I Work On

```text
Backend Engineering
├── REST APIs & Microservices
├── Java / Spring Boot
├── Python / FastAPI
├── PostgreSQL & Redis
└── API Security

Cloud & Distributed Systems
├── AWS
├── Docker & Kubernetes
├── Event-driven architecture
├── Caching & Load Balancing
└── Observability

AI Engineering
├── RAG
├── Vector Search
├── LLM Applications
└── AI-powered Developer Tools
```

---

## Tech Stack

### Languages

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square\&logo=openjdk\&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square\&logo=python\&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square\&logo=typescript\&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square\&logo=javascript\&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square\&logo=postgresql\&logoColor=white)

### Backend & APIs

![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square\&logo=springboot\&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square\&logo=fastapi\&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square\&logo=react\&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square\&logo=next.js\&logoColor=white)

REST APIs • Microservices • API Gateway • JWT • OAuth2 • WebSockets

### Databases & Messaging

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square\&logo=postgresql\&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square\&logo=mongodb\&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square\&logo=redis\&logoColor=white)
![Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=flat-square\&logo=apachekafka\&logoColor=white)

PostgreSQL • MongoDB • Redis • pgvector • Kafka • Redis Streams • Amazon SQS

### Cloud & DevOps

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square\&logo=amazonaws\&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square\&logo=docker\&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square\&logo=kubernetes\&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square\&logo=githubactions\&logoColor=white)

EC2 • S3 • RDS • Lambda • CloudWatch • Docker • Kubernetes • CI/CD • Maven

### Observability & Testing

Prometheus • Grafana • JUnit 5 • Mockito • PyTest • Postman • Integration Testing

### Architecture

`Distributed Systems` · `Microservices` · `Caching` · `Load Balancing` · `Circuit Breakers` · `Event-Driven Systems`

### AI / LLM

`RAG` · `Vector Search` · `LangChain` · `OpenAI API` · `Groq Llama` · `Prompt Engineering`

---

## Featured Projects

### CampusPulse — AI Academic Search

**Next.js • TypeScript • Python • PostgreSQL • Qdrant • Groq Llama 3.1**

An AI-powered academic search platform that provides natural-language answers across **285+ university pages**.

* Built data ingestion, transformation, and indexing pipelines
* Implemented semantic search and AI-assisted content retrieval
* Exposed backend functionality through REST APIs
* Presented the project at the Clark University Tech Innovation Challenge

[View Repository](https://github.com/BhavethraBaabu)

---

### CoinPulse — Real-Time Market Data Platform

**Next.js • TypeScript • PostgreSQL • WebSockets • REST APIs**

A real-time event-driven platform for streaming cryptocurrency market data.

* Built a WebSocket-based real-time data pipeline using Binance APIs
* Streamed live market data for **1,000+ cryptocurrency assets**
* Implemented candlestick visualizations and real-time updates
* Optimized server-side rendering and caching
* Delivered market updates within approximately **2 seconds**

[View Repository](https://github.com/BhavethraBaabu)

---

### Real-Time Monitoring Microservice

**Python • FastAPI • Prometheus • Grafana • Docker**

A cloud-native monitoring service for application health and system metrics.

* Built REST endpoints for service health and diagnostics
* Added Prometheus metrics instrumentation
* Containerized the service with Docker
* Created Grafana dashboards for monitoring
* Designed the service around observable microservice patterns

[View Repository](https://github.com/BhavethraBaabu/Real-Time-Monitoring-Microservice-Python-FastAPI)

---

## Architecture Focus

I enjoy designing systems where the individual components are simple, observable, and independently scalable.

```text
                    ┌──────────────────┐
                    │    Client / UI   │
                    └────────┬─────────┘
                             │
                             ▼
                    ┌──────────────────┐
                    │   API Gateway    │
                    │ Auth / Rate Limit│
                    └────────┬─────────┘
                             │
              ┌──────────────┼──────────────┐
              ▼              ▼              ▼
        ┌──────────┐   ┌──────────┐   ┌──────────┐
        │ Service A│   │ Service B│   │ Service C│
        │ Spring   │   │ FastAPI  │   │ AI/RAG   │
        └────┬─────┘   └────┬─────┘   └────┬─────┘
             │              │              │
             └──────────────┼──────────────┘
                            ▼
                 ┌────────────────────┐
                 │ PostgreSQL / Redis │
                 │ Kafka / SQS        │
                 └─────────┬──────────┘
                           │
                           ▼
                 ┌────────────────────┐
                 │ AWS Infrastructure │
                 │ Observability      │
                 └────────────────────┘
```

Areas I care about:

* API design and versioning
* Authentication and authorization
* Database design and query performance
* Caching and rate limiting
* Asynchronous processing
* Event-driven architecture
* Fault tolerance and retries
* Monitoring and observability
* Horizontal scalability

---

## Engineering Principles

```text
Simple systems are easier to scale.
Observable systems are easier to operate.
Well-designed APIs are easier to evolve.
Failures should be expected and isolated.
Performance starts with good architecture.
```

---

## GitHub Activity

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=BhavethraBaabu&show_icons=true&hide_border=true&rank_icon=github" height="165"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=BhavethraBaabu&layout=compact&hide_border=true" height="165"/>
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=BhavethraBaabu&hide_border=true" />
</p>

---

## Currently Learning

* Advanced Java and Spring Boot
* Distributed systems
* System design
* AWS architecture
* Event-driven systems
* Scalable backend APIs
* AI infrastructure and RAG systems

---

## Let's Connect

I'm interested in **Software Engineer, Backend Engineer, Java/Spring Boot, Full Stack, and Cloud Engineering** opportunities.

<p align="left">
  <a href="https://github.com/BhavethraBaabu">
    <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" />
  </a>
  <a href="https://linkedin.com/in/bhavethrab24">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" />
  </a>
  <a href="https://bhavethraBaabu.github.io/bhavethra-portfolio/">
    <img src="https://img.shields.io/badge/Portfolio-000000?style=flat-square&logo=googlechrome&logoColor=white" />
  </a>
  <a href="mailto:bbaabu@clarku.edu">
    <img src="https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white" />
  </a>
</p>

---

### Building backend systems, one service at a time.
