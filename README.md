# html-sandbox
A lightweight, zero-dependency 2D physics engine and sandbox built entirely in native HTML5 Canvas and JavaScript. Draw, experiment, and simulate.
# 🪐 Ultimate 2D Physics Sandbox

A feature-rich, high-performance **2D Physics Simulation Engine** built entirely from scratch using native HTML5 Canvas and vanilla JavaScript. No external engines, no third-party dependencies—just pure vector mathematics and physics equations running directly in your browser.

With dynamic particle generation, structural mechanics, custom polygon creation, gravity wells, and automated defenses, this sandbox offers a deeply interactive and responsive micro-environment for physics testing.

---

## 🚀 Live Demo
*Host your repository on GitHub Pages and add your link here!*
👉 **[Play in Browser (Live Link)](https://yourusername.github.io/ultimate-2d-physics-sandbox)**

---

## ✨ Key Features

### 🧱 Core Sandbox & Shapes
- **Dynamic Physics Shapes:** Spawn customized Circles, Boxes, and Rigid Static Barriers anywhere on the canvas.
- **Custom Polygon Drawing:** Switch to Freehand Draw Mode to sketch complex custom boundaries and collision hulls on the fly.
- **Material Presets:** Instantly adjust elasticity (bounciness) and friction constants to change how objects slip, slide, and bounce.

### 🌌 Environmental Mechanics
- **Magnetic Flux & Gravity Wells:** Place pulling or pushing magnets that bend object trajectories dynamically using inverse-square distance equations.
- **Particle Systems:** Generate beautiful, cascading water particles, explosive sparks, and glowing element trails.
- **Automated Anti-Gravity Turrets:** Deploy defense turrets that intelligently track closest shapes and open fire with high-velocity kinetic projectiles.

### 🎛️ Comprehensive Control Panel
- **Global Physics Modifiers:** Fine-tune gravity vectors, structural damping, time-step speeds (slow motion), and collision constraints.
- **Destruction & Cleaning Tools:** Isolate specific objects for removal, trigger localized physical shockwaves, or clear the canvas to start fresh.
- **Visual Diagnostics HUD:** Monitor real-time rendering statistics including a raw FPS counter, active physical entity tallies, and engine updates.

---

## ⌨️ Controls & Keybindings

| Key | Action |
|:---:|---|
| `Space` | Toggle Debug Mode (Collision normals, bounding boxes, vectors) |
| `D` | Toggle Custom Polygon Drawing Mode |
| `F` | Spawn a Freehand Static Barrier |
| `T` | Quick-spawn an Automated Kinetic Defense Turret |
| `S` | Save current environment setup to LocalStorage |
| `Delete` / `Backspace` | Erase currently highlighted/selected element |

---

## 🛠️ Technology Stack & Architecture

- **Language:** HTML5 / CSS3 / Vanilla JavaScript (ES6+)
- **Graphics Pipeline:** 2D Canvas API utilizing double-buffered requestAnimationFrame for liquid-smooth 60 FPS performance.
- **Physics Core:** Implements explicit structural integration, custom convex polygon boundary detection, impulse-based collision responses, and positional corrective algorithms to prevent element clipping.

---

## 📦 Local Installation & Setup

Because this project relies exclusively on standard Web APIs, it runs locally without needing a build step, `npm install`, or local server instances.

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/yourusername/ultimate-2d-physics-sandbox.git](https://github.com/yourusername/ultimate-2d-physics-sandbox.git)
