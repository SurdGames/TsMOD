# TsMOD 1.0.0

**TsMOD** is a Borderlands 2 single-player / offline utility mod menu created by **Thiago Millares**.

> Version: **1.0.0**  
> Author: **Thiago Millares**  
> License: **ARR - All Rights Reserved**  
> Game: **Borderlands 2**  
> Hotkey: **F7**

---

## About

TsMOD is a compact control menu for Borderlands 2 focused on single-player quality-of-life, character utilities and gameplay tools.

The project keeps its interface simple and avoids unnecessary pages or oversized text.

---

## Main Features

### Resources
- Cash: up to 99,999,999
- Eridium: up to 500
- Seraph Crystals: up to 999
- Torgue Tokens: up to 999
- Max all supported character currencies

### Character
- Maximum installed level
- Skill Points: 999
- Backpack capacity: 999
- Max Character shortcut

### Combat
- God Mode
- One Shot
- Infinite Ammo
- No Reload behavior while Infinite Ammo is active
- Ultra Ammo target: 9,999,999
- Weapon refill
- Eliminate nearby enemies

### Tools
- Sprint speed controls
- Jump boost controls
- Instant Action Skill cooldown
- Action Skill ready shortcut
- Travel utilities when supported by the current map
- Quick Boost
- Ultra Max Pack
- Reset session effects

### Status
- Compact live status screen
- Character level
- Backpack usage
- Resource values
- Active TsMOD toggles
- Movement multipliers
- Ammo details

---

## Requirements

Before installing TsMOD, Borderlands 2 must already be prepared to load Willow2 PythonSDK / Willow2 Mod Manager mods.

When the mod system is installed correctly, the Borderlands 2 main menu should contain a **MODS** option and the game directory should contain an **sdk_mods** folder.

---

## Installation

1. Close Borderlands 2 completely.
2. Find your Borderlands 2 installation folder.
3. Open the `sdk_mods` folder.
4. Remove older TsMOD `.sdkmod` copies if you have any.
5. Copy `TsMOD.sdkmod` directly into `sdk_mods`.
6. Do **not** extract `TsMOD.sdkmod`.
7. Start Borderlands 2.
8. Open **MODS** from the main menu.
9. Make sure **TsMOD** is enabled.
10. Load your character.
11. Press **F7** to open TsMOD.

Correct example:

```text
Borderlands 2/
└── sdk_mods/
    └── TsMOD.sdkmod
```

Incorrect example:

```text
Borderlands 2/
└── sdk_mods/
    └── TsMOD/
        └── TsMOD.sdkmod
```

---

## Recommended Backup

Before using character-changing features, make a backup of your Borderlands 2 save folder.

Typical Windows location:

```text
%USERPROFILE%\Documents\My Games\Borderlands 2\WillowGame\SaveData
```

Copy the whole `SaveData` folder somewhere safe.

---

## Controls

```text
F7 = Open TsMOD
Enter = Select
Escape = Back / Close
```

The exact menu navigation keys are displayed by Borderlands 2.

---

## Important Notes

- TsMOD is intended for **single-player / offline use**.
- Some values may be limited by Borderlands 2 itself.
- Maximum level depends on the game content installed on the player's copy.
- Travel options only work when the required travel station is loaded by the current map.
- `Reset session effects` restores TsMOD session toggles such as movement and combat effects, but it does not undo permanent character changes such as level, money, skill points or backpack capacity.
- Always keep a backup of your saves.

---

## Troubleshooting

### TsMOD does not appear in MODS

Check that:

```text
TsMOD.sdkmod
```

is directly inside:

```text
Borderlands 2\sdk_mods
```

Do not place it inside another TsMOD folder.

Also make sure the Willow2 mod system is installed correctly.

### F7 does nothing

Open:

```text
MODS → TsMOD
```

and confirm the mod is enabled.

Also check whether another mod or program is using F7.

### I see more than one TsMOD

Remove older TsMOD copies from `sdk_mods` and keep only the current `TsMOD.sdkmod`.

### A permanent value changed and I want the old value back

Use your save backup. Session reset options cannot automatically restore previous permanent character values.

---

## Project Information

**TsMOD 1.0.0**  
Created by **Thiago Millares**

Copyright © 2026 Thiago Millares.  
**All Rights Reserved.**

See the `LICENSE` file for the project license.
