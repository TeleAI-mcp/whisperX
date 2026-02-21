# WhisperX

WhisperX is an extension of the OpenAI Whisper model for improved performance on multilingual transcription and speaker diarization. It builds upon faster-whisper and adds features like:

- **Speaker Diarization**: Identify and separate different speakers in audio
- **Word-level Timestamps**: Get precise timing for each word
- **Batched Inference**: Process multiple audio files efficiently
- **VAD (Voice Activity Detection)**: Only transcribe when speech is detected

## Installation

```bash
pip install whisperx
```

## Quick Start

```python
import whisperx

# Load model
model = whisperx.load_model("large-v3", device="cuda", compute_type="float16")

# Transcribe
result = model.transcribe("audio.mp3", batch_size=32)
```

## Features
- **Multilingual Support**: Works with all Whisper languages
- **Speaker Diarization**: Built-in diarization using pyannote.audio
- **Batched Processing**: Efficient batched inference pipeline
- **Word Alignment**: Precise word-level timestamps
- **VAD Options**: Multiple VAD models supported (Silero, pyannote)
- **Output Formats**: SRT, VTT, TXT, JSON, TSV

## Documentation

For detailed documentation and examples, please visit our [documentation](https://github.com/m-bain/whisperX#readme).

1. related project [openai/whisper](https://github.com/openai/whisper)
2. related project [SYSTRAN/faster-whisper](https://github.com/SYSTRAN/faster-whisper)