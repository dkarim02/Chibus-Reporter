# Nail the Plan — DC 499

Daily planning and bridge-note tool for Distribution Center 499. Tracks planned vs. actual volume, headcount, and financial figures across all departments and shifts, and builds formatted EOD bridge notes ready to copy into Teams.

**Live:** [dkarim02.github.io/Nail-the-Plan](https://dkarim02.github.io/Nail-the-Plan)

---

## Features

- **All departments** — Retail, Ecom, DC Shipping, DC Receiving, Returns, Item Prep
- **Both shifts** — 1st and 2nd, with Mid-Day and EOD checkpoints each
- **Three PPH scores** — Planned PPH, Actual PPH, and Financial PPH per checkpoint
- **Indirect hours** — Track indirect vs. total hours with automatic % display
- **Auto bridge notes** — EOD summaries build automatically as you enter data
- **Post to Teams** — Send bridge notes via Adaptive Card to your shift webhook
- **Submit EOD / Send Report** — Power Automate flow integrations
- **Push / Sync depts** — Share your numbers to a shared store; pull other departments' latest
- **Countdown timer** — Shows how long until the current posting window closes
- **Post Late** — Send a missed posting with a justification reason
- **Shift view toggle** — Filter to 1st shift, 2nd shift, or both
- **Dark mode** — Toggle in the header
- **Export** — JSON (full data) and CSV per day
- **Import** — Load a previously exported JSON to restore a day's data

## Usage

No install, no backend. Open `index.html` in any modern browser or visit the GitHub Pages link above. All data is stored in browser `localStorage` — export before clearing browser data.

Set your Teams webhooks via **Webhooks ▾** in the toolbar (1st shift, 2nd shift, Submit EOD, Send Report, Check Status URLs).

## Disclaimer

This tool measures throughput only and may not be used to evaluate, coach, or hold team members accountable on performance.
