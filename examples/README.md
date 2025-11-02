# Examples

This directory contains example programs demonstrating how to use the go-elevenlabs library.

## Prerequisites

Set the required environment variables:

```bash
export ELEVENLABS_API_KEY="your-api-key"
export ELEVENLABS_VOICE_ID="your-voice-id"
```

## Examples

### Simple TTS

Basic text-to-speech conversion example.

```bash
# Run with default text
go run ./simple_tts

# Run with custom text
go run ./simple_tts "Your custom text here"
```

**Output:** Generates `output.mp3` in the current directory.

### Test Library

Comprehensive test of all library features including:
- User information retrieval
- Models listing
- Voices listing
- Text-to-speech conversion
- History retrieval

```bash
go run ./test_library
```

**Output:**
- Displays test results for each API endpoint
- Generates `test_output.mp3` in the current directory

## Building

Build all examples:

```bash
go build ./...
```

Build specific example:

```bash
go build ./simple_tts
go build ./test_library
```
