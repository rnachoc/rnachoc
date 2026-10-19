### Hi, I'm Ignacio (Nacho) 👋

I build AI agents and automations with LLMs: agents that use tools, work with business data and take actions, with the guardrails, evals and observability they need to run in production.

Before that, I spent 5+ years as a backend engineer in Java and Spring Boot, three of them on a core banking platform. That's where my habits come from: validate everything, trace everything, and never let a model change data without a rule in code.

#### What I build

- **Tool-using agents** on the Claude API: well-described tools, multi-step loops and explicit confirmation before any action that changes data
- **MCP servers** that expose business systems to any AI client
- **Evals** that measure accuracy, cost and latency, so every change to a prompt, tool or model is compared with numbers
- **Guardrails** against prompt injection, data leaks and made-up answers
- **Integrations** with real backends: REST APIs, Postgres, Kafka, Docker

#### Featured projects

**[Hilo](https://github.com/rnachoc/quilora-assistant)**: a customer support agent for a made-up online fashion store. It answers from the store's catalog, stock and order data, handles returns with a two-step confirmation and hands over to a person when needed. Claude tool use, FastAPI, Postgres/pgvector, an MCP server, an Angular widget, evals and OpenTelemetry. The idea behind it: the model proposes, the code decides.

**[Leora](https://github.com/rnachoc/leora)**: a mobile reading library designed around AI recommendations grounded in a real book catalog, so the model never invents titles. React Native, Expo and TypeScript. [Live demo](https://rnachoc.github.io/leora/app/)

#### Stack

- **AI:** Claude API, tool use, MCP, evals, pgvector, OpenTelemetry, Python
- **Backend:** Java 11/17, Spring Boot, Spring Cloud, FastAPI, microservices, REST APIs, Kafka
- **Data & cloud:** PostgreSQL, Oracle, Redis, AWS, Azure, Docker, Kubernetes
- **Frontend:** Angular, TypeScript, React Native

#### Contact

[LinkedIn](https://www.linkedin.com/in/ignaciorodriguezcaro) · rnachoccontact@gmail.com
