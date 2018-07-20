# Hacker News to Telegram crossposter

A quick and dirty bot that reposts news from Hacker News (news.ycombinator.com) into a Telegram channel.

## Subscribe ##

Subscribe to the bot at [@news_ycombinator](https://t.me/news_ycombinator).

## Deployment ##

- Create an Azure Function app.
- Create a JS function with a timer trigger (let's say every 10 minutes).
- Copy index.js and package.json.
- Obtain a bot token from @botfather on Telegram and paste it into index.js.
- Open the console of the Azure Function, `cd` into the directory of your function, and type `npm i`.
- Go back to code and press Run. The first run will send 30 messages at once.
