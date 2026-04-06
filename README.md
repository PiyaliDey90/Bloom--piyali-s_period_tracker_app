# 🌸 Bloom — Period Tracker

A simple, private, offline-first period & cycle tracker PWA designed for iPhone.

**[Live App →](https://piyalidey90.github.io/Bloom--piyali-s_period_tracker_app/)**

---

## Features

- **Cycle Tracking** — Log period start & end dates, automatically predicts your next period
- **Symptom Logging** — Track flow, mood, and 10+ symptoms for any day
- **Calendar View** — Monthly view showing period days, predicted days, fertile window & ovulation
- **Reminders** — Browser notifications before your predicted period (requires install)
- **Offline** — Works without internet after first load
- **Private** — All data stored locally on your device, never sent anywhere

---

## Install on iPhone

1. Open the app link in **Safari**
2. Tap the **Share** icon (box with arrow)
3. Tap **"Add to Home Screen"**
4. Tap **Add**

Bloom will appear on your home screen like a native app, with full offline support and notification access.

---

## How It Works

| Tab | Description |
|-----|-------------|
| 🌸 Home | Days until next period, fertile window, active period status |
| 📅 Calendar | Monthly cycle overview — tap any day for details |
| ✏️ Log | Log today's flow, mood, symptoms & notes |
| ⚙️ Settings | Adjust cycle length, notifications, export or clear data |

**Predictions** are calculated from the average of your last 6 logged cycles. The more you log, the more accurate they get.

**Fertile window** is estimated using the standard Ogino-Knaus model: ovulation occurs ~14 days before the next period, with a 5-day fertile window before it.

---

## Tech Stack

- Pure vanilla JavaScript — no frameworks, no build step
- CSS custom properties for theming (light + dark mode)
- `localStorage` for data persistence
- Service Worker for offline caching & push notifications
- PWA manifest for home screen installation

---

## Data & Privacy

All your data lives in your browser's `localStorage`. Nothing is collected, transmitted, or stored on any server. You can export a JSON backup anytime from the Settings tab.

---

## Local Development

No setup needed. Just open `index.html` in a browser, or serve it with any static server:

```bash
# Python
python -m http.server 8080

# Node (if installed)
npx serve .
```

---

*Made with 💗 as a personal project.*
