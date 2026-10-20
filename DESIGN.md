---
name: A Y M Affordable Tree Service
description: One calm, phone-first page for a Little Falls tree crew, in truck-door greens with one marker-light amber.
colors:
  paper: "#f5f6f2"
  card: "#ffffff"
  field: "#e7ece4"
  ink: "#0e3021"
  body: "#26372d"
  soft: "#4b5a50"
  green: "#1f5a3c"
  deep: "#0e3021"
  on-dark: "#f4f7f2"
  on-dark-soft: "#d0e6d6"
  amber: "#f5a524"
  amber-bright: "#ffbb4a"
  amber-ink: "#874a00"
  line: "rgba(14,48,33,.12)"
  error: "#b3261e"
typography:
  display:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(42px, 12vw, 80px)"
    fontWeight: 400
    lineHeight: 1.02
    letterSpacing: "-0.005em"
  headline:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(30px, 7.6vw, 48px)"
    fontWeight: 400
    lineHeight: 1.08
    letterSpacing: "-0.005em"
  title:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(19px, 5.2vw, 24px)"
    fontWeight: 400
    lineHeight: 1.2
  label:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "18px"
    fontWeight: 400
    lineHeight: 1
  lede:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(17px, 4.6vw, 19px)"
    fontWeight: 400
    lineHeight: 1.7
  body:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "16px"
    fontWeight: 400
    lineHeight: 1.7
rounded:
  field: "10px"
  row: "18px"
  card: "24px"
  pill: "999px"
spacing:
  gutter-phone: "20px"
  gutter-desktop: "40px"
  stack: "16px"
  list-gap: "24px"
  column-gap: "64px"
  band-phone: "64px"
  band-desktop: "96px"
  container: "1160px"
components:
  button-primary:
    backgroundColor: "{colors.amber}"
    textColor: "{colors.ink}"
    typography: "{typography.label}"
    rounded: "{rounded.pill}"
    padding: "0 26px"
    height: "56px"
  button-primary-hover:
    backgroundColor: "{colors.amber-bright}"
    textColor: "{colors.ink}"
  button-ghost:
    backgroundColor: "transparent"
    textColor: "{colors.on-dark}"
    typography: "{typography.label}"
    rounded: "{rounded.pill}"
    padding: "0 26px"
    height: "56px"
  button-line:
    backgroundColor: "transparent"
    textColor: "{colors.ink}"
    typography: "{typography.label}"
    rounded: "{rounded.pill}"
    height: "56px"
  service-row:
    backgroundColor: "rgba(255,255,255,.07)"
    textColor: "{colors.on-dark}"
    typography: "{typography.title}"
    rounded: "{rounded.row}"
    padding: "12px 14px 12px 22px"
    height: "64px"
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
  form-card:
    backgroundColor: "{colors.card}"
    rounded: "{rounded.card}"
    padding: "clamp(20px, 5vw, 32px)"
  step-number:
    backgroundColor: "{colors.amber}"
    textColor: "{colors.ink}"
    rounded: "{rounded.pill}"
    size: "48px"
  float-text:
    backgroundColor: "{colors.amber}"
    textColor: "{colors.ink}"
    rounded: "{rounded.pill}"
    size: "60px"
---

# Design System: A Y M Affordable Tree Service

## Overview

**Creative North Star: "The Truck Door"**

The whole page is painted from the side of AYM's own crane truck: the green of the door lettering, a deeper forest green for the dark bands, and the amber of the marker lights as the one warm signal. It is the calm band style (after lpmr.co.uk) worn in the crew's own colours: full-bleed bands that alternate light and dark so each section announces itself, soft borderless shapes, and one display face that does all the talking. Nothing is decorative for its own sake; the only image is the real truck, used twice.

Density is low and phone-first. Each band carries one idea, one heading and at most one list or control group. Depth is flat colour, not shadow. Motion is a single bounce on the hero headline and a quiet 12px fade-up for everything below the first screen; nothing else moves.

**Key Characteristics:**
- Off-white paper ground; two greens for dark bands; amber as the single accent.
- Amber is a fill. Where it must be text on light, it darkens to amber-ink.
- Cal Sans for every heading, button, list item and field label; the system stack for running text at 16/1.7.
- 24px cards, 18px rows, 10px fields, full pills. No borders on containers.
- Flat at rest. The only shadow belongs to the floating text circle.

## Colors

A restrained two-green palette on near-white paper, with one saturated amber held back for actions and the last phrase of dark-band headings.

### Primary
- **Marker-Light Amber** (amber): the action colour. Primary button fill, step-number discs, the floating text circle, the arrow disc on hover, the selection highlight, and the accent phrase in headings on dark bands. Text on it is always ink (7.0:1).
- **Bright Marker Amber** (amber-bright): hover state of the primary button only.
- **Amber Ink** (amber-ink): amber's text form on light grounds, at 6.4:1 on paper. Trust-list icons, the header phone glyph and hover, accent phrases on paper.

