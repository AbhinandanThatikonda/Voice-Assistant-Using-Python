# Voice-Assistant-Using-Python
<h1>🗣️ Violet - Your Personal Voice Assistant</h1>

Violet is a Python-based voice assistant designed to simplify your digital life. With natural language processing and speech recognition capabilities, Violet can perform a wide range of tasks—from opening apps and browsing the web to sending emails, playing YouTube videos, and more—all triggered by your voice commands.
🔧 Features
✅ Speech Recognition using Google’s Speech API

✅ Text-to-Speech output via pyttsx3

✅ Smart email sending with subject, body, and confirmation

✅ Web search integration with Google and Wikipedia

✅ YouTube search and playback with pywhatkit

✅ Application launcher for popular Windows programs

✅ System control (shutdown, restart, lock, mute, volume)

✅ Real-time webcam access

✅ Screenshot capture with file naming

✅ Time and greetings based on current system time

✅ Fun responses for common queries (who are you, how are you, etc.)

<h2>💻 Technologies Used</h2>
Module	Purpose
pyttsx3	Text-to-speech engine
speech_recognition	Recognizes spoken commands
wikipedia	Fetches brief summaries
pywhatkit	Plays YouTube videos
webbrowser	Opens links in your default browser
pyautogui	Automates mouse and keyboard
cv2 (OpenCV)	Accesses webcam
smtplib	Sends emails securely
os, subprocess	Opens and manages system processes

<h2>🚀 How to Run</h2>
Prerequisites
Python 3.8+

Microphone enabled and configured

Internet connection (for voice recognition & Wikipedia)

<h2>✉️ Email Configuration</h2>
To enable email functionality:

Create a Google App Password:
Visit https://myaccount.google.com/apppasswords
Generate a 16-character password and replace it in the script (send_email() function).

Enable less secure apps access or use 2FA with App Passwords for Gmail security.

<h2>🧠 Example Commands</h2>
“Violet, open Chrome”

“Search on Google for Python tutorials”

“Search on YouTube for lo-fi music”

“Send email” → (Prompts for details)

“Take screenshot”

“Open camera”

“Shutdown the system”

<h2>🙋‍♂️ About Me</h2>
Created with 💙 by Abhinandan
🚀 Passionate about AI, Python, and automation
📧 abhinandan1903@gmail.com
