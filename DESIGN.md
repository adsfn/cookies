---
name: Crumb & Co.
description: Good-for-you cookies. A warm cream-and-chocolate recipe site where each cookie brings its own colour.
colors:
  cream: "#fbf3e6"
  chocolate-ink: "#3b2418"
  cocoa-muted: "#7a5b48"
  biscuit-line: "#e4cfb2"
  night-crust: "#1d1410"
  night-ink: "#f6e7d3"
  night-muted: "#c4a68c"
  night-line: "#3a2a20"
  night-badge: "#4a2a1a"
  curtain-caramel: "#d9a566"
  accent-oat-date: "#e8b36a"
  accent-almond-butter: "#f0c98a"
  accent-dark-cacao: "#b9825c"
  accent-pumpkin-spice: "#f2a65a"
  accent-coconut-lime: "#b8d98a"
  accent-blueberry-walnut: "#a9b4e6"
typography:
  hero:
    fontFamily: "Fraunces, Georgia, serif"
    fontSize: "clamp(3.4rem, 14vw, 10.5rem)"
    fontWeight: 700
    lineHeight: 0.88
  display:
    fontFamily: "Fraunces, Georgia, serif"
    fontSize: "clamp(2.9rem, 9vw, 7.4rem)"
    fontWeight: 700
    lineHeight: 0.92
    letterSpacing: "-0.01em"
  headline:
    fontFamily: "Fraunces, Georgia, serif"
    fontSize: "clamp(2rem, 6vw, 3.2rem)"
    fontWeight: 700
    lineHeight: 1.05
  title:
    fontFamily: "Fraunces, Georgia, serif"
    fontSize: "clamp(1.4rem, 3.4vw, 2rem)"
    fontWeight: 600
    lineHeight: 1.25
  brand:
    fontFamily: "Fraunces, Georgia, serif"
    fontSize: "1.35rem"
    fontWeight: 700
    lineHeight: 1
  card-title:
    fontFamily: "Fraunces, Georgia, serif"
    fontSize: "1.45rem"
    fontWeight: 700
    lineHeight: 1.15
  small-title:
    fontFamily: "Fraunces, Georgia, serif"
    fontSize: "1.25rem"
    fontWeight: 700
    lineHeight: 1.15
  stat:
    fontFamily: "Fraunces, Georgia, serif"
    fontSize: "clamp(2.2rem, 4.5vw, 3.6rem)"
    fontWeight: 700
    lineHeight: 1
  body-lg:
    fontFamily: "DM Sans, system-ui, sans-serif"
    fontSize: "1.05rem"
    fontWeight: 400
    lineHeight: 1.7
  body:
    fontFamily: "DM Sans, system-ui, sans-serif"
    fontSize: "1rem"
    fontWeight: 400
    lineHeight: 1.55
  body-sm:
    fontFamily: "DM Sans, system-ui, sans-serif"
    fontSize: "0.95rem"
    fontWeight: 400
    lineHeight: 1.5
  caption:
    fontFamily: "DM Sans, system-ui, sans-serif"
    fontSize: "0.8rem"
    fontWeight: 400
    lineHeight: 1.3
  label:
    fontFamily: "DM Sans, system-ui, sans-serif"
    fontSize: "0.75rem"
    fontWeight: 600
    lineHeight: 1
    letterSpacing: "0.14em"
  button:
    fontFamily: "DM Sans, system-ui, sans-serif"
    fontSize: "0.85rem"
    fontWeight: 600
    lineHeight: 1
rounded:
  hairline: "2px"
  brand: "6px"
  tooltip: "14px"
  card: "20px"
  pill: "99px"
  circle: "50%"
spacing:
  gutter: "clamp(20px, 4vw, 48px)"
  gutter-wide: "clamp(20px, 6vw, 100px)"
  row: "13px"
  grid-gap: "18px"
  card-pad: "24px"
  section-y: "clamp(56px, 10vh, 110px)"
