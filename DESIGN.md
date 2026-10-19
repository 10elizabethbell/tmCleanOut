---
name: T&M Clean Out LLC
description: A winter window you wipe clear; one family crew's whole service list, one text away.
colors:
  navy: "#132840"
  navy-2: "#1c3657"
  dusk-top: "#132a46"
  dusk-mid: "#1e3d60"
  dusk-low: "#2b4a6a"
  ink: "#10233a"
  ice: "#eaf1f8"
  ice-2: "#dbe6f2"
  gold: "#e2a83c"
  gold-hover: "#ecb751"
  gold-deep: "#8a5a10"
  focus: "#2f7fd0"
  muted: "#46596f"
  mist: "#c3d3e4"
  frost-steel: "#6b819a"
  white: "#ffffff"
typography:
  display:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(38px, 10.6vw, 104px)"
    fontWeight: 900
    lineHeight: 1.02
    letterSpacing: "-0.01em"
  headline:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(30px, 8vw, 52px)"
    fontWeight: 900
    lineHeight: 1.02
    letterSpacing: "-0.01em"
  headline-close:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(34px, 10vw, 72px)"
    fontWeight: 900
    lineHeight: 1.02
    letterSpacing: "-0.01em"
  title:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "20px"
    fontWeight: 900
    lineHeight: 1.15
    letterSpacing: "-0.01em"
  body:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "17px"
    fontWeight: 400
    lineHeight: 1.55
  body-lead:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "18px"
    fontWeight: 400
    lineHeight: 1.55
  label:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "15px"
    fontWeight: 900
    lineHeight: 1.55
    letterSpacing: "0.08em"
  button:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "17px"
    fontWeight: 800
    lineHeight: 1.1
rounded:
  focus: "6px"
  box: "8px"
  pill: "999px"
  circle: "50%"
spacing:
  xs: "12px"
  sm: "16px"
  md: "24px"
  lg: "32px"
  xl: "40px"
  2xl: "56px"
  3xl: "64px"
components:
  button-primary:
    backgroundColor: "{colors.gold}"
    textColor: "{colors.ink}"
    typography: "{typography.button}"
    rounded: "{rounded.pill}"
    padding: "0 24px"
    height: "56px"
  button-primary-hover:
    backgroundColor: "{colors.gold-hover}"
    textColor: "{colors.ink}"
  button-outline-navy:
    backgroundColor: "transparent"
    textColor: "{colors.white}"
    typography: "{typography.button}"
    rounded: "{rounded.pill}"
    padding: "0 24px"
    height: "56px"
  button-outline-ice:
    backgroundColor: "transparent"
    textColor: "{colors.ink}"
    typography: "{typography.button}"
    rounded: "{rounded.pill}"
    padding: "0 24px"
    height: "56px"
  service-row:
    backgroundColor: "transparent"
    textColor: "{colors.ink}"
    height: "52px"
    padding: "6px 0"
  service-check:
    backgroundColor: "{colors.white}"
    rounded: "{rounded.box}"
    size: "28px"
  service-check-checked:
    backgroundColor: "{colors.navy}"
    rounded: "{rounded.box}"
    size: "28px"
  step-marker:
    backgroundColor: "{colors.navy}"
    textColor: "{colors.gold}"
    rounded: "{rounded.circle}"
    size: "52px"
  header:
    backgroundColor: "{colors.navy}"
    textColor: "{colors.white}"
    height: "64px"
---

# Design System: T&M Clean Out LLC

## Overview

**Creative North Star: "The Wiped Winter Window"**

The page is a frosted window at winter dusk. Navy bands are glass with a dark street behind them: rooftops, a few gold-lit windows, snow on the ground. Frost ferns grow in from the edges and the visitor wipes them away with a finger or cursor. Meltwater drops run down the cleared glass, and the frost slowly grows back. Between the glass panes sit pale ice reading bands where the real content lives: the full service list, the steps, the discounts. The metaphor matches the job. T&M leaves a house empty, clean and ready for the cold, and the page lets you clear the glass the same way.

The pacing is dense and plain. Big, heavy, uppercase system-sans headlines, short first-person copy in William's voice, and one gold call to action per screen. Decoration only comes from the winter world: frost, drops, snowdrift and icicle seams. There are no stock photos, icon-card grids or review carousels. The page is a working tool (tick jobs, send a text), and the weather around it is the personality.

