# Pawi — Study Timer & Stats 🐢

**Pawi** is a minimalist, ad-free study timer built to help students and developers reach a state of deep focus. It follows a strict **zero-friction philosophy**: no ads, no accounts, no tracking — just you and your work.

[![Get it on Google Play](https://play.google.com/intl/en_us/badges/static/images/badges/en_badge_web_generic.png)](YOUR_PLAY_STORE_LINK_HERE)

---

## ✨ Why Pawi?

Most study timer apps are cluttered with ads, or fail to deliver reliable background alerts once battery optimization kicks in. As a student developer who needed this myself, I built Pawi to solve those exact problems:

- **Reliable background timers** — runs as a proper foreground service, so break alerts trigger on time, even in battery-saving mode or when the screen is off.
- **Privacy-first stats** — session heatmaps and history are stored **100% locally** on your device via SQLite. No cloud sync, no accounts, no data collection, ever.
- **Ambient focus sounds** — built-in soundscapes (Rain, Library Hum, Deep Sea) to help mask distractions and stay in flow.
- **Clean, minimalist design** — a distraction-free interface built around the Pawikan (sea turtle) mascot.

---

## 🛠️ Technical Overview

Pawi's source is currently closed-source, but here's a look at how it's built:

| Layer | Technology |
|---|---|
| Framework | Flutter (Dart) |
| Architecture | MVVM (Model–View–ViewModel) |
| State Management | Provider |
| Local Storage | Drift (SQLite) — offline-first, no network dependency |
| Background Execution | Foreground service with wake lock support |
| Navigation | go_router |

---

## 📄 Documentation

- [Privacy Policy](PRIVACY.md)
- [License](LICENSE)

---

## 👤 About the Developer

**Reindel Andrada**
Information Systems student at Technological University of the Philippines – Manila

[LinkedIn](YOUR_LINKEDIN_URL) · [Portfolio](YOUR_PORTFOLIO_URL)
