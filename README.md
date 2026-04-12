# Printer Configs

Personal reference repo for my 3D printing setup: printer details, nozzle/filament configs, calibration results, and operating procedures.

## Quick Reference

| | |
|---|---|
| **Printer** | Creality K1C (enclosed CoreXY, 220mm × 220mm × 250mm) |
| **Nozzles** | 0.4mm, 0.2mm |
| **Slicer** | OrcaSlicer (primary), Creality Print (monitoring) |
| **Active filaments** | Creality Ender PLA+ Black, Creality CR-PETG Black |

## Repository Layout

```
printer-configs/
├── README.md                     ← you are here
├── printers/                     ← printer hardware
├── nozzles/                      ← per-nozzle info and calibrated values
├── filaments/                    ← per-filament temps and calibrated values
├── procedures/                   ← step-by-step how-tos
└── profiles/                     ← exported slicer profiles
```

## Index

### Printers
- [Creality K1C](printers/creality-k1c.md)

### Nozzles
- [0.4mm](nozzles/0.4mm.md) - general purpose
- [0.2mm](nozzles/0.2mm.md) - miniatures/detail

### Filaments
- [Creality Ender PLA+ - Black](filaments/pla-plus-creality-black.md)
- [Creality CR-PETG - Black](filaments/petg-creality-black.md)

### Procedures
- [Filament swap](procedures/filament-swap.md)
- [Nozzle change](procedures/nozzle-change.md)
- [Calibration workflow and results](procedures/calibration.md)

### Profiles
Slicer profile exports live in [`profiles/`](profiles/).

## Conventions

- All temperatures in °C, lengths in mm.
