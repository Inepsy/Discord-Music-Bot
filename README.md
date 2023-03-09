# Discord-Music-Bot-V2
A discord bot made with Discord.js that plays music

## Requirements

- [Node](https://nodejs.org/en/) - Version 16 or higher
- [FFMPEG](https://www.ffmpeg.org/)
- [MongoDB](https://www.mongodb.com/)

# Installation

```
# Install the dependencies
npm install

# Configure Discord Bot Token
 In .config
```

# Required permissions

Make sure that your bot has the `applications.commands` application scope enabled, which can be found under the `OAuth2` tab on the [developer portal](https://discord.com/developers/applications/)

Enable the `Server Members Intent` and `Message Content Intent` which can be found under the `Bot` tab on the [developer portal](https://discord.com/developers/applications/)

# Starting the application

```
node index.js
```

# Features & Commands

- /autoplay - Toggle the autoplay of the queue

- /back - Plays the previous track

- /statistic - View your bot statistics

- /channel - It allows you to set the channel or channels where the bot can be used

- /clear - Clears the music queue

- /dj - Allows you to set or reset the DJ role

- /filter - Adds audio filter to ongoing music

- /help - It helps you to get information about bot and commands

- /loop - Turns the music loop mode on or off

- /nowplaying - Provides information about the music being played

- /pause - Stops playing the currently playing music

- /ping - It helps you to get information about the speed of the bot

- /play normal - Play a track

- /playlist - Lets you manage playlist commands

- /queue - It shows you the playlist

- /resume - Start paused music

- /save - It sends and saves the played music to you via dm box

- /search - Used for your music search

- /seek - Set the position of the track

- /servers - The server you want to get information about

- /shuffle - Shuffle the song queue

- /skip - Skips the music being played

- /stop - Plays the previous music again

- /time - Show what minute of the music you are playing

- /volume - Allows you to adjust the music volume

# Common errors

Here is a list of common errors and how you can fix them.

# Dependencies aren't up to date

The packages used in this repository get updated often. That is why it is always worth a try updating those if you get an error like `invalid URL: undefined` or when the bot crashes when running the play command.

# FFMPEG is not installed on the machine running the bot

The `/play` command requires FFMPEG to be installed on the machine that is running the bot. You can download it on the official [FFMPEG website](https://www.ffmpeg.org/).
