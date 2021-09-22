Setup:

How to get API:
-Go to Discord Developer Portal > Create Application > Bot > 'Add Bot' > 'Click Copy under Build-A-Bot

Where to put it:
-Put API key in a .env file then put .env file path in a .gitignore

What packages need to be installed:
-sudo apt install python pip3
-discord.py
-sudo pip3 install python-dotenv



Usage:

Describe code changes I made:
-I added a text function to bot.py that would respond with cat quotes. I fixed the Brooklyn 99 quotes function to work and post quotes. 

Commands for Discord Bot:
-'!jack'
-!towel'
-!99'

Responses from Bot:
-For '!jack' one response is: "I'm a cat, bark bark!"
-For '!towel' one response is: "In the beginning the Universe was created. This has made a lot of people very angry and been widely regarded as a bad move."
-For '!99' one response is "I'm the human form of the :100: emoji."


Research:

Possible solutions to make your bot run 24/7:
-One possible solution is hosting it on Heroku that way you can makes changes to the bot and push it like github without the bot going offline. 

-Another solution is to install screen with 'sudo apt install screen' then run 'screen -S mybot, and finally do CTRL+A then D to detach yourself and keep the bot running while you do other cool sys admin stuff.
