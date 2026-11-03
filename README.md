# Tally Habits

A small habit tracker for iPhone. It runs as a web app you add to your home screen.

- Daily habits on chosen weekdays, plus weekly (N× a week) and monthly (N× a month) goals
- Optional time for each habit: **At a time** (a reminder label) or **Done by** (a deadline). Checking off after the deadline marks it late and it counts half; you can flip late/on time if you forgot to tap
- Optional timer per habit (e.g. read 30 min): start/stop from Today, keeps running in the background, checks the habit off when you hit the goal; partial time counts partly
- Weight 1–5 per habit. Missing a weight-5 habit costs five times as much as missing a weight-1 habit
- Day, week and month scores, a progress chart (14 days, 12 weeks or 12 months), per-habit completion and streaks
- Go back to earlier days to fill in missed check-offs
- Works offline. Data stays on the device (localStorage)

## Install on iPhone

1. Host the folder over HTTPS. With GitHub Pages: repo Settings → Pages → Deploy from branch → `main` / root.
2. Open the URL in Safari, tap Share → **Add to Home Screen**.

No build step. It's plain `index.html`, `sw.js` and `manifest.webmanifest`.
