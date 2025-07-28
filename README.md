# Dagari Realtime voice to voice translation Extension

A custom browser extension for **real-time speech translation** in Microsoft Teams (Enterprise), inspired by the open-source Sokuji project.

##  Features

- Real-time voice-to-voice translation in Teams meetings
- Speech-to-text, machine translation, and text-to-speech using OpenAI, Gemini, or Google APIs
- Easy UI for starting/stopping live translation
- Works on `teams.microsoft.com` (enterprise Teams web)
- Supports multiple languages and major browsers (Chrome/Edge)

## Technologies Used

- JavaScript (ES6+)
- HTML/CSS
- Chrome/Edge Extension APIs (Manifest V3)
- Web Audio API
- OpenAI Whisper / GPT-4o / Google Speech APIs (for translation)
- Optional: Analytics with PostHog (privacy-aware, if enabled)

##  How to Install

1. Clone or download this repository.
2. Open Chrome or Edge and go to `chrome://extensions` or `edge://extensions`.
3. Enable **Developer mode**.
4. Click **Load unpacked** and select the project folder.
5. Join a Teams meeting at `https://teams.microsoft.com` and use the extension popup.

##  How It Works

- Captures your microphone audio in real time during Teams meetings
- Sends audio to cloud APIs for transcription, translation, and speech synthesis
- Plays the translated voice back (or injects into the meeting if supported)
- Lets you select source/target language and manage your API key via the popup UI

## Credits

Based on the [Sokuji open-source project](https://github.com/kizuna-ai-lab/sokuji) by Kizuna AI Lab


