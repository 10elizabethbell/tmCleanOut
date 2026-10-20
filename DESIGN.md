---
name: T&M Clean Out LLC
description: Calm paper and navy bands with the flyer's gold, for a family clean-out and property-care crew in Burlington County, NJ.
colors:
  paper: "#f4f6fb"
  card: "#ffffff"
  ink: "#0f2238"
  body: "#26364a"
  soft: "#4a5868"
  navy: "#1b3a5c"
  deep-navy: "#0f2238"
  on-dark: "#f4f7fb"
  on-dark-soft: "#c9d7ea"
  flyer-gold: "#e2a83c"
  flyer-gold-hover: "#ecbb5c"
  gold-ink: "#7a5410"
  field: "#e6ecf5"
  line: "rgba(15,34,56,.12)"
  line-dark: "rgba(255,255,255,.14)"
  error: "#b3261e"
  facebook-blue: "#1877f2"
typography:
  display:
    fontFamily: "'Cal Sans', 'Avenir Next', 'Segoe UI', system-ui, sans-serif"
    fontSize: "clamp(42px, min(11.4vw, 13svh), 80px)"
    fontWeight: 400
    lineHeight: 1.02
    letterSpacing: "-.005em"
  phone:
    fontFamily: "'Cal Sans', 'Avenir Next', 'Segoe UI', system-ui, sans-serif"
    fontSize: "clamp(30px, 9vw, 52px)"
    fontWeight: 400
    lineHeight: 1
  headline:
    fontFamily: "'Cal Sans', 'Avenir Next', 'Segoe UI', system-ui, sans-serif"
    fontSize: "clamp(30px, 7.6vw, 48px)"
    fontWeight: 400
    lineHeight: 1.08
    letterSpacing: "-.005em"
  title:
    fontFamily: "'Cal Sans', 'Avenir Next', 'Segoe UI', system-ui, sans-serif"
    fontSize: "clamp(22px, 6vw, 26px)"
    fontWeight: 400
    lineHeight: 1.08
  claim:
    fontFamily: "'Cal Sans', 'Avenir Next', 'Segoe UI', system-ui, sans-serif"
    fontSize: "clamp(20px, 5.4vw, 24px)"
    fontWeight: 400
    lineHeight: 1.15
  button:
    fontFamily: "'Cal Sans', 'Avenir Next', 'Segoe UI', system-ui, sans-serif"
    fontSize: "18px"
    fontWeight: 400
    lineHeight: 1
  lede:
    fontFamily: "-apple-system, BlinkMacSystemFont, 'Segoe UI', 'Helvetica Neue', Arial, sans-serif"
    fontSize: "clamp(17px, 4.6vw, 20px)"
    fontWeight: 400
    lineHeight: 1.7
  body:
    fontFamily: "-apple-system, BlinkMacSystemFont, 'Segoe UI', 'Helvetica Neue', Arial, sans-serif"
    fontSize: "16px"
    fontWeight: 400
    lineHeight: 1.7
  label:
    fontFamily: "-apple-system, BlinkMacSystemFont, 'Segoe UI', 'Helvetica Neue', Arial, sans-serif"
    fontSize: "11px"
    fontWeight: 600
    lineHeight: 1
    letterSpacing: ".08em"
  scale:
    xs: "11px"
    sm: "14px"
    sm-plus: "15px"
    base: "16px"
    md-min: "17px"
    md: "18px"
    md-plus: "19px"
    lg: "20px"
    title-min: "22px"
    wordmark: "23px"
    xl: "24px"
    title-max: "26px"
    h2-min: "30px"
    hero-min: "42px"
    h2-max: "48px"
    phone-max: "52px"
    hero-max: "80px"
rounded:
  focus: "6px"
  field: "10px"
  card: "24px"
  pill: "999px"
spacing:
  gutter: "20px"
  gutter-wide: "40px"
  stack: "20px"
  section: "64px"
  section-wide: "96px"