### Secondary
- **Truck-Door Green** (green): mid-tone band ground (services, closing call), the storm list bullets, the Facebook row fill, the wordmark, and the focus/hover outline colour on light grounds.
- **Deep Forest** (deep): the darkest band ground (how it works, footer), carrying the diagonal line texture, and the hero overlay base.

### Neutral
- **Paper** (paper): page ground, header, every light band. Also the theme-color.
- **Card White** (card): the form card on paper.
- **Leaf Wash** (field): fill for inputs and unselected chips, tinted enough to read on the white card.
- **Forest Ink** (ink): headings and text on light; text on amber; the selected-chip fill. Same value as deep, different job.
- **Bark Body** (body): running text on light (11.6:1 on paper).
- **Moss Soft** (soft): ledes, small print, the wordmark's sub-line (6.7:1 on paper).
- **Pale Leaf / Soft Leaf** (on-dark, on-dark-soft): headings and running text on green and deep bands.
- **Hairline** (line): 1px dividers between list items on paper. The only stroke in the system.
- **Error Red** (error): inline error sentences and the invalid-field border.

### Named Rules
**The Fill-Not-Text Rule.** Amber is a fill. Text sitting on amber is ink; amber used as text on paper or white is amber-ink. Bright amber as text appears only on green or deep grounds, and on the mid green only at headline size or larger (it is 4.0:1 there).

**The Dark-Band Accent Rule.** On hero, green and deep bands, the heading's last phrase takes the accent ("we handle it.", "call today."). Light-band headings stay one colour.

**The One Texture Rule.** The 135° line texture (`repeating-linear-gradient(135deg, transparent 0 22px, rgba(255,255,255,.035) 22px 23px)`) lives only on deep bands and the footer, at about 3.5% white so it never reads as lines through text.

## Typography

**Display Font:** Cal Sans (with Avenir Next, Segoe UI, system-ui)
**Body Font:** the system stack (-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial)

**Character:** One friendly, compact geometric display face set at regular weight carries every voice the visitor acts on; the system face stays out of the way for sentences.

### Hierarchy
- **Display** (400, clamp(42px, 12vw, 80px), 1.02): the hero H1 only, max 11ch, white on the overlaid truck.
- **Headline** (400, clamp(30px, 7.6vw, 48px), 1.08): every section H2, balanced wrap.
- **Title** (400, 19–24px fluid, 1.15–1.2): list rows set in display: trust claims, storm points, service rows, the Facebook row, step titles.
- **Label** (400, 17–18px, 1): buttons, field labels and legends, the header phone number; all in Cal Sans.
- **Lede** (400, clamp(17px, 4.6vw, 19px), 1.7): the sentence under a heading, max 40ch, in soft.
- **Body** (400, 16px, 1.7): running text, inputs (never under 16px), error sentences, footer.
- **Phone display** (400, clamp(30px, 9vw, 52px), 1): the number in the closing band, the page's last call.

### Named Rules
**The One Display Face Rule.** Anything the visitor reads as a heading, a choice or an action is Cal Sans at weight 400. Bold is reserved for a single emphasis inside body copy.

**The Sixteen Floor Rule.** No input, error or body text below 16px. Small print (14px) is the "(optional)" field hint only.

## Layout

A single centred column, max 1160px, with a 20px gutter on phones and 40px from 760px up. Bands are full-bleed with 64px vertical padding on phones and 96px from 760px. Headings sit in a head block (max 640px, 16px gaps).

Phones stack everything. From 760px, hero buttons sit side by side (min 240px each) and service rows go two columns. From 1024px, sections split into two columns with a 64px gap: trust heading beside the claims list, storm copy beside the truck photo (1 : 1.1), form heading beside the form (1 : 1.2, heading sticky at 40px), three steps in a row. On desktop the hero photo moves to the right 60%, masked into a solid deep-green text side.

Lists are rhythm, not cards: rows separated by a hairline with 12–15px vertical padding. Tap targets are 44px or more everywhere; primary controls are 56px.

## Elevation & Depth

Flat. Depth comes from band colour changes (paper, green, deep) and from tinted fills sitting on their ground (field on card, 7% white on green). There are no card shadows, no hover lifts and no borders on containers.

### Shadow Vocabulary
- **Floating lift** (`box-shadow: 0 10px 28px rgba(6,26,17,.32)`): the floating text circle only, because it sits over every band.

### Named Rules
**The Flat Band Rule.** Surfaces never cast shadows. If something needs to stand apart, change its ground, not its elevation.

## Shapes

