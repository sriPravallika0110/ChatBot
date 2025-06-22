# ChatBot
This is a simple yet powerful Generative AI-powered chatbot that allows users to upload PDF documents and ask questions about their content. Built using Streamlit, LangChain, and Hugging Face Transformers, the chatbot performs intelligent document understanding by combining semantic search with text generation models.

# 🚀 Features
📄 Upload and parse PDFs
Extracts and processes text content from uploaded PDF files.

🔍 Chunking and Embedding
Splits the PDF content into logical text chunks and creates embeddings using Hugging Face sentence transformers.

🧠 Vector Search with FAISS
Performs semantic similarity search to find relevant chunks for each user question.

🤖 Question Answering with Hugging Face Models
Uses google/flan-t5-base to generate answers based on retrieved context.

🧪 Streamlit Interface
Interactive and user-friendly web app for uploading PDFs and asking questions.

# 🛠️ Tech Stack
LangChain – for chaining together embedding search and LLM reasoning

Hugging Face Transformers – for text2text generation models like FLAN-T5

FAISS – for fast vector similarity search

Streamlit – for building the web interface

PyPDF2 – for reading PDF content

# 📦 Setup Instructions

git clone https://github.com/your-username/genai-pdf-chatbot.git

cd genai-pdf-chatbot

pip install -r requirements.txt

streamlit run chatbot.py

You may need a Hugging Face token if using HuggingFaceHub.

