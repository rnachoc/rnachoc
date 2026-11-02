<div align="center">

![Header](https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=200&section=header&text=Ignacio%20Rodr%C3%ADguez%20Caro&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=AI%20agents%20%C2%B7%20Automations%20%C2%B7%20LLMs&descSize=18&descAlignY=58)

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&pause=1200&color=58A6FF&center=true&vCenter=true&width=640&lines=I+build+AI+agents+and+automations+with+LLMs;The+model+proposes%2C+the+code+decides;Guardrails%2C+evals+and+observability)](https://github.com/rnachoc)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ignaciorodriguezcaro)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:rnachoccontact@gmail.com)

</div>

---

### Hi, I'm Ignacio (Nacho) 👋

I build AI agents and automations with LLMs: agents that use tools, work with business data and take actions, with the guardrails, evals and observability they need to run in production.

Before that, I spent 5+ years as a backend engineer in Java and Spring Boot, three of them on a core banking platform. That's where my habits come from: validate everything, trace everything, and never let a model change data without a rule in code.

---

#### 👨‍💻 About Me

```python
class Ignacio:
    builds = [
        "agents that use tools",
        "MCP servers",
        "evals and guardrails",
    ]

    background = "5+ years as a backend engineer in Java and Spring Boot, three of them on a core banking platform"
    habits = ["validate everything", "trace everything"]
    rule = "never let a model change data without a rule in code"
    idea = "the model proposes, the code decides"
```

---

#### 🚀 What I build

- 🤖 **Tool-using agents** on the Claude API: well-described tools, multi-step loops and explicit confirmation before any action that changes data
- 🔌 **MCP servers** that expose business systems to any AI client
- 📏 **Evals** that measure accuracy, cost and latency, so every change to a prompt, tool or model is compared with numbers
- 🛡️ **Guardrails** against prompt injection, data leaks and made-up answers
- 🔗 **Integrations** with real backends: REST APIs, Postgres, Kafka, Docker

---

#### 📦 Featured projects

**[Turno](https://github.com/rnachoc/turno)**: a team of AI agents that runs the front desk of a fictional clinic over web chat, voice, WhatsApp and email, with published measurements. Agents propose and a Java and Spring Boot core decides (availability, rules, consent, audit), and emergencies are answered by fixed rules before any model is involved. Measured with the real models on 50 simulated-patient scenarios, one run each: Haiku 49, Sonnet 48, Opus 46. 97 of 97 attacks stopped on each build, and about 1,100 automated tests. Synthetic data only. [Replay of the conversations](https://rnachoc.github.io/turno/replay/)

![Claude](https://img.shields.io/badge/Claude_tool_use-D97757?style=flat-square&logo=anthropic&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Temporal](https://img.shields.io/badge/Temporal-141414?style=flat-square&logo=temporal&logoColor=white)
![Postgres](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Angular](https://img.shields.io/badge/Angular_console-DD0031?style=flat-square&logo=angular&logoColor=white)
![MCP](https://img.shields.io/badge/MCP_server-111111?style=flat-square)
![Evals](https://img.shields.io/badge/evals-555555?style=flat-square)

**[GuardiAI](https://github.com/rnachoc/GuardiAI)**: an AI on-call engineer for a seven-service marketplace built to be broken on purpose. When an alert fires, agents investigate with read-only MCP tools over metrics, logs, traces and change history, and every claim must cite evidence that code re-checks. A policy engine written in code decides which approved action may run, keeps a hash-chained audit log and verifies the recovery. 20 incident scenarios recorded with a sealed ground truth. Work in progress: phases 0 to 6 of 10 are done, and no model has been measured yet, so no results are published.

![Claude](https://img.shields.io/badge/Claude_agents-D97757?style=flat-square&logo=anthropic&logoColor=white)
![MCP](https://img.shields.io/badge/MCP_servers-111111?style=flat-square)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-425CC7?style=flat-square&logo=opentelemetry&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)

**[Tramita](https://github.com/rnachoc/tramita)**: an AI agent system that processes claims for a fictional insurer. It reads the documents, checks coverage with exact clause citations, looks for fraud signals with evidence and proposes a resolution, while deterministic rules in code decide whether it runs or goes to a human review console. Work in progress: phase 2 of 12 is done (the core system and rules in Java and Spring Boot), with the agents, retrieval and console planned next.

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![Temporal](https://img.shields.io/badge/Temporal-141414?style=flat-square&logo=temporal&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-111111?style=flat-square)

**[Hilo](https://github.com/rnachoc/quilora-assistant)**: a customer support agent for a made-up online fashion store. It answers from the store's catalog, stock and order data, handles returns with a two-step confirmation and hands over to a person when needed. Claude tool use, FastAPI, Postgres/pgvector, an MCP server, an Angular widget, evals and OpenTelemetry. The idea behind it: the model proposes, the code decides.

![Claude](https://img.shields.io/badge/Claude_tool_use-D97757?style=flat-square&logo=anthropic&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Postgres](https://img.shields.io/badge/Postgres%2Fpgvector-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MCP](https://img.shields.io/badge/MCP_server-111111?style=flat-square)
![Angular](https://img.shields.io/badge/Angular_widget-DD0031?style=flat-square&logo=angular&logoColor=white)
![Evals](https://img.shields.io/badge/evals-555555?style=flat-square)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-425CC7?style=flat-square&logo=opentelemetry&logoColor=white)

**[The Brain](https://github.com/rnachoc/the-brain)**: a local, visual control room for AI agents, one agent per project. You type what you need in a single chat bar, a router sends it to the right agent, and the agent breaks it into orders you can watch in a queue. Anything that touches the outside world waits for your approval as a draft. Built on the Claude Agent SDK, with a folder sandbox per agent, blocked commands and a full log of every tool call.

![Claude Agent SDK](https://img.shields.io/badge/Claude_Agent_SDK-D97757?style=flat-square&logo=anthropic&logoColor=white)
![MCP](https://img.shields.io/badge/MCP_tools-111111?style=flat-square)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js_Fastify-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![React](https://img.shields.io/badge/React_Vite-20232A?61DAFB&logo=react&logoColor=style=flat-square)

**[IA en apuros](https://github.com/rnachoc/iaenapuros)**: a fully local pipeline that writes, renders, reviews and ships one comedy short per day. A scheduled Claude Code agent picks the topic and writes the script following the rules in the repo, and code does the rest: voice, 3D render, QA, captions and a simulated audience of five AI viewers that can send the episode back for up to three rewrites. No paid APIs. An unofficial parody, not affiliated with Anthropic.

![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=flat-square&logo=anthropic&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?black&logo=javascript&logoColor=style=flat-square)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

**[Leora](https://github.com/rnachoc/leora)**: a mobile reading library designed around AI recommendations grounded in a real book catalog, so the model never invents titles. React Native, Expo and TypeScript. [Live demo](https://rnachoc.github.io/leora/app/)

![React Native](https://img.shields.io/badge/React_Native-20232A?61DAFB&logo=react&logoColor=style=flat-square)
![Expo](https://img.shields.io/badge/Expo-000020?style=flat-square&logo=expo&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)

**[Sevilla Sim](https://github.com/rnachoc/sevilla-sim)**: Seville in 3D in the browser with three.js. The historic centre and Triana are generated from OpenStreetMap data, with the IGN orthophoto on ground and roofs and building heights from the Catastro. Inspired by mrdoob's Slop New York, with its own code.

---

#### 🛠️ Stack

**AI**

![Claude API](https://img.shields.io/badge/Claude_API-D97757?style=for-the-badge&logo=anthropic&logoColor=white)
![Claude Agent SDK](https://img.shields.io/badge/Claude_Agent_SDK-D97757?style=for-the-badge&logo=anthropic&logoColor=white)
![tool use](https://img.shields.io/badge/tool_use-333333?style=for-the-badge)
![MCP](https://img.shields.io/badge/MCP-111111?style=for-the-badge)
![evals](https://img.shields.io/badge/evals-555555?style=for-the-badge)
![pgvector](https://img.shields.io/badge/pgvector-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-425CC7?style=for-the-badge&logo=opentelemetry&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

**Backend**

![Java](https://img.shields.io/badge/Java_11%2F17-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Spring Cloud](https://img.shields.io/badge/Spring_Cloud-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![microservices](https://img.shields.io/badge/microservices-333333?style=for-the-badge)
![REST APIs](https://img.shields.io/badge/REST_APIs-333333?style=for-the-badge)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)
![Temporal](https://img.shields.io/badge/Temporal-141414?style=for-the-badge&logo=temporal&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)

**Data & cloud**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)

**Frontend**

![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![React Native](https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![three.js](https://img.shields.io/badge/three.js-000000?style=for-the-badge&logo=threedotjs&logoColor=white)

---

#### 📫 Contact

[LinkedIn](https://www.linkedin.com/in/ignaciorodriguezcaro) · rnachoccontact@gmail.com

<div align="center">

![Footer](https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer)

</div>
