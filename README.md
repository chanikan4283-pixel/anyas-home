# 🏯 Anya's Home — 3D Dollhouse

An interactive, fully-furnished **3D walkthrough** of a U-shape Japanese Muji-style Zen home (plot 16×20 m, 2 floors) with a central Japanese rock garden, bamboo waterfall, and engawa veranda.

### ▶️ Open the live app
**https://chanikan4283-pixel.github.io/anyas-home/**

> Runs in any modern browser — no install needed.

### Controls
- **Orbit:** drag to rotate · right-drag to pan · scroll to zoom
- **Roof / 2F / Walls** buttons — peel the dollhouse open
- **Walk** — first-person tour: `WASD` move, mouse look, `Shift` run, `Space/C` up/down, `Esc` exit
- **Night** — evening lighting · **Smart Home** — show CCTV / smart-lock / sensor markers

### Features
- Central **Zen garden** (rock + sand + bamboo waterfall + koi pond) as the heart of the house
- **Engawa** veranda ring + glass sliding walls facing the garden
- Ground floor: Genkan · Living/Dining · Kitchen · Cat Room 🐈‍⬛ · Golf Simulator ⛳ · Game Room 🎮 · Bath · Laundry · 2-car carport
- Upstairs: Master + Bedroom 2 · 2 bathrooms · Walk-in · Study · Sky bridge & light-well
- Smart-home + safety markers, day/night modes

### Edit it yourself
Everything is in **`index.html`**. The room layout lives in the `F1` array and `f2()` function — edit the numbers (`name, x, z, width, depth, floorColor`) and reload. Colour palette is in `const COL`.

*Made with [Three.js](https://threejs.org/).*
