# Audio Transcript Search with LLM

This project implements an intelligent search system for audio transcripts using a Large Language Model (LLM). The system processes audio files, transcribes them, and allows for semantic search within the transcriptions.

## Features

- Audio extraction from various file formats
- Speech-to-text conversion using Whisper
- Chunking of audio to overcome time limits
- Semantic search in transcriptions using an LLM

## Project Workflow

1. **Audio Extraction**: Extract audio from input files.
2. **Speech-to-Text Conversion**: Use Whisper to transcribe the audio into text.
3. **Audio Chunking**: Split audio into manageable chunks to bypass the 30-second limit.
4. **LLM-powered Search**: Utilize an LLM to perform semantic search within the transcriptions.
