# Simplified-Babagaboosh

This project is a voice assistant application built using Python and various libraries, including Tkinter for the user interface, Cohere for natural language processing, ElevenLabs for text-to-speech, and Pygame for audio playback.

## Features

- **Voice recognition** using a customizable wake phrase
- **Text generation** with the Cohere API (Free)
- **Text-to-speech conversion** with ElevenLabs API (First 10,000 characters free)
- **Audio playback** of generated speech using Pygame
- **Persistent chat history** with a configurable maximum number of entries
- **Customizable voice settings** (e.g., voice ID, model)
- **Support for custom prompts** to guide the language model

## Prerequisites

Before running the application, make sure you have the following:

- **LilySpeech** installed
- **Python 3.10.6** installed
- API keys for **Cohere** and **ElevenLabs**
- Required Python libraries installed:
  - `tkinter`
  - `cohere`
  - `elevenlabs`
  - `requests`
  - `pygame`
  - `random`
  - `string`
  - `time`

## Installation

1. **Clone the repository** or download the source code.
2. **Install the required Python libraries**
3. **Replace the placeholders** in the code with your actual API keys and file paths:
   - `API_KEY` (ElevenLabs API key)
   - `custom_prompt_file` (path to your custom prompt file)
   - `VOICE_ID` (ElevenLabs voice ID)
4. Optionally, customize other settings like the wake phrase, model, and voice settings.

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

Please note that this README file assumes you have already set up the necessary API keys and file paths in the project code. You may need to customize certain sections based on your specific requirements and project structure.
