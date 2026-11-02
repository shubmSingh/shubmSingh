<!-- ═══════════════ HEADER ═══════════════ -->
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:020617,50:164E63,100:2563EB&height=230&section=header&text=Shubham%20Singh&fontSize=58&fontColor=ffffff&fontAlignY=38&animation=fadeIn&desc=Backend%20Engineer%20%7C%20Distributed%20Systems%20%7C%20AI%20Engineering&descSize=18&descAlignY=60" width="100%" alt="Shubham Singh banner"/>

<a href="https://github.com/shubmSingh">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=900&color=38BDF8&center=true&vCenter=true&width=760&height=45&lines=I+build+backends+that+scale+and+don't+fall+over;10M%2B+events%2Fday+%C2%B7+sub-500ms+streaming+latency;Java+21+%C2%B7+Spring+Boot+%C2%B7+Kafka+%C2%B7+Flink;Now+exploring+LLMs%2C+RAG+%26+MCP" alt="Typing animation"/>
</a>

<br/><br/>

<a href="#-about-me">About</a> ·
<a href="#-core-backend-skills">Skills</a> ·
<a href="#-how-i-design-systems">Architecture</a> ·
<a href="#-featured-projects">Projects</a> ·
<a href="#-ai-engineering">AI</a> ·
<a href="#-lets-connect">Contact</a>

<br/><br/>

<img src="https://img.shields.io/badge/Java_21-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white"/>
<img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white"/>
<img src="https://img.shields.io/badge/Apache_Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white"/>
<img src="https://img.shields.io/badge/Apache_Flink-E6526F?style=for-the-badge&logo=apacheflink&logoColor=white"/>
<img src="https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white"/>
<img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white"/>

<br/>

<a href="https://shubmsingh.github.io/Shubhamsingh.github.io/"><img src="https://img.shields.io/badge/Portfolio-2563EB?style=flat-square&logo=googlechrome&logoColor=white"/></a>
<a href="mailto:Shubhammcmt@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white"/></a>
<a href="https://www.linkedin.com/in/your-link-here"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white"/></a>
<img src="https://komarev.com/ghpvc/?username=shubmSingh&label=Profile+Views&color=2563EB&style=flat-square"/>

</div>

---

## ⚡ Quick Glance

<div align="center">

| 🧑‍💻 Role | 📅 Experience | 🎯 Specialty | 🌍 Open to |
|:---:|:---:|:---:|:---:|
| Backend Software Engineer | 5+ years | Event-driven & high-throughput systems | Backend / Distributed Systems / AI-enabled backend roles |

</div>

<div align="center">

<img src="https://img.shields.io/badge/10M%2B-Events%20Processed%20Daily-2563EB?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Sub--500ms-Streaming%20Latency-7C3AED?style=for-the-badge"/>
<img src="https://img.shields.io/badge/30%25-Kafka%20Throughput%20Gain-0891B2?style=for-the-badge"/>
<img src="https://img.shields.io/badge/AWS-Solutions%20Architect%20Associate-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white"/>

</div>

---

## 👋 About Me

I'm a **Backend Software Engineer** who designs and runs production systems that need to be **fast, reliable and easy to operate**.

My day-to-day: event-driven microservices, stream processing, API design, performance tuning, and making sure systems behave well when things go wrong. I'm also exploring how **LLMs, RAG and agentic workflows** can plug into real backend systems.

- ⚙️ Enterprise backends with **Java 21 + Spring Boot**
- 🔄 Real-time pipelines with **Kafka + Apache Flink**
- 🚀 Tuning throughput, latency and resource usage
- ☁️ Cloud-native deployments on **AWS, Docker, Kubernetes**
- 🤖 Exploring **LLMs, RAG, MCP** and AI-assisted engineering

---

## 🧱 Core Backend Skills

<div align="center">

| Area | What I work with |
|---|---|
| **API Design** | REST, gRPC, versioning, pagination, idempotency, validation, error contracts |
| **Microservices** | Service boundaries, inter-service communication, event-driven design, saga / outbox patterns |
| **Messaging & Streaming** | Kafka (partitioning, consumer groups, offsets, retries, DLQ), Flink (windowing, state, exactly-once) |
| **Data & Persistence** | PostgreSQL, MySQL, MongoDB, Redis · indexing, query tuning, transactions, caching strategies |
| **Concurrency & Performance** | Multithreading, virtual threads (Java 21), profiling, JVM tuning, load testing |
| **Resilience** | Timeouts, retries with backoff, circuit breakers, rate limiting, graceful degradation |
| **Observability** | Structured logging, metrics, distributed tracing, alerting, dashboards |
| **Security** | AuthN/AuthZ, OAuth2 / JWT, secrets management, input validation |
| **Testing & Quality** | Unit, integration & contract tests, Testcontainers, code review, clean code |
| **Cloud & DevOps** | AWS, Docker, Kubernetes, Terraform, Jenkins CI/CD, Linux, Git |

</div>

---

## 🏗️ How I Design Systems

A simplified view of the event-driven pattern I commonly work with:

```mermaid
flowchart LR
    C([Client / Upstream]) --> G[API Gateway]
    G --> S1[Spring Boot Service]
    S1 -->|write| DB[(PostgreSQL)]
    S1 -->|cache| R[(Redis)]
    S1 -->|publish event| K{{Apache Kafka}}
    K --> F[Apache Flink<br/>stream processing]
    K --> S2[Downstream Service]
    F --> S3[(Analytics / Store)]
    S2 --> N([Notifications / APIs])
    S1 -. metrics, logs, traces .-> O[Observability]
    F -. metrics, logs, traces .-> O
```

**Design priorities:** decouple with events · keep services stateless · make consumers idempotent · plan for retries and failures · measure before optimizing.

---

