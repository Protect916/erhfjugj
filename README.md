# Spotify download bot
A telegram bot for downlaoding spotify playlist songs on telegram.

## How to setup on heroku
1. Create a telegram bot using [bot father](https://core.telegram.org/bots#3-how-do-i-create-a-bot)
2. Create account on [heroku.com](https://heroku.com/)
3. Create a new application on heroku
4. fork this repository
  * To deploy bot on heroku there are two methods (CLI and Web), we use the heroku.com way:
5. In your application on heroku go to deploy tab and choose Github on deployment method
6. Select this repository you forked there and choose deploy from master option
7. Then go to settings tab on heroku and add two vars to config vars:
  - APP_NAME: name of the app you created on heroku
  - TOKEN: your telegram bot token)
8. install [heroku CLI](https://devcenter.heroku.com/articles/heroku-cli#download-and-install) and run the command `heroku stack:set container -a APP_NAME` (APP_NAME is name of the app you choose when creating heroku application) then login to your account for change to happen
8. In heroku from deploy section scroll down to Manual deploy and press deploy branch for master branch

## Setup everywhere else
1. use the Dockerfile and you're done
