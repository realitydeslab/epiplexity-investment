# 🔮 Epiplexity Investment

**Vision-driven investment research.** Not "will this stock go up?" but "what future is this company building, and can they pull it off?"

Like Perplexity, but for understanding the futures companies are creating — and whether your money can ride that wave.

## Markets Covered

- 🇺🇸 US Stocks (NYSE, NASDAQ)
- 🇭🇰 Hong Kong Stocks (HKEX)
- 🇨🇳 Chinese Stocks (SSE, SZSE, A-shares)
- 🪙 Crypto (BTC, ETH, L1s, DeFi, emerging protocols)

## Research Framework

Every opportunity gets a **Future Report** with three layers:

### 1. 📄 The Vision
- What future is this company/protocol building?
- Roadmap, strategic bets, R&D direction
- Earnings calls, investor letters, founder manifestos

### 2. 👤 The Leader
- Founder/CEO track record and credibility
- Insider buying/selling patterns
- Leadership team depth

### 3. 🎯 The Feasibility
- Total addressable market
- Moat analysis (tech, network effects, brand, regulatory)
- Financial runway
- Competitive landscape
- Scenario modeling: bull / base / bear cases

## Output

Each researched opportunity produces:
- `reports/{ticker}/vision-report.md` — full Future Report
- `reports/{ticker}/leader-profile.md` — CEO/founder deep dive
- `reports/{ticker}/feasibility.md` — can they actually do it?
- `reports/{ticker}/investment-thesis.md` — synthesized thesis
- `reports/{ticker}/meta.json` — structured data, last updated

## Watchlist

Active opportunities tracked in `watchlist.json`. Research runs hourly via cron.

---

*Built by Biber 🦫 for Amber*
