# Telegram Echo Bot (n8n)

A simple n8n workflow that creates a Telegram Echo Bot.

Whenever a user sends a message to the Telegram bot, the workflow replies with the exact same message.

## Features

- Telegram Trigger
- Echoes every received message
- Beginner-friendly n8n workflow
- Easy to import and configure

## Workflow

```
User
   │
   ▼
Telegram Bot
   │
   ▼
Telegram Trigger (n8n)
   │
   ▼
Send Echo Reply
   │
   ▼
User receives the same message
```

## Requirements

- n8n (latest recommended)
- Telegram Bot created using @BotFather
- Telegram Bot Token

## Importing the Workflow

1. Download the workflow JSON file.
2. Open your n8n instance.
3. Click **Import from File**.
4. Select the JSON file.
5. Add your Telegram credentials.
6. Save the workflow.
7. Activate the workflow.

## Configuration

After importing:

1. Open **Telegram Trigger**.
2. Create or select your Telegram credentials.
3. Open **Send Echo Reply**.
4. Select the same Telegram credentials.
5. Activate the workflow.

## Security

This repository does **not** contain:

- API Keys
- Telegram Bot Tokens
- Passwords
- Secrets
- Personal Credentials

All credentials must be added after importing the workflow.

## Project Structure

```
.
├── telegram-echo-bot.json
└── README.md
```

## License

MIT License
