[All guides](../README.md) / Component removal

# Remove a Through-Hole Component

Use a desoldering pump to extract solder from around the leads, then use solder wick to clean up the residue. Lift the component only when every lead is free.

This method keeps two separate pump attempts, with inspection, fresh flux, and a pin-freedom test between them.

## Tools and preparation

Have a temperature-controlled iron with a clean, suitably sized tip, electronics flux, fresh electronics solder, a primed desoldering pump, solder wick, a PCB holder, tweezers or small pliers, and a compatible flux cleaner with a brush or swab.

Work on an unpowered board with batteries disconnected and stored charge addressed. Use eye protection and fume ventilation. Never pull against a soldered lead or lever a tool against a copper pad.

## Procedure

### 0. Secure the board

Support the PCB so the pump cannot shift or bend it. Identify every lead and any mechanical tabs holding the component.

### 1. Heat the joint

Touch the iron to the pad and lead together. Aim to melt the whole joint promptly. If only the surface softens, improve tip contact rather than pressing harder or keeping the iron on the pad for a long time.

For typical tin-lead solder, **320–350°C** is an approximate starting iron setting; some lead-free joints need **350–380°C**. These are tool settings, not solder melting temperatures. Adjust for the tip, alloy, board, and connected copper.

### 2. Apply flux

Apply electronics flux to the joint to help the old solder wet and flow.

### 3. Add fresh solder and pump once

1. Melt a small amount of fresh solder into the joint to improve thermal contact.
2. Keep the primed pump close to the joint, with its nozzle roughly perpendicular to the board.
3. Heat the pad and lead until the solder is fully liquid.
4. Move the iron aside, immediately place the nozzle over the joint, and trigger the **first pump attempt**.

If the solder freezes before suction, the pump will remove little. Reflow it before another attempt.

### 4. Inspect the hole

Look at both faces of the PCB. A clear surface pad can still hide solder inside the barrel or on the far side.

### 5. Apply flux again

Add fresh flux to the remaining solder before reheating the joint.

### 6. Test whether the lead is free

Add a little fresh solder if needed for heat transfer, then heat the pad and lead together. While the solder is molten, use the iron tip to check for slight lead movement. Do not pry, bend the lead, or press against the barrel.

Resistance means the lead is still held. This check comes **before** the second pump attempt.

### 7. Pump a second time

If solder still holds the lead, reheat the remaining solder until fully liquid. With the pump primed and ready, move the iron away, position the nozzle, and trigger the **second pump attempt**.

If the lead is already completely free, avoid unnecessary reheating.

### 8. Finish with solder wick

1. Lay a clean, appropriately fluxed section of braid over the remaining solder.
2. Rest the hot iron on the braid so heat reaches the solder underneath. Use light pressure.
3. When solder flows into the braid, lift the **iron and braid together while hot**.

Use a fresh section when the braid is saturated. If it sticks to the pad, reheat it before lifting. Do not drag it across the copper.

Wick is the finishing step for small deposits; keep the second pump attempt ahead of it when solder still holds the lead.

### 9. Confirm every lead is free

Check each lead and both sides of the board. If a deposit remains, add flux, reheat, and use wick as needed. Allow cooling between repeated attempts.

### 10. Remove the component

Gently lift the component from the opposite side of the board. If it catches, stop and inspect all leads and tabs again. Do not pull harder or use a pad as a fulcrum.

### 11. Clean and inspect

Let the board cool. Remove compatible flux residue with a suitable cleaner, then let it dry completely. Inspect the pads and barrels before fitting a replacement.

If the component is out but solder still blocks a hole, see [Clear a blocked through-hole](clear-blocked-through-hole.md).

## Troubleshooting

| Symptom | What to check |
| --- | --- |
| Solder beads up or will not flow | Clean the tip, add flux, and mix in a little fresh solder. |
| The pump removes little | Reflow the whole joint and shorten the move from iron to pump. Check nozzle placement. |
| The surface looks clear but the lead is stuck | Inspect the barrel and far side; follow the flux, pin-test, and second-pump steps. |
| Wick does not absorb solder | Use a fresh section, suitable flux, and good contact between iron, braid, and joint. |
| A large ground connection will not reflow | Use suitable tip size and thermal capacity; consider controlled PCB preheating. |
| The pad moves or the PCB scorches | Stop. Repeated heating or force can damage the pad and barrel. |

If controlled attempts do not free the lead, stop and consider a temperature-controlled vacuum desoldering tool or professional rework.

## Technical references

- [Circuit Technology Center — Preparation for soldering and component removal](https://www.circuitrework.com/guides/7-1-2.html): tool selection, heat transfer, and board preparation.
- [Chemtronics — Desoldering wick application guide](https://www.chemtronics.com/desoldering-wick-application-guide): braid placement, fresh sections, and lifting braid with the iron.

[Back to all guides](../README.md)
