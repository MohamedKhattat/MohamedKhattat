<!-- ===================== HERO ===================== -->
<div align="center">

<img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&weight=700&size=30&duration=3200&pause=900&color=818CF8&center=true&vCenter=true&width=900&height=80&lines=Mohamed+Habib+Khattat;Enterprise+AI+Architect;Applied+Data+Scientist;Agentic+Systems+%C2%B7+Semantic+AI+%C2%B7+KAG;I+architect+AI+that+cannot+fail." alt="Mohamed Habib Khattat" />

<p><b>I design governed, production-grade AI systems on mission-critical infrastructure.</b></p>

<p>
  <a href="https://www.linkedin.com/in/mohamed-habib-khattat-2b206a173"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:mohamedhabib.khattat@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <a href="https://github.com/MuhamedHabib"><img src="https://img.shields.io/badge/Data_Science_%2F_ML-181717?style=for-the-badge&logo=github&logoColor=white"/></a>
  <img src="https://komarev.com/ghpvc/?username=MohamedKhattat&style=for-the-badge&label=PROFILE+VIEWS&color=6366F1"/>
  <img src="https://img.shields.io/github/followers/MohamedKhattat?style=for-the-badge&logo=github&label=Followers&color=818CF8"/>
</p>

</div>

---

## 🧭 Where I Stand

I sit where **data science meets enterprise architecture**. I don't just train models — I architect the **governed systems** that put them into production *where failure is not an option*. A decade shipping **fiscal & banking infrastructure** — software audited by ministries and trusted by thousands of banks — taught me what "production-grade" actually costs. I bring that same discipline to AI: **observability, idempotency, durability, and governance**, applied to LLMs and semantic reasoning.

> **My edge:** most people can train a model *or* ship a system. I do both — and I make the model *behave* inside the system.

---

## 🏛️ Enterprise AI Architecture

I build **agentic, knowledge-grounded AI** that operates inside a governed semantic world — not a chatbot, an **architecture**:

```mermaid
flowchart LR
  D["Domain Data<br/>SQL · Documents · Streams"] --> S
  subgraph GOV["🔒 Governed Semantic Layer"]
    direction TB
    S["OWL Ontologies<br/>SWRL Rules · RDF4J"] --> K["KAG Retrieval<br/>SPARQL · Vector · BM25"]
  end
  K --> A
  subgraph AGENT["🤖 Agentic Orchestration"]
    direction TB
    A["LLM Reasoner<br/>think · act · observe"] <--> T["Tools · MCP<br/>code · search · gen"]
    A --> V["Verify · Guardrails<br/>adversarial checks"]
  end
  V --> O["⚙️ Governed Action<br/>sign · persist · serve"]
  O --> M["📈 Observability<br/>cost · durability · audit"]
  M -. feedback .-> A
```

| Capability | What I architect |
|---|---|
| **Agentic orchestration** | Multi-agent think/act/observe loops, tool-use, MCP servers, parallel dispatch, self-correction bounds |
| **KAG — Knowledge-Augmented Generation** | LLMs reasoning *inside* OWL/SWRL/RDF4J ontologies — contextual retrieval (SPARQL + vector + BM25), not naive RAG |
| **LLMOps** | Multi-provider routing, prefix/KV caching, cost metering, streaming, durable task recovery |
| **Model serving** | PMML / JPMML portability — train in Python, serve in Java at enterprise scale |
| **Governance & trust** | Adversarial verification, guardrails, tamper-proof audit trails, XAdES/PKCS#11 digital signatures |
| **Production discipline** | Idempotency anchors, single-source-of-truth state, observability, zero-failure SLAs |

---

## 🏆 Flagship — ODS · Temenos-Certified Distribution (3,000+ Banks)

> The system I'm proudest of is one most people will never see — because it simply **never fails**.

**Scale & status.** A **Temenos Exchange–certified** Operational Data Store, deployed across **3,000+ banks worldwide** and featured on temenos.com. Production-hardened; zero critical failures across its production life.

**The problem.** Every bank generates massive **Close-of-Business (COB)** volumes at midnight. They must fan out — reconciled and complete — to **Data-Warehouse, HR, and Audit** systems with **guaranteed delivery before 08:00**. The window is fixed; the tolerance is zero.

**Why it's hard** ⚙️ A fixed overnight window, massive volume, **zero tolerance** — in banking a missed or duplicated batch is a *compliance event*, not an inconvenience. The data has to arrive **reconciled, complete, and on time**, every single night.

**What it represents.** Zero-failure reliability engineering at financial-sector scale — the discipline I carry into every AI system I build.

`Java` · `Spring Boot` · `Redis` · `gRPC` · `Oracle` · `Grafana` · `Linux` &nbsp;|&nbsp; 🔒 *Proprietary production system — described faithfully, at a non-disclosing altitude (no internal design disclosed).*

---

## 🔬 Applied Data Science & ML

Hands-on, end-to-end — from raw signal to served decision:

- **Computer Vision / OCR** — Arabic document OCR pipelines (deskew sweeps, glare/label removal, multi-engine fallback) on real Tunisian ID & fiscal documents.
- **NLP / NLU** — NER + fuzzy entity resolution, semantic invoice checkers, intent classification across **EN / FR / Tunisian**.
- **Classical ML** — risk scoring (credit default, tax-risk), feature selection (RFE/RFECV), dimensionality reduction, cross-validated model selection.
- **Semantic AI** — ontology-driven **fraud detection** with SPARQL + SHACL over knowledge graphs.

