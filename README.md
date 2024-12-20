#### TASK1
## RAG Pipeline for Chatting with PDFs

This repository implements a Retrieval-Augmented Generation (RAG) pipeline that allows users to interact with semi-structured data in multiple PDF files.

### Project Overview

The system performs the following tasks:

1. **Data Ingestion:**

2. **Query Handling:**

3. **Comparison Queries:**

4. **Response Generation:**

### Dependencies

* Python 3.x
* Libraries (to be specified based on your chosen implementations):
    - PDF parsing (e.g., PyPDF2)
    - Text chunking (e.g., spaCy)
    - Text embedding (e.g., SentenceTransformers)
    - Vector database (e.g., Faiss, Pinecone)
    - Large Language Model (e.g., transformers)
 
#### TASK2
## RAG Pipeline for Chatting with Websites

This repository implements a Retrieval-Augmented Generation (RAG) pipeline enabling users to interact with website data.

### Project Overview

The system performs the following tasks:

1. **Data Ingestion:**
    - Crawls and scrapes content from specified websites.
    - Extracts key data, metadata, and text.
    - Segments content into manageable chunks.
    - Embeds chunks using a pre-trained model.
    - Stores embeddings and metadata in a vector database.
2. **Query Handling:**
    - Embeds user queries.
    - Retrieves relevant chunks using similarity search.
    - Passes retrieved chunks and prompts to the LLM for response generation.
3. **Response Generation:**
    - Uses the LLM with retrieval-augmented prompts to generate accurate and context-rich responses.

### Dependencies

* Python 3.x
* Libraries (to be specified based on your chosen implementations):
    - Web crawling/scraping (e.g., Scrapy, Beautiful Soup)
    - Text chunking (e.g., spaCy, NLTK)
    - Text embedding (e.g., SentenceTransformers, OpenAI Embeddings)
    - Vector database (e.g., Faiss, Pinecone, Chroma)
    - Large Language Model (e.g., transformers, OpenAI API)

      
![WhatsApp Image 2024-12-20 at 13 21 39_d44f7ee7](https://github.com/user-attachments/assets/487244bd-4189-45bb-a90c-bcc2b6a94b0d)
