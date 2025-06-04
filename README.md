# YouTube Video Summarizer using Gemini API & YouTranscript API

This is an AI-powered application that summarizes YouTube videos. It uses the [YouTranscript API](https://youtranscript.vercel.app) to extract video transcripts and the **Gemini API** (Gemini Pro model) from Google to generate concise, intelligent summaries.

---

## Features

- Accepts any YouTube video link
- Extracts video transcript automatically
- Generates high-quality summaries using Gemini
- Lightweight and fast
- Option to export summary as text or PDF (optional)

---

## Tech Stack

- **Gemini API** – for summarization
- **YouTranscript API** – to get YouTube transcripts
- **Python**
- **Streamlit** (or Flask – depending on your frontend)
- **Requests** – for API communication

---

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/youtube-video-summarizer.git
cd youtube-video-summarizer
