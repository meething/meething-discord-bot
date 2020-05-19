<img src="https://i.imgur.com/XS79fTC.png" width=200> <img width="100" alt="mozilla-builders" src="https://user-images.githubusercontent.com/1423657/81992335-85346480-9643-11ea-8754-8275e98e06bc.png">

### Meething : Discord Bot
Discord Bot dispatching free Video Meething invites!

![image](https://user-images.githubusercontent.com/1423657/82379720-b045fc00-9a27-11ea-8389-171859ec8dcd.png)


#### Create a Discord Bot
Follow the guide at https://discordpy.readthedocs.io/en/latest/discord.html to create an authorize your Discord bot

Once your *Auth Token* is generated configure it in `config.json`

#### Start
Execute your bot with `pm2`
```
npm install
pm2 start bot.js --name bot
```