components:
  button-primary:
    backgroundColor: "{colors.flyer-gold}"
    textColor: "{colors.ink}"
    typography: "{typography.button}"
    rounded: "{rounded.pill}"
    padding: "0 26px"
    height: "56px"
  button-primary-hover:
    backgroundColor: "{colors.flyer-gold-hover}"
    textColor: "{colors.ink}"
  button-ghost:
    backgroundColor: "transparent"
    textColor: "{colors.on-dark}"
    typography: "{typography.button}"
    rounded: "{rounded.pill}"
    padding: "0 26px"
    height: "56px"
  button-line:
    backgroundColor: "transparent"
    textColor: "{colors.ink}"
    typography: "{typography.button}"
    rounded: "{rounded.pill}"
    padding: "0 26px"
    height: "56px"
  card:
    backgroundColor: "{colors.card}"
    textColor: "{colors.ink}"
    rounded: "{rounded.card}"
    padding: "clamp(20px, 5vw, 32px)"
  input:
    backgroundColor: "{colors.field}"
    textColor: "{colors.ink}"
    typography: "{typography.body}"
    rounded: "{rounded.field}"
    padding: "13px 14px"
    height: "52px"
  chip:
    backgroundColor: "{colors.field}"
    textColor: "{colors.ink}"
    typography: "{typography.body}"
    rounded: "{rounded.pill}"
    padding: "0 18px"
    height: "48px"
  chip-selected:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.card}"
  service-row:
    textColor: "{colors.on-dark}"
    padding: "10px 0"
    height: "64px"
  step-badge:
    backgroundColor: "{colors.flyer-gold}"
    textColor: "{colors.ink}"
    size: "44px"
  text-circle:
    backgroundColor: "{colors.flyer-gold}"
    textColor: "{colors.ink}"
    size: "60px"
---

# Design System: T&M Clean Out LLC

## Overview

**Creative North Star: "The Swept Front Room"**

The page reads like a house after the crew has been through it: calm, ordered, nothing left lying around. Full-bleed bands alternate paper, navy, white and deep navy so each new section is obvious at a thumb's glance, and the flyer's gold is the one warm thing in the room, used only as a fill on the things you tap. Shapes are soft and borderless (24px cards, full pills, tinted fields), the display face is Cal Sans at regular weight, and running text is the system stack at a generous 16/1.7.

Density is low and mobile-first: a 20px gutter, 64px bands on phones and 96px on desktop, one column that splits into two or three only at 1024px. Motion is limited to three named moves (the hero letter bounce-in, one 12px fade-up for content below the first screen, and the floating text circle sliding up), and all three switch off under reduced motion.

There are no photos; the only texture is a faint 135deg line pattern on the navy hero and the deep navy bands.

**Key Characteristics:**
- Alternating full-bleed bands: paper, navy, white, deep navy with line texture.
- One warm accent, flyer gold, as a fill only; gold-as-text uses the darker gold ink on light grounds.
- Cal Sans display at weight 400 for headings, buttons, labels and numbers; system sans for body.
- Soft borderless geometry: 24px card, 10px field, 999px pill, circles for icon buttons.
- Every job is one tap from a text: service rows, pill buttons and a floating 60px gold circle.

## Colors

Cool paper and two navies carry the page; a single flyer gold is the only warm note.

### Primary
- **Flyer Gold** (`flyer-gold`): fill for primary pill buttons, the step-number discs, the floating text circle, hovered arrow discs and text selection. Text on it is always ink navy.
- **Flyer Gold, Lit** (`flyer-gold-hover`): the primary button's hover fill, nothing else.
- **Gold Ink** (`gold-ink`): gold when it must be text or an icon stroke on a light ground: the ampersand in the wordmark, the header phone icon, the trust-claim icons, accent phrases on light bands, the input caret.

### Secondary
- **Harbor Navy** (`navy`): the hero band and the closing band. Also the focus and hover outline on light grounds, so focus never reads as a gold fill.
- **Deep Navy** (`deep-navy`): the services band and the footer, always with the line texture.

### Neutral
- **Cool Paper** (`paper`): page ground, header and alternating light bands; also the theme color.
- **Card White** (`card`): the white band, the estimate form card and the Facebook card; white H1 text on the hero.
- **Ink Navy** (`ink`): headings and strong text on light grounds, text on gold, the selected chip fill. Same value as deep navy; one ink, two jobs.
- **Body Slate** (`body`): running text on light grounds.
- **Soft Slate** (`soft`): ledes, helper text, placeholders and the wordmark tagline on light grounds.
- **Frost Field** (`field`): input and chip fill, visible against the white form card.
- **On-Dark** (`on-dark`) and **On-Dark Soft** (`on-dark-soft`): headings and secondary text on navy bands.
- **Hairline** (`line`) and **Hairline on Dark** (`line-dark`): 1px dividers between trust claims and service rows. Low-alpha tints of ink and white (6-12%) also fill arrow discs and hover washes.
- **Error Red** (`error`): field error text and the error border on invalid inputs.
- **Facebook Blue** (`facebook-blue`): only the Facebook glyph on the Facebook card, because it is Facebook's mark.

