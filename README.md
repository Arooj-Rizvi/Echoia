# Echoia — Voice-Enabled Translation Assistant

Speak or type a phrase, pick a language pair, and get an instant translation — with audio playback, language auto-detect, and a saved history of recent translations. Built as Task 01 for the InternGrow AI Track.

## Features

- **Speech-to-Text** — tap the mic and speak instead of typing
- **Text-to-Speech** — listen to the translated output out loud
- **15 supported languages** — English, Urdu, Arabic, French, Spanish, German, Chinese, Hindi, Turkish, Russian, Japanese, Korean, Italian, Portuguese, Persian
- **Auto-detect input language** — skip picking a source language manually
- **Swap languages** — flip source and target in one click
- **Recent translations panel** — reuse past phrases without retyping
- **Copy to clipboard** — one-click copy of the translated text

## Tech Stack

- Plain HTML, CSS, and JavaScript — no frameworks, no build step
- Web Speech API (`SpeechRecognition` + `speechSynthesis`) for voice input/output
- [MyMemory Translation API](https://mymemory.translated.net/) for translation

## Running It Locally

Voice input needs a **secure context** (HTTPS or `localhost`) — opening the file by double-clicking it (`file://`) will not trigger the mic permission prompt.

Easiest options:

- **VS Code:** install the "Live Server" extension, right-click `index.html`, and choose *Open with Live Server*
- **Python:** run `python -m http.server` in this folder, then open `http://localhost:8000`
- **GitHub Pages:** enable Pages for this repo (Settings → Pages) and use the generated `https://` link

## Project Structure
