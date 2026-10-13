# 🚢 warn_BuildABoat

<div align="center">

![Version](https://img.shields.io/badge/version-1.0-blue.svg)
![Roblox](https://img.shields.io/badge/platform-Roblox-red.svg)
![Game](https://img.shields.io/badge/game-Build%20A%20Boat%20For%20Treasure-orange.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)

**Auto farm, quests and quality-of-life tools for Build A Boat For Treasure**

[Features](#-features) • [Installation](#-installation) • [Usage](#-usage) • [FAQ](#-faq)

</div>

---

## 📖 Table of Contents

- [Overview](#-overview)
- [Features](#-features)
- [Installation](#-installation)
- [Usage](#-usage)
- [Controls](#-controls)
- [Requirements](#-requirements)
- [FAQ](#-faq)
- [Disclaimer](#-disclaimer)
- [License](#-license)

---

## 🎯 Overview

warn_BuildABoat is a Roblox script for **Build A Boat For Treasure** with a retro 8-bit menu. It automates the gold run, finishes the quests and adds a few movement and water tools, all from a single draggable window.

- ✅ **Auto Farm** that clears every cave stage, claims the gold and the final chest, then restarts by itself
- 🧭 **Complete Quests** with one switch
- 🌊 **Walk on Water** with adjustable height and current speed
- 🎨 **Customizable UI** with 7 color themes and an optional background blur
- 📱 **PC and mobile friendly** layout that scales with the screen

---

## ✨ Features

### 🌾 Farm
- **Auto Farm**: goes through the cave stages in order, claims each reward and collects the final golden chest
- Godmode while the run is active, so the character does not die mid-route
- Restarts the run automatically after respawning
- Turns off cleanly and restores your normal movement

### 🌊 Water
- **Walk on Water**: lets you walk over the river and follows you along it
- **Set Water Height**: changes the thickness of the walkable floor
- **No Water Velocity**: stops the river current
- **Set Water Velocity**: sets the current speed

### 📜 Quest
- **Complete Quests**: runs the quests one by one and turns itself off when finished
- **Quest Step (Enter)**: fires a specific quest manually by number

### 🧍 Player
- **Walk Speed** and **Jump Power** with values kept after every respawn

### 🎨 Settings
- **UI Color**: 7 presets (violet, green, red, blue, yellow, cyan, pink)
- **Background Blur**: turn the blur behind the menu on or off

### 🪟 Window
- Draggable by the top bar
- Minimize / expand button
- Animated intro with a pop-in menu

---

## 💾 Installation

1. **Download** `warn_BuildABoat.lua` from this repository
2. **Copy** the entire script content
3. **Open** your Roblox executor while you are inside Build A Boat For Treasure
4. **Paste** the script and **execute** it
5. The menu appears after the intro animation

---

## 🚀 Usage

1. Execute the script and wait for the intro to finish
2. Turn on **Auto Farm** under the **Farm** section to start the gold run
3. Use **Complete Quests** under **Quest** when you want the quests done
4. Adjust the water and player options as you like
5. Pick your favorite color under **Settings**

Switches turn on and off instantly. Executing the script again replaces the previous menu cleanly.

---

## ⌨️ Controls

| Action | How |
|---|---|
| Show / hide the menu | `Right Shift` |
| Move the window | Drag the top bar |
| Minimize / expand | `-` / `+` button in the top bar |
| Set a value | Type it in the box and press `Enter` or click outside |

---

## 🔧 Requirements

- A Roblox executor that supports `loadstring`-style script execution
- `fireclickdetector` support (only needed for one of the quests)
- The game **Build A Boat For Treasure**

---

## ❓ FAQ

**The menu does not show up.**
Press `Right Shift` once. If it still does not appear, execute the script again.

**Auto Farm does nothing.**
Make sure you are inside the game and your character has spawned. The farm starts from your current character.

**A quest is skipped.**
Quests you already completed are skipped on purpose, and a few quests have no automatic solution.

**Walk on Water leaves the floor invisible.**
Turn the switch off and it restores the water and the floor.

---

## ⚠️ Disclaimer

This project is for educational and testing purposes. Using scripts in online games may go against the Roblox Terms of Service and can put your account at risk. Use it at your own risk.

---

## 📄 License

MIT License - Feel free to use, modify, and distribute.

---

## 🙏 Credits

**Version**: 1.0  
**Author**: warn_GameTester  
**Last Updated**: October 12, 2026

---

<div align="center">

**Enjoying warn_BuildABoat?**  
⭐ Star this repository to show your support!

</div>
