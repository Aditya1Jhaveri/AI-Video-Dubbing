# AI Video Dubbing

# Overview

AI video dubbing using Google APIs leverages various machine learning models to automate the process of translating spoken language in a video and dubbing it into another language.

Cloud-based Processing allows to scale and fast processing of video dubbing tasks, enabling the handling of large volumes of videos or real-time dubbing with efficient and high-performance infrastructure.

This technology can be effectively used for dubbing movies or videos that contain speech, enabling the seamless conversion from one language to another. By using Google APIs, the entire process of translating and dubbing videos can be automated and scaled, offering businesses and content creators an efficient way to make their content accessible to global audiences across multiple languages.

This process involves several key components:

# Key Components

# Google Cloud Speech-to-Text (STT):

- Google's Speech-to-Text API transcribes the audio from the video into text in the original language.
- It uses advanced speech recognition to ensure high accuracy, even with different accents, dialects, or background noise.

# Google Cloud Translation:

- Once the original speech is transcribed, Google's Translation API can be used to convert the text into a target language.

- Google's Neural Machine Translation (NMT) system ensures context-aware and fluent translations by using deep learning techniques to better understand language nuances.

# Google Cloud Text-to-Speech (TTS):

- After the translation, Google's Text-to-Speech API takes the translated text and generates audio output in the target language.

- This API allows for customization of voices, accents, speed, and pitch, making the dubbed audio sound natural and tailored to the video content.

# Video Processing and Synchronization:

- Integrates the new audio with the original video.

- Ensures that the dubbed audio is synchronized with the video, including lip-sync and timing adjustments.

## Installation

This steps need to follow after git clone.

```bash
  pip install uv
```

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
