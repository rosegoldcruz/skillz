---
name: cabinet-code-decoder
description: Decodes stock kitchen and vanity cabinet codes and abbreviations (W3036, B15, SB30, VDB, TK, SM and more) and gives standard cabinet sizes. Use when someone asks what a cabinet code means, what standard dimensions are, or needs to read a spec sheet or price list.
---

# Cabinet Code Decoder

Goal: explain cabinet item codes in plain words. Define each term the first time.

Important: codes are not standardized across the industry. The patterns below are the common ones used by stock and RTA (ready-to-assemble) cabinet lines. Always check the manufacturer's catalog before trusting a code.

## Step 1: Know the standard sizes

| Cabinet | Height | Depth | Width |
|---|---|---|---|
| Base | 34.5 in (without countertop) | 24 in | 9 to 48 in, in 3 in steps |
| Wall | 30, 36 or 42 in | 12 in | 12 to 36 in |
| Tall (pantry, utility) | 84 or 96 in | 12 or 24 in | commonly 12, 24 or 36 in |
| Vanity | Varies | 21 in standard | Varies |

Installation heights:
- Base cabinet 34.5 in plus countertop is about 36 in finished.
- The gap between countertop and wall cabinets is typically 18 in.
- Base, wall and crown molding stacked together typically total 84 to 96 in.
- With 8 ft ceilings, 36 or 42 in wall cabinets work well. Taller ceilings can use stacked cabinets.

Accessible (ADA-style) kitchens use lower base heights. See `cabinet-takeoff-from-elevations`.

## Step 2: Read the code format

Common pattern: **letters for the type, then numbers for the size.** Width always comes first.

**Wall cabinets** (standard 12 in deep, so depth is left out of the code)
- W2430 = wall cabinet, 24 wide, 30 tall.
- If depth is not the standard 12 in, depth is added at the end. Example from the article: W362424 reads as a wall cabinet 36 wide, 24 tall, 24 deep.
- Cabinets over refrigerators are deeper and often use a code with an explicit depth. The article's chart shows the pattern as: code, width, height, depth (example W 36 18 24 for a refrigerator-height cabinet).

**Base cabinets** (height and depth are always the standard 34.5 and 24, so they are left out)
- B15 = base cabinet, 15 wide.
- SB30 = sink base, 30 wide.

**Vanities** (standard 21 in deep, so depth is left out)
- V30 = vanity, 30 wide.

**Three numbers like 17x40x35**: usually width, then height, then depth. Used for specialty storage.

## Step 3: Abbreviation list

**Wall cabinets**
- W = wall cabinet
- AC or AG = appliance garage
- WEA = wall end angle cabinet
- RW or WR = wall refrigerator cabinet (24 in deep)
- WER = wall easy reach
- WR = lattice wall or wine rack (note: WR is also used for refrigerator wall cabinet; see conflicts)
- PR = plate rack cabinet
- SWR = stem glass holder

**Base cabinets**
- B = base cabinet
- BFH = base with full-height door
- BWB = base with waste basket
- DB = drawer base
- SB = sink base
- BC = blind cabinet
- LS or LZ = lazy Susan (easy reach corner)
- EZ or EZR = easy reach
- DCB or DC = diagonal corner base
- BES = base end shelf
- BEC or BEA = base end angle cabinet
- MBC = microwave cabinet

**Tall**
- PC = pantry cabinet
- OC = double or single oven cabinet

**Molding and trim**
- OC = outside corner molding (note: also used for oven cabinet; see conflicts)
- LR = light rail molding
- SM or SCM = scribe molding
- QR = quarter round
- CM = crown molding
- BF = base filler
- WF = wall filler
- TK = toe kick
- FF = fluted filler
- BM = base molding

**Panels**
- TEP = refrigerator panel
- DDR or DBEP = decorative end panel

**Decorative details**
- VA = straight valance
- MD = mullion door

## Step 4: Know where codes get tricky

- **Corner cabinets** have many names for similar things. Lazy Susan alone can be LS, LZ, EZ or EZR, and a diagonal corner can be DCB or DC. Never guess. Look it up.
- **Same letters, different meaning.** OC appears for both outside corner molding and for an oven cabinet. WR appears for both wine rack and wall refrigerator cabinet. Decide by context (molding list vs tall cabinet list) and confirm with the catalog.
- **Suffixes.** Hinge side (L or R), butt doors (BD or B) and other options are added by the manufacturer. Check the catalog.
- **Check the article's own example.** The article's chart shows a refrigerator-height cabinet as 36 wide, 18 tall, 24 deep, while its text example W362424 says 24 tall. Treat refrigerator cabinet sizes as something to verify, not memorize.

## How to answer the user

- Decode the code piece by piece. Example: "W2430: W is wall, 24 is width, 30 is height. Depth is 12 because that is standard."
- State what is assumed (standard depth and height) and what should be verified.
- If the user does not say which manufacturer, say codes may differ and ask.
- Do not make up codes that are not on the list.

## Source this skill was built from

- RTA Cabinet Store blog article, "Cracking the Kitchen Cabinet Abbreviation Code" (provided by the user as a screenshot and read from it). Written for stock and RTA cabinet lines.
