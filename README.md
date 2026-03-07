# Elias Ekberg Gasper 🐸💻

Self-taught backend & data engineer based in Sweden. I build production-grade applications with Python, Django, and PostgreSQL — focused on data pipelines, semantic search, and AI-powered backends.

Currently open to **remote backend or data engineering roles**.

---

## What I'm Building

### [MobelQuery](https://www.mobelquery.com) — AI Furniture Search Engine
A full-stack semantic search application for furniture discovery. Users describe what they're looking for in natural language and the engine returns results ranked by semantic meaning using cosine similarity over vector embeddings.

**Stack:** React + Tailwind → Vercel, Django REST API + PostgreSQL + pgvector → AWS EC2, SentenceTransformer `all-MiniLM-L6-v2`, SpaCy

**What's interesting:**
- Vector embeddings stored and queried in PostgreSQL via pgvector
- SpaCy NLP pipeline scores product descriptions for semantic density before embedding
- Replaced in-memory FAISS index with persistent DB similarity search
- Full ETL pipeline from raw product data to searchable vector store

---

## Tech Stack

**Backend:** Python, Django, Django REST Framework  
**Databases:** PostgreSQL, pgvector  
**ML/NLP:** SentenceTransformers, SpaCy, FAISS  
**Frontend:** React, Tailwind CSS  
**Cloud:** AWS EC2, Vercel  
**Tools:** Git, Linux, Nginx, Gunicorn, Docker (learning)

---

## Goals

- Land a remote backend or data engineering role
- Build a production ETL pipeline with real product data at scale
- Contribute to open source projects in the Python/data ecosystem
- Work remotely on backend infrastructure, data pipelines, 
  or developer tooling at a company building things that matter.

---

## Currently Learning

- Docker & containerization
- CI/CD with GitHub Actions
- Advanced PostgreSQL & query optimization
- SQL for data engineering 

---

*Some projects are private while in active development. Architecture breakdowns and demos available on request.*
