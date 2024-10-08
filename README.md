# 📄 Simple Invoice Extraction RAG Application

This repository contains a Retrieval-Augmented Generation (RAG) application for extracting data from invoices using the Hugging Face embedding models, LangChain framework, FAISS vector database, and Llama 2 hosted on a local server.

## ✨ Features

- **Information Retrieval**: Extract relevant and structured information from semi-structured invoice PDFs using advanced Optical Character Recognition (OCR) techniques.
- **Semantic Embeddings**: Leverage Hugging Face's transformer-based embeddings for contextualized semantic search, enabling nuanced understanding of natural language queries.
- **High-Dimensional Vector Search**: Utilize FAISS (Facebook AI Similarity Search) for efficient storage and retrieval of high-dimensional vectors, optimizing nearest neighbor searches in large datasets.
- **Conversational AI Interface**: Integrate with Llama 2 to generate human-like responses through contextual reasoning, enhancing the user experience in dialogue-based interactions.

## 🛠 Technologies Used

- **Hugging Face Transformers**: For embeddings and model handling.
- **LangChain**: To create the RAG framework.
- **FAISS**: For fast similarity search and retrieval.
- **Llama 2**: To generate responses based on extracted data.
- **Python**: The programming language used.

## 📊 Demo

### 📜 Sample Invoice

![image](https://github.com/user-attachments/assets/26d9dafc-e838-4aac-9511-a2a2f1941e38)
### ❓ Query Examples

- "What is the invoice number?"
- "What is the invoice date?"
- "What is the due date?"
- "Give me the complete bill-to address."
- "What is the amount paid?"
- "What is the product in the line item?"


### 💬 Response

![Response Example](https://github.com/user-attachments/assets/7b4ad108-c137-4bf7-b879-50b58fe83886)

