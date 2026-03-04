# 🎯 Aim Trainer

A browser-based aim trainer game built with vanilla JavaScript, HTML, and CSS. Test and improve your mouse accuracy with a combo system, sound effects, and a persistent leaderboard.

**[▶ Play Now](https://ensaaryaman.github.io)**

---

## Features

- **Combo System** — Hit consecutive targets to build up a multiplier and boost your score
- **Sound Effects** — Real-time audio feedback powered by the Web Audio API (no external files needed)
- **Leaderboard** — Top scores are saved locally via `localStorage` and persist between sessions
- **Responsive Design** — Playable on both desktop and mobile browsers
- **No Dependencies** — Pure vanilla JavaScript, zero frameworks or libraries

## Tech Stack

| Layer | Technology |
|-------|------------|
| Logic | Vanilla JavaScript (ES6+) |
| Styling | CSS3 |
| Audio | Web Audio API |
| Storage | localStorage |
| Hosting | GitHub Pages |

## Getting Started

### Play Online

Visit **[https://ensaaryaman.github.io](https://ensaaryaman.github.io)** — no installation required.

### Run Locally

```bash
git clone https://github.com/ensaaryaman/ensaryaman.github.io.git
cd ensaryaman.github.io
# Open index.html in your browser
open index.html
```

No build step or package manager needed.

## How to Play

1. Click **Start** to begin the game
2. Click on the targets as fast as you can before they disappear
3. Build consecutive hits to increase your combo multiplier
4. Missing a target resets your combo
5. Your final score is saved to the leaderboard automatically

## Project Structure

```
ensaryaman.github.io/
├── index.html   # Game layout and UI
├── style.css    # Styling and animations
└── script.js    # Game logic, audio, and leaderboard
```

## License

This project is open source. Feel free to fork and build on it.
