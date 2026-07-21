# Speech Recognition with OpenAI Whisper

A speech-recognition system that transcribes spoken English audio into text using
**OpenAI Whisper**, built as a team project for the Speech Recognition course at
Newgiza University. The system was tested across short, long, and noisy inputs to
evaluate transcription accuracy and robustness under different conditions.

> **Team project (Team 2).**

## Overview
The project uses OpenAI's Whisper model to convert speech to text. Rather than
building an acoustic model from scratch, it leverages Whisper's pretrained
transformer-based architecture and evaluates how well it performs across varied
real-world audio conditions — clean short clips, longer continuous speech, and
audio with background noise.

## Features
- Transcribes spoken English audio to text using Whisper
- Tested on **short**, **long**, and **noisy** inputs to measure robustness
- Compares transcription quality across the three input scenarios

## Approach
- **Input:** English audio samples (short, long, and noisy test cases)
- **Model:** OpenAI Whisper (pretrained speech-to-text transformer)
- **Evaluation:** transcription output compared across the three input types to
  observe how length and noise affect accuracy

## Repository contents
- `Team2_SpeechRecognition_Implementation.ipynb` — full implementation notebook
- `Team2_SpeechRecognition_Presentation.pdf` — project presentation
- `English_Short_Input.mp4`, `English_Long_Input.mp4`, `English_Noisy_Input.mp4`
  — sample test inputs

## Tech stack
`Python` · `OpenAI Whisper` · `Jupyter Notebook`

## Running it
```bash
git clone https://github.com/zeina-abdelaziz/speech_recognition.git
cd speech_recognition

pip install openai-whisper

# open Team2_SpeechRecognition_Implementation.ipynb in Jupyter and run the cells
```
