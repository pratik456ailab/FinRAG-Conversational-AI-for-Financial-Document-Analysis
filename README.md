# 📄 FinRAG – Conversational AI for Financial Documents
## 📌 Overview

FinRAG is a Conversational Retrieval-Augmented Generation (RAG) system that allows users to interact with financial PDF documents—such as CIBIL credit reports—using natural language.
The system combines semantic search, vector databases, and LLMs to deliver accurate, context-aware answers while supporting multi-turn conversations.

## 🚀 Key Features

 - Upload and process financial PDF documents (CIBIL reports)

 - Intelligent text chunking for optimal context preservation

 - Semantic embeddings for meaning-based retrieval

 - Vector search using ChromaDB and FAISS

 - Conversational memory for follow-up queries

- Interactive Streamlit web interface

## 🏗️ System Architecture

PDF Documents
      ↓
Text Extraction
      ↓
Text Chunking
      ↓
Embeddings (OpenAI)
      ↓
Vector Store (ChromaDB / FAISS)
      ↓
Retriever
      ↓
LLM + Conversational Memory
      ↓
Context-Aware Answers


## 🛠️ Tech Stack

- Language: Python

- Framework: LangChain

- Embeddings: OpenAI Embeddings

- Vector Databases: ChromaDB, FAISS

- LLM: OpenAI Chat Models

- UI: Streamlit

- Architecture: Retrieval-Augmented Generation (RAG)


## 🧪 How It Works

- User uploads one or more financial PDF documents.

- Text is extracted and split into overlapping chunks.

- Each chunk is converted into vector embeddings.

- Embeddings are stored in a vector database for semantic search.

- User queries retrieve the most relevant document chunks.

- The LLM generates grounded answers using retrieved context and conversation history.

## ScreenShots Of Output

--
<img width="1366" height="627" alt="Screenshot (89410)" src="https://github.com/user-attachments/assets/45f4fd8f-f1d4-4f5c-9e60-9d3f8d0d2562" /> 

--
<img width="1363" height="641" alt="Screenshot (89411)" src="https://github.com/user-attachments/assets/1d61da7f-0d89-414b-9375-ff060b65f1c1" />

--
<img width="1365" height="625" alt="Screenshot (89416)" src="https://github.com/user-attachments/assets/b7d8e56d-d83f-4e02-bb88-a23ae001e047" />

--
<img width="1362" height="591" alt="Screenshot (89508)" src="https://github.com/user-attachments/assets/ba3afa1f-845b-4b35-93d8-76d3233d9214" />

--
<img width="1363" height="589" alt="Screenshot (89509)" src="https://github.com/user-attachments/assets/b1ef0d84-f697-4975-80ef-ae7819287602" />

--

## ⭐ Why This Project Matters

FinRAG demonstrates a real-world application of RAG and LLMs for financial document intelligence, showcasing skills in  vector databases, conversational AI, and production-ready AI systems.


