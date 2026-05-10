# Contributing to Halal Mortgage Calculator

Thank you for wanting to improve this tool. A few ground rules to keep the codebase clean and the live site safe.

## Ground rules

- **Single file only** — everything stays in `index.html`. No build tools, no npm, no frameworks.
- **No new external CDNs** — only `fonts.googleapis.com`, `fonts.gstatic.com` and `cdnjs.cloudflare.com` are permitted. The CI will reject anything else.
- **No tracking** — no analytics, no cookies, no external data calls. This is a privacy-first tool.
- **Match the design** — use the existing CSS variables, card styles and font sizes. Don't introduce new design patterns.
- **Test your maths** — if you touch any calculation (mortgage, stamp duty, affordability), verify it against a known external calculator and document your source in the PR.

## How to contribute

1. Fork the repo
2. Make your changes to `index.html`
3. Open a pull request against `main`
4. All CI checks must pass before review
5. At least one maintainer review is required before merge

## What needs extra care

| Area | Why |
|---|---|
| Mortgage calculations | Errors mislead real buyers making real decisions |
| Stamp duty bands | These change with each UK budget — cite your source |
| Rate presets | Must reflect real published rates — include a link to the source |
| Provider information | Minimum deposits and LTV limits change — verify before updating |

## Reporting errors

If you spot a calculation error, please open an issue immediately — don't wait. Label it `bug: calculation` so it gets prioritised.
