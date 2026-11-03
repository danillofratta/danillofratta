<h1 align="center">Hi, I'm Danillo Fratta 👋</h1>

<p align="center">
  <b>Tech Lead &amp; Software Architect</b> · .NET + Python · Agentic AI, RAG &amp; event-driven systems
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/danillofratta"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge" alt="LinkedIn"></a>
  <a href="https://medium.com/@danillo.fratta"><img src="https://img.shields.io/badge/Medium-Articles-111111?style=for-the-badge" alt="Medium"></a>
  <img src="https://img.shields.io/badge/Open_to-Remote_roles-2EA44F?style=for-the-badge" alt="Open to remote roles">
</p>

---

### About me

- **20+ years building software** (since 2004): developer, startup founder and, today, technical leader.
- **Tech Lead &amp; Product Owner at Foursys**, leading a team of 12 developers on financial-sector systems for an automotive bank.
- **Fintech background:** founded fintech and financial-education startups (Capitalizo) and hold the **CNPI-T** certification (Brazilian securities analyst), so I speak both code and finance.
- **Current focus: AI that is safe to put in production.** Agents with LangGraph, RAG, MCP and human-in-the-loop, built on top of reliable distributed systems.

> **Looking for:** remote roles as **Tech Lead**, **Software / AI Architect**, **Senior Backend Engineer (.NET / Python)** or **Technical Product Owner**.

| | |
|---|---|
| 📍 **Location** | Brazil (UTC−3), open to remote work worldwide |
| 🌍 **Citizenship** | Brazilian &amp; Italian (EU) |
| 🗣️ **Languages** | Portuguese (native) · English (B2, professional) |
| 💼 **Leadership** | Leading a 12-developer team · Tech Lead + PO |

---

### ⭐ Featured projects

#### 🤖 [Supplier Master AI](https://github.com/danillofratta/supplier-master-ai): Agentic AI, RAG &amp; enterprise workflow

Governed supplier onboarding where **the LLM recommends, but deterministic code decides**. The AI never writes directly to the ERP or the database.

- RAG over corporate policies: chunking, Titan embeddings on **Amazon Bedrock**, **OpenSearch** vector search, structured risk analysis.
- **LangGraph** agent with persistent PostgreSQL checkpoints and **human approval before any state-changing tool**.
- **MCP server** as the agent's only path to the business APIs (no database credentials inside the agent).
- **Transactional Outbox/Inbox** and idempotent **AWS SQS** consumers toward a replaceable SAP boundary; **OpenTelemetry** tracing end to end.

`Python` `FastAPI` `LangGraph` `MCP` `Amazon Bedrock` `OpenSearch` `PostgreSQL` `AWS SQS` `OpenTelemetry` `React` `TypeScript`

#### 💬 [Parley](https://github.com/danillofratta/parley): omnichannel customer service with AI agents *(in progress)*

A customer writes on Telegram; Parley stores the message exactly once, an AI agent proposes a reply, and the Conversations domain approves it or hands the conversation to a human, with per-conversation ordering and no message lost if a service goes down.

- Polyglot microservices: **Go** channel gateway and dispatcher, **.NET 10** core domain, **Python + LangGraph** agent orchestrator.
- **Kafka** with Outbox/Inbox, **DDD + CQRS + Vertical Slices**, MCP tools as another entry point to the same use cases.
- Swappable LLM provider, Architecture Decision Records and an AI-assisted development setup.

`Go` `.NET 10` `Python` `LangGraph` `Kafka` `MCP` `DDD` `CQRS`

#### 💳 [PayFlow Cloud](https://github.com/danillofratta/payflow-cloud): payments microservices on .NET Aspire

Identity, customer, catalog, sales and payment services behind an API gateway, with a payment orchestrator, outbox processors and a **Python fraud-analysis processor**, each service owning its own database.

`.NET 9` `.NET Aspire` `RabbitMQ` `MassTransit` `PostgreSQL` `Python` `Docker` `Azure`

#### 🧪 Architecture labs (earlier .NET work)

