# My_First_Pygame_OpenWorld
An advanced 2-in-1 open-world Pygame action game featuring a custom Haki system, endless wave survival, boss fights, an in-game shop, achievements, and dynamic screen-shake camera effects.

# 🎮 Custom Open-World Pygame Action Engine (v1.0 Release)

Welcome to my first massive open-world game built entirely from scratch using **Pygame**! This project features a fully functional custom physics engine, dynamic camera rendering, multiple game modes, an in-game economy, and shop mechanics.

## 🚀 DOWNLOAD & PLAY (Standalone Windows Executable)
👉 [**CLICK HERE TO DOWNLOAD THE GAME (.ZIP)**](https://drive.google.com/file/d/1FfaogBL3LCl8UtZH20ygzZSynoI-G62p/view?usp=drive_link)
*(Just download the archive, extract it, open the `dist` folder, and run `game.exe`. No Python installation required!)*
*⚠️ Make sure to click 'Extract All' (or 'Extract here') first! Once everything is fully extracted, you can run and play the game❗*

---

## 🕹️ Core Gameplay & Mechanics

This project features a unique **Two-in-One Game System** with distinct game modes accessible from the main terminal interface:

### 🔹 Game Mode 1: The Boss Encounter
* **Objective:** Tactical arena combat against an elite Boss and his active Minion.
* **Mechanics:** Precision hitboxes, boss AI behavior, and dedicated combat tracking.

### 🔹 Game Mode 2: Endless Wave Survival
* **Objective:** Survive against aggressive spawning mobs that attack in tactical waves.
* **Mechanics:** Scaled difficulty, dynamic wave management, and intense crowd-control combat.

---

## ⚡ Unique Legendary Systems

### 🔴 The Haki System (Ultimate Ability)
An epic, anime-inspired ultimate ability that unleashes a devastating energy blast:
* Generates custom-rendered **Red and Black Lightning Bolts** striking outwards directly from the player's core screen location.
* Features a smooth, expanding visual shockwave circle that clears the field and eliminates waves of enemies within its radius.

### 🫨 Dynamic Camera Engine (Screen Shake)
* Implements a realistic tactical screen-shake timer triggered on heavy sword swings, ultimate activations, and enemy deaths.
* Camera offsets (`offset_x`/`offset_y`) dynamically shift using randomized pixel vectors to create a punchy feel to combat without disrupting global world-grid positioning.

### 🛒 In-Game Shop & Economy
* Earn points by crushing enemies and survival streaks.
* Spend your points in the **Integrated Shop** to buy custom weapons, permanent stats upgrades, and combat buffs.

### 🏆 Achievements System
* Fully integrated progress tracker that rewards player milestones (Kill Streaks, High Scores, and Hidden Conditions).
* Saves your progress natively using a robust local JSON file structure.

---

## 🐛 Optimization & Bug Fixes (The Junior Dev Upgrades)
* **Ghost Elimination:** Fixed a critical scope/variable bug where dead mobs would turn into invisible "ghosts" tracking the player's camera.
* **Multi-Kill Threading:** Refactored bullet collision arrays (`bullets.remove` exception handling) to completely prevent Pygame crashes when multiple enemies are pierced by a single frame shot.
* **Screen Coordinate Alignment:** Fully decoupled rendering layers. Particle explosions, impact effects, and the UI overlay are drawn strictly using screen matrix offsets, preventing them from spawning out-of-bounds.

---

## 🛠️ Technology Stack
* **Language:** Python 3.14
* **Graphics Framework:** Pygame 2.x
* **Data Storage:** JSON (Save states and settings management)
* **Compiler:** PyInstaller (Compiled into a lightweight standalone binary)

---
*Developed with a sharp ENTP mindset
