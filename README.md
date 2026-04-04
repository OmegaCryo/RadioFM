# 📻 The Vice FM — Retro Radio Station Web Project

A personal playlist showcase built with an old internet aesthetic inspired by early 2000s websites like Rockstar Games' GTA promotions. Each "station" is its own self-contained page with a unique identity, color palette, and vibe — all linking out to real Pandora playlists.

---

## 🎯 Project Goals

- Build a portfolio-worthy personal project using HTML, CSS, and light JavaScript
- Recreate the gritty, neon-soaked aesthetic of early 2000s web design with a modern twist
- Showcase personal music taste through a creative "multi-station radio network" concept
- Practice CSS animations, theming, and layout without relying on frameworks

---

## 🗂️ Project Structure

```
radio-network/
│
├── the-vice/
│   ├── index.html       # 80s / Miami Nights station
│   ├── style.css
│   └── script.js
│
├── madhouse-fm/         # (Coming soon — Rock station)
│   ├── index.html
│   ├── style.css
│   └── script.js
│
└── index.html           # Hub/dial page linking all stations
```

---

## 📡 Stations

| Station | Genre | Vibe | Status |
|---|---|---|---|
| **The Vice** | 80s / Synth-Pop | Miami neon, VHS nights, hot pink & cyan | 🔨 In Progress |
| **Madhouse FM** | Rock | Gritty red & black, distortion, underground | 📋 Planned |
| More TBD | — | — | 💭 Brainstorming |

---

## 🎨 Design Language

Each station has its own visual identity but they share a common aesthetic foundation:

- **Dark backgrounds** — black or deep navy base
- **Neon glow effects** — CSS `text-shadow` layered for electric text
- **Scanline overlay** — full-page CSS `repeating-linear-gradient` for CRT feel
- **CRT vignette** — `radial-gradient` darkening screen edges
- **Retro typography** — Google Fonts: *Bebas Neue*, *VT323*, *Special Elite*
- **Blinking ON AIR badge** — CSS `@keyframes` animation
- **Scrolling ticker** — JavaScript `setInterval` cycling through track names

---

## 🛠️ Tech Stack

| Technology | Usage |
|---|---|
| HTML5 | Page structure and semantic markup |
| CSS3 | Styling, animations, theming via CSS variables |
| Vanilla JavaScript | Ticker animation, minimal interactivity |
| Google Fonts | Retro typography |

> **No frameworks. No libraries. Just raw HTML, CSS, and JS.**

---

## 🚀 Build Plan

### Phase 1 — Project Setup
- Folder structure, file creation, Google Fonts linked

### Phase 2 — HTML Skeleton
- Header, ticker bar, hero section, tracklist, footer

### Phase 3 — Base CSS Styling
- Colors, fonts, neon glow, ON AIR badge, TUNE IN button

### Phase 4 — Atmosphere CSS
- Scanlines, grain texture, CRT vignette, glowing borders

### Phase 5 — JavaScript Ticker
- Array of track names cycling via `setInterval`

### Phase 6 — Polish & Deploy
- Mobile check, GitHub push, deploy via GitHub Pages or Netlify

---

## 🔗 Deployment

- **GitHub Pages** — Free static hosting via repository settings
- **Netlify** — Alternative free option with drag-and-drop deploy

---

## 💡 Future Ideas

- A hub "dial" page where users can tune between all stations
- CSS variable theming so each station is a reskin of one template
- Ambient audio loop per station (toggleable)
- Fake "listener count" or signal strength meter

---

## 👤 Author

Personal project — built for fun and portfolio purposes.  
Inspired by early 2000s web design and the golden age of internet aesthetics.
