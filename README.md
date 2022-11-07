# discord-bot-lua-obfuscator (python 3.7.9)

# Live Preview: https://discord.gg/STaq3UDbqQ
<img src="https://i.imgur.com/DlO9XIa.png">

# Original code: https://github.com/yunglean4171
<br>
<b>Update: Don't ask [yunglean4171](https://github.com/yunglean4171) for support.<br>
Just [join my discord](https://discord.gg/STaq3UDbqQ) and I will gladly help you.<br><br>

Simple discord bot written in python for obfuscating lua files sent by a user in a specific channel (also works in direct messages). 
Useful for securing your lua scripts (work with fivem/roblox etc resources).
<br><br><b>This is a modified version for repl and heroku.</b>
If you are trying to run this from your desktop just use the original source from yunglean4171: https://github.com/yunglean4171/discord-bot-lua-obfuscator<br><br>


In repl start a blank template and import from github.com. https://github.com/jmesfo0/discord-bot-lua-obfuscator <br>
In repl put DISCORD_TOKEN in system environment variables. <br>
In repl shell type the following:
```
chmod +x bin/*
pip install -r requirements.txt
python bot
```
Enjoy your free private obfuscator.<br>


## Required python modules:
- Discord.py 
- requests
- Flask



## Heroku Guide

Fork this repoistory.<br />
Create an app on Heroku.<br />
Select Deploy->Github and connect your account.<br />
Put repo name in.<br />
Select Enable Automatic Deploys then Deploy Branch<br />
Go to Settings->Reveal Config Vars<br />
Add DISCORD_TOKEN in environmental variables.<br />
Done.

I have also made a simple version of this bot plugin for Red-DiscordBot: https://github.com/jmesfo0/jmes-cogs
