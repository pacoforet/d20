# 🎲 D20 Dice Roller 3D

A studio-quality, tactile 3D D20 dice web application built with **Three.js** and **Cannon-es**. Designed to look, feel, and sound like a real physical 20-sided die rolling on a tabletop velvet tray.

![D20 Roller](https://img.shields.io/badge/WebGL-Three.js_r128-blue)
![Physics](https://img.shields.io/badge/Physics-Cannon--es_0.20-green)
![Audio](https://img.shields.io/badge/Audio-Web_Audio_API-orange)
![PWA](https://img.shields.io/badge/PWA-Ready-purple)

---

## ✨ Features

- 💎 **Realistic PBR Clearcoat Materials**: High-gloss acrylic/resin finish with pearlescent marble swirls, engraved metallic leaf numbering, and multi-angle studio lighting reflections.
- 📐 **Accurate D20 Geometry & Numbering**:
  - Exact standard tabletop D20 number distribution (opposite faces sum to **21**).
  - Mathematically aligned UV mapping so every number is upright and centered within each triangular facet.
- 🧮 **Physics-Driven Tabletop Rolling**:
  - Real-time rigid-body collision dynamics powered by Cannon-es (`ConvexPolyhedron`).
  - Dark felt tray with circular mahogany/brass rim boundaries.
  - Variable-rate delta stepping to ensure silky-smooth physics across 60Hz and 120Hz (ProMotion) displays.
- 🔊 **Procedural Collision Audio**:
  - Real-time synthesized acrylic/wood impact clacks via the **Web Audio API** (zero external MP3 assets to load).
  - Dynamic pitch, volume, and decay scaling based on collision velocity.
- 🌟 **D&D Critical Hits & Pifias**:
  - **Natural 20**: Gold particle burst, radial screen glow, and celebratory fanfare chime.
  - **Natural 1**: Deep crimson shockwave and critical failure cue.
- 🎨 **5 Distinct Dice Themes**:
  - 🩸 *Dragon Ruby* (Crimson resin + Gold foil)
  - 🔮 *Arcane Amethyst* (Purple cosmic swirl + Silver foil)
  - 🌲 *Elven Jade* (Forest emerald + Gold foil)
  - ⚔️ *Obsidian Knight* (Smoky dark resin + Copper foil)
  - ❄️ *Glacial Frost* (Cyan ice + White foil)
- 📜 **Roll History**: Live pill bar displaying the recent roll sequence.
- 📱 **Mobile & PWA Ready**: Safe-area insets, haptic vibration feedback (`navigator.vibrate`), and swipe-to-throw gestures.

---

## 🎮 How to Play / Controls

| Action | Control |
| :--- | :--- |
| **Roll with Momentum** | Click/Tap and **drag/swipe** across the screen to fling the die |
| **Standard Roll** | Tap anywhere on the screen or click **"LANZAR DADO"** |
| **Keyboard Shortcut** | Press <kbd>Space</kbd> |
| **Theme Selection** | Click 🎨 to choose between 5 dice materials |
| **Toggle Sound** | Click 🔊 / 🔇 |

---

## 🚀 Live Deployment

Hosted via GitHub Pages:
[https://pacoforet.github.io/d20/](https://pacoforet.github.io/d20/)