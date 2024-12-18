# Summarization Architecture

![Summarization](https://github.com/Masoudrzpn/PDF_Summarization_Query_LLM/assets/91149593/962aec7c-8436-4471-8bf6-18f0cdd4f987)

# Overview
Explore your PDF application using Langchain, ChromaDB, Sentence Transformers, and the LaMiNi LM Model for searching, along with the T5 model for summarization. This application operates entirely on Open Source Models, eliminating the need for an OpenAI key. Users can effortlessly upload PDF files and obtain answers to their queries by assessing the similarity between the contents and the query. Additionally, the app leverages advanced language models to generate summaries of document content, making the process of summarizing lengthy documents seamless with the capabilities of natural language processing!

# Features
* **Summarization:** The app uses the T5 language model from Hugging Face Transformers to create excellent summaries of PDFs.
* **Optimization:** The app uses the langchain library to manage text splitting and document loading for PDFs.

# Getting Started
1. Implement _PDF_Summarization_Query_LLMs.ipynb_ in your Google Colab.
2. Upload your PDF file by changing the location of your PDF file.

# Requirments
* langchain
* sentence_transformers
* TensorFlow
* transformers
* chromadb
* PyPDF2
