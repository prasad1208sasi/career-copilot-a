# 🎯 AI Career Advisor – Gemini Powered Chatbot

An intelligent AI Career Guidance Assistant built using **Streamlit + Google Gemini API**.  
This application helps students and professionals discover the right career path, identify in-demand skills, and generate a structured learning roadmap through an interactive chat interface.

🔗 **Live Demo:** https://huggingface.co/spaces/prasad799596/genai-career-copilot

---

## 🚀 Project Overview

This project simulates a real-world AI career mentor that:

- Suggests the best career paths based on user goals
- Recommends job-ready skills
- Generates step-by-step learning roadmaps
- Provides resume and portfolio guidance
- Shares current industry trends

Built with a production-level approach including error handling, secure key management, and multi-turn memory.

---

## ✨ Key Features

- 💬 Multi-turn conversation memory
- 🎯 Domain-restricted career guidance
- 🛠 Personalized roadmap generation
- ⚠️ API quota graceful error handling
- 🔐 Secure Gemini API integration using Hugging Face Secrets
- 🧹 One-click clear chat
- 🚀 Live deployment on Hugging Face Spaces

---

## 🏗️ Tech Stack

- **Python**
- **Streamlit**
- **Google Gemini API**
- **Hugging Face Spaces**

---

## 📂 Project Structure

app.py  
requirements.txt  
README.md  

---

## 🌐 Deployment (Hugging Face Spaces)

This project is deployed using **Streamlit SDK on Hugging Face Spaces**.

### Steps:

1. Create a new Streamlit Space
2. Upload the project files
3. Add the API key in:

Settings → Secrets

GOOGLE_API_KEY = your_api_key

The app will automatically build and run 🚀

---

## 🤖 How It Works

- Gemini model is initialized using a cached client for better performance
- Custom system prompt ensures responses are career-focused
- Streamlit session state stores chat history
- Try–except block handles API limits without crashing the app

---

## 🎯 Use Cases

- Students exploring career options
- Freshers preparing for placements
- Career switchers into Data / AI roles
- Learners who need a structured roadmap

---

## 🏆 Production-Ready Highlights

✔ Clean and modular architecture  
✔ Secure secret management  
✔ Graceful error handling  
✔ Scalable deployment  
✔ Real-world chatbot design  

---

## 🔮 Future Enhancements

- 📄 Download career roadmap as PDF  
- 📊 Skill gap analyzer  
- 🧾 Resume reviewer  
- 👤 Personalized career planning form  
- 🔎 RAG with real job market data  

---

## 👨‍💻 Author

**Bejjanki Venkata Siva Prasad**  
Aspiring Data Analyst | GenAI Enthusiast  

---

## ⭐ Support

If you like this project, give it a star ⭐ and share your feedback!
