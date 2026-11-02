# Aetheria Visual Style Guide

A description of the look used on the Aetheria website. Use it to keep future pages, Discord graphics, and game UI consistent.

## Concept

Aetheria's logo is four blue tiles stacked like steps. The whole site builds on that idea: dark space, one blue gradient, and a staircase layout that rises and steps across the page. The look is clean and modern, and it lets the logo be the loudest thing.

## Colors

| Name | Hex | Use |
|---|---|---|
| Black | `#000000` | Page background. Matches the logo's own background. |
| Snow | `#f4f8ff` | Main text and headings. |
| Slate | `#8da2c4` | Secondary text, nav links, captions. |
| Sky | `#3bb4ff` | Light end of the gradient, focus outlines, hover accents. |
| Cobalt | `#0560fb` | Dark end of the gradient. |
| Deep Navy | `#12233f` | Dividers and quiet borders. |
| Ink | `#00112e` | Text on top of the blue gradient buttons. |

**Signature gradient:** Sky to Cobalt, `linear-gradient(90deg, #3bb4ff, #0560fb)`. It's used on the primary button and the step markers (top to bottom). Don't use it on large backgrounds.

Blue is the only accent color. Everything else is black, white, and gray-blue.

## Typography

- **Typeface:** Sora (Google Fonts), weights 300 to 700, used for all text. The logo's wordmark is a wide geometric sans, and Sora has the same feel.
- **Headlines:** Bold (700), tight line height (about 1.02 for the hero, 1.15 for section titles), and slightly negative letter spacing so large type feels compact.
- **Hero headline:** fluid size from 2.8rem to 5.4rem.
- **Section headlines:** fluid size from 1.8rem to 2.8rem.
- **Body:** regular weight (400), 1.0625rem, line height 1.65.
- **Lead text under the hero headline:** 1.2rem in Slate, kept to about 40 characters per line.
- Normal sentence case everywhere. No all-caps labels and no small labels above headings.

## Layout

- Content sits in a 1120px centered column with 24px side padding.
- Text is left-aligned. Nothing is centered except the page column itself.
- **Hero:** two columns on desktop, with the headline, short intro, and buttons on the left and the large logo mark on the right. On mobile the logo moves to the top and the text follows.
- **Staircase section:** each feature has a 3px gradient bar on its left. Each one is indented further right than the last, so the list climbs like the logo. On mobile the indent drops to zero.
- **Sections** are separated by 1px Deep Navy lines. There are no cards, shadows, or boxes.
- Generous space between sections (72px to 96px vertical padding).

## Components

**Primary button:** pill shape (fully rounded), Sky to Cobalt gradient, Ink text, semibold.

**Secondary button:** pill shape, transparent, 1.5px Deep Navy border, Snow text. The border turns Sky on hover.

**Buttons on hover:** lift up 2px. Nothing else on the page animates on hover.

**Status note:** a small line in Slate under the hero buttons, for things like "In development. No downloads yet."

**Links:** plain text with no underline in nav. Nav links go from Slate to Snow on hover.

## Logo usage

- Use the logo mark and wordmark on black only, or with `mix-blend-mode: screen` so the black background of the PNG disappears on dark pages.
- The wordmark appears small in the nav (about 34px tall). The mark appears large in the hero.
- Don't recolor the logo, add shadows or outlines, or place it over busy images.

## Motion

- One entrance animation: the logo mark slides in from the lower left and fades in over about 1.1 seconds on page load.
- Buttons lift slightly on hover.
- Smooth scrolling for in-page links.
- All motion is turned off for people who prefer reduced motion.

## Accessibility

- Text colors have strong contrast on black. Slate is only used for secondary text.
- Keyboard focus shows a 2px Sky outline with 3px offset.
- The layout works down to phone width, and the nav links collapse on small screens.
- Safe-area padding keeps content clear of phone notches and system bars.

## Voice

- Plain, friendly, and short. Say what Aetheria is and what the player can do.
- Describe the community and moderation directly. No hype.
- Buttons say exactly what happens: "Join the Discord", "View on GitHub".
- Sentence case. Typographic apostrophes (’) rather than straight ones.

## Dos and don'ts

**Do**
- Keep backgrounds pure black.
- Use the blue gradient sparingly, mainly on the one main action per section.
- Use space and thin lines to separate things.
- Echo the stepped, stacked shapes from the logo when you add new layouts.

**Don't**
- Add more accent colors.
- Use cards with drop shadows, heavy borders, or gradient backgrounds.
- Add scattered hover and scroll effects.
- Use all-caps labels or decorative eyebrow text.
