# 🚀 Space Raiders — Web

<p align="center">
  <strong>A browser-based 2D space-shooter built with C++ and WebAssembly.</strong>
</p>

<p align="center">
  Fight enemy waves, defeat elite ships and bosses, collect power-ups, and progress through increasingly challenging levels — directly in your browser.
</p>

---

## 🎮 Play Online

### 🌐 Play Space Raiders

**[▶ Play Space Raiders](https://huzaifam-05.github.io/Space-Raiders-Web/)**

No installation is required.Open the game in a modern web browser and start playing. 
But it is recommened to play locally by downloading .exe file from **[HERE](https://github.com/Huzaifam-05/Space-Raiders---Desktop-version./)**

---

## ✨ Features

### ⚔️ Combat

- Fast-paced 2D space combat
- Multiple enemy types
- Elite enemies
- Boss encounters
- Enemy projectile systems
- Power-ups
- Progressive enemy difficulty

### 🌌 Progression

- Multiple levels
- Progressive enemy scaling
- Procedurally generated encounters
- Increasing difficulty
- Boss stages
- Level progression system

### 💾 Save System

- Save and Resume functionality
- Persistent game state
- Checkpoint support
- Resume protection against applying level scaling twice

### 🖥️ Web Experience

- Browser-based gameplay
- No installation required
- 16:9 game presentation
- Fullscreen support
- Custom game interface
- WebAssembly-powered gameplay

---

## 🎮 Controls

| Action | Control |
|---|---|
| Move | Arrow Keys |
| Shoot | Space |
| Other actions | Follow the in-game prompts |

> Controls may vary depending on the current game state.

---

## 🌐 Technology

The Web version is built using:

- **C++**
- **Raylib**
- **GLFW**
- **Emscripten**
- **WebAssembly**
- **HTML**
- **JavaScript**
- **WebGL**

The original C++ game is compiled to WebAssembly for browser deployment.

---

## 📁 Web Build

The repository contains the compiled browser version of Space Raiders.

```text
Space-Raiders-Web/
│
├── shell.html
├── index.html
├── index.js
├── index.wasm
├── index.data
├── features.html
│
└── assets/
    └── Game assets
