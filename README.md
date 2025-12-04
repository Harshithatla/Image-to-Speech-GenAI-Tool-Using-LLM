<h1 align="center">🖼️🔊 Image-to-Speech GenAI Tool</h1>

<p align="center">
  Convert images into natural speech using modern multimodal AI models and a robust backend pipeline.
</p>

---

<<div align="center">

<!-- BACKEND -->
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">
<img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white">
<img src="https://img.shields.io/badge/Gemini%20API-4285F4?style=for-the-badge&logo=google&logoColor=white">

<!-- FRONTEND -->
<img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white">
<img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB">
<img src="https://img.shields.io/badge/TailwindCSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white">

<!-- PLATFORM -->
<img src="https://img.shields.io/badge/macOS-000000?style=for-the-badge&logo=apple&logoColor=white">

<!-- REPO STATUS -->
<img src="https://img.shields.io/github/issues/Harshithatla/Image-to-Speech-GenAI-Tool-Using-LLM?style=for-the-badge&color=yellow">
<img src="https://img.shields.io/github/license/Harshithatla/Image-to-Speech-GenAI-Tool-Using-LLM?style=for-the-badge&color=blue">

<!-- AESTHETIC -->
<img src="https://img.shields.io/badge/Made%20With%20❤️-FF3366?style=for-the-badge">

</div>

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
