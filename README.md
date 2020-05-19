# meething-discord-bot
Discord Bot dispatching free Video Meething invites!

### Create a Discord Bot
Follow the guide at https://discordpy.readthedocs.io/en/latest/discord.html to create an authorize your Discord bot

Once your *Auth Token* is generated configure it in `config.json`

### Start
Execute your bot with `pm2`
```
npm install
pm2 start bot.js --name bot
```