Rejected outright: a black ground (the flyer's black panel does not carry over), cards for services, and any warm accent other than the flyer's gold.

**Key Characteristics:**
- Navy dusk glass bands alternate with ice reading bands, separated by animated SVG snowdrift and icicle seams, never by straight lines.
- The frost-wipe canvas is the signature element. Every navy pane carries one, and text always sits on glass that is already clear.
- Heavy uppercase system sans (900) for every heading. The owner chose this house style on purpose.
- Gold is trim only: the lit phone number, the primary pill button, the ampersand, the second hero line, step numbers and check ticks.
- Services appear as one long ticked list grouped under three plain labels, and the selection becomes a pre-filled text message.

## Colors

A cold, two-ground palette (dusk navy glass and pale ice) with one warm accent, the flyer's gold, used sparingly as light.

### Primary
- **Flyer Gold** (gold): the only warm color. Used for the primary pill button fill, the header phone number, the "&" in the wordmark, the emphasized second line of the hero headline, step numbers, the check tick in the service boxes, the text selection highlight and the focus ring on navy. In the canvas it is lit windows and a low streetlight glow.
- **Gold Lamp** (gold-hover): the primary button's hover fill, slightly lighter, like a lamp turned up.
- **Burnt Gold** (gold-deep): gold darkened enough to read as text on ice. Only used for the service-group labels.

### Secondary
- **Frost Blue** (focus): the focus and hover ring color on ice bands, where gold would fail contrast. Shows on the service checkboxes (3px ring) and the send button. A functional color, never a fill.

### Neutral
- **Winter Dusk Navy** (navy): the header, footer, checked boxes, step-marker discs and the base of the theme color. Navy is the darkest ground the system allows.
- **Deep Dusk** (navy-2): scrollbar thumb, one step lighter than navy.
- **Dusk Sky ramp** (dusk-top, dusk-mid, dusk-low): the vertical sky gradient behind every glass pane (0%, 62%, 100%). The CSS fallback and the canvas sky share these stops, and the seams use dusk-low and dusk-top as their join colors, so pane edges line up without a visible break.
- **Night Ink** (ink): body text on ice, text on gold buttons, the outline button on ice.
- **Window Ice** (ice): the reading-band ground and the page body, like frosted glass in daylight.
- **Ice Rule** (ice-2): 1px row dividers in the service list and the 2px rule above the discounts block.
- **Slate** (muted): secondary text on ice (ledes, sub-lines, step copy, the "or call" line).
- **Mist** (mist): secondary text on navy (the wordmark sub-line, the hero facts line, footer copy).
- **Frost Steel** (frost-steel): the resting border of the service checkbox and the color of the frost-puff flakes.

### Named Rules
**The Never-Black Rule.** The darkest ground is Winter Dusk Navy. No surface, band or overlay goes to black or near-neutral grey. Dark means dusk, not night.

**The Gold-Is-Light Rule.** Gold shows up as small lit things (a number, a pill, a tick, a lit window) and never as a band or large field. If gold covers more of a screen than the primary button does, it has stopped being trim.

**The Two-Rings Rule.** Focus is gold on navy and Frost Blue on ice. Never put a gold ring on an ice ground.

## Typography

**Display Font:** System sans (-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial)
**Body Font:** Same system stack
**Label/Mono Font:** None separate. Numbers use tabular figures (`font-variant-numeric: tabular-nums`) on every phone number.

**Character:** A single system stack carried by weight alone: 900 uppercase for headings, 800 for buttons and links, 700 for list items, 400 for prose. This is the owner's house style and it deliberately overrides the usual rule for a display face. It reads like a hand-painted truck door: loud and plain.

### Hierarchy
- **Display** (900, clamp(38px, 10.6vw, 104px), line-height 1.02, uppercase): the hero headline only. On wide screens it is capped at 10ch so it breaks into two lines, and the second line is set in gold.
- **Headline** (900, clamp(30px, 8vw, 52px), 1.02, uppercase): section headings on ice and glass. The closing pane uses a larger step (clamp(34px, 10vw, 72px), max 12ch).
- **Title** (900, 20px, 1.15, uppercase): step titles and the discounts and "where" sub-heads.
- **Body** (400, 17px, 1.55): default prose. Pane copy and ledes step up to 18px and keep lines short (34 to 44ch).
- **List item** (700, 17px, 1.25): service rows. Sub-lines are 500, 15px, in Slate.
- **Label** (900, 15px, 0.08em tracking, uppercase, Burnt Gold): service-group names, and only as fieldset legends. Wordmark sub-line (800, 11px, 0.14em, Mist) is the only other tracked uppercase text.
- **Button** (800, 17px, 1.1): sentence case, never uppercase.

### Named Rules
**The Weight-Not-Face Rule.** Hierarchy comes from size and weight in a single system stack. Do not add a second family.

**The Shouting-Stops-At-Headings Rule.** Uppercase belongs to headings, the wordmark and group legends. Buttons, list items and prose stay in sentence case, in William's voice.

## Layout

A single column of full-bleed bands, with content held in a 1180px max wrap. Side gutters are 16px on phones and 32px from 700px up (`--pad`), and they respect safe-area insets. The band order alternates: navy header, glass hero, ice service list, glass vacant-homes pane, ice steps and discounts, glass close, navy footer. A seam marks every change between glass and ice.

Vertical rhythm: ice bands use 40px top and 64px bottom on phones, 64px and 96px from 1024px. Glass panes run 56 to 64px on phones and 96 to 120px on desktop. Within a section, h2 to content is 20px, and ledes pull up 8px and leave 28px before the list.

Responsive behavior: the hero buttons stack full-width (max 420px) on phones and sit in a row from 700px. The service groups go from one column to two at 760px and three at 1100px, with a 40px column gap. Steps become three columns at 860px, discounts and "where" become two at 900px, and the footer becomes three columns (1.2fr 1fr 1fr) at 860px. The hero fills the viewport under the header (svh, capped at 720px, 760px on desktop) and leaves a deep bottom area of frost under the content.

Touch targets: buttons are 56px, service rows 52px, header phone and footer links at least 44px.

## Elevation & Depth

Mostly flat. Depth comes from the glass metaphor, not from stacked surfaces: the canvas paints a dusk street behind the glass and frost on top of it, and the seams overlap their neighboring bands by their own height so the edge of the frost is a wave, not a line. There are only two real shadows.

### Shadow Vocabulary
- **Button lift** (`box-shadow: 0 6px 16px -8px rgba(8,20,36,.55)`): only under the gold primary pill, a soft navy shadow so it sits on the glass.
- **Ground halo** (`text-shadow: 0 0 18px rgba(19,40,64,.9), 0 0 3px rgba(19,40,64,.6)`): on all headline and copy text over a glass pane. It is a halo in the ground color that keeps text readable over moving frost, not a colored glow.
- **Ice halo** (`text-shadow: 0 0 10px #f4f8fc, 0 0 4px #f4f8fc`): the reverse, for the ink-colored "Wipe the glass" hint that sits on the frost itself.
- **Focus halo** (`box-shadow: 0 0 0 3px rgba(47,127,208,.22)` on hover, `.45` on focus): the ring around a service checkbox.

### Named Rules
**The Clear-Glass Rule.** Text on a pane never relies on its halo alone. The frost mask is cleared around every `[data-clear]` element's line boxes and buttons, so copy always sits on clear glass and the halo is the backup.

**The Halo-Matches-Ground Rule.** Text halos use the ground color they protect (navy on glass, ice on frost), never an accent.

## Shapes

Two opposite shapes. Controls are fully rounded: pill buttons (999px), circular step markers (50%), and softly squared checkboxes (8px) with a 6px focus-ring radius. Surfaces have no corners at all: bands are full-bleed, and their edges come from the world's own shapes. A rolling snowdrift ends each glass pane going down, and an icicle eave (snow load with hanging icicles that grow drops and let them fall) starts each pane. There are no boxed cards or bordered containers. Dividers are 1px Ice Rule hairlines between rows and one 2px rule above the discounts.

## Components

### Buttons
Big, round, and thumb-first.
- **Shape:** full pill (999px), 56px minimum height, 24px side padding (30px in the hero from 700px), 2px gold border on every variant, 10px icon gap, icons in inline SVG at 1em.
- **Primary:** gold fill, Night Ink text, button lift shadow. One per screen.
- **Hover / Focus:** hover lightens to Gold Lamp (only on devices that can hover). Press scales to 0.98 over 120ms. Color transitions take 180ms. Focus is a 3px offset ring: gold on navy, Frost Blue on ice.
- **Outline (on navy):** transparent with white text and a gold border. Hover adds a 14% gold wash. Used for the secondary "Text William" in the hero.
- **Outline (on ice):** Night Ink border and text, with a 6% ink wash on hover.

### Service list (estimate picker)
The core of the product: one dense, honest list, not cards.
- **Row:** 52px minimum, 14px gap, 700 weight, 1px Ice Rule underline, and the whole row is the tap target. The native checkbox is visually hidden but still focusable.
- **Check box:** 28px, 8px radius, 2px Frost Steel border on white. When checked it fills Winter Dusk Navy and a gold tick springs in (200ms, `cubic-bezier(.2,1.6,.4,1)`). Hover and focus add a Frost Blue border and ring. Forced-colors mode maps to CanvasText and Highlight.
- **Reward:** ticking a job sends six frost flakes out of the box (650ms, `cubic-bezier(0.16,1,0.3,1)`), drawn from the snowflake SVG symbol.
- **Send block:** a polite live count ("3 jobs picked."), then the gold "Text William the list" button whose `sms:` body is built from the ticked items, then a plain "Rather talk? Call" line.

### Step markers
- 52px navy disc with a gold 900-weight numeral at 22px, placed next to an uppercase title and a Slate sentence. It echoes the flyer's gold-on-black numbers, moved onto navy.

### Navigation
- **Header:** a navy bar, 64px tall. The wordmark sits on the left ("T&M" at 24px/900 with a gold ampersand, and "CLEAN OUT LLC" at 11px/800 tracked 0.14em in Mist). The tap-to-call number sits on the right in gold, 800 weight, tabular figures, with a phone icon. That number is the header's only warm element. There is no menu.
- **Footer:** navy with a hairline top border in Mist at 14% opacity. White 700-weight links at least 44px tall, and Mist copy.

### Frost-Wipe Pane (signature)
A full-bleed glass pane: a canvas over the dusk-sky CSS gradient. Behind the glass, a seeded dusk street (two layers of rooftops, mostly dark windows with a few gold-lit ones, a gold radial street glow, sparse stars, a snow ground line). In front, two frost layers, haze and branching fern crystals, grow in from the edges. The frost is heaviest along the bottom and in the corners and is held back from the content. Pointer or touch wipes it with a soft brush (34px on phones, 48px on desktop). The wiped glass stays wet for a while, drops gather along the lower edge of the wipe and slide down in stick-slip motion, and the frost grows back. The hero pane wipes itself after 5 seconds without input until someone touches it, and shows a "Wipe the glass" hint that fades out on first touch. Only the hero captures every drag direction; the panes lower down accept horizontal drags so the page still scrolls. The loop only runs while a pane is on screen. With reduced motion, the frost is drawn once at rest. If the canvas fails, the pane falls back to its CSS gradient.

### Seams (signature)
Animated SVG edges between glass and ice, 44px tall (64px from 1024px), overlapping the pane by their own height. Leaving a pane: a rolling snowdrift in the ice color that moves steadily ("lively" is the owner's tuning). Entering a pane: a slow snow-loaded eave with icicles (mostly stubs, a few long ones, gaps between clusters) whose tips grow drops that fall. They use the same join colors as the pane gradient. With reduced motion, they are drawn once and stay still.

## Do's and Don'ts

### Do:
- **Do** alternate dusk-glass panes and ice reading bands, and join every glass-to-ice change with a seam (snowdrift when leaving a pane, icicle eave when entering one).
- **Do** give every new navy pane the frost-wipe canvas and mark its copy and buttons `data-clear` so the frost stays off them.
- **Do** set headings in the system stack at 900, uppercase, line-height 1.02, -0.01em tracking.
- **Do** keep gold to small lit elements: one gold pill per screen, the phone number, the ampersand, step numerals, ticks.
- **Do** use the gold focus ring on navy and the Frost Blue (#2f7fd0) ring on ice.
- **Do** make every contact action a real `tel:` or `sms:` link with a pre-filled body, at least 56px tall for buttons and 44px for links, with tabular figures on numbers.
- **Do** put text halos in the ground color (navy on glass, ice on frost) and honor `prefers-reduced-motion` by drawing frost and seams once at rest.

### Don't:
- **Don't** use black or neutral grey as a ground. The darkest surface is Winter Dusk Navy (#132840).
- **Don't** use gold as a band, large field or body-text color on ice. Use Burnt Gold (#8a5a10) where gold-family text has to sit on ice.
- **Don't** show services as icon cards or tiles. They are one ticked list under plain group labels.
- **Don't** separate bands with straight rules or hard color cuts where a seam belongs.
- **Don't** add a second typeface or a webfont. The system stack is the house style.
- **Don't** add stock photos, invented before/afters, reviews or a logo mark. The world comes from the frost scene, and the name is set as a wordmark.
- **Don't** set buttons, list items or prose in uppercase.
