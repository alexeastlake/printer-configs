# Filament Swap Procedure

---

## Same Material, Different Roll

Simple case - no purge needed beyond normal loading.

1. Retract filament via printer menu.
2. Unload filament from extruder.
3. Load the new roll and feed it into the extruder.
4. Extrude until new filament flows cleanly.
5. Ready to print.

---

## Cross-Material Swap

Different materials have different print temps. Swapping without purging leaves residual material that can clog or cause layer defects.

> **Rule:** Always purge at the *higher* of the two material temps. That way both filaments fully melt out the nozzle.

### PETG → PLA

1. Heat nozzle to **PETG temp** (~240°C).
2. Retract and unload PETG.
3. Use needle tool to clear any remaining filament from the nozzle.
4. Load PLA filament.
5. **While still at PETG temp**, extrude PLA until it flows clean. This pushes out residual PETG that wouldn't melt at PLA temps.
6. Lower nozzle to **PLA temp** (200°C).
7. Extrude a bit more at PLA temp to confirm clean, consistent flow.
8. Ready to print.

### PLA → PETG

1. Heat nozzle to **PETG temp** (~240°C).
2. Retract and unload PLA.
3. Use needle tool to clear any remaining filament from the nozzle.
4. Load PETG.
5. Extrude until flow is clean and consistent.
6. Ready to print.

---
