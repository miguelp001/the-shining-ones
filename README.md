# The Shining Ones

> A dual-reality RPG blending a bleak, monochrome noir investigation in the waking world with hyper-saturated, tactical turn-based battles across the collective unconscious.

---

## 📖 Overview

* **Genre:** Investigation / Noir Mystery + JRPG (Conditional Time Battle) + Ship Management / Psychological Survival.
* **Engine:** Unity 6 (`6000.6.4f1`) with Universal Render Pipeline (URP).
* **Game Design Document:** See [`Game Design Document_ The Shining Ones.md`](./Game%20Design%20Document_%20The%20Shining%20Ones.md) for full narrative, systems, and archetypes specification.

---

## 🛠️ Project Setup & Unity MCP Connection

This repository includes support for **Unity MCP (Model Context Protocol)** via Unity's AI Assistant relay (`com.unity.ai.assistant`).

### 1. Opening the Project in Unity
1. Open **Unity Hub**.
2. Click **Add** -> **Add project from disk**.
3. Select this folder: `D:\projects\The Shining Ones`.
4. Ensure the Editor version is set to **Unity 6 (`6000.6.4f1`)**.
5. Open the project. Unity will automatically resolve packages (including `com.unity.ai.assistant` and URP).

### 2. Connecting Unity MCP
The AI Assistant relay (`relay_win.exe`) bridges Antigravity with your running Unity Editor:
1. When the project is open in Unity Editor, the Unity AI Assistant service starts the local relay client.
2. The AI assistant can then query active scenes, inspect hierarchies, manage game objects, run tests, and capture scene views directly inside Unity.

---

## 📁 Repository Structure

```
The Shining Ones/
├── Assets/                 # Game scripts, scenes, art, audio, and prefabs
│   ├── Art/
│   ├── Audio/
│   ├── Prefabs/
│   ├── Scenes/
│   ├── Scripts/
│   └── Settings/
├── Packages/               # Package manifest configuring URP and Unity AI Assistant
├── ProjectSettings/        # Unity project version and editor settings
├── Game Design Document_ The Shining Ones.md
└── README.md
```
