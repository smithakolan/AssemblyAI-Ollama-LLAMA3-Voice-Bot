# AssemblyAI-Ollama-LLAMA3-Voice-Bot

🔑 **[Sign up for AssemblyAI's API](https://www.assemblyai.com/?utm_source=github&utm_medium=referral&utm_campaign=smitha)** to get a free API key and $50 in credits. 🔑

Dive into the world of AI with this Ollama Voice Bot! This tutorial shows you how to create a talking AI that can understand and respond to human speech in real-time. The bot integrates AssemblyAI for transcription, LLAMA 3 with Ollama for natural language processing, and ElevenLabs for text-to-speech conversion.

## Features:
- **Real-Time Transcription:** AssemblyAI's Speech-to-Text API ensures accurate transcription of live conversations.
- **Advanced NLP:** LLAMA 3 with Ollama allows the bot to understand and generate natural language responses.
- **Speech Synthesis:** ElevenLabs converts text responses into realistic, natural-sounding speech.

## How to build:
This guide will help you set up a real-time speech transcription and response system using AssemblyAI for transcription, LLAMA 3 for generating responses, and ElevenLabs for streaming the response as live audio.

## Step 1: Install Python Libraries

You'll need to install several Python libraries and other dependencies to get started. Here are the installation instructions for various components:

### Install Python Libraries
```bash
pip install ollama
pip install "assemblyai[extras]"
pip install elevenlabs
```
Install Additional Dependencies
For Debian/Ubuntu:

```bash
apt install portaudio19-dev
```
For MacOS:

```bash
brew install portaudio
brew install mpv
```

### Download the LLAMA 3 Model Locally
To use LLAMA 3 in your project, you need to pull the model data onto your local machine. Run the following command in your terminal:

```bash
ollama pull llama3
```


[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/6ghNRkVNODo/0.jpg)](https://www.youtube.com/watch?v=6ghNRkVNODo)

## Call to Action:
👉 **[Sign up for AssemblyAI's API](https://www.assemblyai.com/?utm_source=github&utm_medium=referral&utm_campaign=smitha)** to power your AI projects with state-of-the-art transcription.
