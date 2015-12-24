# DiscordBot
A chat bot for discord app based off <a href="https://github.com/hydrabolt/discord.js/">discord.js</a>

# Features:
- !gif query => returns a gif example !gif cute cats doing stuff
- !image query => returns an image from Google Images (careful, no adult filter)
- !youtube query=> returns a youtube link
- !wiki query=> returns the summary of the first search result on Wikipedia
- !wolfram query => queries Wolfram Alpha for results
- !meme memetype "text1" "text2" => returns a meme image. notice the quotes around text, they are vitally important
- !say text => echos text
- !alias => create custom shorthand commands in channel!
- !join-server => bot will join the requested server
- !talk => talk with the bot!
- @botname => responds when @mentioned
- channel management!

And much more! Try !help to get a full list of available commands

# Installation
This bot is written to run on top of node.js. Please see https://nodejs.org/en/download/

Once you have node installed running `npm install` from the bot directory should install all the needed packages. If this command prints errors the bot won't work!

## Windows Users
Please note that you must have a working C compiler and Python in your path for
`npm install` to work. The bot has been tested to work on Windows using Visual Studio 2015 Community and Python 2.7, except for `!pullanddeploy`.
* [Installing Node on Windows](http://blog.teamtreehouse.com/install-node-js-npm-windows)
* [npm errors on Windows](http://stackoverflow.com/questions/21365714/nodejs-error-installing-with-npm)
* [Visual Studio Community 2015](https://www.visualstudio.com/en-us/products/visual-studio-community-vs.aspx)
* [Python 2.7](https://www.python.org/downloads/)


## RSS:
You can create an rss.json file adding rss feeds as commands. See rss.json.example for details.

## Image
The !image and !ggif commands use Google Custom Search to provide results.
Setup is somewhat complex, please follow instructions at
https://stackoverflow.com/questions/34035422/google-image-search-says-api-no-longer-available

# Running
Before first run you will need to create an `auth.json` file. The email and password for a discord account are required. The other credentials are not required for the bot to run, but highly recommended as commands that depend on them will malfunction. See `auth.json.example`.

To start the bot just run
`node discord_bot.js`.

# Updates
If you update the bot, please run `npm update` before starting it again. If you have
issues with this, you can try deleting your node_modules folder and then running
`npm install` again. Please see [Installation](#Installation).

# ToDo:
All the things!
