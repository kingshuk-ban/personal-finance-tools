# Start Your Finances Right — Tools

A collection of free, open-source personal finance tools that run entirely in your browser. No server. No account. No data collection. Every calculation happens locally on your device.

---

## Tools

### 🚨 One Shock Away — Financial Fragility Analyzer
`one-shock-away.html`

Maps your true financial fragility — how close you are to a crisis if one thing goes wrong (job loss, medical bill, unexpected expense). Input your income stability, monthly burn rate, debt obligations, and asset coverage to get a scored dashboard and a prioritized action plan.

| Tab | What it covers |
|-----|----------------|
| 👤 Profile | Household context and dependencies |
| 💼 Income & Job Security | Income sources, stability score, concentration risk |
| 🏠 Expenses | True monthly burn rate, fixed vs variable split |
| 💳 Debt & Obligations | Debt-to-income, minimum payments, risk exposure |
| 🏦 Assets & Safety Net | Liquid vs illiquid assets, emergency fund coverage |
| 📊 Dashboard | Fragility score, risk heat map, priority actions |
| 🚨 Full Report | Printable summary with scored findings |

---

### 📈 Medium-Term Wealth Builder
`medium-term-wealth-builder.html`

Bridges the gap between daily cashflow and long-term retirement planning — the 1–7 year horizon that most tools ignore. Define specific goals (house down payment, emergency fund, education), map them to accounts by liquidity tier, and get a funding analysis with monthly savings targets and an allocation architecture.

| Tab | What it covers |
|-----|----------------|
| 👤 Profile & Goals | Goals, timeline, priority |
| 🏦 Accounts & Holdings | Accounts by liquidity tier (liquid → locked) |
| 📊 Goal Funding Analysis | Monthly savings required, priority matrix, funding gaps |
| 🏗 Allocation Architecture | Bucket framework, recommended allocation mix |

---

### 🏦 Retirement Planner
`retirement-planner-saving.html`

Comprehensive retirement planning across all account types. Projects growth across tax buckets, models Roth conversions, calculates optimal withdrawal ordering, and produces a printable PDF report.

| Tab | What it covers |
|-----|----------------|
| 👤 Client Profile | Personal data, retirement age, risk assumptions |
| 🏦 Accounts & Holdings | 401k, Roth IRA, Traditional IRA, HSA, taxable brokerage, Social Security, real estate |
| 📈 Growth Projections | Per-account and tax-bucket projections every 10 years |
| 💸 Tax Analysis | Bracket breakdown, Roth conversion ladder, tax bucket balance score |
| 🔀 Withdrawal Strategy | Optimal drawdown order, early retirement bridge strategies (Rule of 55, SEPP 72(t), Roth ladder), RMD modeling from age 73 |
| 📋 Action Plan | Retirement Confidence Score, scenario analysis, printable 6-page PDF report |

---

### ⚖️ Systematic Risk Diversifier
`systematic-risk-diversifier.html`

Portfolio construction and backtesting tool covering 10 asset classes and 30 ETFs. Explains the difference between systematic risk (market-wide, addressed through asset class diversification) and unsystematic risk (company-specific, addressed through broad ETFs). Backtests 2014–2024 using historically calibrated return data — no live API calls.

| Tab | What it covers |
|-----|----------------|
| 📊 Portfolio Builder | Allocate across 10 asset classes, choose ETFs, load presets |
| 📈 Backtest Results | CAGR, Sharpe, Sortino, Max DD, year-by-year table, holdings breakdown |
| 🌊 Risk Analysis | Risk stat cards, correlation matrix across holdings |
| 🔢 Ratios & Education | Plain-English explanation of every metric with formulas and benchmarks |
| ⚖️ Compare Portfolios | Side-by-side comparison of up to 5 portfolios with a reference anchor |

**Asset classes:** US Large Cap · US Small/Mid Cap · International Developed · Emerging Markets · Aggregate Bonds · Long-Term Treasuries · Short-Term/Cash · REITs · Commodities/Gold · TIPS

**Preset portfolios:** Bogleheads 3-Fund · Total World 2-Fund · 60/40 Classic · All-Weather (Bridgewater) · Aggressive Growth · Global Diversified · Permanent Portfolio

---

## Privacy

All data entered into these tools stays entirely in your browser. Nothing is transmitted to any server. The tools have no backend, no analytics, no cookies, and make no external network requests (other than loading fonts from Google Fonts on first open).

The Systematic Risk Diversifier uses embedded historical return data — it does not call Yahoo Finance or any live data provider.

---

## Usage

Download any `.html` file and open it in a browser — no installation or build step required.

```bash
git clone https://github.com/YOUR_USERNAME/finance-tools.git
cd finance-tools
open retirement-planner-saving.html        # macOS
start retirement-planner-saving.html       # Windows
xdg-open retirement-planner-saving.html    # Linux
```

Or use the live hosted versions via GitHub Pages:

```
https://YOUR_USERNAME.github.io/finance-tools/
```

To enable GitHub Pages: **Settings → Pages → Deploy from branch → main → / (root) → Save**

---

## Stack

Pure HTML, CSS, and JavaScript. No framework. No build step. No dependencies to install.

- **Fonts:** Libre Baskerville (headings) · Outfit (body) · JetBrains Mono (numbers)
- **Charts:** Chart.js (allocation donut only — all other output is tables)
- **Design system:** Navy / Gold / warm off-white palette, consistent across all tools

---

## Disclaimer

These tools are for **educational and informational purposes only**. They do not constitute investment, tax, legal, or financial advice. All projections and backtested results are estimates based on user inputs and simplified models — actual outcomes may differ materially. Past performance is not indicative of future results. Backtested results are hypothetical and do not represent actual trading.

Consult a qualified financial advisor, CPA, and/or attorney before making financial decisions.

---

## License

MIT — see [LICENSE](LICENSE)
