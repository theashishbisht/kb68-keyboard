# 📅 KB68 — Weekend Timeline Tracker

**Schedule:** Sat & Sun, 11 AM – 6 PM | **Budget:** ₹4,000 | **Spent:** ₹0

> Check off tasks as you go. GitHub shows these as progress bars.

---

## Weekend 1 — Setup & KiCad Basics
**Date:** ___/___/2026 | **Spend:** ₹0 | **Cumulative:** ₹0

### Saturday
- [ ] Install KiCad 8.0
- [ ] Watch DigiKey KiCad 8 tutorial (90 min)
- [ ] Install ai03 MX_Alps_Hybrid library
- [ ] Download datasheets (STM32, WS2812B, USB-C, AMS1117, USBLC6)
- [ ] Study 2-3 open-source keyboard KiCad projects

### Sunday
- [ ] Set up QMK build environment
- [ ] Set up project folder + push to GitHub
- [ ] Install Fusion 360
- [ ] Sketch 68-key layout on paper
- [ ] Begin schematic: MCU block (crystal, caps, reset)
- [ ] Begin schematic: USB-C block (connector, CC resistors, ESD)

**✅ Milestone:** Tools installed, MCU + USB sub-circuit drawn

---

## Weekend 2 — Complete Schematic
**Date:** ___/___/2026 | **Spend:** ₹0 | **Cumulative:** ₹0

### Saturday
- [ ] Draw key matrix rows 1-3 (45 switches + diodes)
- [ ] Draw key matrix rows 4-5 (23 switches + diodes)
- [ ] Draw power circuit (AMS1117, 5V→3.3V)
- [ ] Place WS2812B LED pads (unpopulated v0.1)

### Sunday
- [ ] Assign footprints to all symbols
- [ ] Create PIN_ASSIGNMENT.md
- [ ] Run ERC — fix all errors
- [ ] Review schematic against datasheets
- [ ] Compare with reference designs

🔔 **Weekday:** Order USB-UART adapter (₹100)

**✅ Milestone:** Complete schematic, ERC clean

---

## Weekend 3 — PCB Layout + Order
**Date:** ___/___/2026 | **Spend:** ₹1,600 | **Cumulative:** ₹1,600

### Saturday
- [ ] Import netlist to PCB editor
- [ ] Draw board outline (295×105mm)
- [ ] Place USB-C + MCU + power components
- [ ] Place all 68 switch footprints (19.05mm grid)
- [ ] Place LED footprints (future RGB)

### Sunday
- [ ] Route USB differential pair
- [ ] Route power traces (0.5mm+)
- [ ] Route key matrix + LED chain
- [ ] Ground pour on bottom layer
- [ ] Run DRC — fix all violations
- [ ] Add silkscreen + export Gerber files

🔔 **Monday:** Order PCBs (₹1,500) + all components (~₹1,660)

**✅ Milestone:** Gerber files sent to manufacturer

---

## Weekend 4 — Case Design + Firmware
**Date:** ___/___/2026 | **Spend:** ₹1,960 | **Cumulative:** ₹3,560

### Saturday
- [ ] Watch Fusion 360 tutorial (1 hr)
- [ ] Design bottom case + top bezel + plate
- [ ] Export STL → send to 3D printer (₹300)

### Sunday
- [ ] Read QMK Newbs Guide
- [ ] Create keyboard: `qmk new-keyboard`
- [ ] Write config.h, rules.mk, keymap.c

**✅ Milestone:** Case printing, firmware configs written

---

## Weekend 5 — Firmware Dev
**Date:** ___/___/2026 | **Spend:** ₹0 | **Cumulative:** ₹3,560

### Saturday
- [ ] Write kb68.h + info.json
- [ ] First compile: `qmk compile`
- [ ] Fix compile errors

### Sunday
- [ ] Add 4 layers to keymap
- [ ] Add VIA support + recompile
- [ ] Prepare soldering workspace

**✅ Milestone:** Firmware compiles, .bin ready

---

## Weekend 6 — 🔥 BUILD DAY
**Date:** ___/___/2026 | **Spend:** ₹195 | **Cumulative:** ₹3,755

### Saturday — Solder
- [ ] Inspect PCBs
- [ ] Solder STM32 + crystal + caps
- [ ] Solder power circuit + USB-C + ESD
- [ ] **POWER-ON TEST** (3.3V rail check)

### Sunday — Assemble
- [ ] Solder diodes (check polarity!)
- [ ] Flash firmware via USB-UART
- [ ] Test matrix with tweezers
- [ ] Install switches + stabilizers
- [ ] Assemble case + keycaps
- [ ] **FULL TEST** — every key

**✅ Milestone:** 🎉 PROTOTYPE #1 WORKING

---

## Weekend 7 — Testing + Fixes
**Date:** ___/___/2026 | **Spend:** ₹0 | **Cumulative:** ₹3,755

### Saturday
- [ ] 50× press test on every key
- [ ] Gaming test + typing test
- [ ] USB stability test
- [ ] Create bug list

### Sunday
- [ ] Fix hardware bugs (re-solder)
- [ ] Fix firmware bugs (recompile + reflash)
- [ ] Product photos + typing video

**✅ Milestone:** Bug-free prototype, photos taken

---

## Weekend 8 — Launch
**Date:** ___/___/2026 | **Spend:** ₹0 | **Cumulative:** ₹3,755

### Saturday
- [ ] Polish VIA info.json
- [ ] Plan v0.2 RGB upgrade

### Sunday
- [ ] Write + post build story
- [ ] Post on r/MechanicalKeyboards + r/IndianGaming
- [ ] Plan v1.0 production spec
- [ ] Research GST/MSME registration

**✅ Milestone:** Community launched, v1.0 planned

---

## 💰 Budget Summary

| When | Item | ₹ | Total |
|---|---|---|---|
| Wk 3 | PCB batch (5 pcs) | 1,500 | 1,500 |
| Wk 3 | USB-UART adapter | 100 | 1,600 |
| Wk 4 | 3D print case | 300 | 1,900 |
| Wk 4 | Components | 500 | 2,400 |
| Wk 4 | Switches ×70 | 560 | 2,960 |
| Wk 4 | Keycaps | 400 | 3,360 |
| Wk 4 | Stabs + cable + hardware | 200 | 3,560 |
| Wk 6 | Consumables | 195 | 3,755 |
| | **TOTAL** | | **₹3,755** |
| | **Buffer** | | **₹245** |