### Named Rules
**The Gold Is a Fill Rule.** Flyer gold never carries text on a light ground; it fills buttons, discs and the circle, and the words on it are ink navy. When gold has to be a word or an icon on paper or white, it becomes gold ink.

**The Navy Focus Rule.** Focus and hover outlines on light grounds are harbor navy, never gold, so a focused gold button is still visibly outlined. On navy grounds the outline switches to flyer gold.

**The Faint Lines Rule.** The 135deg line texture (1px of 3.5% white every 23px) lives only on the hero and deep navy bands, and stays faint enough never to read as lines through text.

## Typography

**Display Font:** Cal Sans (with Avenir Next, Segoe UI, system-ui)
**Body Font:** the system sans stack (-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial)

**Character:** A friendly geometric display face at a single regular weight gives headings, buttons and phone numbers a sign-painted confidence; the plain system body keeps reading fast and familiar.

### Hierarchy
- **Display** (400, fluid 42px to 80px, also capped by 13svh for landscape phones, line-height 1.02, max 13ch): the hero H1 only, in white, with the place name in gold.
- **Phone** (400, fluid 30px to 52px, line-height 1): the big tap-to-call number in the closing band.
- **Headline** (400, fluid 30px to 48px, line-height 1.08, -.005em): every H2.
- **Title** (400, fluid 22px to 26px): service group headings with a 28px icon.
- **Claim** (400, fluid 20px to 24px, line-height 1.15): the trust claims list.
- **Display small** (400, 18-20px): buttons, form labels, step titles, the deal heading, the Facebook card label, the header phone; wordmark at 23px (26px desktop); step digits at 19px.
- **Lede** (system, fluid 17px to 20px, max 38-44ch): the paragraph under a heading.
- **Body** (system 400, 16px, line-height 1.7): running text, inputs (16px so iOS never zooms), chips, errors. Service row labels are 18px, row sub-lines 15px, helper text 14px.
- **Label** (system 600, 11px, .08em, uppercase): the "Clean Out LLC" tagline under the wordmark, nothing else.

### Named Rules
**The One Weight Rule.** Cal Sans is always weight 400; hierarchy comes from size and color, never from bolding the display face.

**The 16px Floor Rule.** Body copy and every input sit at 16px or larger; 14-15px is reserved for helper text and row sub-lines.

## Layout

A single centered column (`max-width: 1160px`) with a 20px gutter on phones and 40px from 760px up. Bands are full-bleed with 64px vertical padding on phones and 96px from 760px. Heads stack heading, lede and any eyebrow in a 16px gap, capped at 640px.

At 760px the hero buttons move into a row (each at least 240px wide) and the header grows to 76px. At 1024px the trust section splits into two columns (claims on the right spanning both rows), the three service groups sit side by side with a 48px gap, the estimate section becomes a sticky head beside a 1.2fr form, and the closing band places the big phone number at the bottom right. Column gaps at that width are 48-64px.

Vertical rhythm inside sections steps through 12, 16, 20, 28, 40px. The footer adds 96px plus the safe-area inset at the bottom so the floating circle never covers its links.

## Elevation & Depth

Depth comes from band color, not shadow. The page is flat except for two quiet ambient shadows under the white cards that sit on paper, and one stronger shadow under the floating circle, which is the only element that floats above content.

### Shadow Vocabulary
- **Card rest, low** (`box-shadow: 0 6px 18px rgba(15,34,56,.06)`): the Facebook card.
- **Card rest, form** (`box-shadow: 0 10px 30px rgba(15,34,56,.07)`): the estimate form card.
- **Float** (`box-shadow: 0 10px 28px rgba(8,20,36,.3)`): the fixed text circle.

### Named Rules
**The Band Is the Depth Rule.** Sections separate by alternating band color; never add borders, dividers or shadows between bands.

## Shapes

Soft and borderless. Cards round at 24px, inputs at 10px, every button and chip is a full pill, and icon controls (arrow discs, step numbers, the floating circle) are circles. Borders appear only as 2px transparent rings that turn navy on hover and focus, the 1px hairlines between list rows, and the 2px outline of the line button. The focus ring itself rounds at 6px.

## Components

