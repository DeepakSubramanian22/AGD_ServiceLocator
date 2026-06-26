# 🎈 Monkey Shooter

> **Build your defense. Place your monkeys. Pop every balloon before they escape!**

Monkey Shooter is a **2D top-down strategy game** developed in **Unity** using **C#**. Players strategically drag and place monkeys on the map to stop waves of balloons following a predefined path. Each monkey has unique abilities, including different attack ranges, projectile types, projectile speeds, attack cooldowns, and costs. As the waves progress, stronger balloon types appear, requiring smarter strategies and better resource management.

---

# 🎮 Gameplay

Your objective is to stop every balloon before it reaches the end of the path.

* 🎯 Drag and drop monkeys onto valid positions on the map.
* 🐵 Every monkey automatically attacks balloons within its attack range.
* 💰 Purchase monkeys using the available in-game currency.
* ❤️ Every balloon that escapes reduces the player's health.
* 🌊 Survive increasingly difficult waves of balloons.
* ⚫ Starting from **Wave 3**, Metal Balloons appear and require special monkeys to destroy.

---

# 🐵 Monkey Types

## 🟦 Sharp Monkey

**Cost:** 50

* Medium attack range
* Standard dart projectile
* Fast firing speed
* Effective against normal balloons

---

## 🟥 Ninja Monkey

**Cost:** 150

* Larger attack range
* High-speed shuriken projectiles
* Faster attack speed
* Excellent against groups of balloons

---

## ⚫ Sniper Monkey

**Cost:** 300

* Longest attack range
* Powerful sniper bullets
* High projectile speed
* Slow but powerful attack rate
* **Only monkey capable of detecting and destroying Metal Balloons**

---

# ⚙️ Unique Monkey Attributes

Each monkey is designed with its own gameplay characteristics, including:

* 💰 Purchase Cost
* 🎯 Attack Range
* 🔫 Unique Projectile Type
* 🚀 Projectile Speed
* ⏱️ Attack Cooldown (Fire Rate)
* 💥 Damage Output
* 🎈 Balloon Detection Capability

Choosing the right monkey for the right situation is essential to surviving later waves.

---

# 🎈 Balloon Types

## 🔴 Normal Balloon

* Standard enemy
* Can be destroyed by every monkey

---

## ⚫ Metal Balloon

* Introduced from **Wave 3**
* Immune to Sharp and Ninja Monkey attacks
* Can only be destroyed by the **Sniper Monkey**

---

# 🌊 Wave System

Each wave becomes progressively more challenging.

* More balloons spawn
* Stronger balloon combinations appear
* Metal Balloons unlock from Wave 3
* Players must upgrade their strategy and manage resources carefully

---

# ❤️ Health System

Every escaped balloon damages the player.

```text
Balloon Escapes
       ↓
Player Health -1
       ↓
Health Reaches 0
       ↓
Game Over
```

---

# 💰 Economy System

Earn and spend money wisely to build stronger defenses.

| Monkey        | Cost |
| ------------- | ---: |
| Sharp Monkey  |   50 |
| Ninja Monkey  |  150 |
| Sniper Monkey |  300 |

Strategic spending is the key to surviving later waves.

---

# 🕹️ Controls

| Action        | Control                   |
| ------------- | ------------------------- |
| Select Monkey | Left Mouse Button         |
| Drag Monkey   | Hold Left Mouse Button    |
| Place Monkey  | Release Left Mouse Button |
| Start Wave    | Play Button               |

---

# 🛠️ Technical Features

* 🎯 Service Locator Architecture
* ⚡ Object Pooling for Projectiles
* 📦 Scriptable Objects for Monkey & Projectile Configuration
* 🗺️ Tilemap-Based Level Design
* 🖱️ Drag & Drop Monkey Placement
* 🎈 Balloon Path Following System
* 🔍 Automatic Enemy Detection
* 🔫 Projectile Shooting System
* 🌊 Wave Management System
* ❤️ Player Health System
* 💰 Money Management
* 🎵 Audio Management
* 🖥️ Dynamic UI Updates
* ⏱️ Coroutine-Based Timers
* 🧩 Clean Object-Oriented Programming (OOP)

---

# 📂 Project Structure

```text
Assets
│
├── Scenes
│   ├── MainMenu
│   └── Gameplay
│
├── Scripts
│   ├── GameService
│   ├── PlayerService
│   ├── MapService
│   ├── WaveService
│   ├── UIService
│   ├── MonkeyController
│   ├── BalloonController
│   ├── ProjectileController
│   └── SoundService
│
├── ScriptableObjects
├── Prefabs
├── Tilemaps
├── Sprites
└── Audio
```

---

# 📚 Unity Concepts Practiced

* Object-Oriented Programming (OOP)
* Service Locator Pattern
* Scriptable Objects
* Object Pooling
* Drag & Drop Mechanics
* Tilemap System
* Enemy AI Path Following
* Automatic Target Detection
* Projectile System
* Wave Management
* Health & Currency Systems
* UI Programming
* Coroutines

---

# 🎯 Objective

* Protect your health by stopping every balloon.
* Build an effective defense using different monkey types.
* Manage your money wisely.
* Adapt your strategy as tougher balloon types appear.
* Deploy Sniper Monkeys to eliminate Metal Balloons from Wave 3 onward.
* Survive every wave and master the battlefield.

---

---

# 🚀 Future Improvements

* Monkey Upgrade System
* Additional Monkey Types
* More Balloon Variants
* Multiple Maps
* Boss Balloon Waves
* Endless Survival Mode
* Save & Load Progress
* Difficulty Selection
* Upgrade Shop
* Leaderboard

---

# 👨‍💻 Developer

**Deepak Subramanian**

Unity Game Developer

---

⭐ **If you found this project interesting, feel free to give it a Star!**
