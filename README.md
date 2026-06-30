# 🤖 CryptoX — AI-Powered Crypto Telegram Bot

An AI-driven Telegram bot that provides live cryptocurrency 
prices, market comparisons, and personalized investment advice.

## 🚀 Live Demo
[Try the bot on Telegram](https://t.me/cryptoalert_update_bot)

## 🛠️ Tech Stack
- **n8n** — Workflow automation & orchestration
- **Groq (LLaMA 3.3 70B)** — AI reasoning & natural language understanding
- **ScraperAPI** — Live price scraping from CoinMarketCap
- **Telegram Bot API** — User interface

## ✨ Features
- 🪙 Live crypto price checks (BTC, ETH, etc.)
- ⚔️ Coin comparison (e.g., "compare BTC and ETH")
- 📊 Market overview of top coins
- 💼 Personalized investment guidance
- 🌐 Supports Hindi/English/Hinglish queries

## 🏗️ Architecture
Telegram User
↓
Telegram Trigger (n8n)
↓
AI Agent (Groq LLaMA 3.3)
↓
CoinMarketCap (using Scraper API)
↓
Telegram Response

## ⚙️ Setup
1. Import `crypto_tele_bot.json` into your n8n instance
2. Add credentials: Telegram, Groq, ScraperAPI
3. Activate/Publish the workflow
4. Start chatting with your bot on Telegram!

## 📌 Note
This was built as a learning project to explore AI agents, 
tool-calling, and workflow automation in n8n.

