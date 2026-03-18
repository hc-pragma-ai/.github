<p align="center">
  <img src="https://raw.githubusercontent.com/hc-pragma-ai/.github/main/assets/pragma-logo.svg" alt="Pragma AI" width="180" />
</p>

# Pragma AI

**Act on intelligence. Not just data.**

Pragma is a production-grade, multi-agent procurement intelligence platform built on AWS EKS. Event-driven architecture with 4 LangGraph agents communicating via Kafka — converting procurement signals into executable playbooks.

---

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

![Python](https://img.shields.io/badge/Python-3.12-3776AB?style=flat&logo=python)
![FastAPI](https://img.shields.io/badge/FastAPI-0.110-009688?style=flat&logo=fastapi)
![LangGraph](https://img.shields.io/badge/LangGraph-0.2-7C3AED?style=flat)
![Kafka](https://img.shields.io/badge/Kafka-Strimzi-231F20?style=flat&logo=apache-kafka)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-15%20%2B%20pgvector-336791?style=flat&logo=postgresql)
![Next.js](https://img.shields.io/badge/Next.js-14-000000?style=flat&logo=next.js)
![AWS](https://img.shields.io/badge/AWS-EKS%20%7C%20RDS%20%7C%20S3-232F3E?style=flat&logo=amazon-aws)

- **Backend:** Python FastAPI, LangGraph 0.2, Kafka (Strimzi)
- **Data:** PostgreSQL 15 + pgvector
- **Frontend:** Next.js 14, TypeScript, Tailwind
- **Infra:** AWS EKS, Terraform, ArgoCD GitOps

---

*Humancloud Technologies · Pune · 2026*
