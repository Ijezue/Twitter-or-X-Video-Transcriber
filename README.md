# Twitter-or-X-Video-Transcriber

This repository contains a Python-based tool for downloading videos from Twitter/X, extracting audio, transcribing speech using AI-based models (OpenAI's Whisper), and translating non-English transcripts to English. The project includes a Jupyter notebook with detailed explanations and a Gradio interface for an interactive web-based experience.

### Features

- Download Twitter/X videos using `yt-dlp`.
- Extract audio with `ffmpeg`.
- Transcribe audio to text using OpenAI's Whisper, an AI-based automatic speech recognition (ASR) model.
- Detect and translate non-English transcripts to English using deep-translator.
- Optional alternative AI-based transcription with Hugging Face's Transformers library (Whisper large-v2 model).
- Interactive web interface built with Gradio for easy access.


### Prerequisites
- Python: Version 3.8 or higher.
- Conda
- ffmpeg: System dependency for audio extraction.
  - Windows: Download from ffmpeg.org and add to PATH.
  - Linux: Install with `sudo apt-get install ffmpeg`.
  - Mac: Install with `brew install ffmpeg` (requires Homebrew).
 
### How to run

- Clone repo
<pre lang="markdown"> git clone https://github.com/your-username/TwitterVideoTranscriber.git 
  cd TwitterVideoTranscriber  </pre>

- Install `ffmeg` and verify
  `ffmpeg -version`
- Create conda env and install requirements
<pre lang="markdown"> conda create -n xtranscribe python=3.10
conda activate xtranscribe 
pip install -r requirements.txt </pre>

### License

This project is licensed under the MIT License.

