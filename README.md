# Klaam - Egyptian Arabic Speech-to-Text

Klaam is a speech-to-text model specifically designed for Egyptian Arabic. It is developed by **ARABML** and allows real-time transcription of spoken Egyptian Arabic into text. 

## Features
- **Supports real-time transcription** by accepting audio arrays directly, not just `.wav` files.
- **Optimized for Egyptian Arabic**, making it more accurate for dialect-specific speech recognition.
- **Lightweight and efficient**, suitable for various applications, including voice assistants and automated transcription.

## Installation
```bash
git clone https://github.com/Moaz0009/Klaam-Arabic-Speech-To-Text.git
cd Klaam-Arabic-Speech-To-Text
pip install -r requirements.txt
```

## Usage
```python
from klaam import SpeechToText

model = SpeechToText()

# Transcribe from a .wav file
text = model.transcribe("audio.wav")
print(text)

# Transcribe directly from an audio array (NEW FEATURE for real-time processing!)
text = model.transcribe(audio_array)
print(text)
```

## Modifications
- **Real-time usage enabled**: The model now supports **audio arrays** directly instead of requiring `.wav` files.
- **Better efficiency**: Optimized for speed and accuracy in live applications.

## Future Enhancements
- Support for more Arabic dialects.
- Integration with voice assistants.

## Contribution
We welcome contributions! Please fork the repository and submit a pull request with your improvements.

## License
This project is licensed under [MIT License](LICENSE).

