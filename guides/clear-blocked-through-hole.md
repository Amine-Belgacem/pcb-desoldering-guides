[← All guides](../README.md) · Blocked-hole clearing

# Clear a Blocked Through-Hole

Reflow the solder plug, hold a smooth stainless-steel needle in place while it cools, then withdraw the needle to leave a passage.

**Use this guide when:** the component is already out, but pumping or wicking has left the hole blocked.

**Finish when:** the replacement lead fits freely and the copper pad and barrel remain intact.

[Before you start](#before-you-start) · [Prepare](#prepare-the-hole) · [Form the passage](#form-the-passage) · [Check the result](#check-the-result) · [Troubleshooting](#troubleshooting)

---

## Before you start

- **Heat:** temperature-controlled iron, electronics flux, and a little fresh electronics solder.
- **Form the passage:** smooth, clean stainless-steel desoldering needle, preferably with a blunt tip.
- **Hold and inspect:** PCB holder, tweezers or pliers, and good lighting or a magnifier.
- **Clean:** compatible flux cleaner and a swab, if needed.

**Choose the needle:** its diameter must fit inside the plated hole without scraping the copper and leave enough clearance for the replacement lead. Rough or solder-wetted surfaces can make a needle stick.

> [!CAUTION]
> Disconnect power and batteries and address stored capacitor charge. Wear eye protection and use ventilation. Hold the hot needle with tweezers or pliers. Never force it through solid solder or use it on a loose pad or damaged barrel.

**Sequence:** inspect → flux and fresh solder → fully melt → insert the needle → let solder harden → withdraw → inspect and clean.

## Prepare the hole

### 1. Inspect and secure the board

Check both sides of the empty hole for lifted pads, damaged copper, or nearby heat-sensitive parts. Clamp the PCB gently so it cannot move. Stop if the pad or barrel is already coming loose.

### 2. Add flux and a little fresh solder

Apply flux to the blocked hole, then melt a small amount of fresh solder onto the pad. This improves thermal contact with the old plug; use only enough to help it reflow.

### 3. Melt the whole plug

Heat the pad and solder with a clean, suitably sized tip. The solder must be liquid through the board thickness, not just at the surface.

If it does not melt promptly, improve tip contact or pause and reassess. A large copper plane may need more thermal capacity or controlled preheating. Avoid prolonged heating with an undersized tip.

**Checkpoint:** the plug is molten through the full board thickness before the needle enters.

## Form the passage

### 4. Insert the needle while the solder is liquid

Hold the needle with tweezers or pliers and gently slide it straight through the centre of the hole while keeping the solder molten.

If it meets resistance, withdraw it. The plug may not be fully melted, or the needle may be too large. Let the board cool if needed, then reassess and reflow before trying again.

### 5. Hold the needle while the solder hardens

Remove the iron and keep the needle still. Allow the solder to cool and solidify naturally around it. The needle preserves the opening during cooling.

> **Wait before withdrawing:** let the solder harden around the stationary needle.

### 6. Withdraw the needle

After the solder has hardened, gently pull the needle straight out. Do not twist or yank it.

If it sticks, reheat the solder to release it, then reassess the needle's material, surface, and size before another attempt.

## Check the result

### 7. Inspect, check the fit, and clean

Use a light or magnifier to inspect the passage. The replacement lead should pass through without force. If the passage is too narrow, use a suitable needle in a separate controlled reflow operation; do not drill through the copper plating.

After cooling, clean compatible flux residue and inspect the pad and barrel before soldering the replacement lead.

**Completion check:**

- The hole has a clear central passage, with some solder still bonded to the barrel.
- The pad remains flat and attached.
- The replacement lead fits freely.

This method opens space through the solder; it does not strip all solder from the hole.

---

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

<details>
<summary><strong>Background and further reading</strong></summary>

The [joint cross-section](../images/through-hole-joint.svg) shows the copper barrel that this method must leave intact. For general preparation and heat-transfer guidance, see [Circuit Technology Center — Preparation for soldering and component removal](https://www.circuitrework.com/guides/7-1-2.html).

The original guide also referenced practical accounts of needle use: [Electrical Engineering Stack Exchange](https://electronics.stackexchange.com/questions/716379/tips-on-removing-solder-stuck-in-very-small-hole/716391) and [Hackaday](https://hackaday.com/2017/04/03/have-you-ever-tried-desoldering-needles/). These are community examples rather than a board manufacturer's repair procedure.

</details>

---

[← Previous: remove a through-hole component](remove-through-hole-components.md) · [All guides](../README.md)
