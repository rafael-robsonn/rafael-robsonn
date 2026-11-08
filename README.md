<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,100:1a237e&height=140&section=header" width="100%" />

<br/>

<h1>
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=32&duration=1&pause=999999&color=FFFFFF&center=true&vCenter=true&width=700&lines=Rafael+Robson+Nunes+de+Ara%C3%BAjo" alt="Rafael Robson Nunes de Araújo" />
</h1>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=400&size=14&duration=3200&pause=900&color=64B5F6&center=true&vCenter=true&multiline=true&width=700&height=50&lines=CEO+%40+Chesin+%E2%80%94+AI+%26+Data+Engineer+%7C+Brasília%2C+BR;building+pipelines+that+ship+themselves)](https://github.com/rafael-robsonn)
![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=00FF00&center=true&vCenter=true&width=600&lines=Founder+%40+Chesin;Building+AI%2FML+products;Data+Science+%40+UniCEUB)

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0a66c2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/rafael-robson)&nbsp;
[![Email](https://img.shields.io/badge/Email-1a1a2e?style=for-the-badge&logo=gmail&logoColor=ea4335)](mailto:rafaelrobsonnunesdearaujo@gmail.com)&nbsp;
[![GitHub](https://img.shields.io/badge/@rafael--robsonn-1a1a2e?style=for-the-badge&logo=github&logoColor=white)](https://github.com/rafael-robsonn)

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=rafael-robsonn&style=flat-square&color=1a237e&label=profile+views)

</div>

<br/>

---

<table>
<tr>
<td width="52%" valign="top">

### `> whoami`

```
role   : CEO, Chesin
focus  : AI-native data engineering
base   : Brasília, DF — Brazil
study  : Data Science & ML @CEUB
status : building
```

I founded **Chesin** with two bets one automates data pipelines with AI, the other reinvents urban mobility with intelligent electric fleets.

No demos. Real systems.

</td>
<td width="48%" valign="top">

### `> ls ./now`

```python
currently = {
  "shipping" : "DataSM v1 — Decision Layer",
  "training" : "ART v-carbon",
  "target"   : "≥ 85% code acceptance rate",
  "reading"  : "Designing ML Systems",
  "open_to"  : [
    "data engineering roles",
    "AI/ML engineering",
    "founding team"
  ],
}
```

</td>
</tr>
</table>

<br/>

---

## ◈ Featured Work

<br/>

<table>
<tr>
<td width="60%" valign="top">

### ⬡ DataSM &nbsp; `[flagship]`

> **AI agent that writes, reviews and deploys production data pipelines without a human in the loop.**

Built on a **dual-brain architecture**: LangGraph orchestrates the full pipeline while Claude acts as an adversarial Reviewer, catching hallucinations and enforcing schema correctness before anything touches production. A Decision Layer (replacing the broken weighted-blend merge) arbitrates between agent outputs. dbt + BigQuery as the initial wedge.

**North star metric: ≥ 85% code acceptance rate.**

```
User intent
    │
    ▼
[LangGraph Orchestrator]
    ├── Codestral (Generator)
    ├── Claude (Reviewer / Critic)
    └── Decision Layer
            │
            ▼
    [dbt → BigQuery] ── Production
```

![Python](https://img.shields.io/badge/Python-0d1117?style=flat-square&logo=python&logoColor=3776AB)
![LangGraph](https://img.shields.io/badge/LangGraph-0d1117?style=flat-square&logo=chainlink&logoColor=64b5f6)
![Claude](https://img.shields.io/badge/Claude_API-0d1117?style=flat-square&logo=anthropic&logoColor=white)
![React](https://img.shields.io/badge/React-0d1117?style=flat-square&logo=react&logoColor=61DAFB)
![dbt](https://img.shields.io/badge/dbt-0d1117?style=flat-square&logo=dbt&logoColor=FF694B)
![BigQuery](https://img.shields.io/badge/BigQuery-0d1117?style=flat-square&logo=googlecloud&logoColor=4285F4)

</td>
<td width="40%" valign="top">

### ⬡ ChesinBus

> **Intelligent fleet management for hybrid and electric buses.**

Real-time telemetry ingestion, route optimization, and predictive maintenance at scale. Built for the operational complexity of emerging markets where data is sparse and downtime is expensive.

<br/>

![Python](https://img.shields.io/badge/Python-0d1117?style=flat-square&logo=python&logoColor=3776AB)
![Spark](https://img.shields.io/badge/Spark-0d1117?style=flat-square&logo=apachespark&logoColor=E25A1C)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-0d1117?style=flat-square&logo=postgresql&logoColor=4169E1)
![IoT](https://img.shields.io/badge/IoT-0d1117?style=flat-square&logo=mqtt&logoColor=64b5f6)

<br/><br/>

### ⬡ gemma-cli

> Rust CLI with full streaming, runtime flags and 4 subcommands (`ask` `chat` `models` `info`) integrating Gemma 4 E4B via Ollama locally.

![Rust](https://img.shields.io/badge/Rust-0d1117?style=flat-square&logo=rust&logoColor=CE422B)
![Ollama](https://img.shields.io/badge/Ollama-0d1117?style=flat-square&logo=ollama&logoColor=white)

</td>
</tr>
</table>

<br/>

<table>
<tr>
<td width="60%" valign="top">

### ⬡ ART &nbsp; `[new]`

> **Typed decision model: it picks an option, and also knows when not to.**

Started as a fine-tune of a multilingual base with longer context (2k), better zero-shot and calibrated option scoring, without giving up inference speed. **ART v-carbon** is the standalone rewrite: built on mmBERT-base, distilled from the v3 teacher, with kernels ported to TileLang. On top of plain classification it adds abstention, explanations, counterfactuals, batching with cache, multi-criteria scoring and uncertainty reporting.

Released as freeware under the **LART** license: no commercial use, no modification, no reverse engineering.

![Python](https://img.shields.io/badge/Python-0d1117?style=flat-square&logo=python&logoColor=3776AB)
![PyTorch](https://img.shields.io/badge/PyTorch-0d1117?style=flat-square&logo=pytorch&logoColor=EE4C2C)
![HuggingFace](https://img.shields.io/badge/mmBERT-0d1117?style=flat-square&logo=huggingface&logoColor=FFD21E)
![TileLang](https://img.shields.io/badge/TileLang-0d1117?style=flat-square&logo=nvidia&logoColor=76B900)

[`ART-v1`](https://github.com/rafael-robsonn/ART-v1)

</td>
<td width="40%" valign="top">

### ⬡ Esmalteria Bot

> **Conversational scheduling assistant for a nail salon, wired to Trinks.**

Reads real availability, matches service to professional, books and confirms. Built around the messy parts of salon scheduling: services split between professionals, duration blocks and manual reshuffles when someone is out.

<br/>

![Trinks](https://img.shields.io/badge/Trinks_integration-0d1117?style=flat-square&logo=googlecalendar&logoColor=64b5f6)
![LLM](https://img.shields.io/badge/LLM_agent-0d1117?style=flat-square&logo=anthropic&logoColor=white)

</td>
</tr>
</table>

<br/>

<table>
<tr>
<td width="50%" valign="top">

### ⬡ kestrel-mm &nbsp; `[rust]`

> **Statistical market maker, ITCH 5.0 bytes to quote in ~163 ns.**

ITCH 5.0 feed into an L3 order book, SIMD microstructure features (OFI, VPIN, micro-price), an extended Kalman filter for fair value and a GBDT toxicity model, quoting through Avellaneda-Stoikov. Zero heap allocation on the hot path, enforced by a counting-allocator test. `unsafe` limited to the SPSC ring and the TSC clock. Property tests check the book against a reference implementation.

**5.96 M msg/s** on the 3-thread pipeline, pinned cores.

![Rust](https://img.shields.io/badge/Rust-0d1117?style=flat-square&logo=rust&logoColor=CE422B)
![SIMD](https://img.shields.io/badge/AVX--512-0d1117?style=flat-square&logo=amd&logoColor=ED1C24)
![ITCH](https://img.shields.io/badge/ITCH_5.0-0d1117?style=flat-square&logo=shieldsdotio&logoColor=64b5f6)

[`kestrel-mm`](https://github.com/rafael-robsonn/kestrel-mm)

</td>
<td width="50%" valign="top">

### ⬡ almgren-abm-rl &nbsp; `[rust]`

> **Optimal execution with recurrent PPO on an agent-based limit order book.**

Deterministic discrete-event exchange with five agent types, validated against stylized facts, plus an Almgren-Chriss baseline calibrated on the simulator itself. A GRU actor-critic trained with PPO in `burn`, all in one Rust process with no Python boundary. On 2,048 held-out episodes the policy beats the calibrated baseline by 0.49 bps of implementation shortfall (paired, 9.9 standard errors). Limitations and training-seed spread are reported in the repo.

![Rust](https://img.shields.io/badge/Rust-0d1117?style=flat-square&logo=rust&logoColor=CE422B)
![burn](https://img.shields.io/badge/burn-0d1117?style=flat-square&logo=rust&logoColor=E25A1C)
![RL](https://img.shields.io/badge/PPO--GRU-0d1117?style=flat-square&logo=pytorch&logoColor=EE4C2C)

[`almgren-abm-rl`](https://github.com/rafael-robsonn/almgren-abm-rl)

</td>
</tr>
</table>

<details>
<summary><b>↳ more projects</b></summary>

<br/>

| Project | Description | Stack |
|---|---|---|
| **Language Quest** | Gamified language learning — progression system, adaptive quizzes, real-time feedback | React, TypeScript |
| **Java Forum App** | Full MVC application — auth, threads, points system, end-to-end tests | Java, Spring, PostgreSQL, DBUnit, Selenium |
| **DataSM Code Review** | Automated code review dashboard — dual-agent pipeline (Reviewer + Critic), 5-stage WebSocket flow | React, Python, WebSocket |
| **nlp-regras-basico** | Study notes: BoW, TF-IDF, Word2Vec, GloVe, RNN, LSTM, GRU + NLPortugues/USP labs | Python, PyTorch |
| **DER-DF Traffic EDA** | Exploratory analysis of ~6.5M traffic infractions across 83 CSVs, incremental aggregation so it runs on a laptop | Python, pandas, Jupyter |
| **Quantum ML Lab** | Hybrid QCNN on FashionMNIST plus VQC, QAOA and quantum-kernel SVM. Controlled protocols, ablations and null results reported as they came out | PennyLane, PyTorch |
| **TaskTracker** | Task manager in 3 phases: logic design, Git workflow, Docker | Python, Docker |
| **Tessera Rivs AI** | Hackathon build grown into a full app: React front wired to 44 FastAPI routes, i18n, settings drawer, audit chain | React, FastAPI |
| **War Modpack** | Minecraft LAN modpack where each friend runs a nation: trade, raids, alliances, final war. Tuned to run on 8 GB RAM | Minecraft |

</details>

<br/>

---

## ◈ Hackathons

<br/>

<table>
<tr>
<td width="50%" valign="top">

<div align="center">

### Transforming Enterprise Through AI

**`Tessera`**

</div>

> *"The trust layer for enterprise AI agents."*

Real-time multi-agent threat chain detection with LGPD compliance enforcement and cryptographically-signed audit trails. Policy engine with regulatory basis, DPO settings, RoPA (Art. 37), health checks, and a SOC-grade dark UI built for long analyst sessions. Threat severity classification with audit blockchain verification.

<br/>

![React](https://img.shields.io/badge/React-0d1117?style=flat-square&logo=react&logoColor=61DAFB)
![Python](https://img.shields.io/badge/Python-0d1117?style=flat-square&logo=python&logoColor=3776AB)
![LGPD](https://img.shields.io/badge/LGPD_Compliance-0d1117?style=flat-square&logo=shieldsdotio&logoColor=64b5f6)
![Crypto](https://img.shields.io/badge/Audit_Chain-0d1117?style=flat-square&logo=keycdn&logoColor=64b5f6)

</td>
<td width="50%" valign="top">

<div align="center">

###  AMD Developer Hackathon

**`TokenBurners`**

</div>

> *"We burn tokens so you don't have to."*

Automated code review system powered by adversarial AI. Dual-agent pipeline (Reviewer + Critic) in 5 stages with real-time feedback via WebSocket. Issues classified by severity critical, major, minor, suggestion — with per-file stats and tree visualization. AMD ROCm dark mode UI.

<br/>

![React](https://img.shields.io/badge/React-0d1117?style=flat-square&logo=react&logoColor=61DAFB)
![Python](https://img.shields.io/badge/Python-0d1117?style=flat-square&logo=python&logoColor=3776AB)
![WebSocket](https://img.shields.io/badge/WebSocket-0d1117?style=flat-square&logo=socketdotio&logoColor=white)
![AMD](https://img.shields.io/badge/AMD_ROCm-0d1117?style=flat-square&logo=amd&logoColor=ED1C24)

</td>
</tr>
</table>

<br/>

---

## ◈ Stack

<div align="center">

<br/>

[![Skills](https://skillicons.dev/icons?i=python,scala,java,rust,typescript,js&theme=dark&perline=6)](https://github.com/rafael-robsonn)

[![Skills](https://skillicons.dev/icons?i=pytorch,tensorflow,react,fastapi,spring,nodejs&theme=dark&perline=6)](https://github.com/rafael-robsonn)

[![Skills](https://skillicons.dev/icons?i=postgres,docker,git,linux,maven,html&theme=dark&perline=6)](https://github.com/rafael-robsonn)

<br/>

</div>

<details>
<summary><b>↳ full breakdown</b></summary>

<br/>

| Layer | Technologies |
|---|---|
| **AI / LLM** | LangChain, LangGraph, RAG, LSTM/GRU, LLM Fine-tuning, Codestral, Claude API |
| **Data Engineering** | Apache Spark, dbt, BigQuery, PostgreSQL, SQL, ETL/ELT |
| **Languages** | Python, Scala, Java, Rust, TypeScript, COBOL |
| **Backend** | FastAPI, Spring Boot, Node.js, REST, MVC |
| **Frontend** | Javascript, React, TypeScript, HTML/CSS |
| **BI** | Power BI |
| **CLOUD** | AWS, GCP, AZURE |
| **Infra** | Docker, Git, Maven, Tomcat, DBUnit, Selenium, Terraform |

</details>

<br/>

---
## ◈ Stats

<div align="center">
 <br/>
  
<img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=rafael-robsonn&theme=transparent" alt="Profile Summary Card"/>

<div align="center">

<br/>

![My GitHub Game](game.gif)

---

<div align="center">

<sub>systems that work when no one's watching</sub>

<br/><br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a237e,100:0d1117&height=100&section=footer" width="100%" />

</div>
