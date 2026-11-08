---
name: Isra Brini Portfolio (Ligne Six)
description: A Paris Métro tile wall where each of six projects is a coloured line, with a glossy resin 3D token per line.
colors:
  enamel-navy: "#1B2452"
  navy-hover: "#2C3A7E"
  muted-navy: "#4B5578"
  tile-ground: "#F4F5F1"
  grout: "#D9DCD4"
  tile-white: "#FFFFFF"
  line-1-yellow: "#FFCD00"
  line-1-yellow-hover: "#FFDD47"
  line-2-blue: "#1F66B3"
  line-3-green: "#247A4D"
  line-4-magenta: "#C04191"
  line-5-orange: "#F0801F"
  line-6-violet: "#7B54C2"
typography:
  display:
    fontFamily: "Archivo, Helvetica Neue, Arial, system-ui, sans-serif"
    fontSize: "clamp(2.2rem, 4vw, 3.5rem)"
    fontWeight: 800
    lineHeight: 1.02
    letterSpacing: "-0.03em"
  headline:
    fontFamily: "Archivo, Helvetica Neue, Arial, system-ui, sans-serif"
    fontSize: "clamp(1.8rem, 3.4vw, 2.6rem)"
    fontWeight: 800
    lineHeight: 1.08
    letterSpacing: "-0.03em"
  title:
    fontFamily: "Archivo, Helvetica Neue, Arial, system-ui, sans-serif"
    fontSize: "clamp(1.15rem, 1.7vw, 1.4rem)"
    fontWeight: 800
    lineHeight: 1.12
    letterSpacing: "-0.02em"
  body:
    fontFamily: "Archivo, Helvetica Neue, Arial, system-ui, sans-serif"
    fontSize: "17px"
    fontWeight: 400
    lineHeight: 1.55
  label:
    fontFamily: "Archivo, Helvetica Neue, Arial, system-ui, sans-serif"
    fontSize: "0.78rem"
    fontWeight: 700
    lineHeight: 1.4
rounded:
  sm: "6px"
  md: "10px"
  lg: "14px"
  pill: "999px"
  roundel: "50%"
spacing:
  xs: "6px"
  sm: "12px"
  md: "20px"
  lg: "32px"
  gutter: "clamp(16px, 3.4vw, 32px)"
components:
  button-primary:
    backgroundColor: "{colors.enamel-navy}"
    textColor: "{colors.tile-white}"
    rounded: "{rounded.md}"
    height: "48px"
    padding: "0 22px"
  button-primary-hover:
    backgroundColor: "{colors.navy-hover}"
  button-ghost:
    backgroundColor: "{colors.tile-white}"
    textColor: "{colors.enamel-navy}"
    rounded: "{rounded.md}"
    height: "48px"
    padding: "0 22px"
  button-ghost-hover:
    backgroundColor: "{colors.enamel-navy}"
    textColor: "{colors.tile-white}"
  button-sign:
    backgroundColor: "{colors.line-1-yellow}"
    textColor: "{colors.enamel-navy}"
    rounded: "{rounded.md}"
    height: "48px"
  line-tile:
    backgroundColor: "{colors.tile-white}"
    textColor: "{colors.enamel-navy}"
    rounded: "{rounded.md}"
    padding: "14px 18px 12px"
  line-tile-featured:
    backgroundColor: "{colors.line-1-yellow}"
    textColor: "{colors.enamel-navy}"
    rounded: "{rounded.md}"
    padding: "16px 22px"
  kpi-panel:
    backgroundColor: "{colors.enamel-navy}"
    textColor: "{colors.tile-white}"
    rounded: "{rounded.sm}"
    padding: "4px 16px"
  roundel:
    backgroundColor: "{colors.line-2-blue}"
    textColor: "{colors.tile-white}"
    rounded: "{rounded.roundel}"
    size: "34px"
  station-sign:
    backgroundColor: "{colors.enamel-navy}"
    textColor: "{colors.tile-white}"
    rounded: "{rounded.sm}"
    height: "60px"
  tile:
    backgroundColor: "{colors.tile-white}"
    textColor: "{colors.enamel-navy}"
    rounded: "{rounded.md}"
  dialog-sheet:
    backgroundColor: "{colors.tile-ground}"
    textColor: "{colors.enamel-navy}"
    rounded: "{rounded.lg}"
---

# Design System: Isra Brini Portfolio (Ligne Six)

## Overview

**Creative North Star: "The Tile Wall"**

The page is a Paris Métro tile wall and each project is a coloured line. A bevelled white running-bond ceramic ground with faint grout carries deep enamel-navy signs with white caps, six re-tuned line colours used as roundels and fills, and one glossy resin 3D token per project. The mood is public signage: legible at a glance, confident, a little playful, never decorative for its own sake. It rejects the screenshot card grid under a hero with a floating blob.

Density is high on purpose. All six projects are visible in the first viewport, each leading with a numbered roundel, a name, a result line and a quiet category tag. Colour is assigned by meaning (line = project) rather than by mood, so the palette is saturated but disciplined: navy and white do the structural work, line colours mark identity.

