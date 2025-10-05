 RAG Pipeline
## 🧠 Task : 1 -> Interact with PDFs using AI and Retrieval-Augmented Generation (RAG)
This project demonstrates how to build a PDF chatbot that enables users to ask natural language questions and retrieve precise answers using AI-powered tools like LangChain, ChromaDB, and Ollama.


## 🚀 Features
📄 PDF Ingestion: Load and process semi-structured PDFs

🧩 Text Chunking: Split text into manageable chunks for better retrieval.

📊 Vector Database: Use ChromaDB for efficient similarity-based retrieval.

🤖 RAG Pipeline: Retrieve relevant chunks and pass them to an LLM (Llama3) for accurate answers.

🔍 Comparison Queries: Perform tabular or structured comparisons across PDF content.

## 🛠️ Tech Stack
LangChain: Framework for building the RAG pipeline.

Ollama: Local language model to generate responses.

ChromaDB: Vector database for storing and retrieving embeddings.

Python: Core programming language.

## 🧩 How It Works
Load PDF: Load and extract content using UnstructuredPDFLoader.

Split Text: Use RecursiveCharacterTextSplitter to chunk the text into logical pieces.

Create Embeddings: Convert the chunks into vector embeddings using Ollama’s embedding model.

Store in ChromaDB: Store the embeddings in Chroma for retrieval.

Query Handling: Accept user queries, retrieve relevant chunks, and generate responses using the LLM.

Comparison: Perform structured comparisons for specific queries.

## 🏗️ Installation Steps

1. Clone the repository:git clone https://github.com/kalyan936/RAG-CHAT-WITH_PDF/edit/main/README.md

2. Install all the required dependencies

3. Run the note book file in your visual studio code.


