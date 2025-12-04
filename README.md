# StoryGen: Image to Audio Story

Hey! This is a project I built to turn memories into magical stories. You just drop in some photos, pick a vibe (like "Fairy Tale" or "Sci-Fi"), and it uses AI to write a story and narrate it back to you.

It's built using **React** for the frontend and **FastAPI** for the backend, powered by Google's **Gemini 2.5 Flash** model.

## What it does

- **Visual Storytelling:** U# 🎙️ StoryGen — Image-to-Speech GenAI Tool  
_transform your memories into magical narrated stories_

![GitHub Repo Size](https://img.shields.io/github/repo-size/Arundhuti2000/Image-to-Speech-GenAI-Tool-Using-LLM?color=blue)
![GitHub License](https://img.shields.io/github/license/Arundhuti2000/Image-to-Speech-GenAI-Tool-Using-LLM?color=brightgreen)
![GitHub Last Commit](https://img.shields.io/github/last-commit/Arundhuti2000/Image-to-Speech-GenAI-Tool-Using-LLM)
![GitHub Stars](https://img.shields.io/github/stars/Arundhuti2000/Image-to-Speech-GenAI-Tool-Using-LLM?style=social)

---

## 🌟 Overview

**StoryGen** is an AI-powered web application that turns your **images into narrated audio stories**.  
Upload multiple images → choose a style + voice → let Gemini **write & narrate** a story for you.

Built with:

- 🎨 **React + Vite + Tailwind CSS** (Frontend)  
- ⚡ **FastAPI** (Backend)  
- 🤖 **Google Gemini 2.5 Flash** (Story Generation)  
- 🔊 **Gemini Flash TTS** (Text-to-Speech)

Perfect for:
- Travel memories  
- Childhood photos  
- Creative story writing  
- Audiobook-style narration  
- Fun multimedia projects  

---

## ✨ Features

- 📸 Upload multiple images  
- 🧠 AI-generated story using Gemini 2.5 Flash  
- 🔊 Natural TTS narration  
- 🎭 Choose story style (Creative, Fantasy, Thriller, etc.)  
- 🗣️ Choose different narrator voices  
- 🌐 Supports multiple languages (English, Spanish, Hindi…)  
- 💾 Automatic History saving (JSON + WAV)  
- 🎧 Built-in audio player  
- 🚀 Modern clean UI

---

---

## 📂 Project Structure

Image-to-Speech-GenAI-Tool-Using-LLM/
│
├── backend/
│ ├── main.py
│ ├── requirements.txt
│ ├── venv/
│ └── history/ (auto-created)
│
├── frontend/
│ ├── src/
│ ├── package.json
│ └── vite.config.js
│
├── .env
├── LICENSE
└── README.md

---

## 🔧 Backend Setup (FastAPI)

### 1️⃣ Create Python Virtual Environment

```bash
cd backend
python3 -m venv venv
source venv/bin/activate
Your terminal prompt should show:
(venv)
2️⃣ Create requirements.txt
fastapi
uvicorn[standard]
python-multipart
pydantic
pillow
google-generativeai
python-dotenv
Install dependencies:
python -m pip install --upgrade pip
python -m pip install -r requirements.txt
3️⃣ Add Your API Key (.env file)
Create .env in the project root (NOT inside backend):
GOOGLE_API_KEY=your_actual_gemini_api_key_here
4️⃣ Run Backend Server
cd backend
source venv/bin/activate
python -m uvicorn main:app --reload --reload-exclude 'venv/*'
Backend available at:
http://127.0.0.1:8000
http://127.0.0.1:8000/docs (Swagger API)
🎨 Frontend Setup (React + Vite)
Open a new terminal window:
cd frontend
npm install
npm run dev
Frontend available at:
👉 http://localhost:5173/


📜 License
This project is licensed under the MIT License.
MIT License

Copyright (c) 2024

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND.

❤️ Acknowledgements
Google Gemini 2.5 Flash
FastAPI
React + Vite
Tailwind CSS

⭐ Support the Project
If you found this useful:
Star the repo ⭐
Share it
Fork and contribute