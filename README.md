# MagicMirror² : Controlling your MagicMirror from Telegram Bot
A MagicMirror² modules for controlling the magic mirror through Telegram Bot

## Installation
1. Navigate into your MagicMirror's `modules` folder
2. Execute `git clone https://github.com/putera/MMM-TelegramBot.git`
3. Navigate to `cd ~/MagicMirror/modules/MMM-TelegramBot` folder
4. Run `npm install`

## Using the module
To use this module, add it to the modules array in the `config/config.js` file:

```javascript
modules: [
	{
		module: 'MMM-TelegramBot',
		config: {
			// See 'Configuration options' for more information.
			telegramAPIKey: '- Your Telegram API Token -',
			allowedUser: ['- Your Telegram username without @ -'],
			adminChatId: ['- Your chatId with bot -']
		}
	}
]
```

## Configuration Options
The following properties can be configured:

| **Option** | **Description** |
| --- | --- |
| `telegramAPIKey` | Your telegram API token |
| `allowedUser` | List of allowed user to use and control the MagicMirror |
| `adminChatId` | Your chatId with telegram bot |
