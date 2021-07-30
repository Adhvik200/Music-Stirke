# Music-bot
A complete code to download for a music bot. Using a module (discord-player) 🎧


### ⚡ Installation

Well, let's start by downloading the code.
Go to the folder `config` then the file `bot.js`.
For the bot to be able to start, please complete the file with your credentials as follows :

# For emojis

```js
emojis: {
    off: ':x:',
    error: ':warning:',
    queue: ':bar_chart:',
    music: ':musical_note:',
    success: ':white_check_mark:',
}
```

# For configuration

```js
discord: {
    prefix: 'PREFIX',
    activity: 'ACTIVITY',
}
```


- `prefix`, the prefix that will be set to use the bot.
- `activity`, the activity of the bot.

# For Client Login

Make an `.env` file and
```js
token = "You're Bot Token here"
```
- `token`, the token of the bot available on the [Discord Developers Portal](https://discordapp.com/developers/applications) section.


- To start the bot :

```
#With Node
node index.js
```

All you have to do is turn on your bot !

### 🎵 Music commands

```
play <name/URL>, play music in a voice channel.
search <name>, open a panel to choose a music and then play it.
pause, pause the current music.
resume, puts the current music back on.
queue, see the next songs.
clear-queue, remove music in the queue.
shuffle, to mix the queue.
nowplaying, see music in progress.
loop, to enable or disable the repeat function.
volume <1 - 100>, change the volume.
skip, skip to next music.
stop, stop all music.
filter <filter>, add / remove filter.
w-filters, see filters.
```

### 💡 General commands

```
ping, see the bot latency.
help, see the list of available commands.
debug, see number of voice connections.
```

### 🏓 Utilities (to change the code)


This is used with [discord.js](https://www.npmjs.com/package/discord.js) and [discord-player](https://www.npmjs.com/package/discord-player).
