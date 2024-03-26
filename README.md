# VoiceGPT - An AI voice assistant of chatGPT

This project is a voice-activated chatbot that utilizes OpenAI's GPT-3.5 model for conversational interactions. Users can initiate conversations with the chatbot by saying a predefined wake word ("ok chat"), after which they can speak prompts or questions. The chatbot responds by engaging in conversation using the GPT-3.5 model.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Voice-enabled applications are becoming increasingly popular as they provide hands-free interaction, particularly in scenarios where users may have limited mobility or require assistance while performing other tasks. This project aims to demonstrate the integration of speech recognition and conversational AI technologies to create a voice-activated chatbot.

## Features

- **Voice Activation:** Users can activate the chatbot by speaking the wake word ("ok chat").
- **Speech Recognition:** Utilizes a speech recognition library to transcribe user speech into text.
- **Conversational AI:** Engages in conversation with users using OpenAI's GPT-3.5 model.
- **Voice Synthesis:** Converts text responses into speech for natural-sounding output.
- **Flexible Architecture:** The project is built with modularity in mind, allowing for easy integration of additional speech recognition or conversational AI services.

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/voice-chatbot.git
    ```

2. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Set up AWS credentials for Amazon Polly if using voice synthesis.

## Usage

1. Configure your OpenAI API key by replacing `[paste your OpenAI API key here]` with your actual API key in `main.py`.

2. Run the main script:

    ```bash
    python main.py
    ```

3. Wait for the wake word ("ok chat") and speak prompts or questions to interact with the chatbot.

## Contributing

Contributions are welcome! If you have any ideas for improvements or new features, feel free to open an issue or submit a pull request.

## License
---
