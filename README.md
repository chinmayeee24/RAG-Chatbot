# RAG-Chatbot
# ROP-RAG-Chatbot

## Overview

ROP-RAG-Chatbot is a Retrieval-Augmented Generation (RAG) based chatbot developed for answering questions related to Retinopathy of Prematurity (ROP) using research papers.

The chatbot extracts information from ROP research articles, converts the text into embeddings, stores them in a FAISS vector database, and retrieves the most relevant information in response to user queries.

## Features

* PDF document ingestion
* Text extraction using PyPDF
* Text chunking using LangChain
* Embedding generation using Sentence Transformers
* Vector similarity search using FAISS
* Question answering based on ROP research papers
* Interactive query processing

## Technology Stack

* Python
* Google Colab
* PyPDF
* LangChain Text Splitters
* Sentence Transformers
* FAISS
* NumPy

## Workflow

1. Upload ROP research paper PDF.
2. Extract text from the document.
3. Split text into manageable chunks.
4. Generate embeddings for each chunk.
5. Store embeddings in FAISS.
6. Convert user query into embeddings.
7. Retrieve relevant chunks using similarity search.
8. Display the retrieved information as the answer.

## Example Query

Question:
What is Plus Disease in ROP?

Output:
The system retrieves the most relevant sections from the research paper discussing Plus Disease, its characteristics, and its significance in disease progression.

## Future Enhancements

* Integration with Gemini API or other LLMs
* Streamlit web interface
* Support for multiple research papers
* Conversational memory
* Medical answer summarization


