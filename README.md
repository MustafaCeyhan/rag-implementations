# Retrieval-Augmented Generation (RAG) Implementations

This repository contains various implementations of Retrieval-Augmented Generation (RAG) techniques using LlamaIndex and OpenAI models. Each implementation explores a different approach to enhance information retrieval and generation capabilities. Different rag implementations from different frameworks, VectorDBs and models will be added regularly.

## 📂 RAG Types

The following types of rags are currently available in the  repository:

1. **`vanilla-rag`**  
   - **Description**: A basic implementation of RAG using vector-based retrieval.  
   - **Key Features**:  
     - Simple document retrieval using embeddings.  
     - Integration with OpenAI's language models for query answering.

2. **`rerank-rag`**  
   - **Description**: RAG implementation with a reranking mechanism to improve retrieval quality.  
   - **Key Features**:  
     - Rewriting the query for better search
     - Uses a reranker (bi-encoder --> sentence-transformers/all-MiniLM-L6-v2) to prioritize retrieved documents.  
     - Enhanced accuracy for complex queries.

3. **`graph-rag`**  
   - **Description**: Graph-based RAG implementation that leverages knowledge graphs for retrieval.  
   - **Key Features**:  
     - Builds a knowledge graph from documents.  
     - Expands retrieval using graph relationships.

4. **`agentic-rag`**  
   - **Description**: Agent-based RAG implementation with tools for advanced reasoning.  
   - **Key Features**:  
     - Uses a ReAct agent to process queries.  
     - Integrates tools for document search and analysis.

