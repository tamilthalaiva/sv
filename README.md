# Telegram Movie Bot

<p align="center">
  <a href="https://www.python.org">
    <img src="http://ForTheBadge.com/images/badges/made-with-python.svg" width ="250">
  </a>
  <a href="https://t.me/ShadowKing9o">
    <img src="https://telegra.ph/file/93a7e33b65dc93349c0be.jpg" width="250">
  </a><br>
  <a href="https://t.me/ShadowsArena">
    &nbsp;<img src="https://img.shields.io/badge/Shadow%20Arena-Channel-blue?style=plastic&logo=Telegram" width="130" height="18">&nbsp;
  </a>
  <a href="https://t.me/+9Zhp_GdQVctiNjc1">
    &nbsp;<img src="https://img.shields.io/badge/Movie%20Addaa-Group-blue?style=plastic&logo=Telegram" width="130" height="18">&nbsp;
  </a>
  <br>
  <a href="https://github.com/MasterShad0w/IMDb-Movie-Bot/stargazers">
    <img src="https://img.shields.io/github/stars/MasterShad0w/IMDb-Movie-Bot?style=social">
  </a>
  <a href="https://github.com/MasterShad0w/IMDb-Movie-Bot/fork">
    <img src="https://img.shields.io/github/forks/MasterShad0w/IMDb-Movie-Bot?label=Fork&style=social">
  </a>  
  <br>
  <a href="https://youtube.com/channel/UCqVIzF-2AhO_pY4uo8Rr5Hg">
    <img src="https://img.shields.io/badge/Subscribe-Shadow%20Arena-%23FA0606?style=for-the-badge&logo=Youtube" width="300">
  </a>
</p>

## Features

- [x] Auto Filter
- [x] Manuel Filter
- [x] IMDB
- [x] Admin Commands
- [x] Broadcast
- [x] Index
- [x] IMDB search
- [x] Inline Search
- [x] Random pics
- [x] ids and User info 
- [x] Stats, Users, Chats, Ban, Unban, Leave, Disable, Channel
- [x] Spelling Check Feature
- [x] File Store

## Variables

### Required Variables
* `BOT_TOKEN`: Create a bot using [@BotFather](https://telegram.dog/BotFather), and get the Telegram API token.
* `API_ID`: Get this value from [Shadow Scrapper](https://t.me/ShadowScrapperBot)
* `API_HASH`: Get this value from [Shadow Scrapper](https://t.me/ShadowScrapperBot)
* `CHANNELS`: Username or ID of channel or group. Separate multiple IDs by space
* `ADMINS`: Username or ID of Admin. Separate multiple Admins by space
* `DATABASE_URI`: [mongoDB](https://www.mongodb.com) URI. Get this value from [mongoDB](https://www.mongodb.com). For more help watch this [video](https://youtu.be/ttX4OEYwpCQ)
* `DATABASE_NAME`: Name of the database in [mongoDB](https://www.mongodb.com). For more help watch this [video](https://youtu.be/ttX4OEYwpCQ)
* `LOG_CHANNEL` : A channel to log the activities of bot. Make sure bot is an admin in the channel.
### Optional Variables
* `IMDB`: Imdb, the view of information when making True/False.
* `SINGLE_BUTTON`: choose b/w single or double buttons True/False.

## larger result buttons
larger results will be better for reading.

at now:
![139601786-7af37bab-549d-4f96-a65f-96e2d09b5ce0](https://user-images.githubusercontent.com/77600757/143565765-cced52c4-45f6-40e2-bfbf-2e2efd6f811f.png)

add optional larger result buttons:
![139601808-04b7726e-3e58-48a1-bb1a-d946f1d3fdcd](https://user-images.githubusercontent.com/77600757/143565860-4797e96f-5a3c-4acd-8484-6fb6a2c99bbc.png)
* `P_TTI_SHOW_OFF`: Customize Result Buttons to Callback or Url by (True = url / False = callback).
* `PICS`: Telegraph links of images to show in start message.( Multiple images can be used separated by space )
* `FILE_STORE_CHANNEL`: Channel from were file store links of posts should be made. Separate multiple IDs by space
* Check [info.py](info.py) for more

## Deploy
You can deploy this bot anywhere.

<details><summary>Deploy to Heroku</summary>
<p>
<br>
<a href="https://heroku.com/deploy?template=https://github.com/MasterShad0w/IMDb-Movie-Bot">
  <img src="https://www.herokucdn.com/deploy/button.svg" alt="Deploy">
</p>
</details>

<details>
  <summary><b>Deploy to Railway</b></summary>
<br/>

<p align="left">
<a href="https://railway.app/new/template?template=https%3A%2F%2Fgithub.com%2FMasterShad0w%2FIMDb-Movie-Bot"
">
     <img height="30px" src="https://railway.app/button.svg">
  </a>
</p>

</details>

<details><summary>Deploy to VPS</summary>
<p>
<pre>
git clone https://github.com/MasterShad0w/IMDb-Movie-Bot
# Install Packages
pip3 install -r requirements.txt
Edit info.py with variables as given below then run bot
python3 bot.py
</pre>
</p>
</details>


## Admin commands
```
• /logs - to get the rescent errors
• /stats - to get status of files in db.
* /filter - add manual filters
* /filters - view filters
* /connect - connect to PM.
* /disconnect - disconnect from PM
* /del - delete a filter
* /delall - delete all filters
* /deleteall - delete all index(autofilter)
* /delete - delete a specific file from index.
* /batch - to create link for multiple posts
* /link - to create link for one post
* /info - get user info
* /id - get tg ids.
* /imdb - fetch info from imdb.
• /users - to get list of my users and ids.
• /chats - to get list of the my chats and ids 
• /index - to add files from a channel
• /leave - to leave from a chat.
• /disable - do disable a chat.
* /enable - re-enable chat.
• /ban_users - to ban a user.
• /unban_users - to unban a user.
• /channel - to get list of total connected channels
• /broadcast - to broadcast a message to all Eva Maria users
```
## Support
[![telegram badge](https://img.shields.io/badge/Telegram-Group-30302f?style=flat&logo=telegram)](https://t.me/+9Zhp_GdQVctiNjc1)
[![telegram badge](https://img.shields.io/badge/Telegram-Channel-30302f?style=flat&logo=telegram)](https://t.me/ShadowsArena)

## Credits 
* [![Shadow King](https://img.shields.io/static/v1?label=Shadow-King&message=devs&color=critical)](https://telegram.dog/ShadowKing9o)

## Disclaimer
[![GNU Affero General Public License 3.0](https://www.gnu.org/graphics/agplv3-155x51.png)](https://www.gnu.org/licenses/agpl-3.0.en.html#header)    
Licensed under [GNU AGPL 3.0.](https://github.com/ZauteKm/Dingdi/blob/master/LICENSE)
Selling The Codes To Other People For Money Is *Strictly Prohibited*.
