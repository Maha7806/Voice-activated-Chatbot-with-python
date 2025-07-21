
# 🤖 AI Activated Chatbot

This project is a voice-controlled AI chatbot built using Python. It listens to your voice commands, processes them intelligently, and responds with actions like searching Wikipedia, opening websites, telling the current time, or speaking back — just like your personal voice assistant.

---

## 🔍 How It Works

1. **Startup Greeting**
   - When you run the chatbot, it greets you based on the time of day (morning, afternoon, or evening) using the system clock.

2. **Voice Input**
   - The chatbot listens to your voice using the system microphone.
   - It uses `speech_recognition` to convert your voice into text via Google Speech API.

3. **Command Processing**
   - The spoken command is analyzed and matched against predefined keywords like:
     - "Wikipedia" → searches and reads a summary
     - "Open Google" → opens your default browser to Google
     - "What is the time" → tells the current system time
     - "Open YouTube", "Open Notepad", etc.

4. **System Actions**
   - Commands like “shutdown” or “restart” execute system-level functions using `os` and `subprocess`.

5. **Voice Response**
   - The bot responds aloud using `pyttsx3`, which converts text into speech and plays it through your speaker.

6. **Continuous Listening**
   - After responding, the bot continues listening for more commands in a loop.
   - Saying "exit" or "bye" ends the chatbot session gracefully.

---

## ⚙️ Requirements

Make sure your system has:

### 🧰 Hardware:
- Microphone (for voice input)
- Speakers or headphones (for voice output)

### 📦 Python Libraries:

You can install all required libraries with:

```bash
pip install SpeechRecognition pyttsx3 wikipedia pyaudio
```

> ⚠️ If you face issues with `pyaudio`, download the appropriate `.whl` from  
> [https://www.lfd.uci.edu/~gohlke/pythonlibs/#pyaudio](https://www.lfd.uci.edu/~gohlke/pythonlibs/#pyaudio)

---

## 🧠 Technologies Used

- `Python 3.8+`
- `speech_recognition` – to capture and recognize voice
- `pyttsx3` – for offline voice output (TTS)
- `wikipedia` – to fetch summaries
- `webbrowser` – to open URLs
- `datetime`, `os`, `subprocess` – for system actions and time

---

## 📁 File Structure

```
AI_Activated_Chatbot/
│
├── chatbot.py              # Main Python script
├── requirements.txt        # (Optional) Dependency list
└── README.md               # This documentation
```

---

## ✅ Example Commands You Can Try

- “What is Python in Wikipedia?”
- “Open Google”
- “Tell me the time”
- “Open YouTube”
- “Open Notepad”
- “Shutdown the system”
- “Exit”

---

## 🧩 Future Enhancements

- Add GUI interface using Tkinter
- Add personal note-taking and reminders
- Use NLP for free-flow conversation
- Integrate weather/news APIs

---

## 👩‍💻 Developed By

**Maha Lekshmi M**  
AI Enthusiast | Python Developer | Dreamer  
❤️ Passionate about creating things that speak, think, and help people

---