| Project | What it explores |
|---|---|
| [Service bus microservices](https://github.com/danillofratta/app-microservices-servicebus-dotnet-edd-cqrs-ddd-angular) | 4 microservices with interchangeable buses: Rebus, MassTransit, NServiceBus |
| [Gateway + RabbitMQ](https://github.com/danillofratta/app-microservices-dotnet-gateway-rabbitmq-angular) | Pure RabbitMQ messaging behind an Ocelot gateway, Angular front end |
| [CQRS with read/write DBs](https://github.com/danillofratta/app-microservices-cqrs-writeread-twodb-ddd-edd) | Separate command and query databases with MassTransit and Blazor |
| [AWS SQS / SNS / DynamoDB](https://github.com/danillofratta/app-microservices-aws-sqs-sns-dynamo-twodb-ddd-edd-cqrs) | Event-driven CQRS on AWS messaging |
| [Elasticsearch + GraphQL](https://github.com/danillofratta/app-elasticsearch-graphQL) | Search and GraphQL on a CQRS/DDD base |
| [Dapr](https://github.com/danillofratta/app-dapr) | Microservices building blocks with Dapr |

---

### 🛠️ Tech stack

| Area | Tools |
|---|---|
| **AI &amp; LLMs** | LangGraph · LangChain · RAG · MCP · Amazon Bedrock · OpenSearch (vector) · Human-in-the-loop agents |
| **Languages &amp; frameworks** | C# / .NET (ASP.NET Core, .NET Aspire) · Python (FastAPI) · Go · TypeScript |
| **Architecture** | Microservices · DDD · CQRS · Vertical Slices · Event-driven · Outbox/Inbox · API Gateway · Dapr |
| **Messaging** | Kafka · RabbitMQ · MassTransit · AWS SQS/SNS · Rebus · NServiceBus |
| **Data** | PostgreSQL · DynamoDB · Elasticsearch · OpenSearch |
| **Cloud &amp; ops** | AWS · Azure · Docker · OpenTelemetry |
| **Front end** | React · Angular · Blazor |

### 🧭 How I build

- **AI recommends, deterministic code decides.** Business rules and side effects stay outside the model.
- **Reliability first:** idempotency, Outbox/Inbox, correlation IDs and tracing are part of the design, not an afterthought.
- **Decisions are documented** with ADRs and diagrams, so a team can maintain what I build.

---

### ✍️ Latest articles

<!-- BLOG-POST-LIST:START -->
- [From Prompt to Specification: How I Used OpenSpec to Build AgentGate](https://medium.com/@danillo.fratta/from-prompt-to-specification-how-i-used-openspec-to-build-agentgate-16f9aecf689c?source=rss-8db306d501b3------2)
- [AI-First: Stop using Prompting Codex /Claude and Started Engineering with Spec-Driven Development](https://medium.com/@danillo.fratta/stop-using-prompting-codex-and-started-engineering-with-spec-driven-development-ccabf431bbce?source=rss-8db306d501b3------2)
- [Inside My Agentic AI Architecture: From User Prompt to SAP Without Giving the LLM Control](https://medium.com/@danillo.fratta/inside-my-agentic-ai-architecture-from-user-prompt-to-sap-without-giving-the-llm-control-efaaecded091?source=rss-8db306d501b3------2)
- [Microservices Don’t Mean Every Service Gets to Touch Every Database](https://medium.com/@danillo.fratta/microservices-dont-mean-every-service-gets-to-touch-every-database-e299fec434c7?source=rss-8db306d501b3------2)
- [Outbox + Inbox + SQS: How I Handle At-Least-Once Delivery Without Duplicating Business Actions](https://medium.com/@danillo.fratta/outbox-inbox-sqs-how-i-handle-at-least-once-delivery-without-duplicating-business-actions-a3b6ad6702c1?source=rss-8db306d501b3------2)
<!-- BLOG-POST-LIST:END -->

➡️ [All articles on Medium](https://medium.com/@danillo.fratta)

---

### 📫 Let's talk

The best way to reach me is on **[LinkedIn](https://www.linkedin.com/in/danillofratta)**. I'm happy to talk about roles, architecture or AI in production.

<details>
<summary>🇧🇷 Resumo em português</summary>
<br>

Tech Lead e arquiteto de software com mais de 20 anos de experiência, hoje Tech Lead e PO na Foursys liderando 12 desenvolvedores no setor financeiro. Ex-fundador de startups de fintech e analista CNPI-T. Meu foco atual é IA em produção: agentes com LangGraph, RAG, MCP e human-in-the-loop sobre sistemas distribuídos confiáveis (.NET, Python e Go). Aberto a vagas remotas como Tech Lead, Arquiteto de Software/IA, Desenvolvedor Backend Sênior ou PO técnico.

</details>
