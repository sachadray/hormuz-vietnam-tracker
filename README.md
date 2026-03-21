# Hormuz Crisis — Vietnam Impact Tracker

Real-time dashboard tracking the US–Iran conflict's economic impact on Vietnam. Monitors oil prices, fuel costs, exchange rates, stock market, inflation, and strategic reserves.

**Live:** [https://sachadray.github.io/hormuz-vietnam-tracker/](https://sachadray.github.io/hormuz-vietnam-tracker/)

## Data Sources

| Data | Source | License |
|---|---|---|
| Crisis severity, ship transits, carriers, insurance, timeline | [HormuzTracker.com](https://hormuztracker.com) | CC BY 4.0 |
| Brent & WTI crude oil | oilpriceapi.com (live fetch) | Free API |
| Vietnam fuel prices (RON95, Diesel) | MOIT / Petrolimex | Public data |
| USD/VND exchange rate | SBV / TradingEconomics | Public data |
| VN-Index | HoSE | Public data |
| CPI | GSO (National Statistics Office) | Public data |
| VIX | CBOE | Public data |
| Gold | Market data | Public data |

All seed data verified as of March 21, 2026.

## Features

- **3 tabs**: Crisis Overview, Global Markets, Vietnam
- **Auto-scaling charts** with threshold zones (green/amber/red)
- **Live oil price fetch** from oilpriceapi.com with fallback to seed data
- **Admin panel** (password-protected): edit all indicators, time series, situation report
- **JSON export/import**: download full dataset, edit offline, re-upload
- **Persistent storage**: all changes saved to localStorage, survive page reloads
- **Pre-bundled**: React + Recharts compiled to a single `app.js` — no build step needed

## License

Dashboard code: MIT. Data from HormuzTracker.com used under CC BY 4.0.
