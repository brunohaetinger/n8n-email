# n8n-email

Simple workflow to collect Stocks information, put it on a table and share, notifying the user.

## Setting up Telegram node

### Bot Token

On Telegram app, talk with `@BotFather` and create a new bot. It will output the `Bot Token` at the end.

### Chat ID

It's the user `Chat ID`, who will receive the message from the bot.

To find it:
> curl "https://api.telegram.org/botYOUR_BOT_TOKEN/getUpdates"


## Output from this study

n8n is too limited when it need to run custom code. When extracting HTML elements inner text, the default `HTML Extract`  node didnt support good html parsing and multi values output. 
Also, the custom JS code only support native JS and some n8n additional functions, but not external libraries, as the ones for parsing HTML.
