# Persian-to-English Speech 

This project is an educational experiment designed to deepen my understanding of AI models for speech processing and machine translation. The goal is to build a complete end-to-end pipeline that:

- **Converts Persian speech to text (ASR)**
- **Translates the Persian text to English**
- **(Future Work)** Generates English speech that preserves the original speaker's voice (TTS & Voice Cloning)

The project explores various state-of-the-art models and techniques, including OpenAI's Whisper for speech recognition, MarianMT-based models for translation, and potential future work with voice cloning systems.

---

## Project Overview

- **Automatic Speech Recognition (ASR):**  
  Uses OpenAI's [Whisper](https://github.com/openai/whisper) model (specifically `whisper-large-v3`) to transcribe Persian audio into text using Hugging Face pipelines.

- **Machine Translation:**  
 
- **Text-to-Speech (TTS) & Voice Cloning (Future Work):**  
  
---


### Installation Requirements

Before running the project, please install the required packages by running:

```bash
pip install --upgrade pip
pip install --upgrade transformers datasets[audio] accelerate


