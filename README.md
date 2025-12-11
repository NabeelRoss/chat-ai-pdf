# Chat with PDF using Gemini AI 🤖

A powerful Streamlit application that allows you to chat with your PDF documents using Google's state-of-the-art **Gemini Pro** model. This tool uses **RAG (Retrieval-Augmented Generation)** to provide accurate, context-aware answers solely based on the content of your uploaded files.

## 🌟 Features

* **Multi-PDF Support:** Upload multiple PDF documents at once.
* **Deep Analysis:** Extracts text and creates vector embeddings using `GoogleGenerativeAIEmbeddings`.
* **Accurate Responses:** Uses FAISS vector search to find relevant content and answers questions using `Gemini Pro` without hallucinations.
* **Source Transparency:** If the answer isn't in the PDF, the bot will honestly tell you, rather than making things up.
* **User-Friendly Interface:** Clean, responsive UI built with Streamlit.

## 🛠️ Tech Stack

* **Frontend:** Streamlit
* **LLM:** Google Gemini Pro (`gemini-pro`)
* **Embeddings:** Google Generative AI Embeddings (`models/embedding-001`)
* **Vector Store:** FAISS (Facebook AI Similarity Search)
* **PDF Processing:** PyPDF2
* **Framework:** LangChain
