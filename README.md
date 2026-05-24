# 🦖 Gamblesaur

Live moneyline & spread velocity tracker. Detects momentum before the market catches up.

## Features

- **Moneyline velocity** — rate of change in implied probability
- **Acceleration** — rate of the rate, detecting building vs fading momentum
- **Spread velocity** — independent spread tracking for divergence signals
- **BUY / FADE signals** — automated signal detection based on velocity + acceleration
- **Volume split** — money flow visualization between sides
- **Mobile-first PWA** — installable on phone home screens

## Deploy to Vercel (30 seconds)

1. Push this folder to a GitHub repo
2. Go to [vercel.com/new](https://vercel.com/new)
3. Import your repo
4. Click Deploy

That's it. No build step needed — it's a static site.

## Deploy via Vercel CLI

```bash
npm i -g vercel
cd gamblesaur
vercel
```

## Files

- `index.html` — The entire app (self-contained, no build step)
- `manifest.json` — PWA manifest for home screen install
- `vercel.json` — Vercel routing config
