# Simple HTML Side-Scroller (Canvas + JavaScript)

A lightweight **HTML5 canvas side-scrolling game** written in plain JavaScript.  
No frameworks, no build tools — just open the file in a browser and play.

This project demonstrates core 2D game concepts such as:
- gravity & jumping
- platform collision
- camera scrolling
- basic enemies & projectiles
- win / lose states

---

## Features

- 🎮 **Side-scrolling gameplay**
- 🧍 Player movement with gravity and jumping
- 🧱 Platforms and ground collision
- 🔫 Projectile shooting
- 👾 Enemies with hit detection
- 🎥 Camera that follows the player across a wider level
- 🏁 Win condition when all enemies are defeated
- ☠️ Game over on enemy collision
- 🔁 Click to restart after win or loss

All logic lives in a **single HTML file**.

---

## Controls

| Key | Action |
|---|---|
| ← / → | Move left / right |
| ↑ | Jump |
| Space | Shoot |
| Mouse Click | Restart after game over / win |

---

## How to Run

No installation required.

1. Clone or download the repository
2. Open `sidescroller.html` in any modern web browser
3. Play 🎉

Works offline and does not require a web server.

---

## Technical Overview

- **Rendering**: HTML5 `<canvas>`
- **Game loop**: `requestAnimationFrame`
- **Physics**:
  - constant gravity
  - vertical velocity for jumping
- **Collision detection**:
  - axis-aligned bounding boxes (AABB)
- **Camera system**:
  - horizontal scrolling
  - clamped to level bounds
- **Architecture**:
  - simple object literals for player, enemies, platforms, projectiles
  - no external dependencies

---

## Project Structure

sidescroller.html

yaml
Copy code

Everything (HTML, CSS, and JavaScript) is intentionally kept in one file for clarity and portability.

---

## Known Limitations / Intentional Simplicity

- No asset loading (all visuals are rectangles)
- No sound effects or music
- No mobile / touch controls
- No enemy AI (static enemies)
- No level loading system (level is hardcoded)

This is a **learning / demo project**, not a full game engine.

---

## Why this exists

This project is meant to be:
- a **minimal example** of a side-scroller
- easy to read and modify
- suitable for beginners learning canvas game loops
- a base you can extend with sprites, physics, or sound

It’s intentionally framework-free so the core concepts are visible.

---

## Ideas for Extensions

If someone forks this, easy next steps include:
- sprite graphics instead of rectangles
- enemy movement patterns
- scrolling background parallax
- multiple levels
- health system instead of instant game over
- mobile controls

---

## License

Use any license you prefer (MIT is a common choice for small demo projects).
