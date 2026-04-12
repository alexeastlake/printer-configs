# Nozzle Change Procedure

## Procedure

1. **Heat and purge.** Heat nozzle to print temp and retract/unload the current filament through the printer menu.
2. **Clear residual filament.** Use the needle tool to push through any remaining filament in the nozzle while it's still hot.
3. **Cool.** Let the nozzle cool to room temperature before handling.
4. **Open the hotend.** Remove the extruder housing and silicone sleeve.
5. **Remove the current nozzle.** Unscrew the nozzle.
6. **Install the new nozzle.** Screw in snugly, but do **not** overtorque - strip risk.
7. **Load filament and test extrude.** Heat to print temp, load filament, manually extrude. Verify clean, consistent flow before reassembling housing.
8. **Cool.** Let the nozzle cool to room temperature before handling.
9. **Reassemble.** Reinstall the silicone sleeve and extruder housing.
10. **Test extrude.** Heat to print temp, manually extrude. Verify clean, consistent flow before printing.

## After a Swap - Checklist

- [ ] Correct printer profile selected (0.2mm vs 0.4mm)
- [ ] Correct process profile selected (layer height appropriate for nozzle)
- [ ] Correct filament profile selected
- [ ] Test extrusion is clean and consistent

## Notes

- The 0.2mm nozzle prints significantly slower than the 0.4mm
- If you just installed a brand new nozzle (not reusing an old one), run at least a pressure advance check - PA is nozzle-dependent.
- Flow and temp calibrations generally **do not** need to be rerun after a nozzle change, since they're filament-dependent. Pressure advance and retraction **do**.
