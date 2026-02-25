# AI Resume Ranking Engine

Semantic, weighted, explainable resume–job matching system using BGE-large embeddings.

## Features
- Hybrid skill extraction (dictionary + semantic matching)
- Priority-aware skill weighting
- Responsibility-weighted experience scoring
- Multi-candidate ranking

## Tech Stack
- Python
- SentenceTransformers
- PyTorch
- NLTK

## Run Locally

```bash
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
python test_engine.py