
# Market Risk Monitor

![Market Regime](https://img.shields.io/badge/Market%20Regime-Recovery-green)

**🟢 Recovery**  
**Score:** Downturn 0/3 | Recovery 3/3  
**Last Updated:** 2026-09-28

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

Here's a thinking process:

1.  **Analyze the Request:**
   - **Market regime**: 🟢 Recovery
   - **Snapshot data** provided with various tickers and metrics
   - **Output requirements**: 
     - Short risk commentary
     - Bullet-point market summary
     - Must include mortgage rate and condition explicitly in bullets
     - Must include income spread (SP dividend yield vs 10Y) explicitly in bullets
     - Must explicitly state whether income spread favors bonds or equities
     - Must include VIX, SPY trend, and yield context
     - If conditions are unchanged, say they are stable
     - Concise and consistent tone
     - Mention raw data is available in /data

2.  **Extract Key Data Points from Snapshot:**
   - SPY: price 771.35, ma200 718.45 → SPY > MA200, uptrend
   - QQQ: price 744.5, ma100 715.69 → QQQ > MA100, uptrend
   - ARKK: three_month_change_percent 12.58 → strong performance
   - VIX: level 14.87 → low volatility
   - TNX: yield 5.24 → 10Y tenor yield context
   - OVX: level 55.09, regime "low" → low commodity volatility
   - mortgage: rate 7.03, condition "Unfavorable" → key requirement
   - income_spread: sp_div_yield 0.99, ten_year_yield 5.17, spread -4.18, regime "Bond Yield Advantage" → crucial for equity vs bond favorability

3.  **Determine Implications/Interpretation:**
   - Regime: Recovery (given as 🟢 Recovery)
   - SPY above MA200 → bullish trend
   - VIX at 14.87 → low fear, stable environment
   - Mortgage rate 7.03, condition "Unfavorable" → headwind for housing/consumers
   - Income spread: SP div yield 0.99% vs 10Y yield 5.17%, spread -4.18% → negative spread means bonds yield more than equities dividends. Regime labeled "Bond Yield Advantage" → favors bonds explicitly.
   - TNX 5.24 aligns with 10Y at 5.17
   - ARKK up 12.58% 3M → risk-on in growth/tech
   - OVX low → low ag/commodity volatility

4.  **Draft - Step-by-Step:**

   **Risk Commentary:** 
   Concise, sets tone. Mention regime, VIX, mortgage, spread. Conditions stable given data consistency.

   **Bullet-point Market Summary:**
   - Must include: mortgage rate 7.03 + condition "Unfavorable" explicitly
   - Must include: income spread sp_div_yield 0.99 vs ten_year_yield 5.17, spread -4.18, explicitly state favors bonds
   - Must include: VIX 14.87, SPY trend (price vs ma200), yield context (TNX/10Y)
   - Note raw data in /data
   - If unchanged, say stable

   Let's structure bullets:
   - SPY trades at 771.35, above its 200-day MA of 718.45, confirming an uptrend in the recovery regime.
   - VIX at 14.87 reflects low volatility, supporting risk-on sentiment.
   - Mortgage rate at 7.03% remains in "Unfavorable" condition, pressuring housing affordability and consumer spending.
   - Income spread: S&P dividend yield of 0.99% versus 10-year Treasury yield of 5.17% yields a negative spread of -4.18%, explicitly favoring bonds over equities for income seekers.
   - TNX yield of 5.24% aligns with the 10Y backdrop, reinforcing the bond yield advantage.
   - ARKK is up 12.58% over three months, indicating strong momentum in growth/tech names.
   - OVX at 55.09 in "low" regime signals contained commodity volatility.

   Add note about raw data /data and stable conditions.



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
