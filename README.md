Current MVP Scope:
- Insurance Types:
  1. Health Insurance
  2. Term Insurance
  3. Life Insurance

Core Features:
1. User enters:
   - Age
   - Income
   - Marital status
   - Dependents
   - Risk preference

2. System:
   - Recommends insurance type using rule-based logic initially
   - Generates personalized explanation using LLM
   - Supports follow-up chatbot questions using RAG

Tech Stack:
- Python
- Streamlit
- OpenAI API
- FAISS vector database
- OpenAI embeddings
- Later migration to AWS Bedrock

Project Structure:

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