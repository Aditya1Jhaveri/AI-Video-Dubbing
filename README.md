# AI Video Dubbing

# Overview

AI video dubbing using Google APIs involves leveraging Google's suite of machine learning and artificial intelligence tools to automatically translate and dub videos into different languages. Here’s an overview of the process and key components involved:

# Key Components

# Google Cloud Speech-to-Text:

- Function: Converts the audio from the original video into text.

- Use: Captures the spoken content in the source language accurately.

# Google Cloud Translation:

- Function: Translates the transcribed text from the source language into the target language.

- Use: Ensures that the content is accurately translated while maintaining the context and meaning.

# Google Cloud Text-to-Speech:

- Function: Converts the translated text into spoken words.

- Use: Generates natural-sounding speech in the target language. It supports various voices and languages.

# Video Processing and Synchronization:

- Function: Integrates the new audio with the original video.

- Use: Ensures that the dubbed audio is synchronized with the video, including lip-sync and timing adjustments.

## Installation

```bash
  uv venv
  .venv\Scripts\activate
```

```bash
  uv pip install -r requirements.txt
```

```bash
  python dubber.py demo4.mp4 "en-US" outputDirectory --targetLangs '["hi","gu"]'
```
