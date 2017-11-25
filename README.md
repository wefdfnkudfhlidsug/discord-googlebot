# Google based discord-bot.
Simple Google bot made with various apis
> You must have [Node](https://nodejs.org/) installed to run this bot.

## Getting started

```
$ git clone https://github.com/OblivionSan/discord-googlebot.git
$ npm install
```
Create a discord bot token [here](https://discordapp.com/developers/applications/me) and replace it where you see **TOKEN_HERE**, replace **PREFIX** to your prefered prefix.

**config.json** example
```json
{
  "prefix" : "g!",
  "token" : "TOKEN_HERE"
}
```
Invite your bot to your discord server using the link given. Make sure to replace `<client-id>` with your bots [client id](https://discordapp.com/developers/applications/me). 
```
https://discordapp.com/oauth2/authorize?&client_id=<CLIENT ID>&scope=bot&permissions=0
```
To start your bot, simply open up command prompt in your bots directory and then type the following.
```
$ node app.js
```

## Built with
> [Discord.js](https://discord.js.org/#/) - Node Module used.

> [Google](https://www.npmjs.com/package/google) - Node Module used.

> [Google-Translate-api](https://www.npmjs.com/package/google-translate-api) - Node Module used.

> [Node](https://nodejs.org/) - JavaScript run-time environment.

## Author
- **OblivionSan** - [@OblivionSan](https://twitter.com/OblivionSan) | [Discord Server](https://discord.gg/kxNeGRC) | [Website](https://oblivionsan.tk)
