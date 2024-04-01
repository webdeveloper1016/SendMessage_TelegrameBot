# Send to All bot member


![Packagist](https://img.shields.io/packagist/l/doctrine/orm.svg)  ![PullRequest](https://img.shields.io/badge/Pull%20Requst-Accepted!-brightgreen.svg)


A android application that uses java telegram API to send bulk messages to your bot members at once.

## Important Tip

You can configure delay for sending each message depending on your member's count, because right now telegram doesnt support bulk messaging and has some limitation.
[You can visit this page for more info.](https://core.telegram.org/bots/faq#my-bot-is-hitting-limits-how-do-i-avoid-this)

## How to use

You have to just replace your BOT-TOKEN in this directory: `/app/src/main/java/com/example/smn/paypingbotbroadcast/ScrollingActivity.java` and set your POST/GET method to get your telegram bot member Ids.

#### Dependencies

This app is based on [Java Telegram API](https://github.com/pengrad/java-telegram-bot-api), one of [official telegram bot api](https://core.telegram.org/bots/samples#java). You have follow their instruction to add this library to your project.

Finally Build... Done!

## License

[MIT License](LICENSE)

Copyright (c) 2018 PayPing
