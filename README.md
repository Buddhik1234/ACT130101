# ACT 130101 – Financial Accounting Study Dashboard

**University of Colombo · BBA Semester I**

An interactive, offline-capable Progressive Web App (PWA) for studying Financial Accounting (ACT 130101). Covers all 11 LKAS/SLFRS modules with bilingual Sinhala/English content, exam traps, and study-progress tracking.

## Live App

🌐 **[Open the App](https://YOUR_USERNAME.github.io/act130101)**

> Replace `YOUR_USERNAME` with your GitHub username after deploying.

---

## Features

- 📚 **11 Modules** — M01 Conceptual Framework through M11 Employee Benefits
- 🔄 **Two Study Modes** — High-Yield Summary (සරලවම) and Deep Audit (විස්තරාත්මකව)
- 🌐 **Bilingual** — Tap underlined terms for instant Sinhala translations
- ✅ **Study Tracker** — Mark modules as studied; progress bar updates live
- 📱 **Mobile-first** — Optimised for Galaxy A11 and Redmi 10A (380px screens)
- ⚡ **Offline support** — Works without internet after first load (PWA / Service Worker)
- 🏠 **Home Dashboard** — Course overview, progress stats, all modules at a glance

## Modules Covered

| Code | Standard | Topic |
|------|----------|-------|
| M01 | Framework | Introduction & Conceptual Framework |
| M02 | LKAS 01 | Presentation of Financial Statements |
| M03 | LKAS 07 | Statement of Cash Flows |
| M04 | LKAS 16 | Property, Plant and Equipment |
| M05 | LKAS 37 | Provisions, Contingent Liabilities & Assets |
| M06 | LKAS 38 | Intangible Assets |
| M07 | LKAS 10 | Events After the Reporting Period |
| M08 | LKAS 08 | Accounting Policies, Estimates and Errors |
| M09 | SLFRS 15 | Revenue from Contracts with Customers |
| M10 | LKAS 02 | Inventories |
| M11 | LKAS 19 | Employee Benefits |

## Install as a Phone App

### Android (Chrome)
1. Open the app URL in Chrome
2. Tap the **⋮ menu → "Add to Home screen"**
3. Tap **Add** — the app icon appears on your home screen

### iOS (Safari)
1. Open the app URL in Safari
2. Tap the **Share button (□↑) → "Add to Home Screen"**
3. Tap **Add**

---

## Deploy to GitHub Pages (Step-by-Step)

```bash
# 1. Clone or download this repo, then:
git init
git add .
git commit -m "Initial commit"

# 2. Create a GitHub repo and push
gh repo create act130101 --public --source=. --push
# OR: go to github.com → New Repository → push manually

# 3. Enable GitHub Pages
# Go to: Settings → Pages → Source: "Deploy from a branch" → Branch: main → / (root) → Save
```

The app will be live at `https://YOUR_USERNAME.github.io/act130101` within ~1 minute.

---

## Tech Stack

- Vanilla HTML/CSS/JS — no build step, no dependencies
- Google Fonts (Plus Jakarta Sans, Noto Sans Sinhala)
- Service Worker for offline caching
- Web App Manifest for PWA install
