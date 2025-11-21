# FikraFinder
FikraFinder: An AI-powered business intelligence agent for the Lebanese market. Built with Flutter, Python (FastAPI), and Hugging Face. Features real-time location analysis, strategic roadmap generation, and a multilingual voice assistant (AR/EN/FR).
🚀 FikraFinder: AI Business Co-Pilot for Lebanon

FikraFinder is a cross-platform mobile application designed to empower entrepreneurs in Lebanon. By leveraging Generative AI and real-time market data, it acts as a virtual business consultant, helping users validate ideas, analyze locations, and generate strategic roadmaps in English, French, and Arabic.

📱 Project Overview

In the current economic landscape of Lebanon, reliable market data is scarce and expensive. FikraFinder democratizes access to business intelligence.

Key Features:

📍 Location Analyst: Analyzes specific neighborhoods (e.g., Hamra, Batroun) to determine the feasibility of a business idea based on competition and foot traffic.

🗺️ Visual Roadmap: Generates a 12-month, step-by-step execution plan (Legal, Branding, Launch) visualized as an interactive tree.

💡 Idea Ranker: Suggests the top 3 business opportunities for a specific location based on market gaps.

🤖 Fikra Agent: A voice-enabled, multilingual chatbot capable of answering complex business queries.

🌍 Multilingual: Full support for Arabic, English, and French with RTL layout support.

🛠️ Tech Stack & Architecture

This project utilizes a 3-Tier Architecture to ensure scalability and performance.

1. Frontend (Mobile App)

Framework: Flutter (Dart)

UI Style: Modern "Creative Friendly" aesthetic using Cupertino widgets.

State Management: setState / Providers.

Voice: speech_to_text and flutter_tts.

2. Backend (AI Brain)

Language: Python 3.10+

Framework: FastAPI

AI Orchestration: LangChain

Models: * LLM: Meta Llama 3 (via Hugging Face Inference).

STT/TTS: OpenAI Whisper / MMS-TTS.

3. Database & Auth

Platform: Google Firebase

Auth: Secure Email/Password and Social Login.

Firestore: NoSQL database for storing User Profiles, Saved Reports, and Chat History.

📸 Screenshots

Login Screen

Location Analyst

AI Chatbot

🚀 Getting Started

Prerequisites

Flutter SDK installed.

Python 3.10+ installed.

A Firebase Project set up.

Step 3: Backend Setup (Python)

cd backend_server
pip install -r requirements.txt
uvicorn main:app --reload


🔮 Future Roadmap

[ ] Integration with Lebanese local municipality APIs for tax data.

[ ] "Investor Matchmaking" feature to connect startups with VCs.

[ ] Offline mode for core features.

👨‍💻 Author

Katia Jean Matar

University: American Unvercity of Culteur and Education -Koura

Major: Computer Science

Built with ❤️ for Lebanon 🇱🇧
