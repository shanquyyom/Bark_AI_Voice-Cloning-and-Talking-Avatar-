# Bark_AI_Voice-Cloning-and-Talking-Avatar-
# 🎙️ Voice Generation & Cloning using Bark (Week 1 & 2)

This project contains two modules based on Suno's Bark Text-to-Speech system. It allows you to either generate voice from plain text or simulate voice cloning using a reference audio clip.

---

## 🔹 Week 1 – Text-to-Speech Module

In this module, the user simply types any text, and Bark generates a speech waveform using its default voices. The result is a `.wav` audio file.

**✅ Input:** Text  
**🎧 Output:** AI-generated voice (default speaker)

---

## 🔹 Week 2 – Voice Cloning Module (Bark)

This module allows the user to upload a **30–60 second reference audio clip** and type any custom text. Bark then synthesizes the audio using a **default speaker** (due to current model limitations). The final output is a `.wav` file containing the generated speech.

**✅ Input:** Reference Audio + Text  
**🎧 Output:** Simulated cloned voice (default speaker)

📎 **Note:** Bark does not currently support direct voice cloning from reference audio, so default speakers are used instead.

---

## ⚙️ Requirements

Make sure the following libraries are installed:

```bash
pip install git+https://github.com/suno-ai/bark.git
pip install librosa soundfile

▶️ How to Run
This notebook is designed to run in Google Colab for ease of file handling and playback.

Choose your mode:

1 for Week 1: Text-to-Speech

2 for Week 2: Reference Voice + Text

Upload audio file if using Week 2

Enter text

The generated .wav file will be downloaded automatically

📁 Output Files
bark_week1.wav – Text-to-Speech output

cloned_voice_week2.wav – Simulated voice cloning output

💡 Author
Shan Quyyoom
🔗 https://www.linkedin.com/in/shan-quyyoom-452923365
📍 Jhang, Pakistan
