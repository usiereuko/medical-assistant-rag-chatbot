# Medical Assistant: Healthcare Q&A System Using Generative AI and RAG

Generative AI and Retrieval-Augmented Generation (RAG) project using LLMs, embeddings, vector databases, and semantic search to build a healthcare question-answering assistant grounded in trusted medical knowledge sources.

---

## Project Overview

This project develops an AI-powered medical assistant capable of answering healthcare-related questions using Retrieval-Augmented Generation (RAG) and Large Language Models (LLMs).

The system combines semantic search, vector embeddings, document retrieval, and generative AI to retrieve relevant medical information from the Merck Manuals and generate context-aware responses for healthcare queries.

The project demonstrates how Generative AI can improve medical knowledge accessibility while reducing hallucinations through grounded retrieval from trusted healthcare references.

---

## Objectives

- Build a healthcare question-answering assistant using Generative AI
- Implement Retrieval-Augmented Generation (RAG) workflows
- Use embeddings and vector databases for semantic search
- Generate context-aware healthcare responses using LLMs
- Improve medical information accessibility through conversational AI
- Evaluate the impact of prompt engineering and retrieval optimization on response quality

---

## Skills & Tools Used

- Python
- Generative AI
- Retrieval-Augmented Generation (RAG)
- Large Language Models (LLMs)
- LangChain
- Vector Databases (ChromaDB)
- Semantic Search
- Sentence Transformers
- Embeddings
- Prompt Engineering
- Llama.cpp
- Hugging Face Models
- Pandas
- NumPy

---

## Dataset Description

The project uses healthcare reference documents from the **Merck Manuals**, a globally recognized medical reference covering diseases, diagnoses, treatments, medications, and clinical procedures.

The source document consists of a large PDF medical manual containing over 4,000 pages of healthcare knowledge across multiple medical specialties.

---

## System Workflow

The Medical Assistant pipeline includes:

1. Loading and preprocessing medical reference documents
2. Splitting documents into text chunks
3. Generating embeddings using sentence transformer models
4. Storing embeddings in a vector database
5. Retrieving relevant medical context using semantic similarity search
6. Generating grounded responses using a Large Language Model (LLM)

---

## Model Development & Evaluation

The project compares multiple approaches for medical question answering:

- Baseline LLM without retrieval
- Prompt-engineered LLM responses
- Retrieval-Augmented Generation (RAG) pipeline
- Tuned RAG configurations with optimized chunking and retrieval settings

Response quality was evaluated based on:

- Context relevance
- Groundedness
- Completeness
- Response clarity
- Hallucination reduction

---

## Key Insights

- Baseline LLM responses were relevant but often lacked detailed clinical grounding and occasionally introduced unsupported medical information.

- Prompt engineering improved response structure and readability, but responses still relied heavily on the model’s internal knowledge.

- Implementing RAG significantly improved response quality by grounding answers in the Merck Manuals, resulting in more accurate and context-aware healthcare responses.

- Retrieval quality was influenced by embedding model selection, chunk size, overlap configuration, and retrieval depth.

- Optimized retrieval settings improved contextual relevance while reducing hallucinations and unsupported outputs.

---

## Business Recommendations

- Adopt RAG-based healthcare assistants to improve medical information accessibility while grounding responses in trusted medical references.

- Maintain low-temperature settings to improve response consistency and reliability in healthcare applications.

- Optimize chunk size, overlap, and retrieval depth to balance retrieval precision and contextual completeness.

- Implement evaluation metrics such as groundedness and relevance scoring to improve response reliability.

- Continue improving prompt engineering and context management techniques to enhance clinical usability and user experience.

---

## Repository Structure

```text
Medical_Assistant_RAG_Chatbot.ipynb   # Main project notebook
README.md                             # Project documentation
```

---

## Author

**Usiere Uko**  
Business Consultant | Data Science & AI/ML | Applied Machine Learning | Financial & Business Analytics

- LinkedIn: https://www.linkedin.com/in/usiere/
- GitHub: https://github.com/usiereuko
