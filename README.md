AI Healthcare Chatbot

Overview
This project is an AI-powered healthcare chatbot designed to answer medical-related queries using reliable document-based information. It addresses the challenge of users struggling to find specific and verified medical answers by combining retrieval and generation techniques.

Problem
People struggled to get specific medical questions answered and could not find reliable or verified resources for their medical-related queries.

Solution
The system uses a Retrieval-Augmented Generation (RAG) approach to retrieve relevant information from medical documents and generate accurate, context-aware responses. It ensures that answers are grounded in trusted data rather than relying solely on generative models.

Features

Context-aware medical question answering
Semantic search using vector embeddings
Retrieval of relevant document chunks
Safe and structured response generation
Interactive web interface for real-time queries

Tech Stack

Python
pandas, NumPy
FAISS
sentence-transformers
LangChain
Google Generative AI (Gemini)
Streamlit
Google Colab

How It Works

Medical documents are collected and preprocessed
Text is split into chunks and converted into embeddings
Embeddings are stored in a FAISS vector database
User query is embedded and matched with relevant document chunks
Retrieved context is passed to the language model
The model generates a final, context-aware response

Results

Built an end-to-end AI chatbot system
Improved response relevance using retrieval-based grounding
Provided reliable and easy-to-understand medical information
Demonstrated practical use of NLP, embeddings, and LLMs

Dataset Note
Due to large file size, the full dataset and vector database are stored externally and are not included in this repository.

Future Improvements

Integration with APIs for real-time medical data
Deployment as a scalable web application
Enhanced evaluation metrics for response accuracy
Support for multilingual queries
