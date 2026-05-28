# AI Insurance Advisor

A GenAI-powered insurance recommendation and advisory application built using Python, Streamlit, OpenAI, and RAG (Retrieval-Augmented Generation).

# Project Goal

The goal of this project is to build an intelligent insurance advisor that:

- Recommends suitable insurance types
- Generates personalized explanations using LLMs
- Answers insurance-related questions using RAG
- Demonstrates production-style GenAI architecture

# Current MVP Features

## Insurance Recommendations
Supports:
- Health Insurance
- Term Insurance
- Life Insurance

## User Inputs
The system currently accepts:
- Age
- Income
- Marital Status
- Dependents
- Risk Preference

## Recommendation Logic
- Rule-based recommendation engine
- Ranked insurance suggestions
- Expandable for ML-based recommendations later

# Tech Stack

| Technology | Purpose |
|---|---|
| Python | Backend Logic |
| Streamlit | Frontend UI |
| OpenAI API | LLM Responses |
| FAISS | Vector Database |
| OpenAI Embeddings | Semantic Search |
| AWS Bedrock *(Later)* | Cloud LLM Deployment |

# Project Structure

```bash
ai-insurance-advisor/
│
├── app/
│   ├── main.py
│   ├── recommendation_engine.py
│   ├── llm_handler.py
│   ├── rag_pipeline.py
│   ├── prompts.py
│   └── utils.py
│
├── data/
│   ├── insurance_docs/
│   └── processed/
│
├── vector_store/
│
├── requirements.txt
├── .env
└── README.md
```

# Setup Instructions

## 1. Clone Repository

```bash
git clone <your-repo-url>
cd ai-insurance-advisor
```

---

## 2. Create Virtual Environment

### Windows

```bash
python -m venv venv
venv\Scripts\activate
```

## 3. Install Dependencies

```bash
pip install -r requirements.txt
```

# Current Progress

## Completed
- Project structure setup
- Recommendation engine base structure
- User profile schema using dataclass

## In Progress
- Rule-based insurance recommendation engine

## Upcoming
- LLM integration
- Prompt engineering
- RAG pipeline
- FAISS vector search
- Streamlit UI
- AWS Bedrock migration

---

# Learning Objectives

This project is designed to help understand:

- GenAI application architecture
- Prompt engineering
- RAG systems
- Vector databases
- LLM orchestration
- Production-level AI engineering

---

# Future Enhancements

- ML-based recommendation system
- User authentication
- Policy comparison
- Conversational memory
- Multi-agent workflow
- Cloud deployment

---

# Author

Shrinath Rajeshirke

AI/ML Enthusiast | GenAI Learner | Data Science Practitioner