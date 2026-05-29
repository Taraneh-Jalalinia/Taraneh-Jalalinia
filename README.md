# Hi, I'm Taraneh 👋

**Backend Engineer** (Python · FastAPI · PostgreSQL) — 3 years building production systems in health-tech, including a full healthcare SaaS backend, RAG pipelines with ChromaDB, and a team of 4. These repos show how I approach clean, testable backends outside of work constraints.

---

## Tech stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat&logo=django&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6B35?style=flat)
![LlamaIndex](https://img.shields.io/badge/LlamaIndex-6B52AE?style=flat)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)

---

## Portfolio projects

| Repository | What I built | Why it's interesting |
|------------|--------------|----------------------|
| [**Ecommerce-Microservices**](https://github.com/Taraneh-Jalalinia/Ecommerce-Microservices) | API gateway, separate DB per service, JWT auth, Celery for async orders, pytest + GitHub Actions | Shows deliberate service boundary decisions — not microservices for the sake of it |
| [**AI-Knowledge-API**](https://github.com/Taraneh-Jalalinia/AI-Knowledge-API) | Document upload, ChromaDB vector search, Redis caching, background embedding jobs, JWT | Full RAG pipeline from upload to retrieval, close to what I built in production |
| [**Task_API**](https://github.com/Taraneh-Jalalinia/Task_API) | User registration/login, JWT-protected task CRUD, pytest, Docker Compose | Clean baseline — shows how I structure a new project from scratch |
| [**Social**](https://github.com/Taraneh-Jalalinia/Social) | Posts, votes, ownership rules, tests, Docker | Permission logic and ownership rules are where most social APIs cut corners — these don't |

---

## What I care about when building backends

- Clear API contracts (OpenAPI / Swagger)
- Tests that run fast and don't depend on leftover local database files
- Sensible service boundaries — monolith first, split when there's a real reason
- Honest READMEs: what runs in Docker, what needs env vars, what is mocked in CI
