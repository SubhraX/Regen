# Regen Mod

A lightweight, configurable health regeneration mod for Unity-based multiplayer games using **BepInEx** + **Photon**.

---

## 🚀 Features

- ⏱️ Configurable Regen Delay
- ❤️ Fixed per-tick healing (upgrade-independent)
- 💀 Stops regen on death (HP 0)
- 🧠 Smart, client-side safe

---

## ⚙️ Configuration

Located in:  
`BepInEx/config/Xmods.healthregen.cfg`

| Setting                 | Type   | Description                         |
|------------------------|--------|-------------------------------------|
| BaseRegenIntervalSeconds | int  | Delay before regen starts (default: 20s) |
| RegenAmountPerTick     | int    | Health per tick (default: 1)        |
| DebugLoggingEnabled    | bool   | Enable verbose logs (default: false) |

---

## 📦 Installation

1. Install BepInEx (v5)
2. Drop the `.dll` into:  
   `BepInEx/plugins/`
3. Launch the game and configure as needed.

---

## 🧊 Credits

Created by X_MODS Team  
Powered by BepInEx + Harmony
