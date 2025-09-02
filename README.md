Voice Assistant

A simple voice-controlled assistant built using Python. This project uses speech recognition and text-to-speech libraries to interact with the user, execute tasks, and respond intelligently.

✨ Features

- 🎙️ Voice input using microphone
- 🗣️ Text-to-speech responses via `pyttsx3`
- 🔎 Search Wikipedia and read summaries aloud
- 🌐 Open popular websites like Google, YouTube, and StackOverflow
- 🎵 Play local music files
- 🕒 Tell the current time
- 📧 Send emails via Gmail (SMTP)
- 🧠 Personalized greeting based on time of day

📂 Project Structure

assistant.py         # Main script for the voice assistant
README.md            # Project documentation
requirements.txt     # List of required packages

🚀 Getting Started

✅ Prerequisites

Make sure you have Python 3 installed. Then install the required libraries:

```
pip install -r requirements.txt

```
requirements.txt contents

pyttsx3
SpeechRecognition
wikipedia

smtplib, datetime, os, and webbrowser are part of Python's standard library.

▶️ How to Run
python assistant.py
Then just speak into your microphone when prompted.

🔐 Email Configuration

To enable sending emails:
Replace the youremail@gmail.com and your-password in the sendEmail function with your own credentials.
Enable "Less secure apps" or use App Passwords if using 2FA in Gmail.
⚠️ Never hardcode real credentials in production! Use environment variables or a .env file.


📌 Sample Commands

Try saying:
"Open YouTube"
"Search Wikipedia for Python"
"What is the time?"
"Play music"
"Email to Harry"


📋 Todo / Improvements

Add voice feedback for more tasks
Implement GUI interface
Add support for voice-activated shutdown or restart
Use NLP for more complex command handling
Improve error handling and noise filtering

🧑‍💻 Author

Shiwesh Kumar Mishra
https://github.com/shivesh754




