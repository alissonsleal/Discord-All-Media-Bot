# Discord-All-Media-Bot
This Discord bot can play music from most media sources(YouTube, Facebook, Instagram, SoundCloud...)

You need a Discord oAuth code, you can get one by following this guide: https://github.com/Chikachi/DiscordIntegration/wiki/How-to-get-a-token-and-channel-ID-for-Discord

Just copy the oAuth snippet into the OAUTH placeholder in the upper part of the code.
You can add a prefix on the prefix placeholder in the upper part of the code.

Python 3.7 won't work, you'll need it updated up to 3.6.

The bot uses the discord.py, ffmpeg and youtube_dl modules. Just install the requirements.txt on the command line with: pip install -r requirements.txt

# How the bot Works:
Suppose that the chosen prefix for the bot is " - " (Just change the 'PREFIX_HERE' placeholder in the code)
You need to enter a Discord Voice Channel, type -join, then -play (link). You can make the bot leave the voice channel by typing -leave.
