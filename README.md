🧠 LangChain + Ollama + OpenAI | RAG & Prompt Engineering Walkthrough
This project is a hands-on walkthrough of LangChain fundamentals, local LLM integration using Ollama, and Retrieval-Augmented Generation (RAG) with OpenAI APIs. It includes prompt engineering, chaining logic, embedding generation, and document retrieval—all modular and beginner‑friendly.

Contents:
• 01-langchain_Basics.ipynb – LangChain components (LLMs, prompts, memory, chains, tools)
• 02-langchain_Prompts.ipynb – Prompt engineering with PromptTemplate, dynamic variables
• 03-langchain_chains.ipynb – LLMChain, SimpleSequentialChain, custom chain logic
• Embeddings_generation_withOllama.ipynb – Local embeddings via Ollama + FAISS vector storage
• RAG_withOpenai.ipynb – RAG pipeline: OpenAI, vector similarity, LangChain
• requirements.txt – All dependencies

Setup Instructions:

1) git clone https://github.com/your-username/langchain-rag-ollama.git && cd langchain-rag-ollama

2) python -m venv venv && source venv/bin/activate (Windows: venv\Scripts\activate)

3) pip install -r requirements.txt
   ⚠️ Ensure Ollama is installed and running if using local models

Features Demonstrated:
✅ Core LangChain components
✅ Dynamic prompts & chaining
✅ Local embedding generation with Ollama
✅ FAISS vector indexing
✅ RAG using OpenAI APIs
✅ Document splitting + retrieval pipeline

Tools & Libraries: LangChain 0.3.25, Ollama, FAISS, OpenAI API, sentence‑transformers, Python 3.11+, Jupyter
