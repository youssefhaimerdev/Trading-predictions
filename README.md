# APEX Intelligence — AI Trading Predictions

**AI-powered trading analysis for Crypto, Stocks, Forex & Commodities**

> ⚠️ For educational purposes only. Not financial advice.

---

## 🚀 Deploy to Vercel (3 steps)

1. **Push to GitHub**
   ```bash
   git init
   git add .
   git commit -m "feat: APEX Intelligence v10"
   git remote add origin https://github.com/YOUR_USERNAME/apex-intelligence.git
   git push -u origin main
   ```

2. **Connect to Vercel**
   - Go to [vercel.com](https://vercel.com) → New Project
   - Import your GitHub repository
   - Framework Preset: **Other** (static)
   - Output Directory: `.` (root)
   - Click **Deploy**

3. **Done** — your site is live at `https://apex-intelligence.vercel.app`

---

## 📁 File Structure

```
apex-intelligence/
├── index.html        # Main trading dashboard (all-in-one)
├── privacy.html      # Privacy policy page
├── sitemap.xml       # XML sitemap for SEO
├── robots.txt        # Search engine directives
├── vercel.json       # Vercel config (headers, caching, routing)
└── README.md         # This file
```

---

## ✨ Features

### 5-Model AI Ensemble
| Model | Indicators |
|-------|-----------|
| MOMENTUM-AI | RSI, MACD, Stochastic, Rate of Change |
| TREND-AI | EMA 9/21/50, ADX, Market Regime |
| VOLATILITY-AI | Bollinger Bands, ATR, Keltner Channels |
| VOLUME-AI | OBV, Volume RSI, Accumulation/Distribution |
| PATTERN-AI | Support/Resistance, Fibonacci, Key Levels |

### Assets Covered (50+)
- **Crypto**: BTC, ETH, BNB, SOL, XRP, ADA, DOGE, AVAX, DOT, LINK, MATIC, UNI, LTC, ATOM, NEAR, APT, ARB, OP, INJ, SUI
- **Stocks**: AAPL, NVDA, TSLA, MSFT, GOOGL, AMZN, META, AMD, NFLX, COIN, MSTR, PLTR, SOFI, RIVN, INTC
- **Indices**: SPY, QQQ, DIA, IWM, VIX
- **Commodities**: Gold, Silver, WTI Oil, Natural Gas, Copper
- **Forex**: EUR/USD, GBP/USD, USD/JPY, AUD/USD, USD/CHF, USD/CAD

### APIs Used (All Free, No Key Required)
| API | Data | Source |
|-----|------|--------|
| Binance WebSocket | Real-time crypto prices | stream.binance.com |
| Binance REST | OHLCV candles (crypto) | api.binance.com |
| CoinGecko | Crypto market data | api.coingecko.com |
| Alternative.me | Fear & Greed Index | api.alternative.me |
| Frankfurter ECB | Forex rates | api.frankfurter.app |
| Metals.live | Gold & Silver spot | api.metals.live |
| Yahoo Finance | Stocks/ETFs/Commodities | query1.finance.yahoo.com |
| AllOrigins Proxy | CORS proxy for RSS/YF | api.allorigins.win |
| MarketWatch RSS | Market news | feeds.marketwatch.com |
| CoinDesk RSS | Crypto news | coindesk.com/arc/outboundfeeds |
| CryptoPanic | Crypto news | cryptopanic.com |

### Analysis Methods
- **Walk-Forward Validation** — OOS accuracy on held-out data
- **Monte Carlo Simulation** — 200 probabilistic price paths
- **Multi-Timeframe** — 1H / 4H / 1D timeframes
- **TradingView Charts** — Candlesticks via lightweight-charts
- **Support/Resistance** — Auto-detected from price history
- **Fibonacci Levels** — Auto-calculated retracement levels
- **News Sentiment** — Real-time bullish/bearish scoring

---

## 🎯 SEO Features

- Meta tags (title, description, keywords, OG, Twitter Card)
- 2,500+ word SEO content section targeting:
  - AI trading predictions
  - Crypto price prediction
  - Stock market AI signals
  - Forex trading signals
  - Technical analysis AI
  - Machine learning trading
- XML sitemap
- robots.txt
- Canonical URLs
- Semantic HTML structure

---

## 📢 Advertising

The platform includes 3 pre-configured ad slots:
1. **Leaderboard (728×90)** — top of page, below ticker
2. **Rectangle (300×250)** — right sidebar
3. **Wide Banner (970×90)** — bottom of analysis panel

Replace the placeholder `<div>` elements with your actual ad code (Google AdSense, etc.)

---

## ⚠️ Disclaimer

APEX Intelligence is for **educational purposes only**. AI-generated signals are NOT financial advice. Past algorithmic performance does not guarantee future results. Trading involves substantial risk of loss. Always conduct your own research and consult a licensed financial advisor.

---

## 📄 License

MIT License — free to use, modify, and deploy.
