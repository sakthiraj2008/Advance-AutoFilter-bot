<p align="center">
  <img src="https://camo.githubusercontent.com/3182669c1cffde4a5f4b429b7693fddbdfac8e454ab9a381978652d2fe89cd28/68747470733a2f2f696d672e6672656570696b2e636f6d2f7072656d69756d2d70686f746f2f6d616e2d737569742d69732d706c6179696e672d63686573735f313037323133382d3232373037302e6a70673f773d383236" alt="Tactition-Filter-Bot Logo">
</p>
<h1 align="center">
  TACTITION FILTER BOT
</h1>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com/?lines=Welcome+To+Tactition+Filter+Bot!" alt="Typing SVG">
</p>

## ✨ Main Features

- ✅ Clone Feature & On/Off Control
- ✅ Multiple Database Support & On/Off Toggle
- ✅ Premium Plan Feature
- ✅ Refer To Get Premium
- ✅ AI Spell Check
- ✅ Custom Force Subscribe
- ✅ Rename Feature & On/Off Toggle
- ✅ Premium And Refer On/Off Toggle
- ✅ Stream Feature On/Off Toggle
- ✅ URL Shortener On/Off Toggle
- ✅ PM Search On/Off Toggle
- ✅ Request To Join Force Subscribe With Auto File Send
- ✅ Custom Stream With Multi-Player Support
- ✅ Language, Season, Quality, Episode & Year Selection Options
- ✅ Auto Approve & On/Off Toggle
- ✅ Custom URL Shortener Support
- ✅ Token Verification & On/Off Toggle
- ✅ Send All Button
- ✅ Custom Tutorial Button
- ✅ Bot PM File Auto Delete

- **[New] Permanent Link Support** – links never expire, even if the bot is deleted or copyright-struck  
- **[New] Advanced Encoding System** – secure, efficient payload encoding  
- **[New] Expanded Website Support** – share from more sources seamlessly  
- **[New] Short-Net Website Links** – generates compact URLs that redirect straight to your file page  
- **[New] Fixed Link Generation** – robust, error-free deep-link creation  
- **[New] Full Subscription on `/start`** – users get full access immediately when they hit “Start”
- **[New] Two-Way Messaging System** – enables users and admins to communicate via the bot, with all messages and replies logged in the log channel  

> **Note**: You can turn on or off every feature. Just use the features you want by turning them on.

