<!-- ============================================================
     Profile README · Geetha Venkata Sai Pardheev Chunduru
     Place this file in a public repo named exactly: GeethaPardheev
     ============================================================ -->

<div align="center">

<img src="assets/header.svg" width="100%" alt="Geetha Pardheev · Backend & AI Infrastructure Engineer"/>

<p>
<a href="https://linkedin.com/in/geetha-pardheev"><img src="https://img.shields.io/badge/LinkedIn-geetha--pardheev-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="mailto:geethapardheev2@gmail.com"><img src="https://img.shields.io/badge/Email-geethapardheev2%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<img src="https://img.shields.io/badge/Based_in-Bengaluru,_India-2c5364?style=for-the-badge&logo=googlemaps&logoColor=white"/>
<img src="https://img.shields.io/badge/Status-Open_to_opportunities-22c55e?style=for-the-badge"/>
</p>

</div>

---

```python
class Pardheev:
    role       = "Backend Software Engineer · Distributed Systems · Production AI/LLM"
    education  = "B.Tech, IIT Kharagpur (2018–2022) · GPA 8.43"
    experience = "4+ years  →  Amazon  ·  Toyota Connected  ·  Founding Engineer at a 0→1 startup"
    builds     = ["distributed backends", "LLM & agent systems", "AI evaluation", "real-time voice AI"]
    speaks     = ["Python", "Java", "Rust", "Go", "C++", "Kotlin"]
    research   = ["ACM WWW Companion '23", "Expert Systems with Applications '22"]

    def philosophy(self):
        return "Own it from the whiteboard to the pager: architecture → production → p95."
```

## ⚡ Impact at a glance

<div align="center">

| 📞 **36M+** | 🔁 **500K+ / day** | ⏱️ **< 2s p95** | 💸 **~42%** | 🚗 **4M+ DAU** | 📊 **10M+ / day** |
|:---:|:---:|:---:|:---:|:---:|:---:|
| production voice calls served | AI calls on multi-region AWS | conversational voice latency | LLM inference cost cut | Lexus voice assistant users | audit events tracked at Amazon |

</div>

## 🧭 The journey

```mermaid
timeline
    title Career path
    2018 - 2022 : IIT Kharagpur, B.Tech
                : NLP & ML research, two publications
    2022 : Amazon, SDE-1
         : Java microservices, event-driven auditing, AWS CDK
    2023 - 2026 : Toyota Connected, SDE
                : Lexus Virtual Assistant (gRPC, Cap'n Proto)
                : Large Action Models for LLM-driven UI automation
    2026 : HiRobin, Founding Engineer
         : Real-time speech-to-speech AI platform, 0→1
```

## 🏗️ What I've built in production

<details open>
<summary><b>🎙️ HiRobin · Founding Software Engineer</b> &nbsp;·&nbsp; <i>Mar 2026 – Sep 2026</i></summary>
<br>

Joined as a founding engineer and built the core of a real-time AI voice platform from zero to production scale.

| 🎙️ Real-time voice | 🤖 Agent orchestration | 🧪 LLM evaluation | 📐 Platform & cost |
|:---|:---|:---|:---|
| Speech-to-speech streaming, session migration, WebSocket recovery | Tool-calling, scheduling, retries, callback recovery | Synthetic callers, regression suites, quality scoring | A/B experimentation, tracing, ~42% inference cost cut |

- **Voice platform** serving **500K+ calls/day** to **100K+ DAU** at **< 2s p95**, **36M+** calls on multi-region AWS
- **Voice infra** across Gemini Live and ASR + LLM + TTS pipelines: prewarming, session migration, resilient WebSocket recovery
- **Agent orchestration engine** with tool-calling, scheduling, batching and callback recovery: **700K+** outbound calls, **300K+** autonomous workflows
- **LLM evaluation stack** from scratch: grounded regression suites, synthetic AI callers, quality scoring across **32M+** conversations
- **~42% inference cost reduction** via prompt redesign, input-audio gating and canned responses, holding **0.87/1.0** quality
- **In-house A/B experimentation** with deterministic sticky assignment and zero-storage variant allocation
- **Observability** with distributed tracing, call-level correlation and PII-masked logs

