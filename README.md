# Printer Configs

Personal reference repo for my 3D printing setup: printer details, filament configs, and calibrated values.

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
├── README.md            ← you are here
├── printers/            ← printer specs
├── filaments/           ← per-filament info and calibrated values
└── profiles/            ← exported slicer profiles
```

## Index

### Printers
- [Creality K1C](printers/creality-k1c.md)

### Filaments
- [Creality Ender PLA+ - Black](filaments/pla-plus-creality-black.md)
- [Creality CR-PETG - Black](filaments/petg-creality-black.md)

### Profiles
Slicer profile exports live in [`profiles/`](profiles/).

## Conventions

- All temperatures in °C, lengths in mm.
