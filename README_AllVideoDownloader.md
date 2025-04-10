# 🎥 AllVideoDownloader – Telegram Bot

Download any video from any platform — fast, multilingual, and user-friendly.

AllVideoDownloader is a powerful Telegram bot built to fetch and deliver videos from platforms like TikTok, Instagram, Facebook, X (Twitter), YouTube Shorts, LinkedIn, and more — right into your Telegram chat.

---

## ✨ Features

- ✅ Download from 10+ major platforms  
- 🌐 Multilingual UI with 27+ languages supported  
- ⏱️ Fast download + delivery  
- ⚙️ TinyDB usage tracking  
- 💬 Dynamic `/translate` and `/language` switching  
- 💎 Stripe-powered Premium support (optional)  
- 🛡️ Admin-only controls  
- ☁️ Deployable via Replit or Railway  

---

## 📲 Supported Platforms

- TikTok  
- Instagram Reels  
- Facebook Videos  
- X (Twitter)  
- YouTube Shorts  
- LinkedIn  
- Snapchat  
- Pinterest  
- Threads  
- …and more

---

## 💬 Commands

| Command       | Description |
|---------------|-------------|
| `/start`      | Welcome message + supported platforms |
| `/help`       | Instructions on how to use the bot |
| `/account`    | Shows your current usage status |
| `/upgrade`    | Get a link to the premium checkout (Stripe) |
| `/language`   | Choose your preferred language |
| `/translate`  | Switch language quickly anytime |
| `/reset <id>` | (Admin only) Reset user’s download count |

---

## 🧰 Tech Stack

- Python 3.12  
- [python-telegram-bot](https://github.com/python-telegram-bot/python-telegram-bot)  
- [yt-dlp](https://github.com/yt-dlp/yt-dlp)  
- TinyDB  
- Stripe API  
- Railway / Replit for hosting  

---

## ⚙️ Environment Variables

| Key | Description |
|-----|-------------|
| `BOT_TOKEN` | Your Telegram bot token from [BotFather](https://t.me/BotFather) |
| `ADMIN_ID`  | Your Telegram user ID |
| `STRIPE_SECRET` | Stripe secret key for payments |
| `STRIPE_WEBHOOK_SECRET` | Stripe webhook signing key |

---

## 🚀 Deployment (Railway)

1. Upload this project to GitHub  
2. Connect Railway to the repo  
3. Add environment variables  
4. Set your run command (e.g. `python main.py` or `gunicorn app:webhook_app`)  
5. Deploy and you're live!

---

## 🙌 Credits

Built by [Your Name or Handle]  
Powered by [python-telegram-bot](https://github.com/python-telegram-bot/python-telegram-bot) + [yt-dlp](https://github.com/yt-dlp/yt-dlp)

---

## 📜 License

MIT License — feel free to remix, extend, or contribute.
