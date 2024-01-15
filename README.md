# discord-whitelist-bot
Simulate discord activity on channels to get whitelist (NFT or tokensale). 
Bot randomly replies for messages in discord chat using messages from `reactions.txt` and `message.txt` files OR using emoji.
Written on .Net Framework with xNetHTTP library and DiscordAPI.

![alt text](https://github.com/ak1rahunt3r/discord-whitelist-bot/blob/main/discordWL.png?raw=true)
![alt text](https://github.com/ak1rahunt3r/discord-whitelist-bot/blob/main/discordWLtext.png?raw=true)

Requirements:
- Discord tokens for accounts you need
- Channel and chat names

Setup:
- Launch app
- Add info to table for each account:
  - `accName` - account name or ethereum address
  - `accToken` - discord account token
  - `servName` - server name
  - `servChat` - server chat to send messages
  - `notes` - your notes for this account
- Set messaging mode:
  - `replyGmGn` - send GM/GN reply if someone writes GM/GN
  - `replyWow` - send reaction from `reactions.txt` for someones message
  - `meMessage` - send message from `message.txt`
- Set emoji mode:
  - `reactEmoji` - random positive reaction
  - `reactStickers` - random positive sticker
-  extract files with password `midTeQ7Bv`
-  Start bot
- Bot can be hidden to tray
