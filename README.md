# jarvis-5.0

# Jarvis5.0 - Voice AI Assistant

Jarvis5.0 is a personal voice AI assistant built with **Python**, **LiveKit**, and **Google Realtime API**. It allows users to interact with the assistant via **speech**, and it responds with **voice output**, similar to Google ChatGPT or other AI voice assistants.

---

## Features

- Talk to the assistant using your voice.
- Receive responses in natural-sounding speech.
- Powered by **Google Realtime API** and **LiveKit Agents**.
- Noise cancellation support via `livekit-plugins-noise-cancellation`.

---

## Tech Stack

- **Python 3.11+**
- **LiveKit Agents** - Real-time communication framework
- **Google Realtime API** - Voice generation and conversational AI
- **Python-dotenv** - Environment variable management
- **Noise Cancellation** - For cleaner audio input

---

## Prerequisites

- Python 3.11 or higher
- A valid **Google API key** with Realtime API access
- LiveKit account and project setup

---

## Installation

1. Clone the repository:

```bash

git clone https://github.com/Achu-24/jarvis-5.0.git
cd jarvis-5.0

python agent.py download-files
python agent.py console

