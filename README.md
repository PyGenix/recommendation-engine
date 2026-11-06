# Recommendation Engine

Python FastAPI content-based recommender for catalog items.

Ranks related products with TF-IDF features and cosine similarity — no user-tracking history required.

## Stack

- **Backend:** Python 3.11+, FastAPI, Uvicorn
- **ML:** scikit-learn (TF-IDF, cosine similarity), Pandas
- **Frontend (optional demo UI):** React + Vite

## Features

- Item catalog listing and detail endpoints
- Top-N similar-item recommendations
- Sample catalog CSV for immediate demos

## Quick start

```bash
cd backend
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
uvicorn main:app --reload --port 8001
```

API docs: http://localhost:8001/docs

```bash
cd frontend
npm install
npm run dev
```

## Author

Pooja Sharma — [Pooja101117](https://github.com/Pooja101117)
