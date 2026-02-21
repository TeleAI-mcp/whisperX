# WhisperX

[![PyPI](https://img.shields.io/pypi/v/whisperx.svg)](https://pypi.org/project/whisperx/)
[![Python](https://img.shields.io/pypi/pyversions/whisperx.svg)](https://pypi.org/project/whisperx/)
[![License](https://img.shields.io/github/license/m-bain/whisperX.svg)](https://github.com/m-bain/whisperX/blob/master/LICENSE)
[![arXiv](https://img.shields.io/badge/arXiv-2303.00747-b31b1b.svg)](https://arxiv.org/abs/2303.00747)

**WhisperX** is an extension of OpenAI's Whisper model with improved performance and additional features.

## Features

- Improved transcription accuracy
- Faster processing times
- Additional language support
- Enhanced diarization capabilities

## Installation

```bash
pip install whisperx
```

## Usage

```python
import whisperx

# Load model
model = whisperx.load_model("base")

# Transcribe audio
result = model.transcribe("audio.mp3")
```

## Related Projects

1. related project [openai/whisper](https://github.com/openai/whisper)
2. related project [SYSTRAN/faster-whisper](https://github.com/SYSTRAN/faster-whisper)