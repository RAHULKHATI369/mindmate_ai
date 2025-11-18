# mindmate_ai
🧠 MindMate AI
A gentle LLM-powered mental health companion

Built with Flask + React + Transformers

MindMate AI is a simple yet powerful mental-health support assistant.
It provides emotionally aware responses using a mini-LLM and a real-time sentiment detector.

⭐ Features

🧠 AI Chat using LLM (OpenAI / Local model option)

❤️ Emotion detection (DistilBERT sentiment model)

🎨 Clean, responsive UI (Vite + React)

🔐 API key protected backend

⚡ Fast lightweight architecture

🌍 Ready for deployment (Render / Vercel / Railway / VPS)

📁 Folder Structure
mindmate_ai/
│
├── backend/
│   ├── app.py
│   ├── llm_logic.py
│   ├── emotion_model.py
│   ├── requirements.txt
│   └── .env
│
└── frontend/
    ├── src/
    ├── public/
    ├── package.json
    └── vite.config.js

🔧 Installation & Running (Local Machine)
1️⃣ Backend Setup
cd backend
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt


Create .env:

OPENAI_API_KEY=your_key_here


Run server:

python3 app.py

2️⃣ Frontend Setup
cd frontend
npm install
npm run dev


Production build:

npm run build

🚀 Full Production Deployment
🔵 Backend (Render / Railway / VPS)

Upload entire backend/

Add ENV: OPENAI_API_KEY

Start command:

python3 app.py

🟣 Frontend (Vercel / Netlify)

Deploy /frontend

Build command:

npm run build


Output folder:

dist

🤝 Contributing

Pull requests are welcome.
If you want to add new features (emotion chart, voice chat), open an issue.

📜 License

MIT License.
