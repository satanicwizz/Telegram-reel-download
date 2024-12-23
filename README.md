# Instagram Reel Download Bot

A Telegram bot that downloads Instagram reels.

## Setup

1. Create a new bot on Telegram:
   - Message [@BotFather](https://t.me/botfather) on Telegram
   - Use the `/newbot` command
   - Follow the instructions to create your bot
   - Copy the bot token provided

2. Configure the bot:
   - Add your Telegram bot token to the `.env` file:
     ```
     TELEGRAM_BOT_TOKEN=your_token_here
     ```

3. Install dependencies:
   ```bash
   npm install
   ```

4. Start the bot:
   ```bash
   npm start
   ```

## Usage

1. Start a chat with your bot on Telegram
2. Send the bot an Instagram Reel link
3. The bot will download and send you the video

## Commands

- `/start` - Welcome message
- `/help` - Usage instructions