</details>

<details>
<summary><b>🚗 Toyota Connected · Software Development Engineer</b> &nbsp;·&nbsp; <i>Mar 2023 – Mar 2026</i></summary>
<br>

- **Lexus Next-Gen Virtual Assistant:** high-throughput backend components in **gRPC + Cap'n Proto** for **4M+ DAU / 15M+ requests per day**, with **< 2s** responses and **sub-100ms** internal latencies
- **Large Action Models:** owned HLD & LLD for a device-agnostic backend for GenAI-driven UI automation, delivering a 0→1 Android system at **< 6s per action** using **Amazon Bedrock** and on-device LLM reasoning
- **Automation architecture:** containerized execution framework, extended to Toyota One App (Android & iOS) and the Lexus Virtual Assistant
- **Severe Weather Alerts:** geo-targeted real-time alerting on **SQS + Redis**, cutting delivery latency **3s → < 1s**
- **Smart Climate:** adaptive HVAC logic and zone-based microphone processing for context-aware in-vehicle voice

</details>

<details>
<summary><b>📦 Amazon · Software Development Engineer I</b> &nbsp;·&nbsp; <i>Jun 2022 – Mar 2023</i></summary>
<br>

- **Java microservices (Google Guice)** powering regional product-control workflows
- **Auditing subsystem** on Lambda + DynamoDB Streams + SQS, tracking **10M+ events/day** in near real time
- **Fault-tolerant retry mechanism** extending failed-event retention from **24 hours to 14 days**
- **Infrastructure as Code** with AWS CDK, plus CloudWatch monitoring, alerting and anomaly detection

</details>

## 🔬 Research & publications

<table>
<tr>
<td width="50%" valign="top">

### 📄 Syntax-Aware Style Detection
**ACM WWW Companion '23**

Hybrid **BERT + Graph Convolutional Network** that reads syntax graphs to detect *formality* and *politeness*.

🎯 F1 **0.85** (formality) · **0.83** (politeness), beating all baselines

