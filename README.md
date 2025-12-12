# BSPD Routing Challenge - Manchester Stinger Motorsports

Welcome to the **BSPD Routing Challenge** for the Manchester Stinger Motorsports Formula Student team.

The aim of this challenge is to compare PCB layout and routing quality across the team using **the same fixed schematic and board constraints**.

You will fork this repository, route the PCB, and submit your solution via GitHub.

---

## Objective

Produce the **best-routed PCB** possible while strictly adhering to the constraints below.

This is a **layout-only challenge** - no schematic edits, no mechanical changes, no shortcuts.

---

## Deadline

**9th of February (23:59)**

---

## How to Enter

1. **Fork this repository**
2. Open the project in **KiCad** 
3. Route the PCB according to the rules below
4. Commit your changes
5. Submit your fork for review

---

## Rules (Read Carefully)

### 1. Schematic - DO NOT CHANGE
- The **schematic must remain completely unchanged**
- No component changes
- No footprint changes
- No net changes

Any schematic modification will result in **disqualification**.

---

### 2. Board Outline & Connectors - FIXED
- **Board dimensions must remain unchanged**
- **Board outline must not be edited**
- **All connectors must stay in their original positions and orientations**
- Do not move connectors even slightly

This ensures all layouts are directly comparable.

---

### 3. What You ARE Allowed to Change
- Component placement (except connectors)
- Track routing
- Via count and placement
- Copper pours / zones
- Layer usage
- Trace widths (within design rules)
- Decoupling capacitor placement (if already present in the schematic)

---

### 4. What You Are NOT Allowed to Do
- Modify the schematic in any way
- Add or remove components
- Change connector positions
- Change board size or shape
- Change footprints

---

## Judging Criteria

Layouts will be judged on:

- Signal integrity
- Routing quality
- Layer usage efficiency
- EMI considerations
- Manufacturability/Solderability
- Overall cleanliness and readability

Bonus points for:
- Thoughtful via usage
- Clear functional grouping
- Good silkscreen labelling (feel free to add cool graphics!!)

---

## Submission Guidelines

- Commit **only PCB layout changes**
- Final submission must build cleanly with **no DRC errors**
- Do not squash or rewrite history after submission
- When you are happy with your submission send me (Jame) a message.


---

## Point of Contact

The point of contact for this challenge is **me** (James Platt).

That said, please **ask questions and discuss openly in the `#st-electronics` Slack channel** wherever possible so everyone benefits.

---

## Notes

This challenge is intended to:
- Improve PCB routing skills across the team
- Encourage discussion around best practice
- Foster healthy competition within the sparky subteams

Best of luck!!

Jame ⚡
