
# Market Risk Monitor

![Market Regime](https://img.shields.io/badge/Market%20Regime-Recovery-green)

**🟢 Recovery**  
**Score:** Downturn 0/3 | Recovery 3/3  
**Last Updated:** 2026-09-21

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

1.  **Analyze Requirements:**
   - **Market regime**: 🟢 Recovery (given)
   - **Output format**: Short risk commentary + bullet-point market summary
   - **Specific data points to include explicitly**:
     - Mortgage rate and condition
     - Income spread (SP dividend yield vs 10Y) and state whether it favors bonds or equities
     - VIX level
     - SPY trend (relative to MA200)
     - Yield context (TNX yield mentioned)
   - **Additional**: If conditions are unchanged, say they are stable
   - **Constraints**: Concise, consistent tone, mention raw data available in /data

2.  **Extract & Interpret Data from Snapshot:**
   - SPY: price 761.69, ma200 716.28 → Price > MA200, uptrend
   - QQQ: price 721.45, ma100 711.87 → Price > MA100, uptrend
   - ARKK: 3-month change +12.5% → Strong performance
   - VIX: 14.81 → Low volatility
   - TNX: 4.96% → 10-year yield context
   - OVX: 50.39, regime "low" → Low commodities volatility
   - Mortgage: rate 6.95%, condition "Unfavorable" → Explicitly required
   - Income spread: sp_div_yield 0.98%, ten_year_yield 5.01%, spread -4.03%, regime "Bond Yield Advantage" → Bonds favored (negative spread means bond yield > equity yield, favoring bonds)

   - Regime: 🟢 Recovery (given)

3.  **Draft - Section by Section:**

   **Risk Commentary:**
   - Keep it short, tie in regime, volatility, spread, mortgage.
   - Regime is Recovery, VIX low at 14.81, spread favors bonds, mortgage unfavorable at 6.95%.
   - "Markets are in a Recovery regime with equities trading above key moving averages, though credit conditions remain tight with mortgage rates at 6.95% and unfavorable. The income spread continues to favor bonds over equities, holding at -4.03% as the 10-year yield outperforms S&P dividends. Low VIX readings suggest complacency, but the bond yield advantage warrants caution on equity duration."

   **Bullet-Point Market Summary:**
   - Need to include explicitly:
     * Mortgage rate: 6.95% and condition "Unfavorable"
     * Income spread: sp_div_yield 0.98% vs ten_year_yield 5.01%, spread -4.03%, and state it favors bonds
     * VIX: 14.81
     * SPY trend: price 761.69 vs ma200 716.28 (uptrend)
     * Yield context: TNX 4.96%
     * Note: conditions stable? The prompt says "If conditions are unchanged, say they are stable". Looking at data, nothing indicates change, so I should add "conditions are stable" or similar. Actually, re-read: "If conditions are unchanged, say they are stable". The data is a snapshot, so I'll assume stable and mention it, or just naturally incorporate. I'll add a line or note about stability.
   - Let's structure bullets clearly:
     - SPY: $761.69, above MA200 ($716.28) → bullish trend
     - QQQ: $721.45, above MA100 ($711.87) → momentum intact
     - VIX at 14.81 → low volatility environment
     - TNX yield 4.96% → elevated rate backdrop
     - Mortgage rate 6.95%, condition "Unfavorable" → pressuring housing affordability
     - Income spread: S&P div yield 0.98% vs 10Y 5.01%, spread -4.03% → **favors bonds** over equities
     - ARKK +12.5% 3-month → strong risk-on sentiment
     - Conditions are stable

   - Check requirements:
     * Mortgage rate and condition explicitly in bullets ✓
     * Income spread explicitly in bullets, state favors bonds

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
