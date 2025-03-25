# Speech Recognition System

## Overview
This project implements a speech recognition system that can transcribe audio files using Python. It provides methods for:
- **Transcribing entire audio files**
- **Splitting audio based on silence and transcribing chunks**
- **Splitting audio at fixed intervals and transcribing chunks**

## Files
- `main.py`: The main script for processing and transcribing audio files.
- `requirements.txt`: A list of dependencies required for the project.

## Setup Instructions
### Prerequisites
Ensure you have Python installed (preferably Python 3.8+). Install dependencies using:
```sh
pip install -r requirements.txt
```

### Running the Tool
Execute the script:
```sh
python main.py
```
Modify the `path` variable in `main.py` to specify the audio file for transcription.

## Dependencies
This project requires the following key Python libraries:
- `speechrecognition`
- `pydub`
- `numpy`
- `torch`
- `scikit-learn`
- `transformers`

## Features
- Uses **Google Speech Recognition API** for transcribing audio
- Splits large audio files into smaller chunks based on **silence detection**
- Supports **fixed-interval chunking** for structured transcription
- Compatible with **multiple audio formats** via Pydub

## Author
Manisha

