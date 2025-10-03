# 🤖 AI Agent with Semantic Kernel + ChromaDB (RAG)

This project implements an **AI Agentic System** using **Semantic Kernel** and **GPT-4o-mini**, enhanced with **Retrieval-Augmented Generation (RAG)** powered by **ChromaDB**. The agent provides **real-time, context-aware assistance** by retrieving relevant documents, augmenting user queries, and generating precise interactive responses.  

## ✨ Features
- ⚡ **Real-time AI agent** built with Semantic Kernel and GPT-4o-mini  
- 📚 **Retrieval-Augmented Generation (RAG)** using ChromaDB for contextual answers  
- 🧩 **Modular plugins** for gesture actions, library details, and code snippets  
- 💬 **Streaming chat interface** with async memory and function-call handling  
- 🔧 Extensible design for integrating new domains, tasks, and knowledge bases  

## 🏗️ Tech Stack
- **Language Model**: GPT-4o-mini  
- **Framework**: Semantic Kernel  
- **Database**: ChromaDB (vector store for RAG)  
- **Libraries**: AsyncIO, PyAutoGUI, MediaPipe, FaceNet (for gesture system integration)  
- **Interface**: Streaming chat with HTML output  

## 📂 Project Structure
├── app.py # Main agent loop with streaming interface
├── plugins/ # Modular plugins
│ ├── GesturePromptPlugin.py
│ ├── GestureCodePlugin.py
│ ├── GestureActionPlugin.py
│ ├── LibraryInfoPlugin.py
├── chroma_db/ # Persistent ChromaDB storage
├── requirements.txt # Python dependencies
└── README.md # Project documentation
