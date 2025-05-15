# asr-cpp-chunked
Efficient C++ implementation of Whisper-based Automatic Speech Recognition (ASR) on small, chunked audio frames.

## Features

- Transcribes `.wav` audio chunks with timestamps.
- Generates both token-level and sentence-level outputs.
- Computes average time per token.
- Filters silence segments.
- Fast inference with quantized Whisper models (`ggml` format).

## Requirements

- C++17 or higher
- CMake 3.10+
- Whisper C++ implementation (`whisper.cpp`)
- A quantized Whisper model (`.bin` file, e.g., `ggml-tiny-q5_1.bin`)
