# Bright Gems: DESIGN.md (trial draft)

How brightgems.app should look. Read this before changing any page.
Principles borrowed from Apple's public website style (via VoltAgent/awesome-design-md, MIT);
colors, font and personality are Bright Gems' own. Nothing of Apple's identity is used: no SF fonts,
logos, product images or wording.

## Feel
Calm, premium and warm. A parent should feel "this is trustworthy and well made" in two seconds;
the gems add the warmth. The page is a quiet gallery: big headlines, lots of air, one idea per section.

## Rules
1. **One action color.** Gem Blue `#3157d5` is used only for things you can click: buttons and
   links. Nothing decorative is blue.
2. **No decorative gradients or shadows on page chrome.** Sections are flat color. One soft shadow is
   allowed: under the sample parent report, so it reads as an object resting on the page.
3. **Sections are full-width bands that take turns:** white → mist → white → night. The color change
   is the divider; no lines between sections.
4. **Big, tight headlines.** Headlines are large with slightly negative letter-spacing. Body text is
   17px with a relaxed 1.5 line height.
5. **Gem accents are small.** The cyan, purple and gold gem colors appear only as small dots or
   markers (step numbers, skill markers, check marks), never as large fills.
6. **No emoji as icons.** Use small drawn gem-shape markers instead.
7. **Rounded, not bubbly.** Cards 18px corners; buttons are pills.
8. **Keyboard focus is always visible:** a 3px Gem Blue ring (light blue on the dark band). Never remove it.
9. **Colors come from the tokens below,** never written straight into a rule.
10. **Phone first.** Everything stacks to one column under 760px; touch targets at least 44px.

## Tokens

| Token | Value | Use |
|---|---|---|
| `ink` | `#1f1a3d` | Headlines and body text (deep indigo, softer than black) |
| `ink-soft` | `#5f5a7a` | Secondary text |
| `canvas` | `#ffffff` | Main background |
| `mist` | `#f5f4fa` | Alternate band, cards on white |
| `night` | `#1f1a3d` | Dark band (one per page, for "Safe by design") |
| `on-night` | `#ffffff` / `#c9c5e0` | Text on the dark band |
| `action` | `#3157d5` | Buttons and links only |
| `action-on-night` | `#8fb0ff` | Links on the dark band |
| `gem-cyan` / `gem-purple` / `gem-gold` | `#0aa8d8` / `#7a4be0` / `#f2b230` | Small markers only |
| `hairline` | `#e6e4ef` | Card borders, list dividers |
| `on-action` | `#ffffff` | Text on blue or dark buttons |
| `header-glass` / `night-card` / `lift-shadow` | see `styles.css` | Header background, cards on the dark band, the report's one shadow |

| Type | Size / weight / line height / tracking |
|---|---|
| Hero headline | 56px / 700 / 1.07 / -0.02em (36px on phones) |
| Section headline | 40px / 700 / 1.1 / -0.015em (30px on phones) |
| Lead | 21px / 400 / 1.45 |
| Card title | 19px / 600 / 1.3 |
| Body | 17px / 400 / 1.5 |
| Caption, fine print | 14px / 400 / 1.45 |

Font: **Poppins** (already on the site and in the books), weights 400, 500, 700.
Spacing: sections 96px top and bottom (64px on phones); content width 980px.
