## Requirements
- Python 3.6 and up - https://www.python.org/downloads/
- git - https://git-scm.com/download/

## Useful to always have
Keep [this](https://discordpy.readthedocs.io/en/latest/) saved somewhere, as this is the docs to discord.py@rewrite.
All you need to know about the library is defined inside here, even code that I don't use in this example is here.

## How to setup
1. Make a bot [here](https://discordapp.com/developers/applications/me) and grab the token
![Image_Example1](https://i.alexflipnote.dev/f9668b.png)

2. Rename the file **config.json.example** to **config.json**, then fill in the required spots, such as token, prefix and game

3. To install what you need, do **pip install -r requirements.txt**<br>
(If that doesn't work, do **python -m pip install -r requirements.txt**)<br>
`NOTE: Use pip install with Administrator/sudo`

4. Start the bot by having the cmd/terminal inside the bot folder and type **python index.py**

5. You're done, enjoy your bot!

## FAQ
Q: I don't see my bot on my server!<br>
A: Invite it by using this URL: https://discordapp.com/oauth2/authorize?client_id=CLIENT_ID&scope=bot<br>
Remember to replace **CLIENT_ID** with your bot client ID

Q: There aren't that many commands here...<br>
A: Yes, I will only provide a few commands to get you started, maybe adding more later.

Q: Why the beer with the discord logo?<br>
A: Because the framework is made so simple that even a drunk guy can set it up.

### Repl.it
You can run this on Repl.it!
[![Run on Repl.it](https://repl.it/badge/github/AlexFlipnote/discord_bot.py)](https://repl.it/github/AlexFlipnote/discord_bot.py)
Make sure to setup **config.json** in the way stated above.
