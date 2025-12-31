# LangChain RAG – Static Document Example (Google Colab)
This project demonstrates a basic Retrieval-Augmented Generation (RAG) pipeline using LangChain and HuggingFace models in Google Colab.
The notebook uses a sample text document created inside the code and answers a fixed set of predefined questions to show how a RAG system works step-by-step.

## What This Project Does :
The notebook implements a simple, educational RAG workflow:
1.Creates a sample text document programmatically
2.Loads the document using LangChain
3.Splits the text into chunks
4.Converts text chunks into embeddings
5.Stores embeddings in a vector database (ChromaDB)
6.Retrieves relevant chunks
7.Generates answers to predefined questions

## Technologies Used

```md
LangChain
HuggingFace Transformers
Sentence Transformers
ChromaDB
Google Colab
FLAN-T5 (local LLM)
