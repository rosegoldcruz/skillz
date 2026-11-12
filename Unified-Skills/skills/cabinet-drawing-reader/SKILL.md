---
name: cabinet-drawing-reader
description: Explains how to read a set of cabinet or casework shop drawings (plans, elevations, sections, details, schedules). Use when someone uploads or describes cabinet drawings and asks what they show, how to read them, or what a specific view or symbol means.
---

# Cabinet Drawing Reader

Goal: help a person understand a cabinet drawing set in simple words. Assume they are new to it. Define every term the first time you use it.

## Step 1: Figure out what kind of sheet it is

Cabinet sets are built from a few view types. Each one answers a different question.

| View | What you are looking at | What it answers |
|---|---|---|
| Plan | Top-down view of the cabinet footprint | Do the runs fit the room? Corners, island size, clearances around appliances and walls |
| Elevation | Front face of each run of cabinets | What do the doors, drawers and panels look like? Are tall units and appliance openings in the right spots? |
| Section | A slice through a cabinet | What is inside and how is it built? Box thickness, shelves, drawer stacking, toe kick, hinge clearance, how it meets the wall, counter, floor |
| Detail | A zoomed-in piece | Tricky spots: corners, scribes, special joints, custom features |
| Schedules and notes | Tables and text | Hardware part numbers, finishes, quantities, site notes |

Tip: the elevation is the "pretty" view. The section is where the real build decisions live. A set with elevations only is incomplete.

## Step 2: Read in this order

1. **Title block and legend.** Project, sheet number, revision, scale, units. Every symbol should be explained in a legend. If a symbol has no legend, flag it.
2. **Plan.** Get the layout in your head. Which wall, which runs, where the appliances are.
3. **Elevations.** Match each run to the plan. Same cabinets, same order, same count.
4. **Sections.** Find one section per cabinet type. Read the construction.
5. **Details.** Read any callout bubble that points to a detail sheet.
6. **Schedules and notes.** Hardware, finishes, quantities, items "by others."

## Step 3: Read the dimensions

Check these first, because they decide whether things fit:
- Total length of each run vs the wall
- Each cabinet width, height, depth
- Base height and upper height, and the gap between them
- Appliance openings (must include ventilation gaps, not just the appliance size)
- Toe kick height and setback

Watch the units. Metric and inch mix-ups are one of the most common ways people misread a drawing. Confirm the unit and scale in the title block before trusting any number.

## Step 4: Know the two construction styles

- **Face frame:** a wood frame on the front of the box. Drawings show frame stock sizes, rail and stile widths, and overlay measured from the frame.
- **Frameless (European):** no frame. Everything hangs off the box edge. Reveals are tighter and the 32 mm hole pattern shows up in sections.

If you cannot tell which one a set uses, ask. Many dimensions change depending on the answer.

## Step 5: Read the cabinet tags

Some sets tag each cabinet with a code. One common system is the AWI Casework Design Series. See the `cabinet-spec-and-tagging` skill for how to read those tags. If the goal is counting cabinets for pricing, use the `cabinet-takeoff-from-elevations` skill.

Also check that unit numbers match everywhere. If the plan says B-04, the elevation and schedule should say B-04 too, not "4B."

## How to answer the user

- Start with one or two sentences saying what the sheet is.
- Then walk through it using the order above.
- Point out anything missing or unclear instead of guessing. Say "this sheet does not show X, ask for it."
- Do not make up dimensions or specs that are not on the drawing.

## Sources this skill was built from

- ArchiCGI, "Cabinet Shop Drawings: What a Shop Needs Before the First Cut"
- BFP Cabinetry, "How to Read Kitchen Cabinet Drawings and Specifications Like a Pro"
- McLine Studios, "How to Interpret Cabinetry Drawings Effectively?"
- Life of an Architect, "Graphic Standards for Architectural Cabinetry"
