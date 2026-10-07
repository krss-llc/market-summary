
# Market Risk Monitor

![Market Regime](https://img.shields.io/badge/Market%20Regime-Recovery-green)

**🟢 Recovery**  
**Score:** Downturn 0/3 | Recovery 3/3  
**Last Updated:** 2026-10-07

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

- **Equity price mechanics**: SPY is trading 57.99 points above its 200‑day moving average (779.09 vs 721.49), indicating the current price sits 8.03 % above that baseline. QQQ is 40.94 points above its 100‑day moving average (759.66 vs 718.72), a 5.70 % premium to that short‑term trend line.  
- **Volatility context**: VIX at 15.01 reflects low implied volatility levels relative to historical norms, suggesting reduced option‑pricing premiums across equity indices.  
- **Commodities volatility**: OVX at 48.79 with a “low” regime denotes minimal price‑swing risk in oil futures, implying stable input‑cost expectations for energy‑related sectors.  
- **Interest‑rate environment**: TNX shows a 5.28 % yield, setting a benchmark discount rate for fixed‑income assets. The mortgage rate of 7.28 % is 190 basis points above the Treasury yield, and the “Unfavorable” condition reflects the higher financing cost relative to the risk‑free baseline.  
- **Income‑spread mechanics**: SP dividend yield of 0.98 % versus a 5.27 % ten‑year Treasury yield produces a spread of –4.29 %. This negative spread quantifies a **bond‑yield advantage**, meaning the excess return from holding Treasuries exceeds the dividend income from equities by 429 basis points on an annualized basis.  
- **Cross‑asset implications**: The elevated TNX yield depresses present values of future equity cash flows, while the mortgage rate premium raises the cost of capital for real‑estate leverage. The low VIX and OVX levels suggest reduced risk premiums, but the income‑spread calculation still favors bond exposure over equity income generation.  

Current mathematical relationships show equities priced above medium‑term moving averages, low volatility indexes, and a bond‑yield advantage that tilts the relative return calculus toward fixed‑income assets. Raw data is available in **/data**.

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

https://kam-reef.github.io/market-summary/feed.xml

---

## Data

- Signals: [data/signals.json](data/signals.json)  
- History: [data/history.json](data/history.json)
