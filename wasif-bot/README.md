# 🤖 Wasif Rind WhatsApp Bot

A WhatsApp Bot powered by **Baileys** (Multi-Device) and **OpenAI ChatGPT**.

---

## 👤 Owner Info

| Field        | Detail                |
|--------------|-----------------------|
| **Name**     | Wasif Rind            |
| **Email**    | wasifrind27@gmail.com |
| **WhatsApp** | +923272516116         |

---

## ✨ Features

- 🤖 AI-powered auto-reply using OpenAI ChatGPT (GPT-3.5 Turbo)
- 💬 Per-user chat history (up to 20 messages)
- 📱 WhatsApp Multi-Device support via Baileys
- 🔄 Auto-reconnect on disconnect
- 🔁 Auto-reload on file changes

---

## 📦 Requirements

- Node.js v16 or higher
- npm
- A WhatsApp account
- OpenAI API Key

---

## 🚀 Installation

```bash
# 1. Extract the project folder
cd wasif-bot

# 2. Install dependencies
npm install

# 3. Add your OpenAI API key in key.json

# 4. Start the bot
npm start
```

---

## ⚙️ Configuration

### `key.json`
Add your OpenAI API key:
```json
{
  "keyopenai": "YOUR_OPENAI_API_KEY_HERE"
}
```

### `index.js` (top of file)
```js
const owner = ["923272516116"]; // WhatsApp number with country code
```

### `custom_prompt.txt`
Edit this file to customize the AI personality and behavior.

---

## 📁 Project Structure

```
wasif-bot/
├── index.js           # Main bot file
├── wasif.js           # Message handler & OpenAI logic
├── key.json           # OpenAI API key config
├── custom_prompt.txt  # AI system prompt
├── chat_history.json  # Auto-generated chat history
└── package.json       # Dependencies
```

---

## 🔌 Usage

1. Run `npm start`
2. Scan the QR code shown in terminal with your WhatsApp
3. Bot is now live and will auto-reply to messages

---

## ⚠️ Notes

- Delete the `wasifrind/` session folder and re-scan if you get a bad session error
- Do not share your `key.json` or session folder with anyone
- For personal/educational use only

---

## 📄 License

MIT — Free to use and modify.
