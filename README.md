# Capacity Lab — Physiological Work Capacity Trainer

A responsive, private, dependency-free web application for a 12-week programme covering aerobic stamina, anaerobic capacity, strength support, and heat/hydration education.

## What is included

- 12 selectable training weeks, progressing through Foundation, Build Capacity and Performance phases.
- Day-by-day session guidance for easy cardio, VO₂ max intervals, strength support, short sprints, anaerobic capacity and recovery.
- Workout logs for duration, effort (RPE), date and personal notes.
- Training-volume chart, weekly completion, and aerobic/anaerobic progress summaries.
- Guided interval timer with warm-ups, work/recovery stages, pause, skip and reset.
- Five performance tests, saved results and trend graphs.
- Reference library for training methods, heat acclimatisation and hydration, plus an optional environmental/hydration observation log.
- Dark/light themes and export/import of all saved training data as JSON.
- Responsive desktop/mobile layout; installable as a basic PWA when hosted over HTTPS.

## Start immediately

**Fastest option:** Open `Capacity_Lab_Standalone.html` in Chrome, Edge or another modern browser. It includes all code in a single file. This file is available separately from the ZIP.

**From this project ZIP:** Extract it, then open `index.html` in your browser. The app has no installation dependencies, and there is no build step.

## Publish it online free with GitHub Pages

1. Create a public GitHub repository, or choose an existing repository for this site.
2. Upload `index.html`, `styles.css`, `app.js`, `icon.svg`, `manifest.webmanifest`, and `sw.js` to the repository root.
3. Go to **Settings → Pages → Build and deployment**.
4. Choose **Deploy from a branch**, branch `main`, folder `/ (root)`, then save.
5. Wait for GitHub Pages to provide your website URL.

With HTTPS hosting, the bundled service worker caches the app shell to support offline usage after a successful first load. Browser storage is local to the site/device: data entered on a downloaded file will **not** automatically appear on the hosted website. Use **Settings → Export JSON** on one and **Import JSON** on the other to move your data.

## Data and privacy

No accounts, cloud storage, tracking scripts, analytics, or external network libraries are required. Workout history and test results live in your browser's `localStorage` and can be lost if you clear browser data or use another device. Export backups regularly. Private/Incognito mode may not retain them.

## Fitness use

This is a training template, not a substitute for medical care or an individualized programme. Progress gently, especially if new to hard intervals. Never train through symptoms of heat illness or use deliberate dehydration as a training method.
