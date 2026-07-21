# AI
Projects
# 🤖 AI Customer Support Chatbot using RAG, FAISS & Google Gemini

## 📌 Project Overview

This project is an AI-powered Customer Support Chatbot built using **Retrieval-Augmented Generation (RAG)**. It retrieves the most relevant company information using semantic search with **FAISS** and **Sentence Transformers**, then generates accurate, context-aware responses using the **Google Gemini API**.

The application includes a modern **Streamlit** web interface for an interactive chatbot experience.

---

## 🚀 Features

* AI-powered Customer Support Chatbot
* Retrieval-Augmented Generation (RAG)
* Semantic Search using FAISS
* Google Gemini API Integration
* Sentence Transformer Embeddings
* Interactive Streamlit Chat Interface
* Top-3 Document Retrieval
* Context-Aware Responses
* Fast and Lightweight

---

## 🛠️ Technologies Used

* Python
* Streamlit
* Google Gemini API
* FAISS
* Sentence Transformers
* NumPy
* Pickle

---

## 📂 Project Structure

AI-Customer-Support-Chatbot-RAG/

├── app.py

├── rag2.py

├── build_index.py

├── documents.txt

├── documents.pkl

├── faiss_index.bin

├── requirements.txt

├── README.md

└── screenshots/

---

## ⚙️ How It Works

1. User enters a question.
2. The question is converted into an embedding using Sentence Transformers.
3. FAISS retrieves the most relevant company documents.
4. The retrieved documents are used as context.
5. Google Gemini generates an accurate answer.
6. Streamlit displays the response in a chat interface.

---

## 📸 Sample Questions

* What are the office hours?
* How can I reset my password?
* What is the refund policy?
* How long does delivery take?

---

## 💻 Installation

Clone the repository

git clone https://github.com/yourusername/AI-Customer-Support-Chatbot-RAG.git

Move into the project folder

cd AI-Customer-Support-Chatbot-RAG

Install dependencies

pip install -r requirements.txt

Add your Gemini API Key as an environment variable.

Run the application

streamlit run app.py

---

## 🎯 Future Improvements

* PDF Document Upload
* Multiple Knowledge Bases
* Conversation Memory
* Voice Support
* Chat History Export
* Source Citation Display
* Docker Deployment
* Cloud Deployment

---

## 📷 Demo

Add screenshots of your chatbot interface in the **screenshots** folder.

---

## 👩‍💻 Author

**Rama Jaladhani**

M.Sc. Data Science

Aspiring Data Analyst & Generative AI Engineer


⭐ If you found this project useful, please consider giving it a Star!
