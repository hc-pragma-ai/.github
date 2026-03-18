# Pragma AI

**Act on intelligence. Not just data.**

Pragma is a production-grade, multi-agent procurement intelligence platform built on AWS EKS. Event-driven architecture with 4 LangGraph agents communicating via Kafka.

## Repositories

| Repo | Description |
|------|-------------|
| [pragma-core](https://github.com/hc-pragma-ai/pragma-core) | Shared config, Pydantic models, Kafka utils, Docker Compose |
| [pragma-agents](https://github.com/hc-pragma-ai/pragma-agents) | 4 LangGraph agents (Collector, Analyst, Scorer, Synthesizer) |
| [pragma-api](https://github.com/hc-pragma-ai/pragma-api) | FastAPI gateway + Go health service |
| [pragma-frontend](https://github.com/hc-pragma-ai/pragma-frontend) | Next.js 14 dashboard |
| [pragma-infra](https://github.com/hc-pragma-ai/pragma-infra) | Terraform, Helm, ArgoCD |
| [pragma-ml](https://github.com/hc-pragma-ai/pragma-ml) | MLflow, prompt engineering, evals |

## Tech Stack

- **Backend:** Python FastAPI, LangGraph 0.2, Kafka (Strimzi)
- **Data:** PostgreSQL 15 + pgvector
- **Frontend:** Next.js 14, TypeScript, Tailwind
- **Infra:** AWS EKS, Terraform, ArgoCD GitOps

---

*Humancloud Technologies · Pune · 2026*
