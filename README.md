
# Market Risk Monitor

![Market Regime](https://img.shields.io/badge/Market%20Regime-Downturn-red)

**🔴 Downturn Risk**  
**Score:** Downturn 3/3 | Recovery 0/3  
**Last Updated:** 2026-11-27

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

- SPY price (716.7) sits 2.2% below its 200-day moving average (733.16); QQQ price (633.93) sits 10.5% below its 100-day moving average (708.46), indicating QQQ has deviated more from its shorter-term trend anchor than SPY from its longer-term anchor
- ARKK three-month change of -20.37% aligns directionally with QQQ's larger deviation from its 100-day MA, reflecting correlated drawdown in growth/innovation segments over the same quarterly window
- VIX at 26.8 implies an annualized 30-day expected volatility of ~26.8% for S&P 500 options, numerically consistent with index prices trading below trend averages
- TNX yield at 4.94% establishes the annualized risk-free discount baseline; mortgage rate at 7.21% (condition: Unfavorable) represents a 227 basis point spread over TNX, reflecting credit and prepayment risk premiums in residential lending
- OVX at 48.04 with regime "low" indicates oil-implied volatility remains below historical percentiles despite elevated equity volatility (VIX 26.8), showing commodity and equity fear gauges are not mechanically coupled
- Income spread: S&P 500 dividend yield (1.04%) minus 10-year yield (4.85%) equals -3.81%; the negative spread mathematically favors bonds over equities for current income, as the annualized Treasury coupon exceeds the equity yield by 3.81 percentage points

**Synthesis:** The data shows equity prices (SPY, QQQ, ARKK) trading below trend averages over 100-200 day and 3-month horizons, while the annualized 10-year yield (4.85%) exceeds the S&P 500 dividend yield (1.04%) by 3.81%, creating a mechanical income advantage for bonds. Mortgage rates (7.21%) carry a 227bp spread to the 10-year baseline. VIX (26.8) quantifies elevated equity uncertainty versus OVX (48.04, regime low) showing contained oil volatility. Raw data available in /data.

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