[![Paper](https://img.shields.io/badge/Read-ACM_Digital_Library-1f6feb?style=flat-square&logo=acm)](https://dl.acm.org/doi/abs/10.1145/3543873.3587352)
[![Code](https://img.shields.io/badge/Code-formality-24292f?style=flat-square&logo=github)](https://github.com/GeethaPardheev/formality)

</td>
<td width="50%" valign="top">

### 📄 CCNet: Classifying Accident Reports
**Expert Systems with Applications, 2022**

End-to-end NLP pipeline over **16,323** unstructured construction accident reports with a novel hybrid network, **CCNet**.

🎯 Weighted F1 **0.723 → 0.780** over baseline

[![Paper](https://img.shields.io/badge/Read-Elsevier_ESWA-ff6c00?style=flat-square&logo=elsevier)](PASTE_YOUR_PAPER_LINK_HERE)

</td>
</tr>
</table>

## 🛠️ Projects on this profile

| Project | What it is | Stack |
|---|---|---|
| 🩺 **[MedicalVoiceAI](https://github.com/GeethaPardheev/MedicalVoiceAI)** | Real-time medical scheduling voice agent: a LiveKit agent worker bridging Deepgram STT, Cartesia TTS and OpenAI/Anthropic LLMs with tool execution, plus a React dashboard streaming live transcripts, tool calls and summaries | ![](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white) ![](https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![](https://img.shields.io/badge/-LiveKit-000?style=flat-square) ![](https://img.shields.io/badge/-React-20232A?style=flat-square&logo=react) |
| 🧠 **[formality](https://github.com/GeethaPardheev/formality)** | Ensemble transformer classifiers (BERT, RoBERTa, ELECTRA, XLNet, DeBERTa) for formality detection; best ensemble hits **94.91%** on GYAFC. Groundwork for the ACM WWW '23 paper | ![](https://img.shields.io/badge/-PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![](https://img.shields.io/badge/-HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black) |
| 🦀 **[place_capitals](https://github.com/GeethaPardheev/place_capitals)** | Rust crate for place-type detection and capital lookup across countries and US states | ![](https://img.shields.io/badge/-Rust-000000?style=flat-square&logo=rust) |
| ⚡ **[pocket-pikachu](https://github.com/GeethaPardheev/pocket-pikachu)** | A native macOS desk companion with focus/Pomodoro modes, break reminders and physics-driven animations. My for-fun build | ![](https://img.shields.io/badge/-Swift-F05138?style=flat-square&logo=swift&logoColor=white) ![](https://img.shields.io/badge/-macOS-000?style=flat-square&logo=apple) |

## 🧰 Toolbox

**Languages**
<br>
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)

**Backend & APIs**
<br>
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![gRPC](https://img.shields.io/badge/gRPC-244c5a?style=for-the-badge&logo=google&logoColor=white)
![Protobuf](https://img.shields.io/badge/Protobuf-4285F4?style=for-the-badge&logo=google&logoColor=white)
![Cap'n Proto](https://img.shields.io/badge/Cap'n_Proto-555555?style=for-the-badge)
![WebSockets](https://img.shields.io/badge/WebSockets-010101?style=for-the-badge&logo=socketdotio&logoColor=white)
![REST](https://img.shields.io/badge/REST-02569B?style=for-the-badge)

**Data**
<br>
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![DynamoDB](https://img.shields.io/badge/DynamoDB-4053D6?style=for-the-badge&logo=amazondynamodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![OpenSearch](https://img.shields.io/badge/OpenSearch-005EB8?style=for-the-badge&logo=opensearch&logoColor=white)

**Cloud & DevOps**
<br>
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![Lambda](https://img.shields.io/badge/Lambda-FF9900?style=for-the-badge&logo=awslambda&logoColor=white)
![ECS](https://img.shields.io/badge/ECS-FF9900?style=for-the-badge&logo=amazonecs&logoColor=white)
![SQS](https://img.shields.io/badge/SQS-FF4F8B?style=for-the-badge&logo=amazonsqs&logoColor=white)
![CDK](https://img.shields.io/badge/AWS_CDK-FF9900?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)

**AI Infrastructure**
<br>
![LLMs](https://img.shields.io/badge/LLMs-6E40C9?style=for-the-badge)
![AI Agents](https://img.shields.io/badge/AI_Agents-8B5CF6?style=for-the-badge)
![RAG](https://img.shields.io/badge/RAG-A855F7?style=for-the-badge)
![MCP](https://img.shields.io/badge/MCP-111827?style=for-the-badge)
![Bedrock](https://img.shields.io/badge/Amazon_Bedrock-FF9900?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini_Live-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white)

**Architecture:** distributed systems · microservices · event-driven design · async messaging · concurrency control · fault tolerance · high-throughput processing

## 🎓 Education & achievements

<table>
<tr>
<td valign="top" width="55%">

**Indian Institute of Technology Kharagpur**
<br>B.Tech · 2018 – 2022 · GPA **8.43 / 10**
<br><sub>NLP & ML researcher, Aug 2021 – Apr 2022</sub>

</td>
<td valign="top">

🏅 **JEE Advanced 2018:** AIR **1618** (top 1%)
<br>🏅 **JEE Main 2018:** AIR **958** (top 0.1% of 1.5M+)

</td>
</tr>
</table>

---

<div align="center">

### 🤝 Let's build something that scales

Hiring for **backend, distributed systems or AI infrastructure** roles? I'd love to talk.

<a href="mailto:geethapardheev2@gmail.com"><img src="https://img.shields.io/badge/Say_hello-geethapardheev2%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="https://linkedin.com/in/geetha-pardheev"><img src="https://img.shields.io/badge/Connect-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>

</div>
