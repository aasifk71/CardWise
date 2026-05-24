# CardWise — AI Credit Card Recommendation Engine
### Axis Bank × FreechargeBiz · Product Assignment Submission

> **Live Prototype →** [CardWise](https://card-wise-blue.vercel.app/)
> **PRD Document →** [`CardWise_PRD.pdf`](./CardWise_PRD.pdf)

---

## What is CardWise?

CardWise is an AI-powered credit card recommendation engine that replaces static, boring questionnaires with a **90-second personalised journey**. It analyses a user's financial footprint — SMS spend data, bureau soft-pull, and explicit preferences — to surface the single best-fit Axis Bank or Freecharge card, complete with a transparent match score.

**The problem it solves:** 70%+ of users drop off card-finder flows because they feel too long and the results feel generic. CardWise cuts this to under 90 seconds and shows users *why* a card was recommended.

---

## Deliverables

| File | Description |
|------|-------------|
| `cardwise_prototype.html` | Fully interactive prototype (open in any browser) |
| `CardWise_PRD.pdf` | Complete PRD — problem statement, user stories, architecture, prioritisation |
| `README.md` | This file |

---

## Prototype — How to Run

### Option 1: GitHub Pages (Recommended)
1. Fork or clone this repo
2. Go to **Settings → Pages**
3. Set source to `main` branch, `/ (root)`
4. Your live URL will be: `https://your-username.github.io/cardwise/cardwise_prototype.html`

### Option 2: Open Locally
```bash
git clone https://github.com/your-username/cardwise.git
cd cardwise
open cardwise_prototype.html   # macOS
# or double-click the file in Windows/Linux
```

No dependencies. No build step. Pure HTML/CSS/JS — works offline.

---

## Prototype Walkthrough

The prototype demonstrates the full end-to-end user journey across 5 interactive screens:

```
Screen 0 → Consent        Select data sources (SMS, bureau, bank statement)
Screen 1 → Profile        Name, age, city, employment type
Screen 2 → Spending       Category tiles + monthly spend slider
Screen 3 → Goals          Reward preference + credit score range
Screen 4 → AI Analysis    Animated loading with live step indicators
Screen 5 → Result         Personalised card recommendation + match score
```

### Try these flows to see different recommendations:

| Your selections | Recommended card |
|-----------------|-----------------|
| Travel category + Travel goal | Axis Magnus (Super-premium travel) |
| Cashback goal | Axis Ace (5% cashback) |
| Lifestyle goal | Axis Vistara Signature |
| Rewards goal (default) | Freecharge Plus (Zero-fee) |

---

## PRD Summary

The `CardWise_PRD.pdf` covers all three assignment tasks:

**Task 1 — Product Requirements**
- Problem statement & three user personas (Priya, Rajan, Mehak)
- End-to-end user journey with drop-off levers
- Technical architecture (React PWA → AWS microservices → recommendation engine)
- Data strategy: SMS parsing, bureau soft-pull via AA framework, questionnaire fallback
- 6-parameter weighted scoring algorithm

**Task 2 — User Stories & Prioritisation**
- 9 detailed user stories with Gherkin-style acceptance criteria
- MoSCoW prioritisation with RICE scores
- MVP scope: US-01 to US-06 · 8 weeks · 4-person squad

**Task 3 — Prototype**
- See `cardwise_prototype.html` above

---

## Tech Stack (Prototype)

- **HTML5 / CSS3 / Vanilla JS** — zero dependencies, instant load
- **Fonts** — Sora (UI) + DM Serif Display (headings) via Google Fonts
- **Recommendation logic** — rule-based engine mapping spend categories + goal → card
- **Animations** — CSS keyframes + JS-driven progress transitions

---

## Assignment Details

| Field | Value |
|-------|-------|
| Submitted by | [Your Name] |
| Organisation | FreechargeBiz |
| Deadline | May 31, 2026 |
| Version | 1.0 |

---

## License

This project is submitted as part of a product design assignment for FreechargeBiz / Axis Bank. Not for commercial use.
