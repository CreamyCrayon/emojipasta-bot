## Description

It's a discord bot for converting text to emojipasta.

CREDITS: Thanks to Kevinpgalligan for his emojipasta structure and emoji mappings.
These saved a lot of my time.

## Requirements
```
pip3 install discord
cd emojipasta-bot
sudo python3 setup.py install
```

## Usage

Before the use, get an API token from Discord official.
Put it in emojipastabot.py file. (client.run)
And then:
```
cd emojipasta-bot/build/lib/emojipastabot
python3 emojipastabot.py
```

## Bot Command On Discord
Use & as prefix, and add double quotation marks. &help if you need help.
For example:
```
&pasta "This is a shitty bot"
```


## Known Bugs
1: if there are another double quotation marks inside the double quotation marks, the bot wouldn't work.
you can use '' instead of "" to prevent from this.
```
&pasta "she said, 'you're soooo gay.'"
```

## Invite My Bot to Your Server!
You can use this link to invite my bot to your server:
https://discordapp.com/oauth2/authorize?client_id=429662497172357123&scope=bot&permissions=8
Also if you have any problems, add me on discord: toiletplunger#8909