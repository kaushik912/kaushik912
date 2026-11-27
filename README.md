### Hi, I'm Kaushik 👋

**Principal Engineer** · Payments, Fraud & Distributed Systems
Now building **agentic AI systems** on solid backend foundations. Runnable demos, not slide decks.

[Portfolio](https://kaushik912.github.io) · [LinkedIn](https://linkedin.com/in/kaushik-kailasnath/)

---

### 🚀 Live Demos: try them now

| Demo | What it is | Source |
|---|---|---|
| 📝 **[Notes App](https://kaushik912.github.io/mattpococktesting/)** | Notes PWA built end-to-end by a coding agent using Matt Pocock's skills | [mattpococktesting](https://github.com/kaushik912/mattpococktesting) |
| 🧠 **[System Design Quiz](https://kaushik912.github.io/systems-under-load/)** | System-design interview quiz: how systems behave under load | [systems-under-load](https://github.com/kaushik912/systems-under-load) |
| ⚡ **[Instant Quiz Generator](https://quiz-generator-1080967060998.us-central1.run.app/)** | Generate MCQs on any topic with an LLM (bring your own OpenRouter key) | [quiz-generator](https://github.com/kaushik912/ai-mcp-lab/tree/master/quiz-generator) |
| 🌦️ **[Weather MCP Agent](https://weathermcp-1080967060998.us-central1.run.app/)** | Weather agent: OpenAI Agents SDK + MCP tools, bring your own key | [weathermcp-openaisdk](https://github.com/kaushik912/weathermcp-openaisdk) |

> Cloud Run demos scale to zero when idle: the first load can take a few seconds.

---

### 🤖 AI: [ai-mcp-lab](https://github.com/kaushik912/ai-mcp-lab)

| Project | Purpose |
|---|---|
| [ecommerce-ai-assistant](https://github.com/kaushik912/ai-mcp-lab/tree/master/ecommerce-ai-assistant) | AI storefront concierge: RAG, deterministic `@Tool` calls, MCP carrier service, live agent X-ray |
| [spring-ai-basics](https://github.com/kaushik912/ai-mcp-lab/tree/master/spring-ai-basics) | One package per Spring AI concept: chat, memory, structured output, RAG, tools, workflow + LLM-as-judge evals |
| [research-agent](https://github.com/kaushik912/ai-mcp-lab/tree/master/research-agent) | RAG + MCP agent using a news tool (OpenRouter) |
| [research-agent-news-tool](https://github.com/kaushik912/ai-mcp-lab/tree/master/research-agent-news-tool) | MCP server (SSE) exposing `searchNews` |
| [a2a-hello-world](https://github.com/kaushik912/ai-mcp-lab/tree/master/a2a-hello-world) | A2A: LLM orchestrator delegating to joke/quote agents |
| [resilience-llm-failover](https://github.com/kaushik912/ai-mcp-lab/tree/master/resilience-llm-failover) | Gemini → OpenRouter failover via Resilience4j circuit breaker |
| [quiz-generator](https://github.com/kaushik912/ai-mcp-lab/tree/master/quiz-generator) | BYOK OpenRouter MCQ generator, Playwright e2e |
| [weathermcp-litellm](https://github.com/kaushik912/ai-mcp-lab/tree/master/weathermcp-litellm) | Provider-agnostic agent (LiteLLM), pluggable MCP tools |
| [openapi-mcp](https://github.com/kaushik912/ai-mcp-lab/tree/master/openapi-mcp) | MCP server to explore/call endpoints from an OpenAPI spec |
| [spring-ai-mcp-demo](https://github.com/kaushik912/ai-mcp-lab/tree/master/spring-ai-mcp-demo) | Person/account MCP servers + sample client |
| [mcp-quote-server](https://github.com/kaushik912/ai-mcp-lab/tree/master/mcp-quote-server) / [mcp-quote-client](https://github.com/kaushik912/ai-mcp-lab/tree/master/mcp-quote-client) | Spring AI MCP server + client (Ollama/Claude/OpenRouter) |
| [langchain-learning-lab](https://github.com/kaushik912/ai-mcp-lab/tree/master/langchain-learning-lab) | LangChain v1 / LangGraph examples, Streamlit |
| [langgraph_useful](https://github.com/kaushik912/ai-mcp-lab/tree/master/langgraph_useful) | LangGraph lesson scripts |

### ☁️ AI + Cloud

| Project | Purpose |
|---|---|
| [aws-ai-lab](https://github.com/kaushik912/aws-ai-lab) | Cost-optimized RAG + agent on AWS: Bedrock, LangGraph, Lambda streaming, Terraform, zero idle cost |
| [azure-ai-lab](https://github.com/kaushik912/azure-ai-lab) | Enterprise RAG + agentic gateway on Azure: Azure OpenAI, AI Search (hybrid + semantic rerank), AKS |

### 🌱 Spring + System Design: [spring-learning](https://github.com/kaushik912/spring-learning)

| Project | Purpose |
|---|---|
| [saga-orchestrator-tracing-demo](https://github.com/kaushik912/spring-learning/tree/master/saga-orchestrator-tracing-demo) | Orchestrated saga over Kafka with compensation, one end-to-end Jaeger trace |
| [saga-choreography-tracing-demo](https://github.com/kaushik912/spring-learning/tree/master/saga-choreography-tracing-demo) | Choreographed saga across modules, Jaeger |
| [saga-transfer-demo](https://github.com/kaushik912/spring-learning/tree/master/saga-transfer-demo) | Money transfer: buggy version vs saga fix |
| [idempotency-key-race-demo](https://github.com/kaushik912/spring-learning/tree/master/idempotency-key-race-demo) | Check-then-act race → double charge, fixed with Redis SETNX + DB unique constraint |
| [duplicate-delivery-demo](https://github.com/kaushik912/spring-learning/tree/master/duplicate-delivery-demo) | Kafka redelivery → double processing |
| [consumer-lag-demo](https://github.com/kaushik912/spring-learning/tree/master/consumer-lag-demo) | Kafka lag while consumers look healthy |
| [payment-volume-streaming-demo](https://github.com/kaushik912/spring-learning/tree/master/payment-volume-streaming-demo) | Kafka Streams rolling 24h payment total |
| [booking-system](https://github.com/kaushik912/spring-learning/tree/master/booking-system) | Seat booking with conditional-UPDATE concurrency |
| [scheduled-email](https://github.com/kaushik912/spring-learning/tree/master/scheduled-email) | Multi-instance email dedup: JDBC, JPA, outbox/SKIP LOCKED, Kafka |
| [db-io-exhaustion-demo](https://github.com/kaushik912/spring-learning/tree/master/db-io-exhaustion-demo) | DB pool exhaustion from an index-defeating query |
| [io-exhaustion-demo](https://github.com/kaushik912/spring-learning/tree/master/io-exhaustion-demo) | Thread pool exhaustion from a blocking call |
| [resource-exhaustion-demo](https://github.com/kaushik912/spring-learning/tree/master/resource-exhaustion-demo) | CPU/memory "healthy but wrong" bugs |
| [request-latency-tracing-demo](https://github.com/kaushik912/spring-learning/tree/master/request-latency-tracing-demo) | Latency tracing with a local observability stack |
| [singleton-scope-bug-demo](https://github.com/kaushik912/spring-learning/tree/master/singleton-scope-bug-demo) | Race on a singleton bean's field |
| [product-catalog-api](https://github.com/kaushik912/spring-learning/tree/master/product-catalog-api) | Product catalog REST API (Bruno/curl) |

### 📐 Spec-Driven Development

| Project | Purpose |
|---|---|
| [spec-tickets](https://github.com/kaushik912/spec-tickets) | Spec-first, ticket-driven workflow for coding agents: big ask → small resumable tickets, each spec → plan → tasks → TDD |
| ↳ [ecommerce-checkout](https://github.com/kaushik912/spec-tickets/tree/main/examples/ecommerce-checkout) | Checkout flow built ticket-by-ticket, Bruno tests |
| ↳ [todomvc-ticketsplit](https://github.com/kaushik912/spec-tickets/tree/main/examples/todomvc-ticketsplit) | TodoMVC backend + React frontend |
| ↳ [ticket-spec-demo](https://github.com/kaushik912/spec-tickets/tree/main/examples/ticket-spec-demo) | Banking lib demoing ticket specs |
| ↳ [custom-spec-repo](https://github.com/kaushik912/spec-tickets/tree/main/examples/custom-spec-repo) | Quote board, TinyURL, todo scaffolds |
| [mattpococktesting](https://github.com/kaushik912/mattpococktesting) | Matt Pocock's agent skills on a notes PWA (Vite, Playwright). [Live](https://kaushik912.github.io/mattpococktesting/) |

### 🔍 Splunk

| Project | Purpose |
|---|---|
| [splunk-rca-lab](https://github.com/kaushik912/infra-demos/tree/master/splunk-rca-lab) | 6 synthetic incident scenarios for root-cause analysis with Splunk SPL |

### 🏗️ Terraform

| Project | Purpose |
|---|---|
| [terraform-samples](https://github.com/kaushik912/infra-demos/tree/master/terraform-samples) | AWS / S3 / shared remote state / Debezium samples |

### 🧱 Toolbox

`Java` `Spring Boot` `Spring AI` `Python` `LangChain` `LangGraph` `MCP` `A2A` `RAG` `Kafka` `Resilience4j` `Claude Code` `AWS` `Azure` `GCP` `Kubernetes` `Terraform` `Splunk`

### 🔭 Explore

[my-claude-lib](https://github.com/kaushik912/my-claude-lib) · [claude-code-tooling](https://github.com/kaushik912/claude-code-tooling) · [infra-demos](https://github.com/kaushik912/infra-demos)