The first viewport stacks the intro band above a full-width board by design: headline and status on the left, lede with CV and Email buttons on the right, then the board below so all six full-width tiles fit above the fold. Side-by-side hero and board was considered and rejected for that reason.

**Key Characteristics:**
- Tile-wall ground: pale ceramic with grout lines, bevelled white tiles.
- Navy enamel signs (header, KPI panel, contact terminus) with white or yellow text.
- Six line colours, each paired with the ink colour that passes on it.
- Archivo, bold and slightly wide, as signage type.
- Glossy resin 3D tokens rendered with three.js, pinned over each tile, resting partly outside it.
- Soft, low, navy-tinted shadows; no hard offsets.

## Colors

A cool ceramic neutral ground, one deep enamel navy, and six saturated line colours that identify projects.

### Primary
- **Enamel Navy** (`enamel-navy`): text, signs (header, KPI panel, contact band, date pills), primary buttons, focus rings, scrollbar. The structural colour of the system.
- **Line 1 Yellow** (`line-1-yellow`): the featured Juriq line fill, the CV button on navy, the headline highlight mark, selection, the email link on navy, the "seeking" band. Carries navy text.

### Secondary (the six lines)
- **Line 2 Blue** (`line-2-blue`): Respiratory Sound Classification. White roundel text.
- **Line 3 Green** (`line-3-green`): Plant Disease Detection; also the availability status dot. White text.
- **Line 4 Magenta** (`line-4-magenta`): SmartSight. White text.
- **Line 5 Orange** (`line-5-orange`): Social Media Trend Analyzer. Navy text (white fails on it).
- **Line 6 Violet** (`line-6-violet`): Mentora. White text.

### Neutral
- **Tile Ground** (`tile-ground`): page ground and dialog surface, under the tile pattern.
- **Grout** (`grout`): 1px tile edges, dividers, inset borders, flow rail.
- **Tile White** (`tile-white`): tiles, metric cards, status pill, ghost buttons.
- **Muted Navy** (`muted-navy`): secondary copy, result lines, captions.
- **Navy Hover** (`navy-hover`) and **Line 1 Yellow Hover** (`line-1-yellow-hover`): hover steps for navy and yellow buttons.

### Named Rules
**The Line Pairing Rule.** Every line colour travels with one ink colour fixed by contrast: navy on yellow and orange, white on blue, green, magenta and violet. Set per element via the `--pc` / `--pc-ink` pair; never mix.

**The One Line, One Project Rule.** A line colour means one project. Do not use a line colour as generic decoration (the exceptions in the build are the yellow highlight, CTA and seeking band, and the three about-section dots, which are accents rather than project identity).

## Typography

**Display Font:** Archivo (with Helvetica Neue, Arial, system-ui)
**Body Font:** Archivo
**Label/Mono Font:** none; tabular-nums on numerals.

**Character:** Archivo as signage: heavy weight (800) and widened (`font-stretch` 108-112%) for names and station caps, tightly tracked at large sizes. Body copy stays regular and normal width.

### Hierarchy
- **Display** (800, clamp(2.2rem, 4vw, 3.5rem), 1.02): the hero headline; featured line name goes up to clamp(2.3rem, 3.9vw, 3.3rem) at -0.04em.
- **Headline** (800, clamp(1.8rem, 3.4vw, 2.6rem), 1.08): section titles, followed by a 6px navy rule; contact headline up to 3.2rem.
- **Title** (800, clamp(1.15rem, 1.7vw, 1.4rem), 1.12): project names on tiles; job and about titles at 1.05-1.15rem.
- **Body** (400, 17px, 1.55): copy; lede 1.06rem capped at 46ch; dialog prose capped at 62ch.
- **Label** (700, 0.78-0.95rem): category tags, dates, button text (1rem, 700), KPI captions (0.84rem). Station name is uppercase 800 at 112% width.

### Named Rules
**The Signage Weight Rule.** Names, numerals and station caps are 800; everything explanatory is 400-600. No middle-weight display.

## Layout

A 1280px wrapper with a fluid gutter (16px to 32px). The hero is an intro band (1.35fr / 1fr, aligned to the end) stacked above a full-width 6-column board: the featured Juriq line spans all six columns (cube-cluster token, text, KPI panel), then three 2-column tiles, then two 3-column tiles. Gaps are 12px. Below: experience rows (150px / 1fr / 1.5fr), a three-column about grid, and a full-bleed navy contact band that acts as the terminus with a six-roundel route strip.

Responsive: at 1000px the intro stacks and the board becomes 2 columns (featured spans both, KPIs drop below). At 640px the board is single column, nav and station subtitle hide, buttons flex to fill. On short desktop viewports (max-height 840px) padding, tile height and heading sizes tighten so all six lines still fit above the fold. Without WebGL (`no-gl`), tokens are hidden and tiles collapse to text-only.

## Elevation & Depth

