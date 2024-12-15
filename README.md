# RAG-Question-Answering-System

This project processes PDF files by extracting text, splitting it into manageable chunks, and enabling question-answering using Groq with Pinecone as the vector database.
Features
File Upload: Upload and process multiple PDF files.
Text Extraction: Extracts text content from PDFs using PyPDFLoader.
Text Splitting: Divides text into chunks with customizable size (1000 characters) and overlap (100 characters).
LLM Integration: Uses Groq (ChatGPT-like LLM) for answering user questions based on the uploaded content.
Vector Database: Leverages Pinecone to index and store vector embeddings for efficient semantic search.
Prompt-based Q&A: Allows users to ask questions through a prompt section and retrieves accurate answers using the LLM.
