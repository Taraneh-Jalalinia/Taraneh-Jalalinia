# Hi, I'm Taraneh 👋

**Backend Engineer** (Python · FastAPI · PostgreSQL) with 3+ years of production experience. I was the sole architect of a healthcare SaaS backend (70+ table database, RAG pipelines, Azure and Docker) and led a team of 4 backend developers. Earlier I worked as a business analyst and QA engineer on enterprise projects, so I care about clear requirements as much as clean code.

Based in Iran · open to relocation.

---

## Tech stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat&logo=django&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat)
![Alembic](https://img.shields.io/badge/Alembic-6BA81E?style=flat)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6B35?style=flat)
![LlamaIndex](https://img.shields.io/badge/LlamaIndex-6B52AE?style=flat)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)

---

## Portfolio projects

| Repository | What I built | Why it's interesting |
|------------|--------------|----------------------|
| [**Pantry_Graph**](https://github.com/Taraneh-Jalalinia/Pantry_shop) | FastAPI backend with SQLAlchemy and Alembic migrations, JWT login with roles, rate limiting, checkout that is safe to retry (Idempotency-Key), a curated food knowledge graph, local TF-IDF recipe search, pytest and GitHub Actions CI. The React UI was generated with AI (Cursor) as a thin demo. | Backend and documentation are the focus: user stories, BPMN process models and architecture decision records live in the repo, so the "why" is written down, not just the code |
| [**AI-Knowledge-API**](https://github.com/Taraneh-Jalalinia/AI-Knowledge-API) | Document upload, ChromaDB vector search, Redis caching, background embedding jobs, LLM-powered query answering, JWT auth | A full RAG pipeline from upload to retrieval, close to the kind of work I did at HolistiCare |
| [**Ecommerce-Microservices**](https://github.com/Taraneh-Jalalinia/Ecommerce-Microservices) | API gateway, separate database per service, JWT auth, Celery for async orders, pytest and GitHub Actions | Shows deliberate service boundary decisions, not microservices for the sake of it |
| [**Task_API**](https://github.com/Taraneh-Jalalinia/Task_API) | User registration and login, JWT-protected task CRUD, pytest, Docker Compose | A clean baseline that shows how I structure a new project from scratch |
| [**Social**](https://github.com/Taraneh-Jalalinia/Social) | Posts, votes, ownership rules, tests, Docker | Permission and ownership logic is where many social APIs cut corners |

---

## Production experience (not on GitHub)

At **HolistiCare** (2023 to 2026) I built and ran systems that cannot be open-sourced:

- Sole architect of a healthcare SaaS backend: a 70+ table PostgreSQL schema and all production REST APIs in FastAPI and Django, secured with JWT and role-based access control
- Cut API response time by about 30% through query optimisation, indexing and parallel execution
- RAG pipelines with LlamaIndex and ChromaDB, and microservices that connect LLM-powered features to the core platform
- Ran Azure infrastructure (2 production servers, Docker deployments)
- Led 4 backend developers: code reviews, production issue triage, infrastructure escalation

Before that I worked as a business analyst and QA engineer (requirements, data models, prototypes and testing for enterprise clients) and built a price-prediction model with scikit-learn.

---

## What I care about when building backends

- Clear API contracts (OpenAPI / Swagger)
- Tests that run fast and do not depend on leftover local database files
- Sensible service boundaries: monolith first, split when there is a real reason
- Honest READMEs: what runs in Docker, what needs environment variables, what is mocked in CI
- Systems that a new engineer can run locally in under 10 minutes
