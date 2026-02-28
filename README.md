<!--
GitHub Profile README
Repo name must match your GitHub username.
-->

# Felix Sarpong

Backend-first engineer building **reliable, scalable systems** (fintech/payments) and **production-minded agentic AI** tooling.

- **Core:** Java/Spring Boot • Python/FastAPI • AWS • Kafka/JMS • Postgres/Redis • Observability
- **Agentic AI:** LangGraph/LangChain • LlamaIndex • MCP • eval + guardrails • tool/function calling

---

## What I’m focused on right now
- Building **MCP-based** agent systems with **policy gating**, auditability, and safe tool execution
- Designing **incident triage automation** (evidence gathering → reasoning → action with approvals)
- Benchmarking orchestrators (latency, retries, tool reliability, cost) for real-world agent runs

---

## Featured Projects

### 🧪 Crash Lab
A “startup-style” lab for testing and hardening LLM agents under failure modes (tool errors, loops, partial data, policy constraints).
- Guardrails: confirmations for irreversible actions, tool allow/deny lists, audit logging
- Testing: unit + integration patterns for tool calling, retries, idempotency
- Roadmap: eval harness + regression suite for agent behavior

**Repo:** [Crash Lab](https://github.com/[YOUR_GH_USERNAME]/[crash-lab-repo])

---

### 🚨 Incident Triage MCP
An MCP server for incident response workflows (gather evidence, create tickets, generate summaries, produce artifact bundles).
- MCP server (streamable-http / tool calling)
- Evidence bundles + artifact storage (S3/MinIO/PVC patterns)
- Integrations: Jira/Slack/Airflow-style workflows (depending on deployment)

**Repo:** [incident-triage-mcp](https://github.com/[YOUR_GH_USERNAME]/incident-triage-mcp)

---

### 🧬 ORCHID (Orchestrator Benchmarking Harness)
A benchmarking harness comparing agent orchestrators (LangGraph vs others) across LLM providers/runtimes.
- Metrics: latency, token usage, retries, tool failures, cost
- Reproducible scenarios + scoring rubrics

**Repo:** [ORCHID](https://github.com/[YOUR_GH_USERNAME]/[orchid-repo])

---

### 🧑‍🏫 AI Tutor Platform
API-first tutoring platform with ingestion + retrieval workflows.
- Python/FastAPI • PostgreSQL • Docker • AWS (ECS) • Terraform
- Postgres migrations (Alembic), retrieval endpoints, containerized deploys

**Repo:** [AI Tutor Platform](https://github.com/[YOUR_GH_USERNAME]/[ai-tutor-repo])

---

## Experience Snapshot (Fintech / Payments)
- Built high-throughput APIs and event-driven systems (Kafka/JMS)
- Performance and reliability work: SQL tuning, caching (Redis), incident reduction, MTTR improvements
- Production testing culture: JUnit/Mockito + integration tests; Python pytest patterns

*(Keeping this high-level here — details live in my resume/LinkedIn.)*

---

## Tech I use a lot
**Backend:** Java, Spring Boot, Python, FastAPI  
**Data:** PostgreSQL, Redis, SQL tuning, migrations  
**Eventing:** Kafka, JMS  
**Cloud/Infra:** AWS, Docker, Kubernetes (when needed), Terraform  
**Quality:** pytest, JUnit, Mockito, integration tests, CI pipelines  
**Observability:** metrics/logs/traces (Prometheus/Grafana/OpenTelemetry patterns)  
**LLM/Agents:** LangGraph, LangChain, LlamaIndex, MCP, evaluation + guardrails

---

## How I work
- Prefer **clear interfaces**, **boring reliability**, and **measurable outcomes**
- Strong bias for **tests**, **observability**, and **safe automation**
- I like designs that survive messy real-world inputs

---

## Contact
- LinkedIn: [YOUR LINKEDIN]
- Email: [YOUR EMAIL]
- Portfolio: https://[your-portfolio-domain]

---

### Notes for collaborators
If you’re looking at my repos:
- Check `README` for architecture + run instructions
- Look for `docs/` for deeper design notes
- Issues/PRs usually include context + tradeoffs + test notes
