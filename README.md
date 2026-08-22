# Sovereign Industrial AI Workbench — SIH26117

Design and specification baseline for a **sovereign, on-premise agentic AI workbench** that turns confidential industrial data into evidence-backed decisions and governed actions without that data leaving the organisation's network perimeter.

> **Status:** Documentation only. **No component of this system is implemented.** Every capability in these documents carries an explicit maturity marker (`[MVP-P0]`, `[DIFF-P1]`, `[PROPOSED]`, `[FUTURE]`, `[OPTIONAL]`).

---

## Start here

**→ [docs/00-index.md](docs/00-index.md)** — master index, status taxonomy, section map and role-based reading paths.

## The system in one line

A sovereign, on-premise agentic AI workbench that turns confidential industrial data into evidence-backed decisions and governed actions without that data leaving the organisation's network perimeter.

## The system in one flow

```
Private data → Local models → RAG → Agents → Tools → Reasoning
→ Evidence verification → Risk assessment → Human approval → Action → Audit
```

---

## Documentation set

### Part A — Problem and product

| # | Document | Status |
|---|---|---|
| 00 | [Master index](docs/00-index.md) | Written |
| 01 | [Executive summary](docs/01-executive-summary.md) | Written |
| 02 | [Problem statement analysis](docs/02-problem-analysis.md) | Written |
| 03 | [Product vision](docs/03-product-vision.md) | Written |
| 04 | [User personas](docs/04-user-personas.md) | Written |

### Part B — Requirements

| # | Document | Status |
|---|---|---|
| 05 | Functional requirements | Pending |
| 06 | Non-functional requirements | Pending |

### Part C — Architecture

| # | Document | Status |
|---|---|---|
| 07 | System architecture | Pending |
| 08 | Component architecture | Pending |
| 09 | Data flow | Pending |
| 10 | RAG architecture | Pending |
| 11 | Agent architecture | Pending |
| 12 | Multimodal architecture | Pending |
| 13 | Security architecture | Pending |
| 14 | Governance architecture | Pending |
| 15 | Audit architecture | Pending |
| 16 | Industrial integration | Pending |
| 17 | Deployment architecture | Pending |
| 18 | Technology stack | Pending |

### Part D — Interfaces and implementation contracts

| # | Document | Status |
|---|---|---|
| 19 | API architecture | Pending |
| 20 | Database design | Pending |
| 21 | UI/UX architecture | Pending |

### Part E — Quality, scope and operations

| # | Document | Status |
|---|---|---|
| 22 | Failure handling | Pending |
| 23 | AI evaluation | Pending |
| 24 | Performance requirements | Pending |
| 25 | MVP scope | Pending |

### Part F — Business

| # | Document | Status |
|---|---|---|
| 26 | Business model | Pending |
| 27 | Competitive analysis | Pending |
| 28 | Differentiation | Pending |
| 29 | Business economics | Pending |
| 30 | Market opportunity | Pending |
| 31 | Product roadmap | Pending |
| 32 | Risk analysis | Pending |
| 33 | Competitive moat | Pending |
| 34 | Future vision | Pending |
| 35 | Final product definition | Pending |

---

## Proposed architecture at a glance

| Layer | Selection |
|---|---|
| Frontend | Next.js · TypeScript · Tailwind · shadcn/ui |
| Backend | FastAPI · Python |
| Agent orchestration | LangGraph or equivalent state-machine framework |
| Model serving | vLLM / Ollama, local GPU |
| Models | Open-weight LLM, VLM, embedding and reranker families — no mandated vendor |
| Vector store | Qdrant |
| Relational store | PostgreSQL |
| Object store | MinIO |
| Cache | Redis |
| Identity | Keycloak |
| Observability | Prometheus · Grafana · Loki · OpenTelemetry |
| Packaging | Docker Compose for prototype; Kubernetes as a future option |

Full rationale and MVP/future split: [docs/18-technology-stack.md](docs/18-technology-stack.md) *(pending)*.

---

## Evidence conventions used throughout

- External market, regulatory and competitor statements are cited inline to the source actually read.
- Where a figure could not be verified from a primary or reputable secondary source, the documents say so rather than substituting an estimate.
- All costs, prices, valuations and performance figures are **illustrative planning estimates**, explicitly labelled. None are quotes, benchmarks or achieved results.
- Security sections describe controls and residual risk. They do **not** assert that the system is secure, has no vulnerabilities, or guarantees compliance with any named regulation.
