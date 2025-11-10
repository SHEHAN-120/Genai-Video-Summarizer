# 🎥 Gen AI Video Summarizer

This project is a **YouTube Video Summarizer** built using **Gradio**, **Whisper**, and **Transformers**. It automatically downloads a YouTube video's audio, transcribes the speech, and summarizes the content into key points.

## 🚀 Features

* Download YouTube video audio using **yt-dlp**
* Transcribe audio using **faster-whisper**
* Summarize transcript using **facebook/bart-large-cnn**
* Simple and interactive **Gradio** web UI

## 🧰 Tools & Libraries Used

* `yt-dlp` — for downloading YouTube audio
* `faster-whisper` — for speech-to-text transcription
* `transformers` — for text summarization
* `torch` — for deep learning backend
* `gradio` — for creating the user interface
* `pydub` — for audio processing

## 🖥️ How to Run

```bash
pip install yt-dlp faster-whisper transformers torch gradio pydub
python {name}.py
```



## 🧑‍💻 Author

Developed by **Shehan**
