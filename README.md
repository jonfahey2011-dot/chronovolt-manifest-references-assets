# ChronoVolt — Manifest & Asset Library

## 📖 Overview
This repository is the **warehouse** of ChronoVolt.  
It contains all **visuals, sounds, and reference material** used to build the system.

---

## 📦 Contents
- **MASTER SVGS/** → The 3 layout-authoritative SVGs.  
- **SOUND_ASSETS/** →  
  - `sfx/` → click, back, confirm, hover, error, scroll.  
  - `voices/` → Alien, HAL9000, Mother, Fallout Terminal, Talky Toaster, etc.  
- **CRT_THEME_CARDS/** → Reference CRT screen mockups.  
- **TUBE_CARDS/** → Nixie, VFD, numitron selection previews.  
- **NAV_CARDS/** → Example navigation cards.  
- **Logos/** → Weyland logo, ChronoVolt logos.  
- **Reference Images/** → Alien 1979 CRT stills, Alien Covenant screens, MU/TH/UR waking images.  

---

## 🔒 Invariants
- Visuals here are **reference-only**.  
- Specs and authoritative dimensions always come from `chronovolt-mother-memory`.  
- Only the **3 master SVGs** drive layout.  

---

## 🔄 Workflow Role
1. Assets created or stored here.  
2. `assets_map.json` + `references.json` keep everything indexed.  
3. Synced into [`chronovolt-app-build`](https://github.com/jonfahey2011-dot/chronovolt-app-build) under `payload/assets/`.  

---

## 🛰️ Status
This repo is **authoritative for assets**.  
No build happens here directly — it supplies ChronoVolt’s look & sound.
