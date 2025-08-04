
````markdown
# 🧠 AI Research Agent

An AI-powered research assistant that leverages IBM Watsonx.ai and IBM Cloud Lite to simplify and accelerate academic and scientific research. It autonomously searches for relevant literature, summarizes papers, generates hypotheses, and assists in writing reports using Natural Language Processing (NLP) and Retrieval-Augmented Generation (RAG).

## 📌 Project Overview

The **AI Research Agent** is designed to automate repetitive research tasks:
- 🔍 Literature search using arXiv API
- 📄 Summarization and context extraction
- 🧠 Hypothesis generation and contextual question answering
- 📝 Report drafting and citation assistance

## 🚀 Key Features

- ✅ Query understanding using IBM Granite LLM
- ✅ RAG pipeline: retrieve → rerank → generate
- ✅ Paper summarization with citations
- ✅ Section generation (Abstract, Introduction, Conclusion)
- ✅ User prompt-based research assistance

## 🛠️ Technologies Used

- **IBM Watsonx.ai Studio** (Granite-13b-instruct-v1 or v2)
- **IBM Cloud Lite** (Deployment)
- **Python** + **Flask** or **FastAPI** (Backend)
- **FAISS** or **IBM Watson Discovery** (Vector DB)
- **arXiv API** (Paper Retrieval)
- **React / Next.js** (Optional Web Interface)

## 🧠 Architecture

```plaintext
User Query
   ↓
[Frontend (optional)]
   ↓
[Backend API]
   ↓
RAG Pipeline
→ Retrieve Papers (arXiv API)
→ Generate Embeddings (Granite NLP or HuggingFace)
→ Query Vector DB (FAISS / Watson Discovery)
→ Feed to IBM Granite LLM
→ Output Summary / Answer / Section
````



## 🧪 Example Prompts

* `"Summarize the latest research on quantum transformers"`
* `"Give me an abstract and introduction on the topic of explainable AI"`
* `"Generate a hypothesis on the effects of federated learning in healthcare"`



## 📄 Documents

* `AI_Research_Agent_Project.pdf` – Final project report
* `presentation.pptx` – Capstone presentation
* `prompt_examples.txt` – Sample queries

## 📚 Acknowledgements

* [IBM Watsonx.ai](https://www.ibm.com/products/watsonx-ai)
* [arXiv API](https://arxiv.org/help/api/)
* [FAISS by Facebook AI](https://github.com/facebookresearch/faiss)

---

**Developed by:** Shubham Kasture
**Institute:** SVERI coe Pandharpur

```
