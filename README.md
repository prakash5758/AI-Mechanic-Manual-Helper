# AI-Mechanic-Manual-Helper

📌 Project Overview

This project implements Retrieval-Augmented Generation (RAG) to provide intelligent query responses from mechanical client manuals. It leverages large language models (LLMs) like Falcon and LLaMA along with vector databases like Pinecone and in-memory storage to enhance information retrieval and response accuracy.

🎯 Key Features

Intelligent Query Handling: Uses LLMs to generate precise responses based on mechanical manuals.

Vector Database Search: Pinecone and in-memory vector storage for efficient retrieval.

Multi-Model Support: Works with Falcon and LLaMA models for diverse responses.

Optimized Indexing: Efficient chunking and embedding of mechanical manuals.

🏗️ Project Architecture

Document Ingestion: Load and preprocess mechanical manuals (PDF, text, etc.).

Embedding Generation: Convert documents into embeddings using an NLP model.

Vector Storage: Store embeddings in Pinecone and in-memory DB.

Query Processing: User queries are embedded and searched in the vector database.

LLM Response Generation: The retrieved text is fed into Falcon/LLaMA to generate responses.

⚙️ Tech Stack

LLMs: Falcon, LLaMA

Vector Database: Pinecone, In-Memory

Embedding Models: Sentence Transformers (BERT, OpenAI Embeddings, etc.)

Frameworks: LangChain, Hugging Face, OpenAI API

Languages: Python
