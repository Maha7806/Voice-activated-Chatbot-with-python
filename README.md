# 🎙️ Voice-Activated AI Chatbot using Python

A smart, voice-driven AI assistant that listens to your commands, responds audibly, and performs tasks like web search, Wikipedia queries, telling the time, and opening applications — all through your voice.

---

## 📌 Features

- 🧠 **Speech Recognition** using Google's Speech-to-Text API
- 🔊 **Text-to-Speech** response using `pyttsx3` (offline)
- 📚 **Wikipedia Integration** for information lookup
- 🌐 **Web Automation** – opens websites like Google and YouTube
- ⏰ **Time Announcer** – tells current system time
- 💻 **System Commands** – open Notepad, shutdown/restart PC
- 🛠️ Built completely in **Python** with no external GUI

---

## 📦 Technologies Used

| Tool / Library     | Description                                      |
|--------------------|--------------------------------------------------|
| `speech_recognition` | Captures and converts spoken words to text       |
| `pyttsx3`           | Converts chatbot's response text into speech     |
| `wikipedia`         | Fetches summaries from Wikipedia                 |
| `webbrowser`        | Opens URLs like Google and YouTube               |
| `datetime`          | Checks current system time                       |
| `os`, `subprocess`  | Executes basic system-level operations           |
| `Python 3.8+`       | Primary language                                 |

---

## 🚀 Getting Started

### 1. Clone the repository:
```bash
git clone https://github.com/yourusername/voice-activated-chatbot.git
cd voice-activated-chatbot
