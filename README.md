# DecisionLedger

**The micro-journal that turns your choices into patterns.**

---

## Problem

You make 30–50 significant micro-decisions per day — study vs. build, defer vs. act, spend vs. save. You have no record of them. So you diagnose nothing, fix nothing, and repeat the same costly calls every week.

## Who it's for

BCom students, CA aspirants, founders, builders — anyone in high-execution mode with no decision infrastructure.

## Why existing tools fail

| Tool | Failure |
|------|---------|
| Notion | Too heavy, no decision-native schema |
| Journaling apps | Narrative-first, not data-first |
| Eisenhower matrix | Static template, no memory |
| Nothing | Default for 99% of people |

## Why DecisionLedger wins

- **30-second logging** — decision, reason, category, emotion, confidence, reversibility
- **Outcome tagging** — mark each decision Good / Regret / Pending after it plays out
- **Auto pattern detection** — regret rate, confidence calibration, category drains, emotion triggers
- **Day streak** — builds the logging habit
- **Zero friction** — single HTML file, works offline, no account needed

---

## Features

- Glass UI with dark base (`#07070f`), frosted cards, luminous accents
- 3 tabs: Log · Ledger · Insights
- Emotion grid (8 states), confidence slider, reversibility toggle
- Live stats: total logged, good-call %, streak
- Insight engine: regret rate meter, avg confidence, category breakdown, pattern chips
- localStorage persistence — survives browser refresh
- Mobile-first, touch-friendly

---

## Tech

- Pure HTML / CSS / JS — zero dependencies
- Fonts: Syne (display) + DM Sans (body) via Google Fonts
- Storage: `localStorage` (key: `dl_v3`)
- Offline: fully functional with no internet after first load

---

## Install / Use

1. Download `DecisionLedger.html`
2. Open in any browser
3. Log your first decision

That's it. No server, no account, no setup.

---

## Roadmap ideas

- CSV export for spreadsheet analysis
- Weekly email digest (via mailto: link)
- Decision templates for recurring call types
- Spaced review reminders (ServiceWorker)

---

*Built as a single-file micro-app. Fork and own it.*
