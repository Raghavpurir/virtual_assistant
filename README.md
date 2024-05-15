# virtual_assistant

This project is a Python-based voice assistant designed to perform various tasks using voice commands. The assistant, named PAL, interacts with the user through speech synthesis and recognition, providing an interactive and hands-free experience. Key functionalities include greeting the user, fetching information from Wikipedia, opening websites, playing music, telling the time, and sending emails.

Key Components and Functionality:

Text-to-Speech (TTS) with pyttsx3:-

The assistant uses pyttsx3, a text-to-speech conversion library in Python, to vocalize responses.
It initializes the speech engine and sets the voice property to a female voice.

Speech Recognition with SpeechRecognition:-

The assistant uses the speech_recognition library to capture audio from the microphone and convert it into text.
The takeCommand function listens for voice input, recognizes the speech using Google's Web Speech API, and returns the recognized text.

Greeting the User:-

The wishMe function greets the user based on the current time of day, providing a personalized experience.

Handling Commands:-

The assistant listens for specific keywords in the user's commands and performs corresponding actions:
Wikipedia Search: Searches Wikipedia for a given topic and reads a brief summary.
Open Websites: Opens popular websites like YouTube, Google, and Stack Overflow.
Play Music: Plays a song from a predefined directory on the local machine.
**Tell the Time
