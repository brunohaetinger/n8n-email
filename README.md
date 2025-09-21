# n8n-email

Simple workflow to collect Stocks information, put it on a table and share, notifying the user.

## Setting up Telegram node

### Bot Token

On Telegram app, talk with `@BotFather` and create a new bot. It will output the `Bot Token` at the end.

### Chat ID

It's the user `Chat ID`, who will receive the message from the bot.

To find it:
> curl "https://api.telegram.org/botYOUR_BOT_TOKEN/getUpdates"