<sub>📊 Deep-dive ML / DS portfolio → <a href="https://github.com/MuhamedHabib">@MuhamedHabib</a></sub>

---

## 📌 What I Have Delivered

> No placeholder projects — everything below runs in **production**.

| Project | What it is | Stack |
|---|---|---|
| **ODS** — *Temenos Exchange Certified* | Distributes massive midnight COB volumes across DW / HR / Audit systems for **3,000+ banks** — guaranteed delivery before 08:00, zero failures. Featured on temenos.com. | `Java` · `Spring Boot` · `Redis` · `gRPC` · `Oracle` |
| **PMIS Madagascar** — *World Bank* | Full-stack government platform, Ministry of Energy & Hydrocarbons — conception → production. | `Java 21` · `Spring Boot 3` · `Angular 17` · `Spring Batch` · `Docker` |
| **Fiscal POS** — *Ministry-Homologated* | Cash-register system certified by the Ministry of Finance, **5,000+ stations**, tamper-proof audit trail, zero critical failure. | `XAdES` · `PKCS#11` · `Remote Agent/Client` |
| **Fatoora Hub** *(active)* | End-to-end El&nbsp;Fatoura e-invoicing: draft → sign → submit → accept. | `XAdES` · `TunTrust` · `Spring Boot 3` |
| **✦ MCP Orchestration Research** *(active)* | Multi-agent pipelines where LLMs operate inside **governed semantic worlds** (OWL + SWRL + RDF4J). | `Claude AI` · `MCP` · `KAG` · `SPARQL` |

---

## 🛠️ Arsenal

**AI · ML · Data**
<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white"/>
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white"/>
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white"/>
  <img src="https://img.shields.io/badge/spaCy-09A3D5?style=for-the-badge&logo=spacy&logoColor=white"/>
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"/>
</p>

**Agentic & Semantic AI**
<p>
  <img src="https://img.shields.io/badge/Claude_AI-D97706?style=for-the-badge&logo=anthropic&logoColor=white"/>
  <img src="https://img.shields.io/badge/MCP-000000?style=for-the-badge&logo=modelcontextprotocol&logoColor=white"/>
  <img src="https://img.shields.io/badge/LLMOps-6B21A8?style=for-the-badge&logoColor=white"/>
  <img src="https://img.shields.io/badge/KAG-6366F1?style=for-the-badge&logoColor=white"/>
  <img src="https://img.shields.io/badge/OWL_/_SWRL-0D9488?style=for-the-badge&logoColor=white"/>
  <img src="https://img.shields.io/badge/SPARQL-1D4ED8?style=for-the-badge&logoColor=white"/>
  <img src="https://img.shields.io/badge/RDF4J-990000?style=for-the-badge&logoColor=white"/>
</p>

**Enterprise Backend & Platform**
<p>
  <img src="https://img.shields.io/badge/Java_21-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white"/>
  <img src="https://img.shields.io/badge/Spring_Boot_3-6DB33F?style=for-the-badge&logo=springboot&logoColor=white"/>
  <img src="https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white"/>
  <img src="https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white"/>
  <img src="https://img.shields.io/badge/Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white"/>
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white"/>
  <img src="https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white"/>
  <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white"/>
</p>

**Cloud & DevOps**
<p>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white"/>
  <img src="https://img.shields.io/badge/GitLab_CI/CD-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white"/>
  <img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white"/>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black"/>
</p>

---

## 📊 GitHub Analytics

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=MohamedKhattat&show_icons=true&include_all_commits=true&count_private=true&theme=tokyonight&hide_border=true&title_color=818CF8&icon_color=6366F1" alt="stats"/>
<img height="165" src="https://streak-stats.demolab.com/?user=MohamedKhattat&theme=tokyonight&hide_border=true&ring=818CF8&fire=6366F1&currStreakLabel=818CF8" alt="streak"/>

<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=MohamedKhattat&layout=compact&theme=tokyonight&hide_border=true&langs_count=10&title_color=818CF8" alt="top langs"/>

<img src="https://github-profile-trophy.vercel.app/?username=MohamedKhattat&theme=tokyonight&no-frame=true&no-bg=true&row=1&column=7&margin-w=8" alt="trophies"/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=MohamedKhattat&theme=react-dark&bg_color=1a1b27&hide_border=true&color=818CF8&line=6366F1&point=ffffff&area=true" alt="activity graph"/>

</div>

> 🏆 Pair Extraordinaire ×3 · Pull Shark ×3 · YOLO · Quickdraw &nbsp;|&nbsp; 🌍 **GSoC 2026** — Accord Project (Linux Foundation): agentic workflow + LLM template-logic executor.

---

<div align="center">

## 💡 The Case, Plainly

**I worked before AI — and with AI.** That dual lens is my speed *and* my depth.
I don't arrive alone at a mission; I arrive with an **amplification capability** —
orchestrated agentic systems that deliver in **one day** what a team handles in a week,
**without trading away** the governance, audit, and zero-failure discipline an enterprise demands.

<br/>

### 📬 Let's architect something that ships — and holds.

<a href="https://www.linkedin.com/in/mohamed-habib-khattat-2b206a173"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="mailto:mohamedhabib.khattat@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="https://github.com/MohamedKhattat"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/></a>

**Available — Remote · On-site · Relocation (France)**

</div>
