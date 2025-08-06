🧠 Voice-Based Arabic Chatbot – "Al-Musaed Al-Thaki" (المساعد الذكي)
Al-Musaed Al-Thaki is an Arabic-speaking voice assistant built using advanced AI technologies like Cohere (for smart responses) and ElevenLabs (for natural voice generation). It listens, understands, and replies in Saudi dialect, all in real time.

💡 Features
🎤 Real-time Arabic Speech Recognition
🧠 Smart AI responses using Cohere
🔊 Natural voice replies with ElevenLabs TTS
💬 Speaks in Saudi dialect only
🌐 WebSocket-based communication with frontend

🛠️ Tech Stack
Python + Flask + Flask-SocketIO
Cohere API (LLM for Arabic)
ElevenLabs API (TTS)
RealtimeSTT (for speech recognition)
HTML/CSS/JS (Frontend not included)

🧪 How to Run
Install dependencies:
pip install flask flask-socketio flask-cors cohere elevenlabs RealtimeSTT scipy

Replace API keys in chatbot.py:
cohere.Client(...)
ElevenLabs(api_key=...)

Run the app:
python chatbot.py

🔁 How It Works
User speaks Arabic.
Audio is transcribed in real-time using RealtimeSTT.
Final text is sent to Cohere to generate a response.
Response is converted to voice using ElevenLabs and played.

🧠 Assistant Identity
Speaks only in Saudi dialect
Gives concise and friendly answers
Introduces itself as: "Al-Musaed Al-Thaki"
Created by: Aalya Ammar Nahhas
