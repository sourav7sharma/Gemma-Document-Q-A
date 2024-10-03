# Document Q&A Model

## Overview

This repository contains the implementation of a Document Q&A model developed during my internship at **Tcent AI**. The model leverages advanced technologies, including the **Gemma model**, to facilitate efficient information retrieval and enhance user interaction with documents.

## Key Features

- **Fast Similarity Search**: Utilizes **FAISS-CPU** for quick document retrieval.
- **Advanced Language Understanding**: Built on the **Gemma model** for improved comprehension.
- **PDF Document Parsing**: Efficiently extracts information from PDF files using **PyPDF2** and **PyPDF**.
- **Intuitive Web Interface**: Developed using **Streamlit** for user-friendly interaction.
- **Cloud Deployment**: Utilizes **Google Cloud AI Platform** to harness AI capabilities.

## Technologies Used

- **Gemma Model**
- **FAISS-CPU**
- **LangChain** & **LangChain-GROQ**
- **PyPDF2**
- **PyPDF**
- **Google Cloud AI Platform**
- **Streamlit**

**Install the required packages:**
**pip install -r requirements.txt**

**Create a .env file in the project root directory.**
**Add your GROQ API key and Google API key to the .env file:**
**GROQ_API_KEY=your_groq_api_key**
**GOOGLE_API_KEY=your_google_api_key**

**Start the Streamlit application:**
**streamlit run app.py**
