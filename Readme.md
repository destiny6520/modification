# A Guide On How To Customise Bot Further for Personal Use.

1. [Customising Bot /start Message](https://github.com/destiny6520/modification#Customising-Bot-start-Message)
2. [Changing Bot Commands](https://github.com/destiny6520/modification#Changing-Bot-Commands)
3. [Changing Max Allowed Downloads at Time](https://github.com/destiny6520/modification#Changing-Max-Allowed-Downloads-at-Time)
4. [Customising Bot Stats Message]
5. [Customising Bot Status Message]
6. [Customising Bot Message After Download Complete]
8. 


# Customising Bot /start Message
:octocat: In Order to Customise Bot Start Message You have to Edit few lines in `__main__.py` file. 

You Can Find `__main__.py` File Here ⬇️
```
MirrorX/bot/__main__.py
or
https://github.com/iamLiquidX/MirrorX/blob/master/bot/__main__.py
```
(https://github.com/iamLiquidX/MirrorX/blob/master/bot/__main__.py#L46)

![start Message](https://i.ibb.co/7QmMWjM/start-message-init.png)

In Order to Customise the way you want the start Message of Bot,  modify  `line 46` & `line 47` from `__main__.py` file 

### Example :
Below is the Just an Example of How I Customised start message of my Bot. This is Just to Give you an Idea, You can Customise as You like.
![final start Message](https://i.ibb.co/pxVxbcX/start-message-final.png)


# Customising /help message
:octocat: In Order to Customise Bot Start Message You have to Edit few lines in `__main__.py` file. 

You Can Find `__main__.py` File Here ⬇️
```
MirrorX/bot/__main__.py
or
https://github.com/iamLiquidX/MirrorX/blob/master/bot/__main__.py
```

 (https://github.com/iamLiquidX/MirrorX/blob/9b94f800e2e760f5664884d5c43a5dc6e8f55ce4/bot/__main__.py#L78)

![help](https://i.ibb.co/NpKvxwm/help-init.png)
# Changing Bot Commands
:octocat: In Order to Customise Bot Commands, You have to Edit Commands in `bot_commands.py` File.
You Can Find `bot_commands.py` File Here ⬇️
```
MirrorX/bot/helper/telegram_helper/bot_commands.py
or
https://github.com/iamLiquidX/MirrorX/blob/master/bot/helper/telegram_helper/bot_commands.py
```
### Example :
I Changed My Bot Commands Like Following. You Can easily understand by looking at & edit as you want them.

![Bot_Commands](https://i.ibb.co/fHKCLN5/botcommands.png)

# Changing Max Allowed Downloads & Auto Cancel If No Seeders Available
:octocat: In Order to Change Max Allowable Torrents at a Time & Auto Cancel If No Seeders are Available, You Have to Edit `aria.sh` file

### Max Allowed Downloads
You can limit maximum concurrent downloads by changing the value of `MAX_CONCURRENT_DOWNLOADS` in `aria.sh` file. By default, it's set to 7
### Auto Cancel a Torrent 
You can Set the Bot to Auto Cancel a Torrent, If No Seeders are Available by changing the value of `--bt-stop-timeout` in `aria.sh` file. By default, it's set to 1200. ( It means after 1200 Seconds, Torrent will get Auto Cancelled)

# Customising Bot Message When Bot Auto Cancels the Torrent Due to No Seeders are Available
:octocat: In Order to edit Bot Auto Cancel Message, You Have to Edit `aria2_download.py` file.

You Can Find the `aria2_download.py` file Here ⬇️

```
MirrorX/bot/helper/mirror_utils/download_utils/aria2_download.py
or
https://github.com/iamLiquidX/MirrorX/blob/master/bot/helper/mirror_utils/download_utils/aria2_download.py
```
The Line Which You Have to Edit is `Line 65` https://github.com/iamLiquidX/MirrorX/blob/9b94f800e2e760f5664884d5c43a5dc6e8f55ce4/bot/helper/mirror_utils/download_utils/aria2_download.py#L65

### Example: 
This is How I Modified Auto Cancel Message.
```
𝐘𝐨𝐮𝐫 𝐓𝐨𝐫𝐫𝐞𝐧𝐭 𝐇𝐚𝐬 𝐍𝐨 𝐒𝐞𝐞𝐝𝐬, ⚠️ 𝐃𝐞𝐚𝐝 𝐓𝐨𝐫𝐫𝐞𝐧𝐭 !
```

![Auto cancel](https://i.ibb.co/qrJmg1p/Auto-Cancel.png)

# Customising Bot Stats Message
:octocat: In Order to Customise stats Message, You have to Edit few lines in `__main__.py` file. 

You Can Find `__main__.py` File Here ⬇️
```
MirrorX/bot/__main__.py
or
https://github.com/iamLiquidX/MirrorX/blob/master/bot/__main__.py
```
The Lines Which You Have to Edit are from  `Line 31` to `Line 39` . You can Customise the emojis and Words but Don't Alter the words which in closed with {}
https://github.com/iamLiquidX/MirrorX/blob/9b94f800e2e760f5664884d5c43a5dc6e8f55ce4/bot/__main__.py#L31

# Customising Bot Status UI
