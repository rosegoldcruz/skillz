---
name: cabinet-bid-takeoff-method
description: A careful, evidence-based method for taking off cabinets from a full architectural plan set and getting ready to price a bid. Covers inventorying the drawings, solving each run, tracking what is confirmed vs guessed, SKU matching, and gross margin math. Use when someone wants a cabinet bid or takeoff built from plans.
---

# Cabinet Bid Takeoff Method

Goal: produce a takeoff the user can trust, and be honest about what is not proven. This skill gives the method. It does not by itself produce a verified bid. Use it together with `cabinet-takeoff-from-elevations` and `cabinet-code-decoder`.

## Step 1: Inventory the whole drawing package first

Before counting anything, list what is in the set:
- Printed sheet numbers, titles and revisions (read them off the title block, not from file names)
- Plans, elevations, legends, schedules, notes, symbols, detail references

Rules:
- **Not found does not mean not present.** If a legend or schedule seems missing, search every sheet before saying so.
- Do not mix up sheets with similar numbers (an A500 is not an A501). Confirm identity from the printed title.
- Do not guess a unit type from a sheet number. Read the sheet title.

## Step 2: Read in a fixed order

- Kitchens first, bathrooms last.
- Keep each physical run in left-to-right order.
- Separate these groups: base, wall, tall, vanity, openings, fillers, panels, trim, accessories.

## Step 3: Dimensions come from labels first

1. Use labeled dimensions on the drawing first.
2. Use scaled measurements only as a backup, and mark them as scaled.
3. Solve every run as an equation:

   **cabinets + appliance openings + fillers and panels + leftover = total run length**

   The leftover should be near zero. If it is not, something is missing or wrong. Flag it.

Openings are not cabinets:
- A 24 in opening suggests a dishwasher, but width alone does not prove it. Look for a legend or label.
- Do not price an opening as a purchasable cabinet.

## Step 4: Keep three decisions separate

For every cabinet, verify these independently:
1. **Geometry:** is the width and position right?
2. **Function:** is it a sink base, drawer base, wall cabinet, and so on?
3. **SKU fit:** does a real catalog item match the size and specification?

A match on one does not confirm the others. A SKU that appears in a price list is not yet a verified dimensional match. Do not invent a SKU or quietly swap one in. If nothing fits, say so and list it as unresolved.

## Step 5: Label every claim

Tag each item with one of four levels, and note where it came from (sheet and location on the sheet):

| Level | Meaning |
|---|---|
| Confirmed | Directly stated on the drawing |
| Derived | Calculated from confirmed items (for example from the run equation) |
| Inferred | A reasonable guess from context |
| Unresolved | Cannot be determined yet |

Never report inferred items as confirmed. Never quietly drop unresolved items from the list.

## Step 6: Specifications

- The project's drawings and specs override any default.
- Check these: framed or frameless, box material, door material and style, finish, hinges, slides, drawer construction, ADA or accessible unit requirements, installation accessories.
- If the user has a usual spec they quote, treat it as the starting default only. Confirm it against the project documents before pricing.

## Step 7: Pricing rules

- **Gross margin is not markup.** To reach a target gross margin, divide: selling price = cost ÷ (1 − margin).
  - Example: a 15% gross margin gives cost ÷ 0.85. A 15% markup (cost × 1.15) gives a different, lower price.
- Apply only the margin rule the user has approved for that category. Ask if unsure.
- Track supply and installation separately.
- Historical quotes are quotes, not verified job costs or outcomes. Use them as a sanity check, not as proof.
- If the user has an existing pricing workbook, its lookup logic is the source of truth. Do not assume your own recalculation matches it. Reconcile them before presenting totals.

## Step 8: Report honestly

When finishing, give:
1. The takeoff list with confidence tags.
2. Run equations with any leftovers that did not close.
3. Unresolved items and questions.
4. A plain statement of what is verified and what is not.

Do not call a bid "verified" or "ready to send" unless every line is confirmed or the user has accepted the remaining risk. Wait for the user's approval before anything goes to a customer.

## Known failure modes to guard against

- Confusing similar sheet numbers or unit types.
- Missing a legend that was actually in the set.
- Treating a matching width as proof of a matching cabinet function.
- Scoring your own accuracy with a method that flatters the result. Measure against exact function and width, and report partial matches as partial.

## Source

- Method notes written by the user (their own process and lessons learned). Specific project results, quote counts and totals were left out of this skill on purpose. Keep those in the user's own records.
