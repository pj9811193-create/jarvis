# J.A.R.V.I.S.

**Just A Rather Very Intelligent System** — a real voice assistant that runs entirely in your browser.

Single file. No install. No build step. No server.

**Live:** https://pj9811193-create.github.io/jarvis/

---

## What it does

- **Talks and listens** — voice input via your browser's speech recognition, spoken replies via text-to-speech (British voice by default).
- **Offline skills, zero setup** — time, date, mental arithmetic in plain English ("47 times 19", "20% of 50"), jokes, opening websites, and web searches.
- **Full AI brain** — paste an API key and it gains real conversation. Works with Groq, Google Gemini, OpenAI, OpenRouter, Together and Mistral.
- **Animated arc-reactor orb** that reacts live: idle → listening → thinking → speaking.
- **Hands-free mode**, voice selection, and a personality prompt.

## Use it

Open the live URL, tap the mic, and talk. It works immediately in offline mode.

For the full AI brain: click the **gear icon**, pick a provider, paste a free key
([Groq](https://console.groq.com/keys) or [Google AI Studio](https://aistudio.google.com/apikey)),
and hit Save. Your key is stored only in your browser and sent only to the provider you chose.

**Use Chrome or Edge** for voice input — they have the best speech recognition.

## Everything is in `index.html`

The whole assistant — configuration, styling, voice handling and AI logic — is one
self-contained HTML file. To change the default provider/model/personality, edit the
`window.JARVIS_CONFIG` block near the bottom of the file.

## A note on your API key

This repo is **public**. Never commit a real API key here. Use the in-app Settings panel
instead (it keeps the key in your browser's local storage), or keep your own fork private.
