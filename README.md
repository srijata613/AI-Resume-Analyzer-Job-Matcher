# AI Talent Intelligence Engine

Semantic, priority-aware resume ranking system built for modern hiring workflows.

This project is a full-stack AI-powered candidate screening engine that performs structured job description parsing, weighted skill alignment, semantic experience matching, and explainable ranking — exposed through a production-ready FastAPI backend and a modern Next.js SaaS-style frontend.

---

## 🚀 Overview

AI Talent Intelligence Engine helps recruiters and hiring teams:

- Rank multiple candidates against a job description
- Detect matched and missing skills
- Evaluate semantic experience alignment
- Generate weighted, explainable scoring
- Analyze candidates in real time via web interface

The system is designed to move beyond keyword matching and instead use embedding-based semantic intelligence combined with structured weighting logic.

---

## 🧠 Core Intelligence Architecture

The ranking engine combines multiple scoring components:

### 1. Priority-Aware Skill Matching
- Dictionary-based skill extraction
- Embedding-based semantic similarity
- Dynamic similarity thresholds
- Importance weighting based on JD context

### 2. Experience Alignment
- Sentence-level embedding similarity
- Best-match responsibility scoring
- Normalized experience confidence score

### 3. Education Scoring
- Education signal detection
- Optional degree alignment scoring

### 4. Bonus Logic
- Strategic reward for strong core skill overlap

### Final Score Formula