## 🧩 Engineering Principles

> ⚡ **Performance** should be measured, not assumed.
> 🏗️ **Architecture** should evolve with system requirements.
> 🔄 **Distributed systems** should anticipate failure.
> 🔍 **Observability** is essential for production reliability.
> 🧪 **Testing & maintainability** are part of engineering, not afterthoughts.
> 🤝 **AI** is an engineering multiplier — with human judgment at the center.

---

## 🚀 Featured Projects

<!-- Replace the repo names/descriptions below with your real projects. Delete this comment. -->

<div align="center">

<a href="https://github.com/shubmSingh/YOUR-REPO-1">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=shubmSingh&repo=YOUR-REPO-1&theme=tokyonight&hide_border=true"/>
</a>
<a href="https://github.com/shubmSingh/YOUR-REPO-2">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=shubmSingh&repo=YOUR-REPO-2&theme=tokyonight&hide_border=true"/>
</a>

<a href="https://github.com/shubmSingh/YOUR-REPO-3">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=shubmSingh&repo=YOUR-REPO-3&theme=tokyonight&hide_border=true"/>
</a>
<a href="https://github.com/shubmSingh/YOUR-REPO-4">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=shubmSingh&repo=YOUR-REPO-4&theme=tokyonight&hide_border=true"/>
</a>

</div>

**Ideas worth showcasing:** a Kafka + Spring Boot event-driven demo · a Flink streaming job · a rate limiter / circuit-breaker example · a RAG or MCP experiment with a Java backend.

---

## 🛠️ Tech Stack

<div align="center">

**Languages & Frameworks**

<img src="https://skillicons.dev/icons?i=java,spring,maven,gradle&theme=dark"/>

**Data & Messaging**

<img src="https://skillicons.dev/icons?i=postgres,mysql,mongodb,redis,kafka&theme=dark"/>
<img src="https://img.shields.io/badge/Apache_Flink-E6526F?style=for-the-badge&logo=apacheflink&logoColor=white"/>
<img src="https://img.shields.io/badge/gRPC-244C5A?style=for-the-badge&logo=grpc&logoColor=white"/>

**Cloud, DevOps & Observability**

<img src="https://skillicons.dev/icons?i=aws,docker,kubernetes,terraform,jenkins,linux,git,github,grafana,prometheus&theme=dark"/>

</div>

---

## 🤖 AI Engineering

I'm exploring how AI can complement traditional backend engineering.

| Area | Focus |
|---|---|
| 🧠 **LLMs** | Building AI-powered features into applications |
| 🔎 **RAG** | Embeddings, vector search, retrieval strategies |
| 🔌 **MCP** | Model Context Protocol, tools and AI-to-system integrations |
| 🧩 **AI Agents** | Tool use, workflows, agentic systems |
| 🤖 **AI Copilots** | GitHub Copilot and LLM-assisted development |
| ✍️ **Prompt Engineering** | Structured prompts and context design |

<div align="center">

<img src="https://img.shields.io/badge/LLMs-Exploring-7C3AED?style=flat-square"/>
<img src="https://img.shields.io/badge/RAG-Learning-2563EB?style=flat-square"/>
<img src="https://img.shields.io/badge/MCP-Exploring-0891B2?style=flat-square"/>
<img src="https://img.shields.io/badge/GitHub_Copilot-Using-181717?style=flat-square&logo=githubcopilot&logoColor=white"/>

</div>

---

## 🌱 Currently

- 📖 Going deeper into LLM application architecture and RAG pipelines
- 🔬 Experimenting with MCP servers and integrating AI into Java / Spring Boot backends
- 🧠 Sharpening system design and distributed-systems fundamentals

**💬 Ask me about:** Kafka, Flink, Spring Boot, microservices, performance tuning, system design, AWS.

---

## 📈 GitHub Analytics

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=shubmSingh&show_icons=true&theme=tokyonight&hide_border=true&rank_icon=github"/>
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=shubmSingh&layout=compact&theme=tokyonight&hide_border=true"/>

<img width="80%" src="https://streak-stats.demolab.com?user=shubmSingh&theme=tokyonight&hide_border=true"/>

<img width="95%" src="https://github-readme-activity-graph.vercel.app/graph?username=shubmSingh&bg_color=0d1117&color=38bdf8&line=2563eb&point=ffffff&area=true&area_color=2563eb&hide_border=true"/>

</div>

---

## 🐍 Contribution Snake

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/shubmSingh/shubmSingh/output/github-contribution-grid-snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/shubmSingh/shubmSingh/output/github-contribution-grid-snake.svg"/>
  <img alt="Contribution snake animation" src="https://raw.githubusercontent.com/shubmSingh/shubmSingh/output/github-contribution-grid-snake-dark.svg" width="100%"/>
</picture>

</div>

---

## 🎓 Certifications

<div align="center">

<img src="https://img.shields.io/badge/AWS-Certified_Solutions_Architect_Associate-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white"/>
<img src="https://img.shields.io/badge/Backbase-Backend_Engineering_Certified-2563EB?style=for-the-badge"/>

</div>

---

## 🤝 Let's Connect

<div align="center">

Open to interesting backend, distributed-systems and AI-engineering conversations.

<a href="https://github.com/shubmSingh"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/></a>
<a href="mailto:Shubhammcmt@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="https://www.linkedin.com/in/shubham-singh-8b05b8184/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="https://shubmsingh.github.io/Shubhamsingh.github.io/"><img src="https://img.shields.io/badge/Portfolio-2563EB?style=for-the-badge&logo=googlechrome&logoColor=white"/></a>

<br/><br/>

**Engineering at scale. Learning beyond boundaries.**

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:020617,50:164E63,100:2563EB&height=120&section=footer&animation=fadeIn" width="100%" alt="footer"/>

</div>