components:
  button-solid:
    backgroundColor: "{colors.chocolate-ink}"
    textColor: "{colors.cream}"
    typography: "{typography.button}"
    rounded: "{rounded.pill}"
    padding: "16px 28px"
  button-outline:
    backgroundColor: "{colors.cream}"
    textColor: "{colors.chocolate-ink}"
    typography: "{typography.button}"
    rounded: "{rounded.pill}"
    height: "46px"
    padding: "0 18px"
  button-outline-hover:
    backgroundColor: "{colors.chocolate-ink}"
    textColor: "{colors.cream}"
  button-icon:
    backgroundColor: "{colors.cream}"
    textColor: "{colors.chocolate-ink}"
    rounded: "{rounded.circle}"
    size: "46px"
  segmented-option-selected:
    backgroundColor: "{colors.chocolate-ink}"
    textColor: "{colors.cream}"
    rounded: "{rounded.pill}"
    height: "40px"
  pill-tag:
    textColor: "{colors.chocolate-ink}"
    rounded: "{rounded.pill}"
    padding: "5px 12px"
  card-outline:
    backgroundColor: "{colors.cream}"
    rounded: "{rounded.card}"
    padding: "{spacing.card-pad}"
  card-cookie:
    backgroundColor: "{colors.accent-oat-date}"
    textColor: "{colors.chocolate-ink}"
    rounded: "{rounded.card}"
    padding: "20px"
  tooltip:
    backgroundColor: "{colors.chocolate-ink}"
    textColor: "{colors.cream}"
    rounded: "{rounded.tooltip}"
    padding: "10px 14px"
---

# Design System: Crumb & Co.

## Overview

**Creative North Star: "Warm Cream, Chocolate Ink, One Cookie at a Time"**

Crumb & Co. looks like a bakery printed on warm paper. The page is cream, everything is set in a deep chocolate brown, and headings use Fraunces, a soft high-contrast serif that does most of the expressive work. Depth and colour come from the cookies, not from the interface. Each recipe shows one 3D cookie on a large soft disc of that cookie's accent colour, and that accent tints the whole recipe page.

The interface around the cookie is quiet and generous. It is single-column and centred on the landing wheel, then moves to an editorial two-column recipe layout with thin biscuit-coloured rules, small uppercase labels and large serif numbers. Motion is cinematic but brief. A caramel curtain lifts on load, lines of headings rise out of masks, and the recipe page slides up as a sheet. All of it falls back to still when the visitor prefers reduced motion.

There is a full dark mode ("night bake"). Cream becomes a near-black crust and the ink becomes a warm off-white, while the cookie accents stay the same.

**Key Characteristics:**
- Two-colour base (cream and chocolate) with one cookie accent at a time.
- Fraunces for anything a person reads as a name or a number; DM Sans for everything else.
- Hairline rules and outlines rather than filled panels.
- Pills, circles and 20px cards make every control soft.
- Large type and a single centred hero object per screen.

## Colors

A warm, low-saturation bakery base with six fruit- and spice-derived accents, one per cookie.

### Primary
- **Chocolate Ink** (chocolate-ink): All text, outlines, focus rings and the one solid button style. It is also the fill of the selected option in segmented controls and of tooltips.

### Secondary: the cookie accents
Each recipe defines an accent (`a` in the recipe data). It drives `--acc` on the landing glow and `--dacc` on the recipe page, and it fills that cookie's card under "More cookies".
- **Oat Gold** (accent-oat-date): Oat & Date. It is also the default `--acc` before any cookie is chosen, so it shows on About and in link underlines.
- **Almond Sand** (accent-almond-butter): Almond Butter.
- **Cacao Clay** (accent-dark-cacao): Dark Cacao.
- **Pumpkin Amber** (accent-pumpkin-spice): Pumpkin Spice.
- **Lime Leaf** (accent-coconut-lime): Coconut Lime.
- **Blueberry Haze** (accent-blueberry-walnut): Blueberry Walnut.

