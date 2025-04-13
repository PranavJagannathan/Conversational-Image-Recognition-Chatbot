# IQMath Technologies - Conversational-Image-Recognition-Chatbot
This project is a lightweight AI-powered chatbot that can analyze images and answer questions about them. It combines Flask, Google Gemini 1.5 Flash, and a simple HTML frontend, with public hosting enabled using ngrok. **This Project is done by Pranav J, Litin S, Mohanraj M.**
# 🛠️ Tech Stack
Backend: Python + Flask (running on Google Colab)

Frontend: HTML, CSS, JavaScript (no frameworks)

AI Model: **Google Gemini 1.5 Flash** (via Generative AI API)

Public URL Exposure: **ngrok **(tunnel Colab backend to web)

🚀 Features
Upload an image from your device 📷

Ask natural language questions about the uploaded image

Gemini processes both the image and the question to generate a smart response

Chat-like interface with real-time question/answer updates

Accessible through a public ngrok link, so no need for deployment

🌐 How It Works
A simple HTML file serves as the chatbot interface.

User uploads an image and asks a question.

The image and message are sent to the Flask server.

Flask uses the Google Gemini API to analyze both inputs.

Gemini responds with intelligent analysis.

Flask returns this response back to the frontend.

All this happens live via a public ngrok URL generated in Colab.

🔧 Public Hosting with ngrok
The app is hosted using ngrok, which exposes your Colab-based Flask server to the public internet.
