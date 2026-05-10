# 🕌 Halal Mortgage Calculator

> **Free, open-source tool for UK Muslims to compare Islamic Home Purchase Plans (HPPs) with conventional mortgages — side by side, with real 2025 rates.**

[![Live Site](https://img.shields.io/badge/🌐_Live_Site-halalmortgagecalculator.org.uk-1D9E75?style=flat-square)](https://halalmortgagecalculator.org.uk)
[![MIT License](https://img.shields.io/badge/License-MIT-0F6E56?style=flat-square)](LICENSE)
[![No dependencies](https://img.shields.io/badge/Dependencies-None-1a1a18?style=flat-square)]()
[![Single file](https://img.shields.io/badge/Size-Single_HTML_file-888780?style=flat-square)]()

---

## Why I built this

For years I never really understood how Islamic finance worked when it came to buying a home. The information is out there — but it's scattered across lender websites, broker articles, and comparison tools that want your data.

I wanted one honest tool that just showed me the numbers. So I built it.

---

## What it does

Compare an **Islamic Home Purchase Plan (HPP)** — using the Diminishing Musharakah structure offered by Gatehouse Bank, StrideUp and others — against a **conventional interest-based mortgage**, in real time.

| Feature | Details |
|---|---|
| 📊 Side-by-side comparison | Monthly payments, total cost, profit vs interest |
| 🎚️ Live sliders | Adjust price, deposit, term and rates instantly |
| 📅 Year-by-year charts | Remaining balance and cumulative cost difference |
| 💡 Payment breakdown | See exactly what you're paying — rent vs acquisition vs riba |
| 📱 Mobile optimised | Works on any screen size |
| 📄 PDF export | Save your results via browser print |
| 📲 WhatsApp share | Native share sheet on mobile |
| ℹ️ How it works modal | Plain-English explainer on Diminishing Musharakah |
| 🔒 No tracking | Zero data collected. No cookies. No analytics. |
| ⚡ No install | Single HTML file — open in any browser, works offline |

---

## Live demo

👉 **[halalmortgagecalculator.org.uk](https://halalmortgagecalculator.org.uk)**

---

## How to use it locally

No npm. No Node. No build step. Just:

```bash
# Clone the repo
git clone https://github.com/sohaibsohail98/halal-mortgage-calculator.git

# Open in browser
open index.html
```

Or just [download index.html](https://raw.githubusercontent.com/sohaibsohail98/halal-mortgage-calculator/main/index.html) directly and double-click it.

---

## How Islamic HPPs actually work

Islamic mortgages avoid **riba** (interest), which is forbidden in Islam (Quran 2:275). Instead, UK providers use a structure called **Diminishing Musharakah**:

1. **The bank co-buys the property with you** — your deposit is your initial ownership share
2. **You pay two things each month** — rent on the bank's share, and an acquisition payment that buys more of their share
3. **Your ownership grows, their share shrinks** — until you own 100% at the end of the term
4. **No interest is ever charged** — the bank earns profit through rent, not riba

The calculator models this accurately, showing you both the rent and acquisition components of each payment.

---

## UK providers covered

| Provider | Min deposit | Notes |
|---|---|---|
| [Gatehouse Bank](https://gatehousebank.com/personal/home-finance) | 5% | Most established. Up to 80% LTV. England & Wales. |
| [StrideUp](https://strideup.co) | 10% | Accepts gifted deposits & complex income. Up to 6.5× income. |
| [Offa](https://offa.co.uk) | TBC | New FCA-authorised Islamic fintech (2025). |
| [Wayhome](https://wayhome.co.uk) | Low | Gradual homeownership / shared equity model. |
| [Pfida](https://pfida.com) | 15–20% | Community-driven. Long waiting lists. |

> **Rates in the calculator are based on publicly available 2025 data.** Always get a personalised quote directly from providers.

---

## Tech stack

- Pure HTML, CSS, and vanilla JavaScript — zero dependencies
- [Chart.js](https://www.chartjs.org/) (loaded via CDN) for charts
- [DM Sans + DM Serif Display](https://fonts.google.com/) (loaded via Google Fonts)
- Works completely offline once fonts/charts are cached

---

## Contributing

Contributions welcome. If you spot an error in the calculations, want to add a new provider, or improve the UI — open an issue or submit a pull request.

Ideas for future improvements:
- [ ] Add stamp duty calculator
- [ ] Add affordability checker (income × multiplier)
- [ ] Add more provider rate presets
- [ ] Urdu / Arabic language toggle
- [ ] Embed-friendly iframe version for other sites

---

## Disclaimer

This tool is for **educational purposes only**. It does not constitute financial advice and is not regulated by the FCA. Always speak to a qualified Islamic mortgage broker before making any financial decisions.

---

## License

[MIT](LICENSE) — free to use, share, fork and build on. No copyright claimed.

---

*Built by [Sohaib Sohail](https://github.com/sohaibsohail98) — share it with anyone who needs it 🤲*