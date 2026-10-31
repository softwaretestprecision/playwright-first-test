# Video 1 — Playwright Tutorial for Beginners: Your First Test in 15 Minutes

Companion code for the Software Test Precision video. Four small tests against the public demo store https://www.saucedemo.com.

## Requirements
- Node.js 18+ (20 LTS recommended)

## Run it
```bash
npm install
npx playwright install --with-deps chromium
npx playwright test            # headless run
npx playwright test --headed   # watch the browser
npx playwright test --ui       # UI mode, great for learning
npx playwright show-report     # open the HTML report
```

## What's inside
| File | Purpose |
|---|---|
| `playwright.config.ts` | baseURL, reporter, browser project |
| `tests/first-test.spec.ts` | page load, login, locked-out error, add to cart |

## Starting from zero instead
`npm init playwright@latest` creates the same layout. This repo is what you get after following the video.

Want a full framework (Page Objects, fixtures, auth, CI) instead of a single test file? See the starter frameworks at https://swtestprecision.gumroad.com

---

## Software Test Precision
- 📺 YouTube: https://www.youtube.com/@softwaretestprecision
- 🧰 Templates & starter frameworks: https://swtestprecision.gumroad.com

License: MIT (see `LICENSE`).
