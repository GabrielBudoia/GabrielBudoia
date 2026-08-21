<h1 align="center">Gabriel Budoia</h1>

<p align="center">
  <b>Backend Developer</b> · Go · Kubernetes · Distributed Systems<br>
  <sub>Barcelona, Spain 🇪🇸 · 🇧🇷 🇮🇹</sub>
</p>

<p align="center">
  <a href="https://linkedin.com/in/gabrielbud"><img src="https://img.shields.io/badge/-LinkedIn-0077B5?style=flat&logo=Linkedin&logoColor=white"/></a>&nbsp;
  <a href="mailto:gabbudoia@gmail.com"><img src="https://img.shields.io/badge/-Email-D14836?style=flat&logo=Gmail&logoColor=white"/></a>&nbsp;
  <a href="https://github.com/GabrielBudoia"><img src="https://img.shields.io/badge/-GitHub-05122A?style=flat&logo=github&logoColor=white"/></a>
</p>

---

### About

Backend developer focused on **Go** and cloud-native infrastructure.

For the last two years I worked inside production environments — a global fintech in Brazil and an IT services provider in Madrid — doing the same thing in different forms: finding manual operational processes and replacing them with code. Python data pipelines, C#/WPF desktop applications, Azure-based notification services.

Now I'm going deep on **distributed backend systems**: gRPC services, NATS messaging, OpenTelemetry instrumentation and Kubernetes orchestration — while reading for a BSc in Computer Engineering at **UOC**.

Most of what I build these days orbits one question: *what does it actually take to run a database as a managed service?* The repos below are my answer, in progress.

---

### 🚧 Currently building

A miniature managed-database platform, split into three services:

| Project | What it does | Stack |
|---|---|---|
| **pgfleet** | Control plane for managed PostgreSQL — a gRPC API that provisions, inspects and decommissions database instances by driving Kubernetes StatefulSets through `client-go` | `Go` `gRPC` `Kubernetes` `PostgreSQL` |
| **dbwatch** | Distributed health and telemetry pipeline — collectors publish database health events to NATS JetStream, consumers evaluate thresholds and raise alerts, traced end-to-end with OpenTelemetry | `Go` `NATS` `OpenTelemetry` `Prometheus` |
| **backup-orchestrator** | Fault-tolerant backup scheduler for database fleets — leader election for job coordination, MongoDB-backed job store, S3-compatible storage, deployed via Helm | `Go` `MongoDB` `Kubernetes` `Helm` |

---

### 🛠 Tech Stack

**Backend & infrastructure**

![Go](https://img.shields.io/badge/-Go-05122A?style=flat&logo=go&logoColor=00ADD8)&nbsp;
![gRPC](https://img.shields.io/badge/-gRPC-05122A?style=flat&logo=trpc&logoColor=2596BE)&nbsp;
![NATS](https://img.shields.io/badge/-NATS-05122A?style=flat&logo=natsdotio&logoColor=27AAE1)&nbsp;
![Kubernetes](https://img.shields.io/badge/-Kubernetes-05122A?style=flat&logo=kubernetes&logoColor=326CE5)&nbsp;
![Docker](https://img.shields.io/badge/-Docker-05122A?style=flat&logo=docker&logoColor=2496ED)&nbsp;
![Helm](https://img.shields.io/badge/-Helm-05122A?style=flat&logo=helm&logoColor=0F1689)&nbsp;
![OpenTelemetry](https://img.shields.io/badge/-OpenTelemetry-05122A?style=flat&logo=opentelemetry&logoColor=F5A800)&nbsp;
![Linux](https://img.shields.io/badge/-Linux-05122A?style=flat&logo=linux&logoColor=FCC624)

**Data**

![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-05122A?style=flat&logo=postgresql&logoColor=4169E1)&nbsp;
![MongoDB](https://img.shields.io/badge/-MongoDB-05122A?style=flat&logo=mongodb&logoColor=47A248)&nbsp;
![SQL Server](https://img.shields.io/badge/-SQL%20Server-05122A?style=flat&logo=microsoftsqlserver&logoColor=CC2927)

**Also work with**

![Python](https://img.shields.io/badge/-Python-05122A?style=flat&logo=python&logoColor=3776AB)&nbsp;
![C#](https://img.shields.io/badge/-C%23-05122A?style=flat&logo=csharp&logoColor=239120)&nbsp;
![.NET](https://img.shields.io/badge/-.NET-05122A?style=flat&logo=dotnet&logoColor=512BD4)&nbsp;
![Azure](https://img.shields.io/badge/-Azure-05122A?style=flat&logo=microsoftazure&logoColor=0078D4)&nbsp;
![JavaScript](https://img.shields.io/badge/-JavaScript-05122A?style=flat&logo=javascript&logoColor=F7DF1E)&nbsp;
![Node.js](https://img.shields.io/badge/-Node.js-05122A?style=flat&logo=nodedotjs&logoColor=339933)&nbsp;
![Git](https://img.shields.io/badge/-Git-05122A?style=flat&logo=git&logoColor=F05032)

---

### 🎓 Background

- **BSc Computer Engineering** — Universitat Oberta de Catalunya (UOC) · *in progress*
- **Higher Diploma, Multiplatform App Development (DAM)** — UpgradeHub
- **Backend Master Class: Go, PostgreSQL, Kubernetes & gRPC** — Udemy
- **Docker and Kubernetes: The Complete Course** — Udemy

🗣 Portuguese (native) · Spanish (fluent) · English (fluent)

---

### 📊 GitHub Analytics

<p align="center">
  <img height="165em" src="https://github-readme-stats.vercel.app/api?username=GabrielBudoia&show_icons=true&theme=algolia&include_all_commits=true&count_private=true"/>
  <img height="165em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=GabrielBudoia&layout=compact&langs_count=8&theme=algolia"/>
</p>
