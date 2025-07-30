# medchatbot_MedMCQA LangGraph

A **LangGraph-powered medical question-answering chatbot** using the [MedMCQA dataset](https://huggingface.co/datasets/medmcqa). This chatbot is designed to help medical students and researchers practice real NEET PG and AIIMS MCQs from over 21 medical subjects.

---

## Features

- Retrieval-Augmented Generation using **FAISS**
- Dataset-grounded responses (no hallucination)
- Confidence filtering (threshold ≥ 0.75)
- Powered by **LangGraph** for structured conversation flow
- Uses SentenceTransformers + FLAN-T5 
- Explanations, subject, and topic included

---

## Setup Instructions

### 1. Clone the repo

```bash
git clone https://github.com/yourusername/medchatbot_MedMCQA.git
cd medchatbot_MedMCQA
