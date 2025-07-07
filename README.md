# QA Bot: LangChain + LLM PDF Question Answering

> Build an intelligent assistant that reads PDF documents and answers your questions in real time.

---

## 📋 Project Overview

This project constructs a **question‑answering (QA) bot** using:

- **LangChain** for document loading, text splitting, embeddings & retrieval  
- A **Large Language Model (LLM)** (e.g. GPT‑3.5‑turbo) for generating answers  
- **Chroma** (or FAISS) vector store to index embedded text chunks  
- **Gradio** front‑end for a simple web UI  

You’ll point the bot at a folder of PDFs—legal docs, manuals, reports, whatever—and it’ll instantly answer user queries by retrieving the most relevant passages and feeding them to the LLM.

---

## 🚀 Features

1. **PDF Loading** via LangChain’s PyPDFium2Loader  
2. **Text Splitting** into overlapping chunks for better context  
3. **Embeddings** with OpenAI (or another provider)  
4. **Vector Storage & Retrieval** for lightning‑fast similarity search  
5. **LLM QA** that generates clear, concise answers  
6. **Gradio UI** so anyone can try it in their browser  

---

## ▶️ Demo

<video controls width="600" src="https://raw.githubusercontent.com/ssccddaasa/QA-bot/main/asset_video.mp4">
  Your browser does not support the video tag.
</video>


---

## 🛠️ Installation & Usage

1. **Clone the repo**  
   ```bash
   git clone https://github.com/ssccddaasa/QA-bot.git
   cd QA-bot
