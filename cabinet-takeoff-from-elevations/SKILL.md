---
name: cabinet-takeoff-from-elevations
description: Walks through counting cabinets and accessories off architectural kitchen and bath elevations for pricing (a "takeoff"). Covers reading cabinet codes, hinge side, entry order, fillers, scribe, toe kick and end panels. Use when someone wants to price, list or enter cabinets from architect elevations.
---

# Cabinet Takeoff From Elevations

A takeoff means listing every cabinet and accessory shown on the drawings so it can be priced. Explain in plain words. Define terms the first time.

Important: cabinet codes differ by manufacturer. The patterns below are common, not universal. Tell the user to check the manufacturer's catalog before entering codes. For a longer abbreviation list and standard sizes, see the `cabinet-code-decoder` skill.

## Step 1: Know the standard heights

- Standard base cabinet: about 34 1/2 in tall. Add the countertop thickness and you get the usual 36 in finished height.
- Accessible (ADA-style) kitchen: base cabinet about 32 1/2 in, countertop about 34 in finished.
- Wall cabinets are drawn with a height. A short cabinet over a microwave (for example 18 in) usually sits halfway between the taller wall cabinets beside it, so you can confirm its height by looking at the drawing.
- Always check each elevation for which kitchen type it is. Accessible units use different heights.

## Step 2: Read the cabinet code

Pattern: **type + width + height**, width always first.

| Part | Meaning | Example |
|---|---|---|
| W | Wall cabinet | W3036 = wall cabinet, 30 wide, 36 tall |
| B | Base cabinet | B24 = base cabinet, 24 wide |
| SB | Sink base | SB30 = sink base, 30 wide |
| BD (or just B) | Butt door: two doors with no center stile, so nothing blocks the plumbing | SB30 BD |
| R or L | Hinge side (right or left) | W936R, B9R |

Notes:
- A 9 in base cabinet often has just a single door and no drawer, because a drawer that narrow is almost useless. Many manufacturers do not offer a 9 in drawer base.
- An open wall cabinet has no doors and needs a finished interior. Enter it as its own item.
- Dishwasher and range are appliances, not cabinets. Do not price them as cabinets, but note their openings.

## Step 3: Find the hinge side from the drawing

Doors are drawn with dotted lines in a V shape. The point where the two dotted lines meet (the apex) is the hinge side. Apex on the right means a right-hand hinge, so add R. Apex on the left means add L.

## Step 4: Enter cabinets in a set order

1. Start at the left side of the kitchen and work clockwise, like reading a book.
2. Enter all wall cabinets first, left to right.
3. Then enter the base cabinets, left to right.
4. In an L-shaped kitchen, finish one elevation, then move clockwise to the next. Side views of the same cabinets are not new cabinets. Do not count them twice.

## Step 5: Watch for what the architect forgot

Architects often leave out small parts that still need to be priced.

- **End panels:** a dishwasher end panel (also called a base end panel) is often missing between the dishwasher and the range. Add it even when it is not drawn. Also include the one at the end of the dishwasher run when it is needed.
- **Missing wall cabinet over the refrigerator:** if the drawing has none, do not add one. Note it as "none shown."
- Flag anything you added that the drawing did not show, so the user can confirm.

## Step 6: Add the accessories

After the cabinets, count three accessory items.

**Fillers**
- A filler is a flat strip that closes a gap where a cabinet meets a wall or at a corner.
- Count where the drawing shows them: wall ends and corner situations.
- Fillers usually come in 3 in and 6 in widths, sometimes 9 in. A drawing may call for 2 in. The takeoff in the video rounds up to the stock size (3 in), so check what the manufacturer offers.

**Scribe molding**
- Scribe is thin trim that covers the gap when a cabinet meets a wall that is not perfectly straight or plumb.
- You estimate it. Make sure there is enough.
- It comes in 8 ft pieces. Count where cabinets touch walls, where an end panel meets a framed wall, and along a soffit if the cabinets meet one.
- In the video, one 8 ft piece covers a run of 34 1/2 in base plus a wall cabinet up to about 42 in. The L-shaped example needed four pieces total.
- Round up if unsure and tell the user it is an estimate.

**Toe kick**
- The toe kick is the strip covering the bottom of the base cabinets.
- Add up the linear feet of base cabinets, including corner runs.
- It comes in 8 ft lengths. Example: about 7 ft needed means one piece.
- Count bathrooms separately.

## Step 6b: Peninsulas, vanities and whole units

**Peninsulas**
- A peninsula is a run of base cabinets sticking out into the room, often holding the sink. Treat it like any other run.
- Its open end needs an end panel. Depending on the manufacturer this is called a dishwasher end panel or a base return panel.
- Count toe kick for the peninsula too, including its sides.

**Filler heights**
- Base fillers are short. Wall fillers are tall (36 in in the example).
- Some manufacturers only make wall fillers 42 in tall, and the installer cuts them down on site. Check the catalog.
- Put a filler against every side wall a cabinet touches.
- Put a filler where a door frame (jamb) sticks out, so drawers can open without hitting it.

**Round accessories up**
- Toe kick, scribe, crown molding and light rail all come in 8 ft lengths.
- Fillers waste material, so you often need more than the plain footage says. In the example, exactly 8 ft of toe kick was needed, but the plan priced two lengths to be safe.
- Scribe can be split. One piece can be cut in half to cover two short wall runs.
- If scribe goes unused on site, that is fine. It is cheap insurance.

**Bathroom vanities**
- Vanities have their own elevation, usually on a different sheet (the example used sheet A421, elevation K4). Use the sheet and elevation references on the drawing to find them.
- Vanity codes vary a lot by manufacturer. Examples from the video: a vanity drawer base with four drawers might be VDB12-4, and a 36 in vanity sink base with butt doors might be VSB36 BD. Always look up the real code in the manufacturer's spec guide or SKU catalog.
- Vanity sink bases use butt doors for the same reason as kitchen sink bases: no center stile blocking the plumbing.
- Each vanity needs its own fillers, scribe and toe kick.

**Repeated elevations**
- If one elevation applies to both bathrooms, enter those cabinets once for each bathroom. Two bathrooms means two sets.

**Cross-check against the unit floor plan**
- Look at the elevations and the floor plan together.
- Confirm the number of vanities, the kitchen shape (one-wall, galley, L, U, peninsula, island) and that the layout in the elevations matches the plan.
- Price everything as it is shown.

## Step 7: Produce the list

Output a clean list in order:

1. Wall cabinets (left to right, per elevation)
2. Base cabinets (left to right, per elevation)
3. End panels
4. Fillers (size, height and quantity)
5. Scribe (pieces)
6. Toe kick (pieces)
7. Vanities and bathroom items, listed per bathroom
8. **Assumptions and questions:** anything estimated, anything added that was not drawn, any code that needs checking against the catalog

## How to answer the user

- Do not invent cabinets or dimensions you cannot see. If an elevation is unclear, say so.
- Say which items came straight from the drawing and which are estimates.
- If you do not know the manufacturer, ask for it before finalizing codes.

## Source this skill was built from

- Transcripts of the YouTube videos "How To Read Architectural Drawings for Basic Cabinetry" Video 1 and the follow-up peninsula and vanity video (Multi-Family Cabinetry 101), provided by the user. This is one supplier's workflow for multi-family kitchens and baths, so practices may differ elsewhere.
- Note: the auto-generated transcripts are rough. One code in the second video was garbled ("W236 L"), so the skill does not rely on it.