Hybrid: bevel plus soft ambient lift on tiles, true 3D depth only in the tokens. Tiles read as ceramic through an inset 1px grout edge, a white inset top highlight and a faint navy inset bottom edge. A low, wide navy-tinted drop shadow seats them on the wall. Hover lifts a tile 4px and swaps the grout edge for a 2.5px line-colour edge.

### Shadow Vocabulary
- **Tile bevel** (`box-shadow: inset 0 0 0 1px grout, inset 0 1.5px 0 #fff, inset 0 -3px 0 rgba(27,36,82,.05), 0 12px 22px -16px rgba(27,36,82,.45)`): white tiles and `.tile` surfaces.
- **Featured tile** (`inset 0 0 0 1px rgba(27,36,82,.16), inset 0 2px 0 rgba(255,255,255,.55), inset 0 -4px 0 rgba(27,36,82,.08), 0 18px 30px -18px rgba(27,36,82,.6)`): the yellow line.
- **Hover lift** (`inset 0 0 0 2.5px line-colour, ..., 0 22px 30px -18px rgba(27,36,82,.55)`): with translateY(-4px).
- **Dialog** (`0 30px 80px rgba(27,36,82,.4)`, backdrop `rgba(27,36,82,.62)`).
- **Resin token material** (three.js `MeshPhysicalMaterial`): roughness 0.24, metalness 0, clearcoat 1, clearcoatRoughness 0.1, envMapIntensity 1.05, lit by RoomEnvironment plus a white directional key (1.6) and ambient (0.35). Palette limited to navy, white and the line colours; a translucent navy disc (opacity 0.55, roughness 0.05) is used as a lens-like detail.

### Named Rules
**The Soft Seat Rule.** Shadows are blurred, negative-spread and navy-tinted. Depth beyond that belongs to the 3D tokens, not to CSS.

## Shapes

Soft-cornered ceramic: 10px on tiles, buttons and cards, 6px on signs and the KPI panel, 14px on the dialog, full pills for tags, status and dates, and perfect circles for roundels. Rounded-box geometry (RoundedBoxGeometry, radius about 0.07-0.1 on unit-scale cubes) and torus rings echo the tile bevel in the tokens. Borders are 1px grout (tiles) or 2px navy (ghost buttons, dialog close).

## Components

### Buttons
- **Shape:** 10px corners, 48px minimum height (40px small), 2px border, 700 weight.
- **Primary:** navy fill, white text, 0 22px padding; hover lightens to navy-hover. On navy bands (header, contact) it becomes yellow fill with navy text, hover to yellow-hover.
- **Ghost:** 70% white fill, navy border and text; hover inverts to navy fill and white text. On the contact band: transparent, white border, hover to white fill.
- **Press:** translateY(1px) scale(.99). Colour transitions 0.2s on the expo-out ease (cubic-bezier(.16,1,.3,1)).

### Cards / Containers
- **Tile:** white, 10px, the Tile bevel shadow; used for experience rows and about panels.
- **Dialog sheet:** tile-ground surface, 14px, up to 920px wide, full-screen on mobile. A line-colour band opens it (roundel inverted, name at display size), followed by metric cards with a coloured bottom edge.

### Navigation
- Sticky 60px navy station sign: boxed station name (uppercase, 1.5px translucent white border, 6px corners), links in 82% white that brighten on hover, the current link in yellow, CV button in yellow at the right. Under 640px the links and subtitle hide.

### Line tile (signature)
A button-as-tile: numbered roundel, name, result line, category pill and a "view" arrow in a two-column grid, with the 3D token pinned in the right column and allowed to overlap the tile edge. White by default, line-colour edge on hover and focus. The featured variant is full-width yellow with an inverted navy roundel (40px) and a navy KPI panel of three result rows.

### Roundel
A circular badge (default 34px, scaled 20px to 52px) in `--pc` with `--pc-ink` numerals at 52% of its diameter, tabular numerals. Also used as the flow step marker in the dialog (fills with the line colour when active) and in the contact route strip.

### Station sign and KPI panel
Navy enamel plates with white text: the header sign and the KPI panel (rows split by 20% white rules, numerals in tabular 800 weight).

## Do's and Don'ts

### Do:
- **Do** pair each line colour with its fixed ink colour via `--pc` / `--pc-ink`.
- **Do** keep navy `#1B2452` as the only text and sign colour; use muted navy for secondary copy.
- **Do** give new surfaces the tile bevel and soft seat shadow, and 10px corners.
- **Do** build new 3D tokens from `MeshPhysicalMaterial` with the shared resin settings and the navy, white and line-colour palette.
- **Do** keep the page usable without WebGL and honour `prefers-reduced-motion` (transitions and animations off).
- **Do** keep focus visible: 3px navy outline, switching to yellow on navy bands.

### Don't:
- **Don't** copy RATP's line colours or marks; the six colours are re-tuned originals.
- **Don't** use white text on yellow or orange, or navy text on blue, green, magenta or violet.
- **Don't** replace the board with a screenshot card grid or a hero with a floating blob.
- **Don't** use hard offset shadows, or a second typeface alongside Archivo.
- **Don't** use a line colour as generic decoration where it should identify a project.