Text on any accent fill is always Chocolate Ink (#3b2418), in both themes.

### Tertiary
- **Curtain Caramel** (curtain-caramel): Only the full-screen intro curtain that lifts on first load.

### Neutral
- **Cream** (cream): The page background, also the `theme_color` in the manifest.
- **Cocoa Muted** (cocoa-muted): Secondary text, uppercase section labels, notes and counters.
- **Biscuit Line** (biscuit-line): Every hairline rule, card outline, pill outline and the segmented control's track.
- **Night Crust / Night Ink / Night Muted / Night Line** (night-*): The dark-theme swaps for cream, chocolate ink, cocoa muted and biscuit line.
- **Night Badge** (night-badge): Dark-theme badge fill.

### Named Rules
**The Page Wears Its Cookie Rule.** A recipe page takes its accent from its own cookie: the hero disc, the swap arrow badges and the step numbers (accent mixed 50% with ink). No other cookie's accent appears on that page except on its own card in "More cookies".

**The Ink On Accent Rule.** Accent fills always carry Chocolate Ink text. They are never white and never flipped in dark mode.

## Typography

**Display Font:** Fraunces (with Georgia, serif), weights 500 and 700, optical size 9–144
**Body Font:** DM Sans (with system-ui, sans-serif), weights 400 and 600

**Character:** A soft, generous serif for names and numbers, paired with a clean geometric sans for instructions. The serif feels baked; the sans keeps the kitchen steps legible.

### Hierarchy
- **Hero** (700, clamp(3.4rem, 14vw, 10.5rem), 0.88): The cookie name on a recipe page. Set with `nowrap` and fitted to the viewport (`--fs`), capped at 34svh.
- **Display** (700, clamp(2.9rem, 9vw, 7.4rem), 0.92, -0.01em): The About hero. Italic 500 is used for emphasis words.
- **Headline** (700, clamp(2rem, 6vw, 3.2rem), 1.05): The cookie tagline on the landing wheel, and closing calls like "Ready to bake?".
- **Title** (600, clamp(1.4rem, 3.4vw, 2rem), 1.25): Lead sentences on recipe and About sections.
- **Card Title** (700, 1.45rem, 1.05–1.15): Swap names, ingredient cards and cookie card names.
- **Brand** (700, 1.35rem, 1): The header wordmark.
- **Small Title** (700, 1.25rem, 1.15): Team names, "Look closer" items, avatar initials and the cook-mode title.
- **Stat** (700, clamp(2.2rem, 4.5vw, 3.6rem), 1): Prep and bake time, oven temperature, cookie count and nutrition figures.
- **Body Large** (400, 1.05rem, 1.7): About prose, the method list and cook-mode ingredient rows.
- **Body** (400, 1rem; 1.5–1.7 line height): Descriptions and method steps. Long prose is held to about 60ch.
- **Body Small** (400–600, 0.95rem, 1.5): Footer text, header links, swap notes, the counter and other secondary text.
- **Caption** (400–600, 0.8rem): Pills, card index numbers, notes and the footer's © line.
- **Label** (600, 0.75rem, 0.14em tracking, uppercase, Cocoa Muted): Every section heading ("The recipe", "Healthy swaps", "You'll need"). 0.75rem (12px) is the smallest text on the site.

### Named Rules
**The Twelve-Pixel Floor Rule.** No text is set below 0.75rem. New sizes join one of the steps above rather than adding an in-between value.

**The Serif Counts Rule.** Numbers a baker reads at a glance (times, temperature, cookie count, nutrition, step numbers like "01") are set in Fraunces 700. Quantities inside the ingredient list stay in DM Sans 600 with tabular numerals, so they line up.

**The Quiet Label Rule.** Section headings are small uppercase DM Sans in Cocoa Muted, never large. Size and weight go to the content beneath them.

## Layout

- **Landing:** a full-viewport, non-scrolling column made of a header, the wheel stage that fills the remaining height, and the info block below (centred, max 620px). Height uses `100dvh` minus safe-area insets.
- **Recipe page:** a fixed full-screen sheet that slides up over the wheel. The first part is a sticky scroll scene (420svh desktop, 300svh mobile) in which the giant name, the cookie and its disc move as you scroll. Below it come editorial sections separated by hairline top borders.
- **Recipe body:** a two-column grid (5fr ingredients, 7fr method, gap clamp(32px, 6vw, 96px)) that becomes one column below 700px.
- **Card grids:** `auto-fit` with min tracks of 190–240px and 16–18px gaps. "More cookies" is a horizontal scroll-snap row of 3:4 cards (min(72vw, 280px) wide).
- **Gutters:** `clamp(20px, 4vw, 48px)` for chrome and recipe sections; `clamp(20px, 6vw, 100px)` for About and the ingredient index. Content caps at 1200–1300px.
- **Breakpoints:** one main break at 699/700px, plus 380px for the narrowest phones (the header brand is hidden there).
- Safe-area insets are respected on every fixed or sticky edge.

## Elevation & Depth

The interface is flat. Depth belongs to the cookie: the WebGL model (or its SVG fallback, with a `drop-shadow(0 14px 14px rgba(59,36,24,.25))`) sits on a large soft accent disc at 22–40% opacity. Layering is by z-order and full-screen sheets, not by raised surfaces.

### Shadow Vocabulary
- **Cookie drop** (`filter: drop-shadow(0 14px 14px rgba(59,36,24,.25))`): The 2D cookie fallback only.
- **Tooltip lift** (`box-shadow: 0 6px 18px rgba(0,0,0,.18)`): The hover tooltip on the wheel.

### Named Rules
**The Flat Chrome Rule.** Buttons, cards and panels have no shadow. Hover states change fill or move up 2–6px; they never add a shadow.

## Shapes

Everything is round or softly rounded. Controls are pills (99px) or circles (46px icon buttons, 56px avatars, 30px swap badges). Cards are 20px. The tooltip is 14px and tilted -2°. Big soft circles are the recurring motif: the landing glow, the recipe disc, the About hero disc, and a faint white circle clipped into the corner of ingredient cards. The only sharp shape is the small rotated diamond bullet in About lists.

## Components

### Buttons
Outlined and soft; they fill with ink on hover.
- **Outline** (`button-outline`): 1.5px Chocolate Ink border on Cream, a pill 46px tall. Hover fills with ink and turns the text cream. Used for "Jump to recipe", "Back to top" and the footer button.
- **Icon** (`button-icon`): A 46px circle with the same outline-to-fill behaviour. Used for prev/next on the wheel and back on the sheet.
- **Solid** (`button-solid`): An ink pill with cream text. It is the single primary action on a screen ("See the recipe", and the About page's closing call to action). Hover lifts it 2px or drops opacity to 0.88; press scales it to 0.97.
- **Focus:** a 2px Chocolate Ink outline, offset 3px, on every interactive element.
- **Press:** `scale(.94–.97)`.

### Segmented control (batch size)
A pill track with a Biscuit Line border and 3px padding. Options are 40px tall and at least 44px wide, in DM Sans 600 with tabular numerals. The selected option is an ink pill with cream text; unselected options get a 10% ink wash on hover. It uses `role="radio"` and `aria-checked`.

### Chips
**Pill tags:** a Biscuit Line outline, 99px radius, 5px 12px padding, 0.82rem DM Sans 600. They show the dietary and benefit tags under each cookie.

### Cards / Containers
- **Outline card** (swaps, About, team): a 1px Biscuit Line border, 20px radius and 22–24px padding, on Cream. The content is an uppercase label, then a Fraunces title, then muted body text below a hairline.
- **Cookie card** ("More cookies"): filled with that cookie's accent, a 20px radius and a 3:4 shape. It holds a small "02" index at the top, a live 3D cookie in the middle, and the Fraunces name and tagline at the bottom. It rises 6px on hover.
- **Ingredient card:** filled with the page accent, 20px radius, at least 210px tall, with a white circle at 18% opacity clipped into the top-right corner.

### Lists
Ingredient and method rows are separated by Biscuit Line top borders with 13px vertical padding. Method steps carry a leading-zero counter ("01") in Fraunces 700, coloured with the accent mixed into the ink.

### Navigation
The header is the Fraunces brand wordmark (1.35rem, 700) on the left, with text links and a tabular "01 / 06" counter on the right. Text links are DM Sans 600 at 0.9rem; on hover a 2px accent underline grows from the left. In the footer, the current page shows as muted text followed by "· reading".

### Signature: the cookie wheel
A drag, scroll or swipe carousel of 3D cookies on a soft accent glow. It changes cookie with a short fade-and-rise of the info block (0.18s) and a 0.6s colour cross-fade of the glow. Keyboard focus is shown as an inset 2px ink ring on the stage. Clicking the cookie or "See the recipe" slides up the recipe sheet (0.9s, `cubic-bezier(.76,0,.24,1)`).

## Do's and Don'ts

### Do:
- **Do** keep the base to Cream and Chocolate Ink, and let the current cookie's accent be the only colour on its page.
- **Do** put Chocolate Ink (#3b2418) text on every accent fill, in light and dark mode alike.
- **Do** set names and glanceable numbers in Fraunces 700, and section labels in small uppercase DM Sans 600 with 0.14em tracking in Cocoa Muted.
- **Do** separate content with 1px Biscuit Line hairlines and 20px outlined cards rather than shaded panels.
- **Do** use the 2px ink focus ring with a 3px offset on every interactive element.
- **Do** make interactive controls at least 44px tall, and buttons and icon buttons 46px.
- **Do** give every reveal or transform animation a `prefers-reduced-motion` fallback that shows the end state at once.
- **Do** use the house ease `cubic-bezier(.22,1,.36,1)` for reveals and `cubic-bezier(.76,0,.24,1)` for full-screen sheets and the curtain.

### Don't:
- **Don't** add drop shadows to buttons, cards or panels; depth belongs to the cookie.
- **Don't** use white text on an accent or invert accents in dark mode.
- **Don't** mix several cookie accents on one recipe page outside the "More cookies" row.
- **Don't** use sharp corners on controls or cards; everything is a pill, a circle or a 20px radius.
- **Don't** introduce a third typeface.
