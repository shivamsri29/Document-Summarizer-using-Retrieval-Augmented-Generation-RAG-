# Document-Summarizer-using-Retrieval-Augmented-Generation-RAG-
Built an intelligent document summarization and question-answering system using Retrieval-Augmented Generation (RAG) with LangChain and Google Gemini 2.5 Flash, enabling accurate, context-aware understanding of large documents.  🤖 AI-Powered Document Summarization &amp; Q&amp;A Python · LangChain · Gemini 2.5 Flash · HuggingFace · ChromaDB

🤖 AI-Powered Document Summarization & Q&A
Python · LangChain · Gemini 2.5 Flash · HuggingFace · ChromaDB

📖 Overview

This project implements a Retrieval-Augmented Generation (RAG) pipeline that allows users to upload documents (PDF/Text) and:

Generate meaningful summaries

Ask natural language questions

Get context-grounded answers

Instead of relying only on the LLM, the system first retrieves relevant document chunks from a vector database and then uses Gemini to generate accurate responses.

This improves:
✅ Factual accuracy
✅ Context relevance
✅ Reliability over plain LLM prompting

🛠️ Tech Stack

Language: Python
Libraries & Tools:

LangChain

Google Gemini 2.5 Flash

HuggingFace Sentence Transformers

ChromaDB (Vector Database)

PyPDF

Jupyter Notebook / Google Colab

🚀 Features

📄 PDF/Text document ingestion

✂️ Text chunking and preprocessing

🧠 Embedding generation using HuggingFace

📦 Vector storage using ChromaDB

🔍 Semantic retrieval of relevant content

📝 Document summarization using RAG

💬 Question-answering over uploaded documents

🧩 Modular and scalable project architecture

📊 Workflow
flowchart LR
A[Upload Document] --> B[Text Chunking]
B --> C[Generate Embeddings]
C --> D[Store in ChromaDB]
D --> E[User Query / Summarize Request]
E --> F[Retriever Fetches Relevant Chunks]
F --> G[Gemini Generates Context-Aware Output]

📈 Results

Produces high-quality document summaries

Handles multi-page PDFs effectively

Generates accurate answers grounded in document content

Successfully tested on academic papers, reports, and notes

Example:

User: Summarize the main points of this document
System: Generates concise, document-grounded summary using RAG pipeline

📂 Repository Structure
document-summarizer-rag/
│
├── data/           # Sample documents (PDF/Text)
├── notebooks/      # Jupyter / Colab experiments
├── src/            # Source code
│   ├── config.py
│   ├── load_documents.py
│   ├── embeddings.py
│   ├── vector_store.py
│   ├── rag_pipeline.py
│   └── app.py
│
├── screenshots/    # Demo screenshots
├── outputs/        # Sample summaries & answers
└── README.md

▶️ How to Run
git clone https://github.com/your-username/document-summarizer-rag
cd document-summarizer-rag
pip install -r requirements.txt
python src/app.py

🎯 Use Cases

Academic paper summarizer

Research assistant

PDF chatbot

Notes summarization tool

Knowledge-base assistant

Resume-grade Generative AI project

👤 Author

Shivam Srivastava
GitHub: https://github.com/your-username

LinkedIn: https://linkedin.com/in/your-profile

