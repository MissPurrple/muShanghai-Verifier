# muShanghai Telegram Verification Bot

A Telegram bot that verifies event attendees by email before granting access to the private muShanghai group.

## Features
- Email-based verification using allowlist
- One-time use invite links
- Bilingual support (English/Chinese)
- Runs on Cloudflare Workers (free tier)

## Setup
1. Create a bot with @BotFather
2. Deploy to Cloudflare Workers
3. Set TELEGRAM_TOKEN as a secret
4. Add approved emails to allowlist

## Commands
- `/start` - Shows welcome message
- `/verify [email]` - Verify your registration
- `/help` - Show help

## Tech Stack
- Cloudflare Workers
- Telegram Bot API
- JavaScript/ES6