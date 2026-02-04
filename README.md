# FeelTheRoom — AI-Enhanced Online Meeting Dashboard

EmotionMeet is a hackathon prototype exploring how **AI can improve online meetings** through emotion awareness, live subtitles, audio capture, and speaker profiling.

The project demonstrates how frontend experience and backend AI concepts can combine to create more **human-centered virtual collaboration**.

Built for **Hackathone Tirana 2026**.

## Project Vision

Traditional video meetings lack emotional context.

EmotionMeet introduces an intelligent layer on top of meetings by visualizing:

- participant emotions  
- speech activity  
- engagement levels  
- speaker information  

The goal is to help hosts better understand group dynamics and improve communication quality.

This repository contains the **frontend prototype**, designed to later connect with real AI backend services.

## Features

### Implemented Frontend

- 🎥 Webcam preview  
- 🎙️ Microphone audio recording (with download)  
- 💬 Live subtitles (Web Speech API)  
- 🧠 Emotion visualization (simulated values)  
- 📊 Animated emotional graph (Canvas)  
- 👤 Speaker info form (saved locally)  
- ▶ Start / Save / Upload / Delete controls  

### Backend Concepts (Future Integration)

- Emotion recognition from video/audio  
- Speech-to-text processing  
- Sentiment analysis  
- Audio upload API  
- Meeting summaries  
- Participant analytics  

## Emotion System

Emotions are currently **mocked on the frontend** to simulate AI output.

The architecture allows replacing this with real endpoints such as:

