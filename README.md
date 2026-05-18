# Telegram Sports Betting Bot v.0.1.2

Automated sports content and odds analysis bot for Telegram.

## Features
- **Multi-Sport Support**: Football (Soccer), MMA (UFC), Basketball (NBA).
- **Automated Previews**: Team form, H2H, and match context.
- **Odds Analysis**: Value bet detection (>5% edge) using The Odds API.
- **Smart Scheduling**: Auto-posts at optimal times.
- **Admin Commands**: `/stats` and `/tips`.

## Setup

1. **Clone the repository**
2. **Install dependencies**: `pip install -r requirements.txt`
3. **Configure Environment**: Copy `.env.example` to `.env` and fill in your keys.
4. **Run Migrations**: `alembic upgrade head`
5. **Start the Bot**: `python -m src.bot.main`

## Docker Deployment
```bash
docker-compose up -d --build
```

## Disclaimer
18+ Gamble Responsibly. This bot is for educational and informational purposes only.
