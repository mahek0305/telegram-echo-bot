# Telegram Echo Bot (n8n)

A simple n8n workflow that creates a Telegram Echo Bot.

Whenever a user sends a message to the Telegram bot, the workflow replies with the exact same message.

## Features

- Telegram Trigger
- Echoes every received message
- Beginner-friendly n8n workflow
- Easy to import and configure

## Workflow Screenshort
![Telegram Echo Bot Workflow](./screenshorts/telegram-bot.png)

## Workflow

```
Telegram Trigger
        │
        ▼
Send Echo Reply
        │
        ▼
Replies with the same message received
```

## Requirements

- n8n
- Telegram Bot created using @BotFather
- Telegram Bot Token

## Importing the Workflow

1. Download the `telegram-echo-bot.json` workflow.
2. Open your n8n instance.
3. Click **Import from File**.
4. Select the workflow JSON file.
5. Add your Telegram credentials.
6. Save and activate the workflow.

## Configuration

1. Open **Telegram Trigger** and connect your Telegram credentials.
2. Open **Send Echo Reply** and use the same credentials.
3. Activate the workflow.
4. Send a message to your Telegram bot—the bot will reply with the exact same message.

## Security

This repository does **not** contain:

- API keys
- Telegram Bot tokens
- Passwords
- Secrets
- Personal credentials

All credentials must be added after importing the workflow.

## Project Structure

```
.
├── README.md
├── telegram-echo-bot.json
└── screenshots
    └── telegram-bot.png
```

## License

MIT License
