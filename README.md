# MusicBot

A powerful and easy-to-use Discord music bot with support for YouTube, Spotify, SoundCloud, and more. Fully customizable and self-hosted.

## Features

- High-quality audio playback  
- Multi-source support (YouTube, Spotify, etc.)  
- Easy configuration via `.env` and `config.js`  
- Simple setup and self-hosting  

## Getting Started

1. Clone the repository  
   ``git clone https://github.com/Unknownzop/MusicBot.git``

2. Navigate into the project directory  
   ``cd MusicBot``

3. Install dependencies  
   ``npm install``

4. Set up environment variables  
   ``cp .env.example .env``  
   Edit ``.env`` with your bot token, client ID, guild ID, and Lavalink values.

   Example configuration:
   ```env
   DISCORD_TOKEN=YOUR_BOT_TOKEN
   CLIENT_ID=1544280709223555082
   GUILD_ID=1544249019876769863
   NO_PREFIX_USERS=1105509323511169086
   LAVALINK_HOST=127.0.0.1
   LAVALINK_PORT=2333
   LAVALINK_PASSWORD=YOUR_PASSWORD
   ```

5. (Optional) Customize settings in  
   ``config.js``

6. Start the bot  
   ``node index.js``

## License

This project is licensed under the GPL-3.0 License  
[View License](https://github.com/Unknownzop/MusicBot/blob/main/LICENSE)
