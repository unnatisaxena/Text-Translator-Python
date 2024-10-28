# Text Translation and Audio Conversion Tool

A Python-based tool for translating text from one language to another and converting the translated text into an audio file. This project leverages the `googletrans` library for translation and `gTTS` (Google Text-to-Speech) for generating audio.

# Features

- **Multilingual Text Translation**: Translate text between numerous languages by selecting source and target language codes.
- **Text-to-Speech Conversion**: Convert the translated text into an audio file with support for saving and playback in a Jupyter Notebook.
- **Error Handling**: Displays user-friendly error messages for smooth operation even if translation or audio generation fails.

# Prerequisites

Make sure you have Python installed. Then, install the following packages:

```bash
pip install googletrans==4.0.0-rc1 gTTS
