# jarvis-ai-assistant-
A lightweight voice-controlled desktop assistant built in Python. Jarvis listens to your commands, responds with speech, opens websites, searches Wikipedia, plays music, shows time, reads news, and can even send your live location on WhatsApp in emergencies.
arvis is a lightweight, voice-activated desktop assistant built entirely using Python.
It listens to your commands, speaks responses, opens apps & websites, plays music, fetches information, reads news, and even sends your live location through WhatsApp during emergencies.

All using just your voice — no GUI.


---

✨ Features

🔊 Voice Interaction

Understands speech using speech_recognition

Responds naturally using SAPI5 voices (win32com.client)


📚 General Tasks

Search Wikipedia and read results aloud

Tell the current time

Read live news headlines

Play any song from YouTube Music

Open popular websites:

YouTube

Google

Instagram

Gmail

WhatsApp Web

Flipkart

Swiggy



🚨 Emergency Mode

When you say "help", Jarvis:

Fetches latitude & longitude

Generates Google Maps live location link

Sends it to a WhatsApp number using pywhatkit


Perfect for emergency SOS automation.


---

🧰 Tech Stack

Python

speech_recognition

numpy

sounddevice

wikipedia

pywhatkit

win32com.client (TTS)

requests

webbrowser



---

⚙️ How to Run

1. Install Requirements

pip install -r requirements.txt

2. Run the Assistant

python jarvis.py

(Replace jarvis.py with your actual file name.)


---

📂 Folder Structure (example)

Jarvis-AI/
│── jarvis.py
│── requirements.txt
│── README.md


---

🧠 How It Works (Internals)

1. Listens through microphone


2. Converts voice → text


3. Matches keywords


4. Executes the action


5. Responds using text-to-speech



Example commands:

“Open YouTube”

“Search Wikipedia for Python”

“Play music”

“What is the time”

“Help” → triggers SOS mode



---

🚀 Future Improvements

Wake word activation (“Hey Jarvis”)

Offline speech recognition (Vosk)

Dark-theme GUI (optional)

More system controls

OpenAI API integration



---

💡 Purpose of This Project

Learning Python automation

Building a real-world assistant

Understanding speech I/O

Helpful for resume + GitHub portfolio

Foundation for advanced AI/NLP projects
