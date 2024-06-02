# Voice Assistant Using OpenAI's API

This project demonstrates how to create a voice assistant that records audio from a microphone, transcribes it using OpenAI's Whisper API, and interacts with OpenAI's GPT-4 model to provide responses. The assistant can transcribe audio, process the text, and return responses in both text and speech formats.

## Features

1. **Audio Recording**: Capture audio from the microphone and save it as a WAV file.
2. **Audio Transcription**: Transcribe the recorded audio to text using OpenAI's Whisper API.
3. **Assistant Interaction**: Send the transcribed text to an OpenAI GPT-4 assistant and get a response.
4. **Text-to-Speech**: Convert the assistant's response to speech and save it as an MP3 file.

## Requirements

To run this project, you need to have the following packages installed:

- `openai`: OpenAI API client
- `pyaudio`: Library for audio input/output
- `wave`: Standard library for handling WAV files
- `typing_extensions`: Provides backports of typing features

## Installation

1. Clone this repository.
2. Create a virtual environment and activate it.
3. Install the required packages using `pip`:

  ```bash
   pip install -r requirements.txt
  ```
## Usage
1. Ensure you have a valid OpenAI API key.
2. Replace the placeholder API key in the script with your actual API key.
3. Run the script:

  ```bash
   python voice_assistant.py
  ```

The script will record audio from your microphone for the specified duration, transcribe it, send it to the assistant, and save the assistant's response as an MP3 file.

## File Structure
- voice_assistant.py: The main script that contains the logic for recording, transcribing, and interacting with the assistant.
- requirements.txt: The file listing the necessary Python packages for the project.
## Notes
- Ensure your microphone is properly set up and accessible by the script.
- The OpenAI API key must have the necessary permissions to access the Whisper API and GPT-4 model.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.