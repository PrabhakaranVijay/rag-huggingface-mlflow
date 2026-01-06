# Retrieval-Augmented Generation (RAG) with Hugging Face & MLflow

This project implements a **Retrieval-Augmented Generation (RAG)** pipeline using **Hugging Face Large Language Models (LLMs)** with **MLflow** for experiment tracking.
The entire workflow is demonstrated end-to-end in a **Jupyter Notebook**.

---

## 🚀 Project Overview

Retrieval-Augmented Generation (RAG) enhances LLM responses by retrieving relevant context from external documents before generating answers.
This project demonstrates:

* Document ingestion & preprocessing
* Semantic retrieval using vector embeddings
* Answer generation using a Hugging Face LLM
* Experiment tracking with MLflow

---

## 🧠 RAG Architecture

```
User Query
    ↓
Embedding Model
    ↓
Vector Store (Retriever)
    ↓
Relevant Context
    ↓
Hugging Face LLM
    ↓
Final Answer
```

---

## 🛠 Tech Stack

* **Python**
* **Jupyter Notebook**
* **Hugging Face Transformers**
* **Sentence Transformers / Embeddings**
* **Vector Store (FAISS or similar)**
* **MLflow** (experiment tracking)

---

## 📂 Project Structure

```
.
├── rag.ipynb        # Complete RAG implementation
├── README.md        # Project documentation
└── mlruns/          # MLflow artifacts (ignored in git)
```

> ⚠️ Note: `mlruns/` is generated automatically by MLflow and should not be committed to GitHub.

---

## 📒 Notebook Highlights (`rag.ipynb`)

The notebook covers:

1. **Environment Setup & Imports**
2. **Document Loading and Chunking**
3. **Embedding Generation**
4. **Vector-Based Retrieval**
5. **LLM-Based Answer Generation**
6. **MLflow Logging**

   * Parameters
   * Metrics
   * Artifacts

---

## ▶️ How to Run

### 1. Install Dependencies

```bash
pip install -r requirements.txt
```

### 2. Start MLflow UI (Optional)

```bash
mlflow ui
```

### 3. Run the Notebook

```bash
jupyter notebook rag.ipynb
```

Run all cells sequentially to execute the full RAG pipeline.

---

## 📊 MLflow Integration

This project uses **MLflow** to track:

* Model parameters
* Retrieval and generation configurations
* Experiment runs

MLflow UI allows easy comparison of experiments.

---

## 🎯 Use Cases

* Question Answering over documents
* Knowledge-base chatbots
* Enterprise document search
* AI assistants with grounded responses

---

## 📌 Key Learnings

* How RAG improves factual accuracy of LLMs
* Practical usage of Hugging Face LLMs
* Vector similarity search for retrieval
* MLflow for reproducible ML experiments

---

## 👨‍💻 Author

**Prabhakaran Vijay**
Software Developer | ML Engineer
📍 Bangalore, India

---

## ⭐ If You Like This Project

Give it a ⭐ on GitHub and feel free to fork or improve it!

---

### 🔥 Next (Optional Improvements)

* Convert notebook logic into modular Python scripts
* Add FastAPI for serving the RAG pipeline
* Deploy with Docker
* Add evaluation metrics for answer quality

---

If you want, I can also:

* Optimize this README for **LinkedIn**
* Add **architecture diagrams**
* Create a **resume-ready project description**
* Convert notebook → **production-ready code**

Just tell me 🚀
