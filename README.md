# 🐉 DragonUI v2.6 – TwinStar Edition (MoP 5.4.8 | Helios / Persés)

Modern Retail **Dragonflight-style UI** ported, fixed, and optimized specifically for **TwinStar WoW – Mists of Pandaria 5.4.8** (Helios & Persés).

* **Original 3.3.5a Port:** EncarnacionDev (MIT License)
* **MoP 5.4.8 Fixes & Optimization:** Bulbasaur of TwinStar

---

## ✨ Key Features & TwinStar 5.4.8 Fixes
* **Native MoP 5.4.8 Core:** Updated `.toc` files (`50400`), fixed MoP API calls, and eliminated `ADDON_ACTION_FORBIDDEN` and background Lua errors.
* **Fixed Guild Bank & Bagster:** Resolved `Shift+Click` stack splitting issues in the Guild Bank, fixed conflicts between Bagster and default bag skinning, and fixed micromenu bag toggle crashes.
* **Movable Extra Action Button & LFG Eye:** Freely reposition `ExtraActionButton1` in Editor Mode (`/dragonui edit`) and adjust the LFG/RDF minimap eye via `/lfgmove`.
* **Optimized Nameplates & Minimap:** Fast MoP health updates (`UNIT_HEALTH_FREQUENT`), fixed minimap tracking API, and full performance tooltip (FPS, Home/World latency, memory usage).
* **High Raid Performance:** Lightweight memory footprint with zero FPS drops in 25-man raids and PvP. Compatible with **DBM, BigWigs, WeakAuras, Details!, Questie, and SexyMap**.
* **Multi-Language Client Support:** Built-in support for 10 official game client locales.

## ⌨️ In-Game Commands
* `/dragonui` or `/dui` – Open configuration panel
* `/dragonui edit` – Toggle Editor Mode (move & resize all UI elements)
* `/lfgmove` – Adjust LFG / RDF eye anchor position

## 📥 Download & Installation
1. Click on **`DragonUI_TwinStar_MoP_5.4.8.zip`** in the file list above, then click the **Download raw file** button (arrow icon on the right).
2. Extract the `.zip` archive.
3. Delete any old `DragonUI` and `DragonUI_Options` folders in `World of Warcraft\Interface\AddOns\` (your saved profiles in `WTF` will remain safe).
4. Copy both **`DragonUI`** and **`DragonUI_Options`** folders directly into `World of Warcraft\Interface\AddOns\` (without any parent folder).
5. Restart the game client completely (a simple `/reload` is not enough).
