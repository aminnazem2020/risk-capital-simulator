
### Step 5 — Run Simulation

Click **▶ Run Simulation** and explore 7 tabs:

1. **📈 Equity** — 2,000 equity curves with statistics
2. **📉 Drawdown** — max drawdown analysis
3. **📋 Trades** — full trade-by-trade table
4. **🎲 Probability** — binomial distribution of outcomes
5. **🎯 Evaluation** — comparison against professional standards
6. **📄 Report** — full text report
7. **❓ Help** — built-in documentation

---

## 📖 Concepts Explained

### What Does "2,000 Paths" Mean?

When we say "2,000 paths", we mean **2,000 imaginary traders**, each running the same strategy but experiencing a different sequence of wins and losses.

**Example:** With 50% Win Rate and 10 trades, the most likely outcome is 5 wins / 5 losses. But other outcomes happen too:

| Outcome | Probability |
|---|---|
| 10 wins | 0.098% |
| 9 wins | 0.977% |
| 8 wins | 4.395% |
| 7 wins | 11.719% |
| **5 wins** ⭐ | **24.609%** |
| 3 wins | 11.719% |
| 1 win | 0.977% |
| 0 wins | 0.098% |

The simulator shows the entire distribution — not just the average.

### The Probability of Ruin

**Ruin** = losing 90% of your starting capital.

Even with a positive-expectancy strategy, ruin is possible if:
- Risk % per trade is too high
- The number of trades is too large
- Luck goes against you for a long stretch

This simulator lets you see ruin probability **before** risking real money.

### Three Loss Metrics

| Metric | Meaning |
|---|---|
| **Theoretical Max Loss** | Worst-case scenario (N consecutive losses). Probability ≈ 0.1% |
| **95% Confidence Loss** | In 95% of scenarios, loss is less than this |
| **50% (Median) Loss** | In half of scenarios, loss is less than this |

---

## 🛠️ Technical Stack

- **HTML5 + CSS3 + Vanilla JavaScript**
- **Plotly.js** for interactive charts (loaded from CDN)
- Zero dependencies, zero build step, single file
- Fully responsive — works on desktop, tablet, and mobile

---

## 📋 Roadmap

- [x] Monte Carlo simulation engine
- [x] Position sizing with 6 lock modes
- [x] Commission modeling
- [x] Compound vs Profit Lock modes
- [x] Professional evaluation vs industry standards
- [x] Multi-currency support
- [ ] Sharpe / Sortino / Calmar ratios
- [ ] Kelly Criterion auto-recommendation
- [ ] Value at Risk (VaR) and CVaR
- [ ] CSV export of trades table
- [ ] Multi-symbol portfolio simulation
- [ ] Real historical data backtesting

---

## 📜 License

This project is licensed under the **MIT License** — free to use, modify, and distribute with attribution.

---

## 👤 Author

**Risk & Capital Management**
- Designer & Manager
- 📞 **009224957723**

---

## ⚠️ Disclaimer

This simulator is an **educational and analytical tool**. It does not constitute financial advice. Simulation results are based on statistical models and do not guarantee future performance. Always conduct your own research and consult with a licensed financial professional before making real trading decisions.

---

## 🙏 Acknowledgements

Built with the goal of helping traders think probabilistically about risk — the way institutions do — instead of chasing certainty.

**If this tool helps you, share it with a trader who needs it.**
