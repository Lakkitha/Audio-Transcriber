# Audio-Transcriber

A browser-based application for transcribing audio and video files using OpenAI's Whisper API.

## Features

- Transcribe audio and video files (.mp3, .mp4, .mpeg, .mpga, .m4a, .wav, .webm)
- Local browser-based processing
- Automatic file compression for large videos
- Support for files larger than 25MB through automatic chunking
- Save transcriptions as text files
- Secure - your API key is stored locally and never sent to any server except OpenAI

## How to Use

1. Open the application in your web browser
2. Enter your OpenAI API key
3. Select an audio or video file to transcribe
4. Choose whether to compress large video files (recommended)
5. Click "Transcribe Audio"
6. Wait for processing to complete
7. View or download the transcript

## Requirements

- A modern web browser that supports:
  - MediaRecorder API
  - Canvas API
  - Blob API
- An OpenAI API key with access to the Whisper model

## Privacy

- Your API key is stored in your browser's localStorage for convenience
- Audio files are processed locally in your browser
- Only the audio data is sent to OpenAI's servers for transcription

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Author

Lakkitha Niwunhella
