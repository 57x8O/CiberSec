# Discord Hack Week Productivity Bot Submission
![alt text](https://cdn-images-1.medium.com/max/2600/1*lh6NS8hx0pu5mlZeSqnu5w.jpeg)
*[Source](https://blog.discordapp.com/discord-community-hack-week-build-and-create-alongside-us-6b2a7b7bba33)*

**CiberSec** is a simple bot that is mainly focused on cyber security. The bot works like a command shell - You simply type in a Linux shell command, and the bot will return the output from the executed command.

# Installation
In order to clone GitHub repositories, it's necessary to install git.

**Install git via:**
```bash
$ sudo apt update
$ sudo apt install git
```

**Clone the repository via:**
```bash
$ git clone https://github.com/WodxTV/CiberSec.git
```

Python 3 has to be installed, in order to be able to run the code.

**Install Python 3.7 via:**
```bash
$ sudo apt update
$ sudo apt install python3.7
```
PIP (a package-management system) for Python 3.7 also has to be installed, in order to install the Discord API/module for Python.

**Install PIP via:**
```bash
$ sudo apt update
$ sudo apt install python3-pip
```
discord.py, which is an API/a module for bot development in Python, is needed in order to make the bot run.

**Install discord.py via:**
```bash
$ pip3 install discord
```

After installing Python 3, discord.py and PIP, create a new client bot by using [this link](https://discordapp.com/developers/applications/).

Copy the client ID of the bot you have created, and paste [this link](https://discordapp.com/oauth2/authorize?client_id=CLIENT_ID_HERE&scope=bot&permissions=8) into your browser and change 'CLIENT_ID_HERE' in the URL to your new bot's client ID, to invite it to your Discord server.

# Running the bot
I recommend you running the bot on a penetration testing Linux distribution like **Kali Linux** or **Parrot OS**, as they have a lot of pre-installed penetration testing/hacking tools installed.

1. Edit the config in ``./config/config.json``

2. Start the bot via ``$ python3 cibersec.py``

# Work in progress
* Auto create category named 'CiberSec'
* Auto create text channel named 'Terminal' under category 'CiberSec'
* Auto create role named 'CiberSec User'
* Auto create text channel named 'Command History' under category 'CiberSec'
* Auto set permissions for 'CiberSec' category (private channel for 'CiberSec User' role only)
* Design a logo for the bot
* Create console menu (Start bot, view repository, show credits etc.)

# Developer
**WodX**
* Github: [WodXTV](https://github.com/wodxtv)
* Discord: [wodx#0666](http://discordapp.com)
* Twitter: [@wodxofficial](https://twitter.com/wodxofficial)

**wodx@root:\~/CiberSec:~$** echo *If I had more time, I'd develop something more advanced than a built-in command shell for Discord servers.* > something.txt
