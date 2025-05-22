# edu_kbot

# Description

This is a simple bot for educational purposes written on Go.

# Features

- Echoes hello messages
- Echoes unknown messages

# Usage

Start a conversation with the bot and send a message.
Link: [Telegram Bot](https://t.me/devops_tech_fang_edu_bot)

# Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/devops-tech-fang/edu_kbot.git
   cd edu_kbot
   ```
2. Set up your environment:

    - Telegram Bot Token
      ```bash
      export TELE_TOKEN=<your_telegram_bot_token>
      ```

3. Build the bot:

   ```bash
   go build -ldflags "-X 'github.com/devops-tech-fang/edu_kbot/cmd.appVersion=1.0.0'" -o edu_kbot
   ```

4. Run the bot:

   ```bash
    ./edu_kbot
    ```