### Buttons
Big, round and tappable: 56px tall, full pill, Cal Sans 18px.
- **Shape:** full pill (999px), 2px border, 26px side padding, 10px gap for a 20px leading icon.
- **Primary:** flyer gold fill and border, ink navy text. Full width on phones inside the form and empty-homes band.
- **Hover / Focus:** primary hover lightens to flyer-gold-hover (pointer devices only). Press scales to .98. Focus is a 3px outline offset 3px, navy on light grounds and gold on navy ones; inside the form the hover and focus outline is 2px navy.
- **Ghost:** transparent with a 70% on-dark border on navy grounds; hover turns the border white over a 10% white wash.
- **Line:** transparent with an ink border, used for the secondary "Copy message" action.

### Chips
- **Style:** frost field fill, 48px tall pill, 16px system text in ink, 2px transparent border.
- **State:** hover turns the border navy; selected fills ink navy with white text, and selected hover adds a 2px navy outline offset 2px.

### Cards / Containers
- **Corner Style:** 24px.
- **Background:** card white on a paper band.
- **Shadow Strategy:** the two card rest shadows above.
- **Border:** none.
- **Internal Padding:** fluid 20px to 32px for the form; the Facebook card is 14-22px around a 72px-tall row ending in a 44px arrow disc.

### Inputs / Fields
- **Style:** frost field fill, no visible border (2px transparent), 10px radius, 52px minimum height (120px for textareas), 16px text, gold ink caret. Labels are Cal Sans 18px above the field with an 8px gap.
- **Focus:** the border turns harbor navy; no glow.
- **Error:** the border turns error red and a 16px error line appears below; the error border wins over focus.

### Navigation
A paper header with the T&M wordmark (Cal Sans, gold ink ampersand, 11px uppercase tagline) on the left and the tap-to-call number with a gold ink phone icon on the right; hover turns the number gold ink. There is no menu. The footer is a deep navy band of 44px-tall links that turn gold on hover.

### Service Rows
Each job is a full-width 64px row on deep navy, 18px on-dark text, separated by dark hairlines, ending in a 44px circular arrow disc on a 10% white wash. Hover or focus fills the disc gold with an ink arrow; the row itself never highlights. Every row opens a prefilled text about that job.

### Step Discs
How-it-works steps are numbered by 44px gold discs with an ink Cal Sans digit, beside a 20px Cal Sans step title and soft body text.

### Floating Text Circle
One 60px gold circle with a 26px chat icon, fixed 16px from the bottom-right corner (plus safe-area insets). It waits 120px below the viewport and slides up once the visitor scrolls past the hero (.35s, `cubic-bezier(.2,.8,.2,1)`). It is never a bottom bar.

### Motion
- **Letter bounce-in:** each hero H1 letter starts 50px to the right at opacity 0 and settles in 1s on `cubic-bezier(.34,1.56,.64,1)`, staggered 20ms per letter. Words never break mid-word.
- **Fade-up:** content below the first screen rises 12px and fades in over .4s ease-out. Nothing in the first viewport fades.
- **Reduced motion:** all three moves and button transitions switch off, and smooth scrolling stops.

## Do's and Don'ts

### Do:
- **Do** alternate full-bleed bands (paper, navy, white, deep navy with the line texture) so each section starts visibly.
- **Do** put ink navy text on every flyer gold fill, and switch to gold ink whenever gold has to be text on a light ground.
- **Do** keep tap targets at 44px or more: 56px buttons, 48px chips, 52px inputs, 64px service rows, 44px footer links.
- **Do** set Cal Sans at weight 400 for headings, buttons, labels and phone numbers; keep body copy on the system stack at 16/1.7.
- **Do** use the documented radii only: 24px cards, 10px fields, full pills, circles for icon controls.
- **Do** gate hover styles behind `(hover: hover)` so taps never leave them stuck on.

### Don't:
- **Don't** put white or gold text directly on a flyer gold fill, or gold text on paper or white.
- **Don't** add borders or shadows between bands; the band color is the separator.
- **Don't** turn the floating text circle into a bottom bar, or add a second floating element.
- **Don't** add motion beyond the letter bounce-in, the 12px fade-up and the circle slide, and never animate content in the first viewport other than the H1.
- **Don't** use flyer gold as the focus color on light grounds; focus there is harbor navy.
- **Don't** raise the line texture above about 4% white.

The small eyebrow pills above the hero H1 and two section headings are a client-house exception Ellie chose (recorded in HANDOFF.md), not a component for new surfaces to repeat.
