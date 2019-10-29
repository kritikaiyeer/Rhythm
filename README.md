# Rhythm Discord MusicBot
***  
This module is a simple Node.js based music extension/bot for Discord.js projects using YouTube.

__The commands available are: (default names)__  
* `play <url>|<search string>`: Play audio from YouTube.
* `skip `: Skip a song or multi songs with skip .
* `stop`: Stop the current playing song.  

# Installation
***  
__Pre-installation:__  
1. `npm install discord.js`  
It is recommended to have the stable branch.  

2. `ffmpeg installed` __correctly__ for your OS/env.  
Allows the bot to join voice as well as speak.  

3. `npm install ytdl-core` and `npm install opusscript`  
Required for voice. Discord.js _prefers_ node-opus.  

