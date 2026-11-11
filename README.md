
# Market Risk Monitor

![Market Regime](https://img.shields.io/badge/Market%20Regime-Recovery-green)

**🟢 Recovery**  
**Score:** Downturn 0/3 | Recovery 2/3  
**Last Updated:** 2026-11-11

---

⚠️ **Disclaimer**

This is an automated market signal summary for informational purposes only.
It is not financial advice.

A note from the author:
There are hundreds of resources on the Internet in addition to learning resources available through your investment platform.
For example, [this one by Ramit Sethi](https://youtu.be/FF5-FbhaAyc?si=52cXbGUBFqxifu7Q), or [this one by Jaspreet Singh](https://youtu.be/qdqLIjszqy4?si=-R0Sa7C_Q0bCHY08), or [this one by Erin Moriarity](https://youtu.be/FYMfX3Aljow?si=MPQ7nICG0nA1U6vh), or articles like [this one by Fidelity](https://www.fidelity.com/learning-center/smart-money/roth-ira-taxes).
Seek out the information you need for your future self!

---

## AI Risk Commentary

- SPY price (749.92) exceeds its 200-day moving average (730.99) by 18.93 points (2.59%), while QQQ price (674.76) sits 40.73 points (5.69%) below its 100-day moving average (715.49), creating a 8.28 percentage-point divergence between large-cap breadth measured at 200-day versus 100-day horizons
- ARKK three-month return of -6.65% contrasts with SPY's position above its 200-day average, indicating differential performance between broad market and innovation-focused segments over the same quarterly window
- VIX at 19.46 implies an expected annualized S&P 500 price movement of ±19.46% (one standard deviation), while OVX at 53.1 in "low" regime indicates crude oil implied volatility trades at a 33.64-point premium to equity volatility
- TNX yield at 5.0% establishes the annualized risk-free discount rate baseline; mortgage rate at 7.18% ("Unfavorable" condition) represents a 218 basis-point spread over the 10-year Treasury, reflecting credit and prepayment risk premiums embedded in residential lending
- Income spread: S&P 500 dividend yield (1.0%) versus 10-year Treasury yield (4.88%) produces a -3.88 percentage-point spread, mathematically favoring bonds over equities by 388 basis points in current annualized cash yield terms
- The 4.88% ten-year yield exceeds the 1.0% equity dividend yield by a factor of 4.88x, meaning fixed income provides nearly five times the annualized cash return of equity income at current index levels
- Raw data available in /data

**Synthesis:** The mathematics show SPY trading above its long-term trend anchor (200-day MA) while QQQ trades below its intermediate trend anchor (100-day MA), an 8.28% structural divergence. The risk-free rate (5.0%) and mortgage rate (7.18%) both exceed equity dividend yield (1.0%) by 400 and 618 basis points respectively, with the income spread explicitly favoring bonds by 388 basis points. Volatility differentials (VIX 19.46 vs OVX 53.1) indicate commodity options pricing significantly higher uncertainty than equity options

---

## Charts

### SPY Trend
![SPY](charts/spy.png)

### QQQ Trend
![QQQ](charts/qqq.png)

### ARKK Drawdown
![ARKK](charts/arkk.png)

### VIX
![VIX](charts/vix.png)

### MOVE
![MOVE](charts/move.png)

### 10Y Yield
![TNX](charts/tnx.png)

### Oil Volatility
![OVX](charts/ovx.png)

### Mortgage Conditions
![Mortgage](charts/mortgage.png)

### SPY Trailing Dividend Yield (proxy)
![Income Spread](charts/income_spread.png)

---

[View raw data](data/market_snapshot.json)

---

## RSS Feed

https://raw.githubusercontent.com/krss-llc/market-summary/refs/heads/main/docs/feed.xml

---

## Data

- Signals: [data/signals.json](data/signals.json)  
- History: [data/history.json](data/history.json)
