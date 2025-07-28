# A Blue Moon – Fallout: New Vegas Modlist

---

## Table of Contents
- [Introduction](#Introduction)
- [Features](#features)  
- [Recommended Specs](#recommended-specs)  
- [Installation](#installation)  
- [Optional Tools and Enhancements](#optional-tools-and-enhancements)  
- [Troubleshooting](#troubleshooting)  
- [Known Issues & Notes](#known-issues--notes)  
- [Feedback & Support](#feedback--support)  
- [Final Thoughts](#final-thoughts)  
- [Additional Notes](#additional-notes)  
- [Changelog](#changelog)  
- [Special Thanks](#special-thanks)  
- [Thank You](#thank-you)  

---

# Introduction

*A Blue Moon* is a complete visual and gameplay overhaul for **Fallout: New Vegas**, designed to modernize the game while preserving its heart. Built using **Wabbajack**, this modlist incorporates difficulty and survival enhancements from mods like **LoneStar** and **Vicious Wastes**, alongside comprehensive graphical updates to bring the Mojave closer to modern visual standards. My goal is to make the Mojave feel truly lived-in and deliver an experience that highlights just how harsh and unforgiving the wasteland can be showing how difficult survival really is.

This is a **hardcore survival-focused list**, blending elements from my good friend Rage’s list *Wasteland Prospects* into my vision of an ideal *New Vegas*. Some gameplay mechanics and difficulty tweaks may feel familiar if you’ve played his list, while others are uniquely tailored here. We do use similar mods to adjust difficulty but with our own distinct approach.

Whether you're returning to the wasteland or exploring it for the first time—this list is for you.

---

## Features

- Overhauled visuals with updated textures, lighting, weather, and effects  
- Difficulty and gameplay tuning through **LoneStar** and **Vicious Wastes**  
- Refined combat mechanics, smarter AI, and deeper survival systems  
- Modernized UI via **Vanilla UI Plus**, **Vanilla UI Extension**, and **M.U.X.**  
- Fully modular and customizable via **MO2**, with **Wabbajack** installation  
- Hardcore survival gameplay with scarcity-based balancing  
- Visual design reflects the author’s personal vision of an ideal *New Vegas*  

---

## Recommended Specs

*A Blue Moon* is built with modern systems in mind. Performance may vary depending on your configuration, but here are the tested setups so far:

### Development System
- **CPU:** Ryzen 9 9800X3D  
- **GPU:** Radeon 7900 GRE  
- **RAM:** 64GB DDR5  
- **Storage:** NVMe SSD  
- **Resolution:** 1440p  
- **Performance:** 100+ FPS (without New Vegas Reloaded)  

> **Note:** With New Vegas Reloaded on my system, I get around 50-60 FPS using the included preset.  
> If you wish, turning off exterior shadows can significantly improve performance.

### Test System
- **CPU:** Intel i7-12700K  
- **GPU:** Radeon RX 6700 XT  
- **RAM:** 32GB  
- **Storage:** NVMe SSD  
- **Resolution:** 1440p  
- **Performance:** ~80 FPS (without New Vegas Reloaded)

### Storage Recommendation
- An **NVMe SSD** is highly recommended for smooth performance and reduced loading times.  
- If NVMe is not available, a **SATA SSD** will suffice.  
- Traditional HDDs are **not recommended**, as they may cause significant stuttering or extreme loading times.

### Compatibility Notice
At this time, the list has **not been tested on older or low-end hardware**.  
As such, I cannot confidently provide minimum system requirements yet.

---

## Installation

This list is intended for installation through **Wabbajack**. Some required files must be downloaded manually, as Pull Requests have not yet been completed.

### Manual Downloads (Optional Backups)

Place these files in your Wabbajack downloads folder:

- [Vanilla UI Extension 1.0](#)  
- [Vanilla UI Plus – NV (Mirror 1)](#)  
- [Vanilla UI Plus – NV (Mirror 2)](#)  
- [SecuritronHD by macintroll](#)  
- [Ghouls Retexture by macintroll](#)  

**Note:** If you encounter issues with Wabbajack’s auto-download, these files are essential for achieving the intended visual fidelity.

---

## Optional Tools and Enhancements

### BSA Decompressor

A **BSA Decompressor** is included in the tools folder (credit to the original author). It can help improve performance by recompressing archive files. Use it if you experience:

- Game stuttering  
- Long loading times

---

### New Vegas Reloaded (NVR)

This list supports **New Vegas Reloaded** and includes compatible presets.

To install NVR:

1. Join the [Elder Scrolls Reloaded Discord]
2. Download the latest *Ready* build  
3. Follow their documentation to install manually

NVR is optional but recommended. Presets are included, but NVR-related mods are disabled by default.

Included NVR Presets:  
- H2O  
- Caffeine

If using NVR, make sure:  
- Cartographer is enabled  
- Enable NVR mods in **MO2**  
- Optionally enable:  
  - `Caffeine PBR Disabler`  
  - `Caffeine NVR Cinema Disabler`

---

## Troubleshooting

### Installation Script Issue

If `InstalScript.vdf` fails to install:

- Open the file in a text editor  
- Ensure the line beginning with `run process` is entirely lowercase  
  - `Run Process` → Incorrect  
  - `run process` → Correct  

---

## Known Issues & Notes

- This is an early build, so bugs are expected  
- Report any serious bugs or crashes via GitHub Issues  
- Feedback is highly appreciated to shape future updates  

---

## Feedback & Support

This is a personal project and my first ever modlist. I’m learning as I go—please be patient.  
Feel free to open issues, submit suggestions, or contact me directly.

---

## Final Thoughts

*A Blue Moon* was built to breathe new life into *Fallout: New Vegas* without losing its soul. It’s not perfect, but with your help, it will improve over time.

---

## Additional Notes

### DXVK Compatibility

DXVK is included in the `stockgame` folder to resolve alt-tabbing issues.  
If you experience issues (crashes, visual bugs), delete `d3d9.dll` and `dxvk.conf` from that folder.

### Gameplay State

The current gameplay setup is barebones and not final.  
It acts as a framework for future mechanics and balance tuning.  
Your feedback on gameplay feel is incredibly valuable.

### Alternate Hardcore Profiles

Several alternate survival profiles are included in **MO2**.  
They are fully patched, but not thoroughly playtested.  
Feel free to experiment and provide feedback.

---

## Changelog

### Version 0.0.4

**Summary**  
- Added: 40 mods  
- Removed: 4 mods  

---

### Added Mods
- Accidental Discharge  
- B42 Descriptions (Pip-Info)  
- B42 Dynamic Pip-Boy – Bouncy Natural Buttons (ESPless)  
- B42 True Leaning – Contextual (ESPless)  
- Benny Encounter Improvements  
- Caffeine NVR Cinema Disabler  
- Caffeine PBR Disabler  
- Challenges Tracker and Rewards Hints (ESPless)  
- ELITE .45 Auto Pistol Animation Overhaul (kNVSE)  
- ghouls  
- H2O  
- Hardcore Forever  
- High Priority LOD  
- High Priority LOD Mojave Flora Patch  
- Immersive Fast Travel Encounters  
- Immersive Karma  
- Immersive Sleeping Encounters  
- Improved Lighting Shaders  
- INI Config – Gun Runners' Arsenal Merged  
- ML Utilities Checker  
- Mojave Arsenal  
- Mr. House Upscale  
- No Stealthboy In Power Armor  
- NVR Ready  
- Other Profiles Requirements_separator  
- Physically Based Terminals  
- S6S Immersive Fast Travel Hardcore Patch  
- Shotgun Buffs  
- Sweet 6 Shooter Perks – TTW – NV  
- Sweet Dynamic Detection System  
- Townie Names  
- Venom Not Poison  
- xLODGEN OUTPUT  

---

### Removed Mods
- Character Kit Remake Simple Character Exp  
- Simple Character Expansions – YUPDate  


This update is not save-safe.

---

## Special Thanks

- **macintroll** – For allowing the use of his retextures  
- **Rage** – For guidance, support, and constant encouragement throughout this project.  
  Rage, you have no idea how much your continued help has pushed this forward.  
  The hours you spent patiently guiding me, answering all my questions no matter how dumb.  
  I truly appreciate it.
- **Salamand3r** – For providing NVR presets and setup support  
- **Mod Authors** – Of **LoneStar**, **Vicious Wastes**, **Vanilla UI Plus**, and all others included in the list  

---

## Thank You

Thank YOU for reading this and enjoy playing A Blue Moon!


