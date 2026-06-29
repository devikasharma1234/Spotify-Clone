<p align="center">
  <h1 align="center">🎵 Spotify Clone — Frontend UI</h1>
  <p align="center">
    <em>A pixel-perfect, responsive Spotify Web Player clone built with pure HTML & CSS</em>
  </p>
  <p align="center">
    <img src="https://img.shields.io/badge/HTML5-61.9%25-E34F26?logo=html5&logoColor=white" />
    <img src="https://img.shields.io/badge/CSS3-38.1%25-1572B6?logo=css3&logoColor=white" />
    <img src="https://img.shields.io/badge/No%20Frameworks-Pure%20HTML%20%26%20CSS-brightgreen" />
    <img src="https://img.shields.io/badge/Theme-Dark%20Mode-1DB954?logo=spotify&logoColor=white" />
    <img src="https://img.shields.io/badge/License-ISC-blue" />
  </p>
</p>

---

## 📌 Table of Contents

- [About](#-about)
- [Features](#-features)
- [UI Layout Breakdown](#-ui-layout-breakdown)
- [Tech Stack](#️-tech-stack)
- [Project Structure](#-project-structure)
- [Getting Started](#-getting-started)
- [What I Learned](#-what-i-learned)
- [Roadmap](#️-roadmap)
- [Author](#-author)

---

## 📖 About

**Spotify Clone** is a front-end UI recreation of the **Spotify Web Player** — built entirely with **HTML5** and **CSS3**, without any external libraries or frameworks.

The goal of this project was to deeply understand and implement:
- **CSS Flexbox & Grid** for complex multi-panel layouts
- **CSS Custom Properties (variables)** for consistent theming
- Replication of a production-grade dark UI with pixel-level attention to detail

This is a **static frontend project** — no backend, no API calls, no JavaScript frameworks. Just clean, handcrafted HTML and CSS.

---

## ✨ Features

| Feature | Details |
|---|---|
| 🖥️ **Three-Panel Layout** | Navigation Sidebar · Library Panel · Main Content area — all built with Flexbox |
| 🎛️ **Media Player Bar** | Fixed bottom playback bar with seek slider, volume control, and playback buttons |
| 🎴 **Card-Based Content** | "Recently Played" and "Trending Now" sections using responsive card grids |
| 🖱️ **Hover Interactions** | Smooth hover states on playlist cards, nav links, and action buttons |
| 🌑 **Dark Mode Aesthetic** | Spotify's signature dark green & black palette via CSS custom properties |
| 📐 **Semantic HTML** | Clean, accessible structure using proper HTML5 semantic elements |
| 🔠 **Font Awesome Icons** | Crisp vector icons for player controls and navigation items |

---

## 🗂️ UI Layout Breakdown

```
┌─────────────────────────────────────────────────────┐
│  NAVBAR  (Logo + Nav Links + Install App)           │
├──────────┬──────────────┬───────────────────────────┤
│          │              │                           │
│   LEFT   │   LIBRARY    │     MAIN CONTENT          │
│SIDEBAR   │   PANEL      │  • Recently Played Cards  │
│(Nav +    │  (Playlists) │  • Trending Now Section   │
│ Browse)  │              │  • Featured Artists       │
│          │              │                           │
├──────────┴──────────────┴───────────────────────────┤
│  PLAYER BAR  (Track Info · Controls · Volume)       │
└─────────────────────────────────────────────────────┘
```

---

## 🛠️ Tech Stack

| Technology | Usage |
|---|---|
| **HTML5** | Semantic structure — `<nav>`, `<main>`, `<section>`, `<footer>` |
| **CSS3** | Layout (Flexbox + Grid), custom properties, transitions, hover states |
| **CSS Variables** | Spotify's green (`#1DB954`), black (`#121212`), and grey palette |
| **Font Awesome** | Vector icons for player controls, navigation, and actions |

> ⚡ Zero dependencies — no npm, no build step, no framework. Open and run.

---

## 📁 Project Structure

```
Spotify-Clone/
│
├── spotifyclone.html    # Complete single-page UI markup
├── style.css            # All styles — layout, theme, components, hover states
└── README.md
```

This is intentionally a **single-file HTML + single CSS** architecture — keeping the project simple, portable, and easy to inspect.

---

## 🚀 Getting Started

No installation, no setup, no build step required.

**Option 1 — Just open it:**

```bash
git clone https://github.com/devikasharma1234/Spotify-Clone.git
cd Spotify-Clone
# Open spotifyclone.html in any browser
```

**Option 2 — VS Code Live Server:**

1. Open the folder in VS Code
2. Install the **Live Server** extension
3. Right-click `spotifyclone.html` → **Open with Live Server**

That's it. No `npm install`. No config files. ✅

---

## 🧠 What I Learned

Building this project strengthened my understanding of:

- **CSS Flexbox** for building multi-column, multi-row layouts that mirror production apps
- **CSS Grid** for the card-based content sections
- **CSS Custom Properties** for maintaining a consistent design system (colours, spacing)
- **Fixed positioning** for the persistent bottom player bar
- **Overflow handling** for scrollable content panels inside a fixed-height viewport
- **Hover & transition effects** for interactive UI without JavaScript
- **Semantic HTML** for accessibility and clean document structure

---

## 🗺️ Roadmap

- [x] Three-panel layout (Sidebar + Library + Main Content)
- [x] Dark mode Spotify theme with CSS variables
- [x] Responsive card grid (Recently Played / Trending)
- [x] Fixed bottom media player bar
- [x] Hover states and transitions
- [ ] JavaScript — functional play/pause toggle
- [ ] JavaScript — seek bar interaction
- [ ] JavaScript — volume slider control
- [ ] Web Audio API — actual audio playback
- [ ] Responsive/mobile layout (media queries)

---

## 👩‍💻 Author

**Devika Sharma**  
B.Tech CSE (AI/ML) · UIET Kurukshetra · Expected 2027  
Head of Tech & Media, Hail Jarvis Club

[![GitHub](https://img.shields.io/badge/GitHub-devikasharma1234-181717?logo=github)](https://github.com/devikasharma1234)

---

## 📄 License

This project is licensed under the **ISC License**.

---
