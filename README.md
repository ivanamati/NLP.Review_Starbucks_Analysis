# Voice Assistant

This project is a simple voice assistant that recognizes and processes spoken input using speech recognition libraries, and responds to user queries like checking the weather, time, or playing music. The project uses two different speech recognition engines: Whisper and Google. The recognized text is then processed to remove stopwords, punctuation, and perform lemmatization before matching it against predefined commands.

## Features

- **Speech Recognition**: Uses `speech_recognition` library to convert speech to text.
- **Natural Language Processing**: Utilizes `nltk` for tokenization, stopword removal, and lemmatization.
- **Text-to-Speech**: Uses `pyttsx3` for converting text responses into speech.
- **Multiple Speech Recognizers**: Includes support for both Whisper and Google recognizers.
- **Predefined Command Recognition**: Supports commands related to weather, time, and playing music.

## Installation

To run this project, you'll need to install the following Python packages:

pip install SpeechRecognition nltk pyttsx3
