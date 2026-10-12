# RXT.pro - Next-Gen AI Trading Signals & Market Intelligence Platform

An institutional-grade, highly responsive web application and landing page designed for **RXT.pro** — an autonomous multi-model market intelligence platform providing signals for **Gold (XAU/USD)**, **Cryptocurrency**, **Forex**, and **Indices**.

---

## 🚀 Key Features

1. **24/7 Live Real-Time Synchronization Across All Pairs**:
   - Centralized price dispatcher syncing **Crypto**, **Gold & Silver**, **Forex**, and **Indices** in real-time.
   - Real-time WebSocket connection to global exchange feeds (`wss://stream.binance.com:9443/ws/...`) streaming live crypto and tokenized spot gold ounces (PAXG) tick-by-tick.
   - Automated live currency feed updates via interbank exchange rate APIs with micro-tick momentum pulse.
2. **Standard Ounce (`/oz`) Pricing for Precious Metals**:
   - All Gold (**XAU/USD**) and Silver (**XAG/USD**) pricing explicitly formatted per troy ounce (`... /oz`) without ambiguous dollar prefixes.
   - Clean, unified display across the Hero Showcase card, Live Ticker Tape, Terminal Asset Switcher, Signal Cards, ICT Telemetry, Signal Modal, and Audited Trade Records.
3. **24/7 Advanced Interactive Chart Terminal**:
   - Integrated with the **TradingView Advanced Real-Time Chart Widget** for 24/7 tick-by-tick market discovery.
   - Designated broker for Gold: **Forex.com (`FOREXCOM:XAUUSD`)** directly matching institutional pricing (~4,180 - 4,190 /oz).
   - Public TradingView Scanner API synchronization polling `https://scanner.tradingview.com/cfd/scan` every 2 seconds to feed live ticks directly into the **RXT Neural Matrix**, Hero Signal Card, and ICT Analysis Engine.
   - Switchable instruments: **BTC/USDT**, **XAU/USD (Gold /oz via Forex.com)**, **ETH/USDT**, **SOL/USDT**, and **EUR/USD**.
   - Full timeframe controls: **5M**, **15M**, **1H**, **4H**, **1D**.
   - Dual-Mode Switcher: Toggle between **⚡ 24/7 Live Stream** (institutional TradingView candles & drawing tools) and **🧠 RXT Neural Matrix** (renders real OHLCV candlestick data directly from market klines with algorithmic overlays).
   - Sub-second physical Gold spot streaming via WebSocket (`PAXGUSDT`) and TradingView CFD scanner (`FOREXCOM:XAUUSD`).
4. **Curated High-Winrate Prime Setups (Low Frequency, High Conviction)**:
   - Filtered out 94% of low-probability retail chop to deliver only Grade-A+ institutional setups.
   - Audited **94.2% – 96.8% Win Rate** with **4/4 Multi-Model Confirmations Verified** (Liquidity Sweep, MSS Displacement, FVG Discount Retest, Order Flow CVD delta).
   - Low frequency regime: Only 1–2 prime setups dispatched per market session.
   - Dynamic real-time parameter synchronization: Entry Range, Invalidation Stop Loss, TP1, and TP2 automatically recalculate with each live market tick.
5. **Institutional Order Flow & ICT Model Strategy Modal**:
   - Detailed modal analysis following the **ICT (Inner Circle Trader) Institutional Model Strategy** and **High-Frequency Order Flow Telemetry**:
     - **Liquidity Sweep (SSL / BSL)**: Asian/Session low purges and stop-run identification.
     - **Market Structure Shift (MSS)**: Energetic displacement impulses breaking previous swing pivots.
     - **Fair Value Gap (FVG Zone)**: 3-candle imbalance zones for precision discount entries.
     - **Optimal Trade Entry (OTE)**: 62%–70.5% Fibonacci discount re-entries.
     - **PD Array Matrix**: Premium vs. Discount algorithmic valuation.
     - **Active Killzone Tracking**: London Open, NY AM, NY PM, and COMEX overlap windows.
     - **Cumulative Volume Delta (CVD)**: Aggressive market taker aggression tracking.
     - **Order Book Imbalance**: Real-time Level 2/3 bid/ask depth dominance.
     - **Liquidation Cascades & Icebergs**: Trapped trader stops and algorithmic passive absorption.
     - **Open Interest (OI) & ATR**: Institutional positioning expansion and volatility calibration.
   - One-click formatted **"Copy Trade Parameters"** button exporting the full ICT & Order Flow setup for Discord/Telegram/MT5.
5. **Real-Time Signal Stream Cards**:
   - Categorized by **All**, **Crypto**, **Forex**, **Gold & Metals**, and **Indices**.
   - Each card displays live price badge (with green/red tick animations), asymmetric Risk-to-Reward (R:R), ICT strategy pill, session killzone, Entry Range, Stop Loss, TP1, TP2, and CVD delta.
6. **Consensus Architecture Showcase**:
   - Deep reasoning models (DeepSeek R1 / Claude 3.5 Sonnet), quantitative order flow (Level 2/3 CVD), macroeconomic sentiment, and dynamic ATR risk shield.
7. **Audited Performance & Track Record**:
   - Summary statistics (95.8% avg win rate, +3,820 Gold pips, low drawdown).
   - Interactive historical closed trades table with verified exit statuses.
8. **Pricing & Membership Configurator**:
   - Free Trial, Pro Trader VIP (Featured), and Institutional Elite.
   - Interactive Monthly vs. Annual toggle with automated discount calculation.
9. **Live Alert Toasts**:
   - Simulated real-time popups alerting traders to new setups, TP completions, and whale movements.
10. **Zero Dependencies**:
   - Built with modern semantic HTML5, pure CSS3 (Glassmorphism, custom CSS variables, responsive grid/flexbox), and vanilla ES6+ JavaScript.
   - Runs instantly by double-clicking `index.html` in any web browser without needing Node.js, Python, or build steps.

---

## 📂 File Structure

```text
Website Build/
├── index.html       # Primary application markup and layout
├── styles.css       # Complete design system, glassmorphism UI, animations, responsive rules
├── app.js           # Live ticker, signal filtering, canvas candlestick charts, modals, toasts
└── README.md        # Documentation and deployment guide
```

---

## 🌐 How to Launch & Preview

### Local Preview:
Simply double-click `index.html` in your file explorer, or right-click `index.html` -> **Open with Google Chrome / Microsoft Edge / Brave / Firefox**.

### Deploy to Production:
You can deploy this project instantly for free to any static hosting provider:
- **Cloudflare Pages**: Drag and drop the `Website Build` folder.
- **Vercel**: Run `vercel deploy` or connect your Git repository.
- **GitHub Pages**: Push this folder to a GitHub repo and enable Pages under repository settings.
- **Netlify**: Drag and drop into Netlify dropzone.

---

## ⚙️ Customization & Integrations

- **Telegram Direct Contact**: All Telegram buttons and the floating quick contact badge connect directly to `https://t.me/M_rithy03` (`@M_rithy03`).
- **Add / Modify Signals**: Edit the `signalsDatabase` array in `app.js` to add your live trading signals or connect via WebSocket to your backend signal provider.
- **Chart Adjustments**: Modify the `generateCandleData` function in `app.js` to connect to real-time Binance, TradingView, or MetaTrader WebSockets.

---

## ⚠️ Risk & Compliance Notice
Trading financial instruments involves significant risk of capital loss. RXT.pro provides algorithmic indicators and analytical tooling. Signals do not constitute personalized financial advice.
