# PDF Upload and Chat App

This app allows you to upload a PDF document via a web interface and start chatting with the app. The backend is hosted using FastAPI on Google Colab, with Ngrok being used for reverse proxy.

## Features

- Upload a PDF document
- Process and chat with the app using the uploaded document

## Requirements

- Python 3.x
- FastAPI
- Streamlit
- Ngrok
- Google Colab

## How to Use

Follow these steps to get the app up and running:

### 1. Run the Colab

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1D2zLA3zKGckroaDruv2tIFh-t6g8ZJeQ?usp=sharing)

First, run the FastAPI backend on Google Colab. Follow these steps:

- Open the Colab notebook that contains the FastAPI backend code.
- Run all the cells to start the FastAPI server.

### 2. Get Ngrok URL

Once the Colab notebook is running, you will receive an Ngrok public URL (something like `https://xxxx.ngrok.io`). This URL will expose your FastAPI app to the internet.

### 3. Paste Ngrok URL to Web

On the frontend (using Streamlit or any other UI you have set up):

- Paste the Ngrok URL into the web app where required (usually in the URL endpoint for the FastAPI backend).

### 4. Upload a Document

- In the web app, choose a PDF document to upload via the provided uploader.

### 5. Start Chatting

- Once the document is uploaded, you can start interacting and chatting with the app based on the content of the uploaded PDF.

## Troubleshooting

- If you encounter a `400 Bad Request` error, ensure that CORS is enabled in your FastAPI backend.
- Ensure that the file size is within the limits allowed by Ngrok or FastAPI.

---

Enjoy using the app!
