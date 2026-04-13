# Chatbot Assignment 1

A simple AI chatbot web application built with JavaScript, Python, and Flask.

## Purpose

This application allows users to chat with a locally running AI model through a clean web interface — no internet connection required.

## Technologies Used

- HTML / CSS / JavaScript
- Bootstrap 5
- Python & Flask
- Ollama
- DeepSeek-R1:8b

## How to Run

1. Install [Python](https://www.python.org/downloads/) and [Ollama](https://ollama.com/download)
2. Download the AI model:
   ```
   ollama pull deepseek-r1:8b
   ```
3. Install dependencies:
   ```
   pip install flask requests
   ```
4. Start Ollama in one terminal:
   ```
   ollama serve
   ```
5. Run the app in another terminal:
   ```
   python app.py
   ```
6. Open your browser and go to `http://127.0.0.1:5000`
