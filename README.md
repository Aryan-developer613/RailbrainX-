# 🚆 RailbrainX — AI Railway Traffic Management Dashboard

A real-time AI-powered railway traffic management and simulation dashboard built with pure HTML, CSS, and JavaScript.

![RailbrainX Dashboard](https://img.shields.io/badge/RailbrainX-AI%20Traffic%20Management-2563eb?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Live-16a34a?style=for-the-badge)
![Tech](https://img.shields.io/badge/Tech-HTML%20%7C%20CSS%20%7C%20JS-f59e0b?style=for-the-badge)

---

## 🌐 Live Demo

🔗 **[View Live Dashboard](https://Aryan-developer613.github.io/railbrainx/)**


---

## ✨ Features

- 🗺️ **Live Railway Map** — Canvas-based animated train simulation across Indian railway routes
- 📊 **Analytics Dashboard** — Speed, delay, and performance charts powered by Chart.js
- 🛰️ **GPS Live Tracking** — Real-time train tracking via RapidAPI (IRCTC)
- 🕐 **Timetable View** — Schedule and status of all trains
- 🚉 **Platform Manager** — Live platform occupancy and status
- ⚡ **KPI Bar** — Real-time metrics: active trains, delays, conflicts, energy usage
- ⌨️ **Keyboard Shortcuts** — Space (play/pause), Arrow keys (step), R (reset), +/- (zoom)

---

## 🖥️ Tech Stack

| Technology | Usage |
|---|---|
| HTML5 Canvas | Railway map & train animation |
| CSS3 | Responsive layout, animations |
| JavaScript (Vanilla) | Simulation engine, data logic |
| Chart.js v4.4.1 | Analytics charts |
| RapidAPI (IRCTC) | Live train status (optional) |
| Google Fonts | Inter + JetBrains Mono |

---

## 🚀 Getting Started

### Run Locally
```bash
# Clone the repo
git clone https://github.com/YOUR-USERNAME/railbrainx.git

# Open in browser
open index.html
```
No build step needed — it's a single HTML file!

### Live API Setup (Optional)
1. Get a free API key from [RapidAPI — IRCTC](https://rapidapi.com/IRCTCAPI/api/irctc1/)
2. Open the dashboard → click **"Set API Key"** banner
3. Enter your key → GPS Live Tracking will activate

---

## 📁 Project Structure

```
railbrainx/
├── index.html      # Main dashboard (all-in-one)
└── README.md       # Project documentation
```

---

## ⌨️ Keyboard Shortcuts

| Key | Action |
|---|---|
| `Space` | Play / Pause simulation |
| `→` | Step forward one frame |
| `←` | Step backward one frame |
| `R` | Reset simulation |
| `+` / `=` | Zoom in |
| `-` | Zoom out |
| `0` | Reset zoom |

---

## 🙌 Credits

Built with ❤️ using vanilla web technologies. Train data based on Indian Railways network.

---

## 📄 License

MIT License — free to use and modify.
