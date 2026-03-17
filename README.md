# AI Job Matcher 🚀

AI-powered system for matching resumes with job listings using NLP and machine learning.

## 🔥 Features

- Resume analysis and preprocessing
- Job matching using TF-IDF + cosine similarity
- Asynchronous processing with Celery
- REST API for interaction
- Analytics module for insights
- Scalable architecture (ASGI-ready)

## 🧠 Tech Stack

- Backend: Django, Django REST Framework
- Async: Celery, Redis
- ML: scikit-learn, pandas, numpy
- Database: PostgreSQL
- Analytics: Peewee
- Server: Uvicorn (ASGI)

## ⚙️ How it works

1. User submits a resume
2. Resume is processed asynchronously
3. Text is vectorized using TF-IDF
4. Similarity scores are calculated
5. Top matching jobs are returned

## 📡 API Endpoints

- `POST /resume` — upload resume
- `GET /jobs` — list jobs
- `POST /match` — get job matches
- `GET /analytics` — view statistics

## 🚀 Getting Started

```bash
git clone https://github.com/yourusername/ai-job-matcher.git
cd ai-job-matcher

uv venv 
source .venv/bin/activate

uv init
uv sync
