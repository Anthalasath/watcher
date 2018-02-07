# Watcher
A simple Discord bot offering functionality for tracking PRPS &amp; DUBI related information

You can find information about Purpose and DUBI, cryptocurrencies aimed at providing Universal Basic Income for the planet here:

#### Website: https://www.prps.io/

#### Reddit: https://www.reddit.com/r/PRPS/

#### An explanation on how PRPS and DUBI can go up in value so fast: https://youtu.be/wwleqKixhUg

#### Livestream: https://www.twitch.tv/athenelive

#### Whitepaper: https://www.prps.io/Purpose.pdf

#### Purpose source code: https://github.com/nionis/purpose

#### Discord: https://discord.gg/q2CEKkr

<!> If you make use of this bot in your server, please make sure that your servers admins have a role called "Admin"
to make use of the admin commands<!>

You can type !help to get a list of all the commands available to you.


This bot is still WIP and completely open source,
feel free to submit any issues or fork and make your
own version of Watcher.


================

### How to use Watcher:
Watcher is a custom Discord bot made with discord.js. 
You'll need to follow this guide on how to create bot accounts for Discord:
https://discordpy.readthedocs.io/en/rewrite/discord.html

You can host the bot on different hosting services such as Heroku (beware of the 550h limit for free versions!)

=> https://www.heroku.com/

If you plan on using Heroku, make sure to set the worker dyno to 1 and the web to 0 as you don't need it.
The worker dyno makes sure that the bot is running all the time, while the web dyno is mainly used
for web apps with web pages.

If you have the Heroku CLI installed, you can use the following commands for this:

heroku ps:scale web=0

heroku ps:scale worker=1

You can find more information about getting started with Heroku here:
=> https://devcenter.heroku.com/articles/getting-started-with-nodejs#introduction

<!> NEVER make changes to the settings-default.json file unless you are sure that you want to override the default settings permanently! This is your reset file in case you want to start with fresh settings again.<!>

