# Hormuz Crisis — Vietnam Impact Tracker

Real-time dashboard tracking the US–Iran conflict's economic impact on Vietnam.

**Live:** [https://sachadray.github.io/hormuz-vietnam-tracker/](https://sachadray.github.io/hormuz-vietnam-tracker/)

## How to Update Data

All dashboard data lives in a single **`data.csv`** file. To update:

1. Open `data.csv` in any text editor, Excel, or Google Sheets
2. Edit values (indicators, time series, situation report, etc.)
3. Save and push to GitHub — the dashboard reads `data.csv` at page load

The CSV uses `[sectionName]` headers to organize data into labeled sections. Comments (lines starting with `#`) are ignored.

## Files

```
index.html   — Dashboard HTML shell
app.js       — Bundled React + Recharts application
data.csv     — All dashboard data (edit this to update)
README.md    — This file
```

## License

Dashboard code: MIT. Data from HormuzTracker.com used under CC BY 4.0.
