[All guides](../README.md) / Blocked-hole clearing

# Clear a Blocked Through-Hole

Use this method when the component has already been removed, but pumping or wicking has left a solder plug inside its hole.

Reflow the plug, slide a smooth stainless-steel needle through the liquid solder, and hold it still while the solder hardens. Withdraw the needle after cooling to leave a central passage. Some solder will remain on the copper barrel.

## Tools and preparation

Have a temperature-controlled iron, electronics flux, a small amount of fresh electronics solder, a PCB holder, tweezers or pliers, and good lighting or a magnifier. Use a compatible flux cleaner and swab if cleanup is needed.

Choose a **smooth, clean stainless-steel desoldering needle**, preferably with a blunt tip. Its diameter must fit inside the plated hole without scraping the copper and leave enough clearance for the replacement lead. Rough or solder-wetted surfaces can make a needle stick.

Work on an unpowered board with batteries disconnected and stored charge addressed. Use eye protection and ventilation; hold the hot needle with tweezers or pliers. Do not use this method on a loose pad or damaged barrel, and never force a needle through solid solder.

## Procedure

### 1. Inspect and secure the board

Check both sides of the empty hole for lifted pads, damaged copper, or nearby heat-sensitive parts. Clamp the PCB gently so it cannot move. Stop if the pad or barrel is already coming loose.

### 2. Add flux and a little fresh solder

Apply flux to the blocked hole, then melt a small amount of fresh solder onto the pad. This improves thermal contact with the old plug; use only enough to help it reflow.

### 3. Melt the whole plug

Heat the pad and solder with a clean, suitably sized tip. The solder must be liquid through the board thickness, not just at the surface.

If it does not melt promptly, improve tip contact or pause and reassess. A large copper plane may need more thermal capacity or controlled preheating. Avoid prolonged heating with an undersized tip.

### 4. Insert the needle while the solder is liquid

Hold the needle with tweezers or pliers and gently slide it straight through the centre of the hole while keeping the solder molten.

If it meets resistance, withdraw it. The plug may not be fully melted, or the needle may be too large. Let the board cool if needed, then reassess and reflow before trying again.

### 5. Hold the needle while the solder hardens

Remove the iron and keep the needle still. Allow the solder to cool and solidify naturally around it. The needle preserves the opening during cooling.

### 6. Withdraw the needle

After the solder has hardened, gently pull the needle straight out. Do not twist or yank it.

If it sticks, reheat the solder to release it, then reassess the needle's material, surface, and size before another attempt.

### 7. Inspect, check the fit, and clean

Use a light or magnifier to inspect the passage. The replacement lead should pass through without force. If the passage is too narrow, use a suitable needle in a separate controlled reflow operation; do not drill through the copper plating.

After cooling, clean compatible flux residue and inspect the pad and barrel before soldering the replacement lead.

## What the result should look like

The hole has a clear central passage, with some solder still bonded to the barrel. The pad remains flat and attached, and the replacement lead fits freely. This method opens space through the solder; it does not strip all solder from the hole.

## Troubleshooting

| Symptom | What to do |
| --- | --- |
| The needle will not pass through | Fully reflow the plug and check needle size. Never push through resistance. |
| The needle sticks after cooling | Reheat to release it gently; check its surface, material, and fit. |
| The passage is too small | Reflow with a suitable needle that still clears the copper barrel. |
| Only surface solder melts | Improve tip contact or thermal capacity; reassess before heating again. |
| The passage closes after withdrawal | Wait for the solder to solidify around the needle before removing it. |
| A pad lifts or changes shape | Stop immediately and inspect the copper for damage. |

Stop if the board discolours or repeated attempts fail. A temperature-controlled vacuum desoldering tool or professional rework may be more suitable.

## Background and further reading

The [joint cross-section](../images/through-hole-joint.svg) shows the copper barrel that this method must leave intact. For general preparation and heat-transfer guidance, see [Circuit Technology Center — Preparation for soldering and component removal](https://www.circuitrework.com/guides/7-1-2.html).

The original guide also referenced practical accounts of needle use: [Electrical Engineering Stack Exchange](https://electronics.stackexchange.com/questions/716379/tips-on-removing-solder-stuck-in-very-small-hole/716391) and [Hackaday](https://hackaday.com/2017/04/03/have-you-ever-tried-desoldering-needles/). These are community examples rather than a board manufacturer's repair procedure.

[Back to all guides](../README.md)
