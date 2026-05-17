# AI Exporter (Chrome Extension)

AI Exporter is a lightweight Chrome extension that extracts webpage content, cleans it, and optionally formats it using AI (Gemini API).

It is designed for users who want a simple way to turn messy web pages into readable text or structured notes.

---

## 🚀 Features

- Extracts main text from any webpage
- Removes clutter like navigation bars, scripts, and footers
- Copies or downloads clean text as a `.txt` file
- Optional AI formatting using Google Gemini API
- Lightweight popup-based interface (no background services required)

---

## 🧠 How it works

1. Open any webpage
2. Click the AI Exporter extension icon
3. Choose an action:
   - Copy page text
   - Download as TXT
   - Format using AI (optional)
4. If AI is enabled, the text is processed using Gemini API

---

## 🔐 AI (Gemini API)

AI features are optional.

To use AI formatting:
- Users must provide their own Google Gemini API key
- The key is stored locally in the browser using `chrome.storage.local`
- No API key or page content is sent to any external server controlled by this extension

### Supported Models
Any model available in your Gemini API account can be selected dynamically (via model list API).

---

## 📦 Installation (Development Mode)

1. Download or clone this repository
2. Open Chrome and go to: