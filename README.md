# 🎯 DART AR — Projector Dartboard Games

A collection of browser-based augmented reality darts games designed to run on a **projector mounted above a physical dartboard**. A control window runs on a device (phone, tablet, or laptop) while a separate projection window is displayed on the wall via the projector — players throw real darts at the projected board and scores are entered through the control interface.

---

## Projects

### 🎯 DART AR (`dart-ar.html`)
The main multi-mode darts game controller with three classic game modes:

- **X01** — Traditional countdown game (301 / 501 / 701). Players subtract scores from their starting total and must finish on a double. Includes checkout hints for remaining scores.
- **Cricket** — Players must "close" numbers 15–20 and Bull with 3 marks each, then score on closed numbers. First to close all numbers with the highest score wins.
- **Killer** — Each player is assigned a random number to defend. Hit opponents' segments to drain their lives (3 / 5 / 7 lives). Last player standing wins.

Supports **1–6 players** with color-coded scorecards, undo functionality, and real-time checkout suggestions.

---

### 👑 DART AR — King of the Hill (`dart-ar-koth.html`)
A territory-control variant where players compete to claim and hold segments of the board across multiple rounds.

- Hit a free segment to **claim** it
- Hit an opponent's segment to **steal** it
- Doubles and triples earn bonus claim points
- Configurable number of rounds: 3, 5, 7, or 10
- Supports **2–6 players**

The player with the most territories and bonus points at the end of all rounds wins.

---

### 🦹 DART AR — Thief (`dart-ar-thief.html`)
A race-to-target game with a theft mechanic.

- Race to reach exactly **301 or 501** points
- Hit any segment to score its value
- Hit a segment **owned by an opponent** to steal their accumulated points (double damage)
- Going over the target is a **bust** — score stays frozen
- First to reach the exact target wins

Features real-time racing progress bars and segment ownership indicators.

---

## How It Works

Each HTML file is fully self-contained (no dependencies, no build step). Open it in any modern browser:

1. **Open the file** in a browser on your control device.
2. Click **"Open Projection Window"** to launch the dartboard display.
3. Move/extend the projection window to your projector output.
4. Use the **calibration controls** (position, scale) to align the projected board with your physical dartboard.
5. Players throw darts, then enter scores through the control panel.

---

## Features

- Fully offline — no server, no internet required
- Projection mapping with calibration controls (position + scale)
- Futuristic neon UI with dark theme (Orbitron + Space Mono fonts)
- HTML5 Canvas dartboard rendering
- Toast notifications for game events
- Undo functionality
- Supports 1–6 players with custom names and color assignments

---

## Requirements

- A **projector** pointed at your dartboard wall
- A modern browser (Chrome recommended for multi-window projection)
- A control device (phone, tablet, or laptop on the same desk)

---

## Author

Hugo Richard — built for personal use at home. Throw straight! 🎯
