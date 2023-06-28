<p align="center">
  <img src="https://telegra.ph/file/40d57ed99e47ec4aa468d.jpg" alt="MafiaMoviesBot Logo">
</p>
<h1 align="center">
  <b> 𝗠𝗮𝗳𝗶𝗮𝗠𝗼𝘃𝗶𝗲𝘀 𝗕𝗼𝘁 </b>
</h1>

## ⚡️Features
- [x] Auto Filter
- [x] Manual Filter
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
- [x] Custom File Caption
- [x] Group Broadcast 
- [x] AutoFilter auto delete
- [x] Junk Group & users clearing on database 
- [x] Global Filter
- [x] Url Shortner in AutoFilter 
- [x] Custom Button Lock
- [x] image editor & background remover
- [x] Telegraph, pin, json, password generator
- [x] Ban, mute, unmute, etc... Group manager 
- [x] Custom Welcome message
- [x] Advanced Admin Panel
- [x] Photo Changing in All buttons
- [x] Custom Start message
- [x] Custom Button Alter message
- [x] advanced status (disk, cpu, ram, uptime..)
 
 ### Required Variables
* `BOT_TOKEN`: Create a bot using [@BotFather](https://telegram.dog/BotFather), and get the Telegram API token.
* `API_ID`: Get this value from [telegram.org](https://my.telegram.org/apps)
* `API_HASH`: Get this value from [telegram.org](https://my.telegram.org/apps)
* `CHANNELS`: Username or ID of channel or group. Separate multiple IDs by space
* `ADMINS`: Username or ID of Admin. Separate multiple Admins by space
* `DATABASE_URI`: [mongoDB](https://www.mongodb.com) URI.
* `DATABASE_NAME`: Name of the database in [mongoDB](https://www.mongodb.com).
* `LOG_CHANNEL` : A channel to log the activities of bot. Make sure bot is an admin in the channel.
* `Support Chat` : Username of a Support Group / ADMIN. ( Should be username without @ and not ID )

### Optional Variables
* `PICS`: Telegraph links of images to show in start message.( Multiple images can be used seperated by space )
* `USE_CAPTION_FILTER` : Whether bot should use captions to improve search results. (True False)
* `CUSTOM_FILE_CAPTION` : A custom file caption for your files. formatable with , file_name, file_caption, file_size, Read Readme.md for better understanding
* `CACHE_TIME` : The maximum amount of time in seconds that the result of the inline query may be cached on the server
* `IMDB` : Imdb, the view of information when making True/False
* `SINGLE_BUTTON` : choose b/w single or double buttons 
* `P_TTI_SHOW_OFF` : Customize Result Buttons to Callback or Url by (True = url / False = callback)

### Url Shortner Variable
* `SHORT_URL` : Url Of Shortner Site You Use
* `SHORT_API` : Api Key Of Shortner Which You Use

## Deploy
<a target="_blank" href="https://app.koyeb.com/deploy?type=git&repository=github.com/MafiaDarkWeb/MafiaMoviesBot&branch=master&name=mafiamoviesbot"><img alt="Deploy to Koyeb" src="https://binbashbanana.github.io/deploy-buttons/buttons/remade/koyeb.svg"></a>


<details><summary>Deploy To Heroku</summary>
<p>
<br>
<a href="https://heroku.com/deploy?template=https://github.com/MafiaDarkWeb/MafiaMoviesBot">
  <img src="https://www.herokucdn.com/deploy/button.svg" alt="Deploy">
</a>
</p>
</details>

<details><summary>Deploy To VPS</summary>
<p>
<pre>
git clone https://github.com/MafiaDarkWeb/MafiaMoviesBot
# Install Packages
pip3 install -U -r requirements.txt
Edit info.py with variables as given below then run bot
python3 bot.py
</pre>
</p>
</details>


## Commands
```
• /start - check bot alive
• /ping - pong
* /settings - get settings
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
* /info - get user info
* /id - get tg ids.
* /imdb - fetch info from imdb.
• /users - to get list of my users and ids.
• /chats - to get list of the my chats and ids 
• /index  - to add files from a channel
• /leave  - to leave from a chat.
• /disable  -  do disable a chat.
* /enable - re-enable chat.
• /ban  - to ban a user.
• /unban  - to unban a user.
• /channel - to get list of total connected channels
• /broadcast - to broadcast a message to all LazyPrincess users
• /batch - to create link for multiple posts
• /link - to create link for one post
• /set_caption - to set new custom caption #renaming_feature
• /del_caption - To delete custom caption #renaming_feature
• /viewthumb - To view custom thumbnail #renaming_feature
• /delthumb - To delete custom thumbnail #renaming_feature

```
## Support
[![telegram badge](https://img.shields.io/badge/Telegram-Bot-30302f?style=flat&logo=telegram)](https://telegram.dog/MafiaMovies_Bot)
[![telegram badge](https://img.shields.io/badge/Telegram-Channel-30302f?style=flat&logo=telegram)](https://telegram.dog/+VfeOHeNBNFU4NDc9)

### Note

[Join Movie Channel](https://t.me/+VfeOHeNBNFU4NDc9): MAFIA MOVIES 🎁

## Disclaimer
[![GNU Affero General Public License 2.0](https://www.gnu.org/graphics/agplv3-155x51.png)](https://www.gnu.org/licenses/agpl-3.0.en.html#header)    
Licensed under [GNU AGPL 2.0.](https://github.com/EvaMariaTG/evamaria/blob/master/LICENSE)
Selling The Codes To Other People For Money Is *Strictly Prohibited*.
