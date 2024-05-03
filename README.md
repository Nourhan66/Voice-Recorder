# Voice Recorder Algorithm

This Python script implements a simple voice recorder algorithm using the **pyaudio** and **tkinter** libraries.
It provides a user interface with a microphone button to start and stop recording audio. The recorded audio is saved as a WAV file with a unique filename.
The script displays the elapsed time of the recording while it's in progress.

## Requirements
- Python 3.x
- pyaudio library
- tkinter library (usually comes pre-installed with Python)

## Key Features
- **User Interface**: Utilizes tkinter to create a simple GUI with a microphone button.
- **Recording Control**: Allows users to start and stop recording by clicking the microphone button.
- **Elapsed Time Display**: Shows the elapsed time of the recording in hours, minutes, and seconds.
- **File Saving**: Saves recorded audio as WAV files with incrementing filenames (recordingN.wav).

## Usage
1. **Clone Repository**: Clone the repository to your local machine.
2. **Install Dependencies**: Install required libraries using pip install -r requirements.txt.
3. **Run Script**: Execute the script using python voice_recorder.py.
4. **Start Recording**: Click the microphone button to begin recording.
5. **Stop Recording**: Click the microphone button again to stop recording.
