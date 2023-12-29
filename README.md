# Discord Bot Readme

This repository contains a simple Discord bot implemented using the Discord.js library. The bot is designed to reply with a greeting message when it detects a new message in a guild channel.

## Requirements
- Node.js: Make sure you have Node.js installed on your machine. You can download it from [https://nodejs.org/](https://nodejs.org/)

## Installation
1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/Satyam5665/discord_bot.git
   ```

2. Navigate to the project directory:
   ```bash
   cd discord-bot
   ```

3. Install the required dependencies:
   ```bash
   npm install
   ```

## Configuration
1. Create a new Discord bot on the [Discord Developer Portal](https://discord.com/developers/applications).
2. Copy the token provided for your bot.
3. Create a `.env` file in the project root and add the following line, replacing `"YOUR_BOT_TOKEN"` with the actual token:
   ```plaintext
   token=YOUR_BOT_TOKEN
   ```

## Usage
Run the bot using the following command:
```bash
npm start
```

The bot will now be online and respond to messages in the guild channels it has access to. By default, it replies with a simple "Hi From Bot" message.

## Customization
Feel free to customize the bot's behavior by modifying the `messageCreate` event handler in the `index.js` file. You can change the reply message or add additional functionality to suit your needs.

