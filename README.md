🎙️ Ten Days of Voice Agents — Day 1
AI Voice Agent Challenge (Murf Falcon + LiveKit)

Welcome to my submission for Day 1 of the 10 Days of Voice Agents Challenge powered by Murf.ai Falcon TTS + LiveKit.
This repository contains:

✔ Fully working Backend (Python + LiveKit Agents)
✔ Fully working Frontend (Next.js + LiveKit React SDK)
✔ Integrated Murf Falcon TTS, Deepgram STT, Google Gemini LLM
✔ Ready to run locally

🚀 Project Setup
1️⃣ Clone this repository
git clone https://github.com/SaloniSsSaini/ten-days-of-voice-agents-2025Day1.git
cd ten-days-of-voice-agents-2025Day1

🧩 Backend Setup (LiveKit + Murf Falcon)
cd backend

✔ Dependencies Install:
uv sync

✔ Create .env file:

In backend/.env add:

LIVEKIT_URL=wss://<your-livekit-project>.livekit.cloud
LIVEKIT_API_KEY=YOUR_KEY
LIVEKIT_API_SECRET=YOUR_SECRET

GOOGLE_API_KEY=YOUR_GOOGLE_KEY
MURF_API_KEY=YOUR_MURF_FALCON_KEY
DEEPGRAM_API_KEY=YOUR_DEEPGRAM_KEY

✔ Download required models:
uv run python src/agent.py download-files

✔ Run Backend:
uv run python src/agent.py dev

🖥️ Frontend Setup (Next.js + LiveKit)
cd frontend
pnpm install

✔ Create .env.local
NEXT_PUBLIC_LIVEKIT_URL=wss://<your-livekit-project>.livekit.cloud
NEXT_PUBLIC_LIVEKIT_API_KEY=YOUR_KEY
SANDBOX_ID=

✔ Run Frontend
pnpm dev


Open:
👉 http://localhost:3000

▶️ Full App Run (Alternative)

You can also run everything from root:

chmod +x start_app.sh
./start_app.sh


This will start:

LiveKit server

Backend agent

Frontend interface

🏆 Challenge Info

This voice agent includes:

✔ Murf Falcon TTS (Ultra-Fast Voice)
✔ LiveKit Turn Detection
✔ Realtime Voice Interaction
✔ Custom Personas
✔ Background Audio Cancellation
✔ Complete backend + frontend integration

📸 Screenshots

(Add your screenshots here later if needed)

📢 Connect

If you have questions or want to collaborate, feel free to reach out!
Also follow my journey on LinkedIn for daily updates.

📜 License

This project uses licenses from the Murf Falcon + LiveKit starter frameworks.

❤️ Thanks!

Excited for the next 9 days of AI Voice Agents 🚀
