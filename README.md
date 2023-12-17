# AI English Tutor

## Overview
This project is an AI-powered English tutor that leverages various OpenAI APIs to create an interactive learning experience. It combines the capabilities of Chat Completions, Whisper (Speech to Text), and Text-to-Speech (TTS) to facilitate an engaging and dynamic English learning environment.

## Features
- [Chat Completions](https://platform.openai.com/docs/guides/text-generation/chat-completions-api): Creates an interactive chat thread for text-based English tutoring.
- [Whisper API](https://platform.openai.com/docs/guides/speech-to-text/speech-to-text): Implements Speech to Text functionality, allowing users to speak and have their speech converted to text.
- [Text-to-Speech (TTS)](https://platform.openai.com/docs/guides/text-to-speech/text-to-speech): Converts the language model's responses into audio, enabling an auditory learning experience.

## Prerequisites
- OpenAI API keys for Chat Completions, Whisper, and TTS services.
- Python 3.6 or later.
- Jupyter Notebook.

## Installation
1. Clone the repository:

```bash
git clone git@github.com:jasonkang14/ai-english-tutor.git
cd ai-english-tutor
```

2. Install required Python packages:
```bash
pip install -r requirements.txt
```

3. Setup OpenAI API keys:

Set your OpenAI API keys as environment variables and store it in `.env` as `OPENAI_API_KEY`

## Running the Project

1. Launch Jupyter Notebook:
```bash
jupyter notebook
```

you can also use VS Code if you would like

2. Open the project notebook (e.g., ai_english_tutor.ipynb) in the Jupyter interface.
3. Run the cells in sequence, following any instructions provided within the notebook.

## Usage
- Interact with the chatbot via the Jupyter Notebook interface. Type your English queries or statements, and the chatbot will respond.
- Use a microphone for the Speech to Text feature, speaking in English. The Whisper API will transcribe your speech.
- Listen to the TTS audio responses from the language model for auditory learning and practice.

## Contributions
- Contributions to this project are welcome! Please refer to the contribution guidelines for more information.