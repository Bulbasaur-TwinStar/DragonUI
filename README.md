<img width="4096" height="2160" alt="1" src="https://github.com/user-attachments/assets/d63dee95-0c58-46d4-a2b2-c797cf6261aa" />
<img width="4096" height="2160" alt="2" src="https://github.com/user-attachments/assets/3709dcd0-7b42-4c62-abed-a495f15b4e08" />
<img width="4096" height="2160" alt="3" src="https://github.com/user-attachments/assets/9f6208b9-833e-4f65-b33c-1b326ae2c52d" />

# 🐉 DragonUI v2.6 – TwinStar Edition (MoP 5.4.8 | Helios / Persés)

**DragonUI** is a modern, clean, and lightweight Retail **Dragonflight-style** user interface overhaul backported and specifically tuned for **TwinStar WoW — Mists of Pandaria 5.4.8 (Helios & Persés)**.

* **Original 3.3.5a Port:** EncarnacionDev (MIT License)
* **MoP 5.4.8 Port, Fixes & Optimization:** **Bulbasaur** of TwinStar

---

## ✨ Key Features & MoP 5.4.8 Fixes

* **Native MoP 5.4.8 Core & Zero Lua Errors:**
  * Fully updated `.toc` (`50400`) metadata and rewritten MoP API calls.
  * Eliminates combat taint and `ADDON_ACTION_FORBIDDEN` popups during encounters.
* **Action Bars, XP & Reputation Bars:**
  * Authentic Dragonflight action bar art, gryphons/wyverns, stance/pet bars, and micro menu.
  * **Fixed Reputation Bar:** Properly displays and updates whenever a faction is tracked (*Show as Experience Bar*).
* **Full Layout Freedom (`/dragonui edit`):**
  * Built-in visual editor to drag, align, and scale action bars, unit frames, castbars, **Raid Frames (`CompactRaidFrames`)**, **Extra Action Button**, and the **LFG/RDF Eye** (`/lfgmove`).
* **Minimap & Tracking Polish:**
  * Clean Dragonflight minimap styling with working tracking icons, calendar, and mail indicators.
  * **Permanent Minimap Buttons:** Addon icons around the minimap stay permanently visible when the button collector is disabled.
* **Guild Bank & Bagster Integration:**
  * Fixed **Guild Bank item stack splitting** (`Shift+Click`) without UI errors or lockups.
  * Smooth all-in-one bag (`Bagster`) and micromenu integration.
* **Dark Mode & Multi-Language Support:**
  * One-click sleek **Dark Mode** tint for frames and borders.
  * Supports 10 official client languages.
* **Raid & PvP Performance:**
  * High FPS in 25-man raids and Battlegrounds with fast nameplate health & castbar updates.
  * 100% compatible with **DBM, BigWigs, WeakAuras, Details!, Recount, Questie, SexyMap, and TwinGear**.

---

## ⌨️ In-Game Slash Commands

| Command | Description |
| :--- | :--- |
| `/dragonui` or `/dui` | Open the main DragonUI configuration window |
| `/dragonui edit` | Toggle **Editor Mode** to move and resize UI elements |
| `/lfgmove` | Unlock and reposition the LFG / RDF minimap eye |

---

## 📥 Download & Installation

> [!WARNING]
> **DO NOT download via the green `<> Code -> Download ZIP` button!** GitHub renames the folder to `DragonUI-main`, which prevents WoW from loading the addon properly.

1. 1. Go to the Latest Release page (`https://github.com/Bulbasaur-TwinStar/DragonUI/releases/tag/v2.6`) and download **`DragonUI-TwinStar.zip`** under **Assets**.
2. Extract the `.zip` archive.
3. Delete any older `DragonUI` and `DragonUI_Options` folders inside `World of Warcraft\Interface\AddOns\` *(your saved profiles in the `WTF` folder will remain safe)*.
4. Copy both **`DragonUI`** and **`DragonUI_Options`** folders directly into `World of Warcraft\Interface\AddOns\`.
5. **Completely restart** your WoW game client *(a simple `/reload` is not enough for newly added folders)*.
