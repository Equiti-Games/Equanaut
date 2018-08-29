# Equanaut
This Repo is based on a couple repositories: 
* [Python-Telegram-bot on Heroku](https://github.com/Eldinnie/ptb-heroku-skeleton)
* [Tele_bot] (https://github.com/drahamim/tele_bot) 




## Installation Notes
* This bot is currently hosted on Heroku and utilizes Heroku's Config Variables so as not to hard-code use specific details. 
** BOT_TOKEN (This is the token from @BotFather)
** BOT_H_NAME (This is the Name of the dyno running the bot found under settings)

## Things to know

* [Heroku getting started with Python](https://devcenter.heroku.com/articles/getting-started-with-python#introduction)
* [Heroku CLI](https://devcenter.heroku.com/categories/command-line) - Not required but very usefull
* Basic knowledge with git


## Things you will need
* A token for your bot from [@BotFather](https://t.me/botfather)
* The name for your app. Either gathered from the web-interface or given when running

```
$ heroku create <appname>
```

## Procfile
The Procfile in this repository is currently set to run Herokubot.py which uses Heroku's built in webhook server.

## Credits
[Python Telegram Bot](https://github.con/python-telegram-bot) the creaters of the library this bot uses. [Their telegram group](https://t.me/pythontelegrambotgroup) 

## Contributing to this reposiory
If you would like to contribute to this repository please file Pull Requests for your code. 