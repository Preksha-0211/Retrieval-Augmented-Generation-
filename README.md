# Retrieval-Augmented Generation (RAG) System

This project implements a **Retrieval-Augmented Generation (RAG)** system using a combination of information retrieval techniques and large language models (LLMs). The RAG system improves the performance of LLMs by retrieving contextually relevant documents and using them as input to generate more accurate and context-aware responses.

## Features

- Combines document retrieval with large language models (LLMs).
- Uses ChromaDB as the vector store to handle document retrieval.
- Utilizes Langchain and Ollama libraries to interact with LLMs and generate responses based on retrieved documents.
- Supports splitting text for effective document processing using recursive text splitters.
- Embeddings generated using OllamaEmbeddings for document similarity calculation.

## Libraries and Dependencies

This project uses the following Python libraries:
- `bs4`: For web scraping and data extraction.
- `ollama`: For interacting with Ollama-based language models.
- `chromadb`: Vector database for handling document retrieval and similarity searches.
- `langchain`: To orchestrate the interaction between LLMs and the document retrieval system.
- `langchain_core`: Provides core components such as document structures, prompts, and output parsers.

## Contributions
Feel free to contribute by opening an issue or submitting a pull request. All contributions are welcome!
