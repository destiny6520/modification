# A Guide On How To Customise Bot Further for Personal Use.

1. [Customising Bot /start Message](https://github.com/destiny6520/modification#Customising-Bot-start-Message)
2. [Customising /help message](https://github.com/destiny6520/modification#Changing-Bot-Commands)
3. [Changing Bot Commands](https://github.com/destiny6520/modification#Changing-Bot-Commands)
4. [Changing Max Allowed Downloads at Time](https://github.com/destiny6520/modification#Changing-Max-Allowed-Downloads-at-Time)
5. [Customising Bot Stats Message]
6. [Customising Bot Status Message]
7. [Customising Bot Message After Download Complete]
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
Below is the an Example of How You Can Customise
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
:octocat: In Order to Customise Bot Start Message You have to Edit Commands in `bot_commands.py` File.
You Can Find `bot_commands.py` File Here ⬇️
```
MirrorX/bot/helper/telegram_helper/bot_commands.py
or
https://github.com/iamLiquidX/MirrorX/blob/master/bot/helper/telegram_helper/bot_commands.py
```
### Example :
I Changed My Bot Commands Like Following. You Can easily understand by looking at & edit as you want them.

![Bot_Commands](https://i.ibb.co/fHKCLN5/botcommands.png)

# Changing Max Allowed Downloads & Auto Cancel If No Seeders
:octocat: In Order to Change Max Allowable Torrents at a Time & Auto Cancel If No Seeders are Available, You Have to Edit `aria.sh` file

You can limit maximum concurrent downloads by changing the value of `MAX_CONCURRENT_DOWNLOADS` in `aria.sh` . By default, it's set to 7

You can Set Auto Cancel a Torrent, If No Seeders are Available by changing the value of `--bt-stop-timeout` in `aria.sh` . By default, it's set to 1200   (It means after 1200 Seconds, Torrent will get Auto Canceled)

# Customising Bot Status UI