Soft and borderless. Four radii: 10px for fields, 18–20px for full-width link rows, 24px for the form card and the photo frame, and full pills for buttons, chips and every circle (arrow discs, step numbers, bullets, the float). The only lines are the 1px hairline between list items and the 2px state borders on controls. Photos are clipped to the 24px card radius and always `object-fit: cover` at their own aspect ratio.

## Components

### Buttons
Big, round and plainly labelled.
- **Shape:** full pill, 56px tall, 26px side padding, label in Cal Sans 18px, optional 20px icon.
- **Primary:** amber fill, ink text, amber border. Hover (pointer devices only) brightens to amber-bright; in the form it also gains a 2px green outline.
- **Ghost:** transparent with a 70% pale-leaf border, on the hero only; hover turns the border white over a 10% white wash.
- **Line:** transparent with an ink border, full width, the form's fallback "Copy message".
- **Press:** scales to .98. Focus is a 3px outline offset 3px: green on light, amber on dark.

### Chips
- **Style:** pill, 48px tall, field fill, 2px transparent border, body text in ink. They are visually hidden checkboxes with real labels.
- **State:** hover draws a green border; selected fills ink with white text (amber border on hover); focus is an outline with offset, never a border, so it shows on the ink fill.

### Cards / Containers
- **Corner Style:** 24px.
- **Background:** card white on paper.
- **Shadow Strategy:** none (see Elevation).
- **Border:** none.
- **Internal Padding:** clamp(20px, 5vw, 32px), 22px between fields. The form card is the only card; content elsewhere sits directly on its band.

### Inputs / Fields
- **Style:** field fill, 10px radius, 2px transparent border, 52px min height, 16px text, green caret. Label above in Cal Sans 17px, optional hint in 14px soft.
- **Focus:** border turns green; no glow.
- **Error:** border turns error red and stays red while focused; a plain-sentence error appears under the field.

### Navigation
- **Header:** paper, 64px (76px desktop). Wordmark left: "AYM" in Cal Sans green over a 12px uppercase sub-line; tap-to-call number right in Cal Sans with an amber-ink phone glyph, which disappears below 360px. No menu.
- **Footer:** deep with the line texture; name, area, phone and a 44px Facebook link in pale leaf, amber on hover.

### Service Rows (signature)
Each service is a full-width link on the green band: 7% white fill, 18px radius, 64px tall, title in Cal Sans, and a 44px arrow disc on the right. Only the disc changes: on hover or focus it fills amber with ink arrow. The row itself never changes. Tapping a row pre-selects the matching chip in the form. The Facebook row under the storm photo is the same pattern on solid green (20px radius, 76px).

### Numbered Steps
An ordered list of three: a 48px amber disc with the number in Cal Sans ink, a title in Cal Sans pale leaf, one line of soft-leaf body. Stacked on phones, three across on desktop.

### Floating Text Circle
A 60px amber circle bottom right that opens a pre-filled text. It slides in once the hero has scrolled away and hides while the form is on screen, so two text controls are never in view together. One circle, never a bar.

### Not part of this system
The build carries three small eyebrow pills (hero, storm, form). They are a house-style exception owned by `~/.claude/skills/pitch-site/references/calm-photo-style.md` (item 5) and noted in HANDOFF.md, not a rule of this design system; new pages in this pitch-site family should still use them (14px, accent dot, faint tint, no hover) because Ellie chose them for the house style.

### Motion
The hero H1 alone bounces in letter by letter (each letter from 50px right, `1s cubic-bezier(.34,1.56,.64,1)`, 20ms apart), then restores to plain text. Everything else marked to rise fades up 12px over 400ms, and only if it starts below the first screen. Under reduced motion or without JS, everything is simply there.

## Do's and Don'ts

### Do:
- **Do** use amber for fills and ink for text on it; switch to amber-ink when amber has to be text on paper or white.
- **Do** alternate full-bleed bands (paper, green, paper, deep) so every new section is obvious.
- **Do** set headings, buttons, list rows and field labels in Cal Sans 400; keep sentences in the system stack at 16/1.7.
- **Do** separate list items with the 1px hairline instead of boxing them.
- **Do** give fields the field fill so they read on the white card, and keep the error border winning over focus.
- **Do** use the real truck photo (or other real client photos) at their own aspect ratio, `object-fit: cover`, under a deep-green overlay when text sits on them.
- **Do** keep tap targets at 44px or more and primary actions at 56px.

### Don't:
- **Don't** use amber as text on paper or white, or on the mid green below headline size.
- **Don't** add shadows to cards, rows or buttons; the floating circle is the only lifted object.
- **Don't** draw borders around containers or fields at rest.
- **Don't** animate anything beyond the hero H1 bounce and the 12px fade-up; no letter reveals on other headings, no parallax.
- **Don't** change a service row's own background on hover; only its arrow disc responds.
- **Don't** add a second accent colour or a third green.
