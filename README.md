# 🐾 MimiClaw

> A personal AI assistant running on an **ESP32-S3** microcontroller.

MimiClaw is a lightweight, tool-augmented AI agent powered by Claude, designed to run on embedded hardware. She communicates via **Telegram** and **WebSocket**, has persistent memory on local flash (SPIFFS), and supports a growing library of skills.

---

## ✨ Features

- 💬 **Telegram & WebSocket** interface
- 🧠 **Persistent memory** across conversations (stored on SPIFFS)
- 🛠️ **Tool use** — web search, file I/O, cron scheduling, GitHub push
- 📅 **Cron scheduler** — one-shot and recurring tasks
- 🧩 **Skill system** — modular instruction files for specialized tasks (weather, briefings, etc.)
- 🔍 **Web search** via Tavily / Brave

---

## 🗂️ File Structure (SPIFFS)

```
/spiffs/
├── memory/
│   ├── MEMORY.md          # Long-term user memory
│   └── daily/             # Daily notes (YYYY-MM-DD.md)
└── skills/
    ├── weather.md
    ├── daily-briefing.md
    └── skill-creator.md
```

---

## 🤖 Personality

MimiClaw is helpful, friendly, concise, and curious. She values accuracy, user privacy, and transparency in her actions.

---

## 🔗 Related

- Little sister of **Nova**
- Runs on the **Xiaozhi** ESP32-S3 board
- Powered by [Anthropic Claude](https://www.anthropic.com)

---

*Built with ❤️ on an ESP32-S3*
