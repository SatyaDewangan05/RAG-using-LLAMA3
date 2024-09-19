# LLaMa3-RAG Document Intelligence System

Website URL: https://satyadewangan05-rag-using-llama3-web-jeqers.streamlit.app/

This project implements a Retrieval-Augmented Generation (RAG) system using LLaMa3 and LlamaIndex, deployed with FastAPI and Streamlit. It enables efficient, user-friendly access to advanced AI-powered document retrieval and generation capabilities.

## Features

- Utilizes LLaMa3 for advanced natural language processing
- Implements efficient document indexing and semantic search using LlamaIndex
- FastAPI backend for robust API endpoints
- Streamlit frontend for an intuitive user interface
- Supports document upload and intelligent querying

## How to Use the App

Follow these steps to set up and use the application:

1. **Run the Colab Notebook**

   - [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1D2zLA3zKGckroaDruv2tIFh-t6g8ZJeQ?usp=sharing)

   - Open and run the provided Google Colab notebook
   - This will start the FastAPI backend and set up ngrok for public access

2. **Get the ngrok URL**

   - Look for the ngrok URL in the Colab notebook output
   - It should look something like `https://xxxx-xx-xx-xxx-xx.ngrok.io`

3. **Access the Streamlit Web Interface**

   - Open the Streamlit app in your web browser
   - Paste the ngrok URL into the designated input field on the sidebar

4. **Upload a Document**

   - Use the file upload feature in the Streamlit interface
   - Support file types include .txt, .pdf, and .docx (adjust as necessary for your implementation)

5. **Start Chatting**
   - Once your document is uploaded, you can start asking questions
   - The system will use the uploaded document as context for answering your queries

## Technical Details

- Backend: FastAPI
- Frontend: Streamlit
- AI Model: LLaMa3
- Vector Store: LlamaIndex
- Deployment: Google Colab with ngrok for public access

## Notes

- Ensure you have a stable internet connection while using the app
- The ngrok URL will change each time you run the Colab notebook
- For persistent deployment, consider using a cloud platform instead of Colab and ngrok

## Future Improvements

- Add support for multiple document uploads
- Implement user authentication for personalized experiences
- Enhance the UI with more interactive visualizations of the document retrieval process

For any issues or suggestions, please open an issue in this repository.
