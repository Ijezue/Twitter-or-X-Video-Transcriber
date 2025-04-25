# Twitter-or-X-Video-Transcriber

This repository contains a Python-based tool for downloading videos from Twitter/X, extracting audio, transcribing speech using AI-based models (OpenAI's Whisper), and translating non-English transcripts to English. The project includes a Jupyter notebook with detailed explanations and a Gradio interface for an interactive web-based experience.

### Features

- Download Twitter/X videos using `yt-dlp`.
- Extract audio with `ffmpeg`.
- Transcribe audio to text using OpenAI's Whisper, an AI-based automatic speech recognition (ASR) model.
- Detect and translate non-English transcripts to English using deep-translator.
- Optional alternative AI-based transcription with Hugging Face's Transformers library (Whisper large-v2 model).
- Interactive web interface built with Gradio for easy access.
