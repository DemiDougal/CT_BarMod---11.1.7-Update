# CT_BarMod – 11.1.7 Update

This is an **unofficial update** of the CT_BarMod addon, adapted for **World of Warcraft 11.1.7 (The War Within)**.  
The original version is no longer maintained, and this release ensures compatibility and continued functionality for users who rely on CT_BarMod.

---

## ✨ What's Changed

- Removed deprecated template `ActionBarButtonSpellActivationAlert` that caused startup errors
- Fixed `CreateFrame()` and `nil overlay` errors
- Added two installation options: **with working spell glow effects** or **without glow**
- Integrated support for [LibCustomGlow-1.0](https://www.curseforge.com/wow/addons/libcustomglow) for modern button highlight visuals

---

## 📦 Installation

Choose **one** of the two installation options below:

---

### ✅ Option 1: No Glow (Simplified version)

This version removes glow entirely for maximum stability.

1. Replace the file:

CT_BarMod\CT_BarMod_Use.lua
with the one from:
CT_BarMod (NO glow)\CT_BarMod_Use.lua

2. You're done! The addon will work without errors or glow effects.

---

### ✅ Option 2: With Spell Glow (via LibCustomGlow)

This version re-enables glow functionality using a modern library.

1. Replace **both files**:
CT_BarMod\CT_BarMod_Use.lua
CT_BarMod\CT_BarMod.toc

with the versions found in:
CT_BarMod (with glow)\CT_BarMod\

2. Install the required library:
Copy the entire `LibCustomGlow-1.0` folder from:
CT_BarMod (with glow)\LibCustomGlow-1.0\
into your WoW addons directory:
Interface\AddOns\

3. Restart the game or run `/reload` in-game.

---

## ⚠️ Notes

- The glow version requires the `LibCustomGlow-1.0` library to be installed and enabled
- Be sure to **fully replace the original files** depending on which option you choose
- Tested on WoW version **11.1.7**

---

## 🙏 Credits

- Original Addon: CTMod team  
- Spell glow system: [LibCustomGlow by Stanzilla](https://www.wowace.com/projects/libcustomglow-1-0)

---

**CT_BarMod – 11.1.7 Update**  
Unofficially maintained for modern WoW compatibility.
