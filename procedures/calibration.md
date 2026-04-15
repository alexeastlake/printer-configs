# Calibration Workflow and Results

Calibration runs, recorded per nozzle × filament combination. All calibrations below were done with OrcaSlicer's built-in calibration tools.

## Standard Workflow (New Filament or Nozzle)

1. **Nozzle Temperature Tower**
2. **Max Volumetric Speed**
3. **Pressure Advance**
4. **Flow Ratio**
5. **Retraction**
6. Record results in the matching filament file (and update the nozzle file's summary table).
7. Export the OrcaSlicer profile to [`../profiles/`](../profiles/).

---

## Outstanding Calibrations

| Nozzle | Filament | What's needed |
|---|---|---|
| 0.4mm | PLA+ (Creality Ender Black) | PA and retraction (temp and flow carry over from 0.2mm) |
| 0.2mm | PETG (Creality CR Black) | Full suite (temp, flow, PA, retraction) |
| 0.4mm | PETG (Creality CR Black) | Full suite (temp, flow, PA, retraction) |

---

## Run Log

### 0.2mm Nozzle × Creality Ender PLA+ Black

Tool: OrcaSlicer 2.3.2 built-in calibration.

- **Temp tower:** 190-230°C in 5°C steps. 200°C won — clean bridging, minimal stringing. Below 195°C risked weak adhesion; above 210°C stringing and sag increased.
- **Flow rate:** Pass 1 blocks looked virtually identical. Settled on 0.98, pass 2 skipped.
- **Pressure advance:** PA Line method, 0-0.1 range at 0.002 step. Lines from 0.08+ were complete end to end; picked 0.09.
- **Retraction:** 0-2 mm in 0.1 mm steps. Heavy stringing below 0.4 mm, cleanest 0.8-1.2 mm, slight return above 1.5 mm. Picked 1.0 mm at 35 mm/s.
- **Max volumetric flow:** 5–20 mm³/s range, 1 mm³/s steps. Defects started at 1 cm height (0.9 mm measurement), slicer reported 14.06 mm³/s at that point. Took ~15% safety margin — **12 mm³/s**.

Final values recorded in [`../filaments/pla-plus-creality-black.md`](../filaments/pla-plus-creality-black.md).

---

## General Notes

- When switching to a new filament brand/type, at minimum rerun the temp tower — every other calibration is less useful if the temp is wrong.
