<!--Project Video Link - https://drive.google.com/file/d/1BcdqpYm3tIkvyUZ4fCE418QETPQKPSwg/view?usp=sharing

<h4 align="center">There are many features that are not inlcuded in this video. To enjoy the functionality clone this repo and just play with it.</h4> 

<h4>Live Project Link - https://.../</h4> 

<br/> -->
<br/> 
<a id="top"></a>

<h1 align="center">Project Name</h1>

<p align="center">

  <img alt="profile views" src="https://komarev.com/ghpvc/?username=PrabhakaranVijay&label=Profile%20Views&color=7F00FF&style=flat"/>
  
  <img alt="Github top language" src="https://img.shields.io/github/languages/top/PrabhakaranVijay/rag-huggingface-mlflow?color=7F00FF">

  <img alt="Github language count" src="https://img.shields.io/github/languages/count/PrabhakaranVijay/rag-huggingface-mlflow?color=7F00FF">

  <img alt="Repository size" src="https://img.shields.io/github/repo-size/PrabhakaranVijay/rag-huggingface-mlflow?color=7F00FF">

  <img alt="License" src="https://img.shields.io/github/license/PrabhakaranVijay/rag-huggingface-mlflow?color=7F00FF">

  <!-- <img alt="Github issues" src="https://img.shields.io/github/issues/PrabhakaranVijay/rag-huggingface-mlflow?color=7F00FF" /> -->

  <img alt="Github forks" src="https://img.shields.io/github/forks/PrabhakaranVijay/rag-huggingface-mlflow?color=7F00FF" />

  <img alt="Github stars" src="https://img.shields.io/github/stars/PrabhakaranVijay/rag-huggingface-mlflow?color=7F00FF" />
</p>

<h4 align="center"> 
	🚧 Project under active development 🚀
</h4> 

<hr>

<p align="center">
  <a href="#rocket-project-overview">Project Overview</a> &#xa0; | &#xa0; 
  <a href="#brain-architecture">Architecture</a> &#xa0; | &#xa0; 
  <a href="#hammer_and_wrench-tech-stack">Tech Stack</a> &#xa0; | &#xa0;
  <a href="#white_check_mark-requirements">Requirements</a> &#xa0; | &#xa0;
  <a href="#arrow_forward-how-to-run">Starting</a> &#xa0; | &#xa0;
  <a href="#memo-license">License</a> &#xa0; | &#xa0;
  <a href="https://github.com/PrabhakaranVijay" target="_blank">Author</a>
</p>

<br>

This project implements a **Retrieval-Augmented Generation (RAG)** pipeline using **Hugging Face Large Language Models (LLMs)** with **MLflow** for experiment tracking.
The entire workflow is demonstrated end-to-end in a **Jupyter Notebook**.

## 🚀 Project Overview ##

Retrieval-Augmented Generation (RAG) enhances LLM responses by retrieving relevant context from external documents before generating answers.
This project demonstrates:

* Document ingestion & preprocessing
* Semantic retrieval using vector embeddings
* Answer generation using a Hugging Face LLM
* Experiment tracking with MLflow

---

## 🧠 Architecture ##

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

<!--
## :sparkles: Features ##

✔ **Features 1**: (explain one line)  
✔ **Features 2**: (explain one line)
✔ **Features 3**:(explain one line)  
✔ **Features 4**: (explain one line)  
✔ **Features 5**:(explain one line)  
-->

---

## 🛠️ Tech Stack ##

The following tools were used in this project:

- [Python](https://www.python.org/)
- [Jupyter Notebook](https://jupyter.org/)
- [Hugging Face Transformers](https://huggingface.co/docs/transformers/index)
- [Sentence Transformers / Embeddings](https://www.sbert.net/)
- [Vector Store (FAISS)](https://faiss.ai/)
- [MLflow](https://mlflow.org/)

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

## :white_check_mark: Requirements ##

Before starting :checkered_flag:, you need to have [Git](https://git-scm.com) and [Python](https://www.python.org/) installed.

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

## :memo: License ##

This project is under license from MIT. For more details, see the [LICENSE](LICENSE.md) file.


Made with ❤️ by <a href="https://github.com/PrabhakaranVijay" target="_blank">Prabhakaran Vijay</a>

&#xa0;

---
<div align="center">
  <h2>⭐ If You Like This Project</h2>

  <p>Give it a ⭐ on GitHub and feel free to fork or improve it!</p>
</div>

	
<br/>
<br/>

<p align="center">
  <a href="#top">Back to top</a>
</p>




