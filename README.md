# BattleBot
A Discord bot that rolls dice and stuff.
The original boilerplate code and the original /roll command was stolen from Eruantien. Much thanks to him for that.

Type /help on any server on which Battlebot exists to get a list of the commands the bot will respond to.

## Installation
1. Go to [https://discordapp.com/developers/applications/me](Discord Developers) and create a new application. Name it something memorable.
2. Click the button to **Create a Bot User**.
3. **Click** the link **to reveal** the bot user **token**.
4. Copy the token somewhere (e.g. to your system clipboard). You'll need it later.
5. Make sure you have Python 3.5 installed on your system.
6. Install the latest version of [https://github.com/Rapptz/discord.py](discord.py) as per manufactorer instructions.
7. Clone this repository to anywhere you like.
8. Create a text file in the repo's root directory named "bot.token".
9. Fill in this file with the token you copied earlier.
10. You should be good to go! Simply type `python battlebot.py` to launch the bot. It will print its own invite link to the console when it starts up. Copy this link into a web browser to add the bot to your server!

Optionally, you may set up another Discord app and place its token in another file named "devbot.token". Invoke the bot using `python battlebot.py dev` to use this token instead of the normal one.  
This is how I can work on the bot while also letting it run unaffected: I have two separate discord apps, one for the public bot and one for my oen testing. This effectively allows me to run two different bots off the same code base. It works well.



