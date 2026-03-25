# Rag Done Properly

## Goal

In this repository we explore different things about RAG (retrieval augmented generation)
Notebooks containing code and explanations on:

- Chunking
- Using custorm vector store using pgvector_rs
- A rag pipeline that answers questions over a set of documents
- A hybrid search using keyword search and vector search
- Reranking retrieved context to be passed to the llm

## Requirements

To interact with the data in the repo, you will need:

- jupyter lab installed
- postress running on your machine
- an env file with OPENAI_API_KEY in the parent folder of the current folder/directory
- llama_index installed
- python installed