Join my [Update Channel](https://telegram.dog/tactition) for more updates regarding this repo.

### 📹 How To Deploy: [Video Tutorial](https://youtu.be/3SJR7vH2kRo)

## 🤖 Commands

```
• /start - Start the bot
• /clone - Create your own clone auto filter bot
• /index - Index files from your channel
• /setskip - Skip messages when indexing files
• /logs - Get recent errors
• /stats - Get database file status
• /connections - See all connected groups
• /settings - Open settings menu
• /filter - Add manual filters
• /filters - View filters
• /connect - Connect to PM
• /disconnect - Disconnect from PM
• /del - Delete a filter
• /delall - Delete all filters
• /deleteall - Delete all indexed files
• /delete - Delete a specific file from index
• /info - Get user info
• /id - Get Telegram IDs
• /library or /bookinfo - Fetch info from library of books
• /search - Search from various sources like libGen Zlib
• /users - Get list of users and IDs
• /chats - Get list of chats and IDs
• /leave - Leave a chat
• /disable - Disable a chat
• /enable - Re-enable chat
• /ban - Ban a user
• /unban - Unban a user
• /channel - Get list of connected channels
• /broadcast - Broadcast a message to all users
• /grp_broadcast - Broadcast to all connected groups
• /batch - Create link for multiple posts
• /link - Create link for one post
• /set_template - Set custom IMDb template for groups
• /gfilter - Add global filters
• /gfilters - View all global filters
• /delg - Delete a specific global filter
• /delallg - Delete all global filters
• /deletefiles - Delete PreDVD and CamRip files
• /add_premium - Add user to premium list
• /remove_premium - Remove user from premium list
• /plan - Check plan details
• /myplan - Check your plan stats
• /shortlink - Set URL shortener in your group
• /setshortlinkoff - Turn off shortlink in your group
• /setshortlinkon - Turn on shortlink in your group
• /shortlink_info - Check group shortlink and tutorial details
• /set_tutorial - Set shortener tutorial URL
• /remove_tutorial - Remove tutorial URL
• /restart - Restart the bot server
• /fsub - Add force subscribe channel in group
• /nofsub - Remove force subscribe in your group
• /rename - Rename your file
• /set_caption - Add caption for renamed files
• /see_caption - See your saved caption
• /del_caption - Delete your saved caption
• /set_thumb - Add thumbnail for renamed files
• /view_thumb - View your saved thumbnail
• /del_thumb - Delete your saved thumbnail
• /stream - Generate stream and download link
• /telegraph - Get telegraph link for files under 5MB
• /stickerid - Get sticker ID and unique ID
• /font - Get different font styles for text
• /repo - Search and get repository links
• /purgerequests - Delete all join requests from database
• /totalrequests - Get total number of join requests
• /message userID Message  - to send message from bot to User and then reply from log channel to continue messaging
```

## 🛠️ Variables

### Required Variables
* `BOT_TOKEN`: Create a bot using [@BotFather](https://telegram.dog/BotFather), and get the Telegram API token.
* `API_ID`: Get this value from [telegram.org](https://my.telegram.org/apps)
* `API_HASH`: Get this value from [telegram.org](https://my.telegram.org/apps)
* `CHANNELS`: File Channel, Username or ID of channel/group. Separate multiple IDs by space
* `ADMINS`: Username or ID of Admin. Separate multiple Admins by space
* `DATABASE_URI`: [mongoDB](https://www.mongodb.com) URI. Get this value from [mongoDB](https://www.mongodb.com). For more help watch this [video](https://youtu.be/DAHRmFdw99o)
* `LOG_CHANNEL`: A channel to log bot activities. Make sure bot is an admin in the channel.

## 🚀 Deployment Options

<details>
<summary><b>Deploy To Heroku</b></summary>
<p>
<br>
<b>First connect your GitHub account, then select the repo and deploy with Procfile.</b>
</p>
</details>

<details>
<summary><b>Deploy To Koyeb</b></summary>
<br>
<b>The fastest way to deploy the application is to click the Deploy to Koyeb button below.</b>
<br>
<br>

[![Deploy to Koyeb](https://www.koyeb.com/static/images/deploy/button.svg)](https://app.koyeb.com/deploy?type=git&repository=github.com/Tactition/Tactition-Filter-Bot&branch=main&name=Tactition-Filter-Bot)
</details>

<details>
<summary><b>Deploy To Render</b></summary>
<br>
<b>
Use these commands:
<br>
<br>
• Build Command: <code>pip3 install -U -r requirements.txt</code>
<br>
<br>
• Start Command: <code>python3 bot.py</code>
<br>
<br>
Go to https://uptimerobot.com/ and add a monitor to keep your bot alive.
<br>
<br>
Use these settings when adding a monitor:</b>
<br>
<br>
<img src="https://telegra.ph/file/a79a156e44f43c9833b50.jpg" alt="render template">
<br>
<br>
<b>Click on the below button to deploy directly to render ↓</b>
<br>
<br>
<a href="https://render.com/deploy?repo=https://github.com/Tactition/Tactition-Filter-Bot/tree/main">
<img src="https://render.com/images/deploy-to-render-button.svg" alt="Deploy to Render">
</a>
</details>

<details>
<summary><b>Deploy To VPS</b></summary>

```bash
git clone https://github.com/Tactition/Tactition-Filter-Bot.git
cd Tactition-Filter-Bot
pip3 install -U -r requirements.txt
# Edit info.py with variables as given above
python3 bot.py
```
</details>

<hr>

## 🙏 Credits
- Thanks to [Pyrogram Library](https://github.com/pyrogram/pyrogram) & [Pyrofork Library](https://github.com/Mayuri-Chan/pyrofork)
- Thanks to [Tactition](https://telegram.dog/tactition) for creating and maintaining this repo
- Thanks to [Eva Marie](https://t.me/TeamEvamaria) for the base repo
- Thanks to everyone who contributed to this project

## 📞 Contact

[![Contact Developer](https://img.shields.io/static/v1?label=Contact+Developer&message=On+Telegram&color=critical)](https://telegram.me/Tactition)

Feel free to fork the repo and edit as per your needs.

## ⚠️ Disclaimer
[![GNU Affero General Public License 2.0](https://www.gnu.org/graphics/agplv3-155x51.png)](https://www.gnu.org/licenses/agpl-3.0.en.html#header)  

Licensed under [GNU AGPL 2.0.](LICENSE)  
Selling the code to other people for money is **strictly prohibited**.