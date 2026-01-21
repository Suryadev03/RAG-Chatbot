# 🤖 RAG Chatbot using Gemini API

A **Retrieval-Augmented Generation (RAG) chatbot** that combines document retrieval with generative AI to deliver **accurate, context-aware answers** based on user-provided documents.  
The chatbot is powered by **:contentReference[oaicite:0]{index=0}**.

---

## 📌 Overview

Large Language Models can hallucinate when answering questions without context.  
This project solves that problem using **Retrieval-Augmented Generation (RAG)** by grounding responses in relevant document content.

The chatbot:
- Retrieves the most relevant document chunks
- Injects them into the prompt
- Generates reliable answers using Gemini

---

## 🧠 How RAG Works

1. User uploads documents (PDF / TXT / CSV)
2. Documents are split into chunks
3. Embeddings are generated for each chunk
4. Chunks are stored in a vector database
5. User query retrieves the most relevant chunks
6. Gemini generates a response using retrieved context

---

## 🚀 Features

- 📄 Document-based question answering  
- 🔍 Semantic search using embeddings  
- 🧠 Gemini-powered response generation  
- ⚡ Fast retrieval with vector similarity search  
- 🖥️ Interactive UI (Streamlit)  
- 🔐 Secure API key handling using environment variables  

---

## 🛠️ Tech Stack

| Component | Technology |
|--------|-----------|
| LLM | Gemini API |
| Embeddings | Gemini Embedding Model |
| Vector Store | FAISS / Chroma |
| Backend | Python |
| UI | Streamlit |
| File Handling | PDF / Text Loaders |
| Environment | python-dotenv |

---

## 🔐 Environment Variables

Create a `.env` file in the root directory:

```env
GEMINI_API_KEY=your_gemini_api_key_here

---


git clone [https://github.com/your-username/rag-chatbot.git](https://github.com/Shreyabhat11/RAG_chatbot.git)
cd rag-chatbot

python -m venv venv
source venv/bin/activate    # Windows: venv\Scripts\activate

pip install -r requirements.txt



