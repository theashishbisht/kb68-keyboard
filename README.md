# ⌨️ KB68 — Custom 65% Mechanical Keyboard

> India's first R&D-driven custom mechanical keyboard. Designed, coded, and built from scratch.

![Status](https://img.shields.io/badge/status-prototype--v0.1-orange)
![PCB](https://img.shields.io/badge/PCB-KiCad%208.0-blue)
![Firmware](https://img.shields.io/badge/firmware-QMK-red)
![License](https://img.shields.io/badge/license-MIT-green)
![Budget](https://img.shields.io/badge/prototype%20budget-₹4%2C000-purple)

---

## What is this?

A fully custom 68-key (65%) mechanical keyboard built from the ground up in India — custom PCB, custom case, custom firmware, custom key mapping. No kit builds, no pre-made boards. Every component designed and specified in-house.

**Phase:** Prototype v0.1 (no RGB — PCB is RGB-ready for v0.2)

## Features

- 68-key 65% ANSI layout (compact with arrow keys)
- STM32F103C8T6 ARM Cortex-M3 microcontroller
- QMK firmware with VIA configurator support
- USB-C connection (USB 2.0 Full Speed)
- N-Key Rollover (NKRO) anti-ghosting
- 4-layer key mapping (Base / Fn / Gaming / Macro)
- PCB designed for per-key RGB (WS2812B — populated in v0.2)
- 3D printed case with 6° typing angle
- Custom PCB manufactured in India

## Project Structure

```
kb68-project/
├── pcb/                    # KiCad project files
├── firmware/               # QMK firmware source
│   └── yourfirmname/kb68/
├── case/                   # Case design (STL + STEP)
├── hardware/               # BOM, specs, pin maps
├── docs/                   # Datasheets, assembly guide
├── software/               # Custom configurator (v2)
├── assets/                 # Photos, branding
├── TIMELINE.md             # Weekend progress tracker
├── PROGRESS.md             # Build journal
└── CHANGELOG.md            # Version history
```

## Quick Links

| Resource | Link |
|---|---|
| 📅 Progress Tracker | [TIMELINE.md](TIMELINE.md) |
| 📦 Bill of Materials | [hardware/BOM.md](hardware/BOM.md) |
| 📐 Technical Specs | [hardware/SPECS.md](hardware/SPECS.md) |
| 🔌 Pin Assignment | [hardware/PIN_ASSIGNMENT.md](hardware/PIN_ASSIGNMENT.md) |
| 📝 Build Log | [PROGRESS.md](PROGRESS.md) |
| 🔧 Assembly Guide | [docs/ASSEMBLY_GUIDE.md](docs/ASSEMBLY_GUIDE.md) |

## v0.1 Specs

| Parameter | Value |
|---|---|
| Layout | 68-key, 65%, ANSI |
| MCU | STM32F103C8T6 (72MHz ARM Cortex-M3) |
| PCB | 2-layer FR4, 1.6mm, ~295×105mm |
| Connection | USB-C (USB 2.0) |
| Firmware | QMK + VIA |
| Switches | Cherry MX compatible (soldered) |
| Case | 3D printed PLA, tray mount |

## Timeline

Weekend builds only (Sat–Sun, 11 AM – 6 PM). See [TIMELINE.md](TIMELINE.md).

| Weekend | Phase | Status |
|---|---|---|
| 1 | Setup + KiCad basics | ⬜ |
| 2 | Complete schematic | ⬜ |
| 3 | PCB layout + Gerber | ⬜ |
| 4 | Case design + firmware | ⬜ |
| 5 | Firmware development | ⬜ |
| 6 | Build prototype #1 | ⬜ |
| 7 | Testing + fixes | ⬜ |
| 8 | VIA + community launch | ⬜ |

## Roadmap

- [x] Project planning and BOM
- [ ] **v0.1** — Working keyboard, no RGB, 3D printed case
- [ ] **v0.2** — Add per-key RGB (WS2812B)
- [ ] **v1.0** — CNC aluminum case, hot-swap, gasket mount, custom app
- [ ] **v2.0** — Wireless (BLE), production batch

## License

MIT — see [LICENSE](LICENSE). Open-source hardware.

---

*Designed and built in India 🇮🇳*
