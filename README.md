
# Market Risk Monitor

![Market Regime](https://img.shields.io/badge/Market%20Regime-Recovery-green)

**🟢 Recovery**  
**Score:** Downturn 0/3 | Recovery 3/3  
**Last Updated:** 2026-09-22

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

1.  **Analyze the User's Request:**
   - **Market regime**: 🟢 Recovery
   - **Snapshot data**: Provided with various tickers/metrics
   - **Output requirements**:
     - Short risk commentary
     - Bullet-point market summary
     - Must include explicitly: mortgage rate & condition
     - Must include explicitly: income spread (SP dividend yield vs 10Y)
     - Must explicitly state whether income spread favors bonds or equities
     - Must include VIX, SPY trend, and yield context
     - If conditions are unchanged, say they are stable
     - Concise and consistent tone
     - Mention raw data is available in /data
   - **Provided data** to parse:
     - SPY: price 773.5, ma200 716.74
     - QQQ: price 741.47, ma100 712.71
     - ARKK: three_month_change_percent 18.31
     - VIX: level 14.87
     - TNX: yield 4.97
     - OVX: level 50.31, regime "low"
     - mortgage: rate 6.95, condition "Unfavorable"
     - income_spread: sp_div_yield 0.98, ten_year_yield 4.96, spread -3.98, regime "Bond Yield Advantage"

2.  **Deconstruct the Requirements & Map Data:**
   - *Mortgage rate*: 6.95%, condition: "Unfavorable" -> must appear in bullets
   - *Income spread*: sp_div_yield 0.98, ten_year_yield 4.96, spread -3.98, regime "Bond Yield Advantage" -> must appear explicitly, and state whether it favors bonds or equities. The regime says "Bond Yield Advantage", and spread is negative (-3.98%), meaning bonds are yielding more than equity dividends relative to risk/term. So it favors bonds. I'll state that explicitly.
   - *VIX*: 14.87 -> include in bullets
   - *SPY trend*: price 773.5 vs ma200 716.74 -> SPY is above its 200-day MA, indicating an uptrend. I'll mention the trend.
   - *Yield context*: TNX 4.97, 10Y 4.96 (income spread uses 10Y yield 4.96). I'll tie them together.
   - *Conditions unchanged*: The prompt says "If conditions are unchanged, say they are stable." Looking at the data, nothing explicitly says "unchanged" but I can note stability or just follow the instruction if applicable. I'll probably add a brief stability note or just ensure the tone fits. The regime is "Recovery" 🟢, data seems like a snapshot, I'll mention conditions are stable/default as per instruction. Actually, the instruction says "If conditions are unchanged, say they are stable." I need to decide if I should state they are stable. I'll just include a line like "Conditions remain stable across key metrics" or similar, but only if it makes sense. Maybe I'll just note that the regime is Recovery and data is current, implying stability, or explicitly say "Conditions are stable" as a safe phrase. I'll read carefully: "If conditions are unchanged, say they are stable." It's a conditional instruction. Since I don't have before/after, I'll assume the snapshot represents current unchanged conditions, so I'll say "Conditions are stable" or similar. I'll integrate it naturally.
   - *Mention raw data is available in /data* -> must include at the end or in the commentary.
   - *Concise and consistent tone* -> risk commentary style, professional, clipped.

3.  **Draft - Section by Section:**

   **Risk Commentary:**
   - Brief macro tone. Recovery regime, VIX low/modest, mortgage unfavorable, bond-equity spread favoring bonds. I'll keep it short.

   **Bullet-point Market Summary:**
   - Must include: mortgage rate & condition, income spread & favorability, VIX, SPY trend, yield context.
   - Format: bullet points.

   Let's outline bullets:
   - SPY trading above its 200-day MA (773.5 vs 716.74), confirming an uptrend within the Recovery regime.
   - QQQ holding

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
