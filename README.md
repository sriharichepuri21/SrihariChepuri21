<div align="center">

# Hi, I'm Srihari Chepuri 👋

<a href="https://github.com/sriharichepuri21">
  <img src="https://readme-typing-svg.demolab.com?font=Inter&weight=600&size=22&pause=1400&color=2C6E9B&center=true&vCenter=true&width=640&lines=Software+Engineer+%E2%80%94+Distributed+Systems+%26+Data+Platforms;Java+%C2%B7+Spring+Boot+%C2%B7+Kafka+%C2%B7+Spark+%C2%B7+AWS;I+build+systems+and+measure+that+they+work" alt="Software Engineer — Distributed Systems & Data Platforms" />
</a>

[![Portfolio](https://img.shields.io/badge/Portfolio-2C6E9B?style=for-the-badge&logo=googlechrome&logoColor=white)](https://sriharichepuri21.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sri-hari-417b191a1)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sh.chepuri21@gmail.com)

</div>

---

## 👨‍💻 About Me

```yaml
role:        Software Engineer @ LiveRamp
experience:  3+ years — LiveRamp, Zebra Technologies, University of North Texas
focus:       distributed systems, data platforms, event-driven microservices
education:   MS Business Analytics, University of North Texas
location:    Seattle, WA
principle:   every project ships with measured results — and its limits
```

---

## 💼 Experience Highlights

| | What I built | Result |
|---|---|---|
| **LiveRamp** | Java/Python control- and data-plane services on AWS | **10+ TB/day**, 500M+ daily requests, multi-tenant |
| | Parquet ingestion pipeline redesign | **90 → 700 configs/day** (7×) |
| | Pipeline observability and tuning | P95 latency **1.2 s → 340 ms** |
| | Temporal + Airflow migration workflows | **50+ TiB** migrated, +20% throughput |
| **Zebra Technologies** | Versioned data-access service (Java, Thrift, MySQL, OAuth2) | Consistent data access for downstream teams |
| | On-call for JVM services behind PTT Pro | **50+** critical incidents resolved, 10,000+ daily users |

---

## 🚀 Featured Projects

<a href="https://github.com/sriharichepuri21/stateverdict">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/sriharichepuri21/stateverdict/main/docs/assets/hero-dark.svg">
    <img alt="StateVerdict: a payment message is delivered twice. Without the fix the customer is charged twice and the verdict is FAIL; with the fix it is PASS." src="https://raw.githubusercontent.com/sriharichepuri21/stateverdict/main/docs/assets/hero-light.svg" width="100%">
  </picture>
</a>

<a href="https://cotab.center">
  <img alt="Cotab: Receipts, read by Tabby, with Tabby the AI agent waving in front of his name" src="assets/cotab-hero.jpg" width="100%">
</a>

| Project | What it does | Proof | Built with |
|---|---|---|---|
| **[StateVerdict](https://github.com/sriharichepuri21/stateverdict)**<br>[▶ live demo](https://sriharichepuri21.github.io/stateverdict/) | Makes Kafka messages arrive twice, late or out of turn **on purpose**, then checks the databases, not the status codes | 🐞 Found a **money-creation bug** in an open-source Kafka app<br>✅ **0 false alarms** in 510 valid scenarios<br>🎯 **6/6** planted bugs caught<br>⚡ **~35 ns** overhead per message | Java 21, Spring Boot, Kafka, PostgreSQL, Testcontainers |
| **[Kairo](https://github.com/sriharichepuri21/kairo-marketplace-intelligence)** | A marketplace plus the data platform behind it: dbt bronze/silver/gold models, churn ML, data-quality monitoring | 📦 **16M+** generated records<br>🧪 dbt **153 passing, 0 errors**<br>💰 **$0** reconciliation variance | Next.js, FastAPI, PostgreSQL, dbt, DuckDB, scikit-learn, Streamlit |
| **[Cotab](https://github.com/sriharichepuri21/Cotab)**<br>[▶ try it](https://cotab.center) | An AI-powered money app. **Tabby**, its AI agent, reads every line of a receipt (photo, PDF or forwarded email), keeps item-level budgets, splits bills to the cent with pro-rata tax and tracks who owes whom. Ask in plain words; every change waits for your approval | 🚀 **Live** at cotab.center<br>🧪 **826** backend · **185** unit · **50** browser tests<br>🔒 17 typed tools; AI-written SQL is read-only, parsed, allow-listed and user-scoped<br>✅ Every AI change needs your yes | Python, FastAPI, Gemini, PostgreSQL, Next.js, TypeScript |

---

## 🛠️ Tech Stack

**Languages**<br>
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C#](https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)

**Backend & Messaging**<br>
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![gRPC](https://img.shields.io/badge/gRPC-244C5A?style=flat-square&logo=grpc&logoColor=white)

**Data**<br>
![Apache Spark](https://img.shields.io/badge/Apache_Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![Apache Airflow](https://img.shields.io/badge/Apache_Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white)

**Cloud & Delivery**<br>
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

---

## 📊 GitHub Stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=sriharichepuri21&show_icons=true&hide_border=true&theme=transparent&title_color=2C6E9B&icon_color=2C6E9B&text_color=8B949E" alt="GitHub stats" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=sriharichepuri21&layout=compact&hide_border=true&theme=transparent&title_color=2C6E9B&text_color=8B949E" alt="Top languages" />

</div>

---

## 🤝 Connect

<div align="center">

Open to conversations about **backend, distributed systems and data infrastructure** roles.<br>
The fastest way to reach me is [LinkedIn](https://www.linkedin.com/in/sri-hari-417b191a1) or [email](mailto:sh.chepuri21@gmail.com).

</div>
