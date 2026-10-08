---
name: Harsh Patel · AI Developer
description: Dark frosted-glass portfolio lit by soft violet light, with one solid violet for action.
colors:
  night-ink: "#0a0a12"
  panel-ink: "#0e0e18"
  scrollbar-ink: "#2b2b40"
  text-bright: "#f3f3f8"
  text-body: "#b9bacb"
  text-muted: "#8d8fa5"
  text-placeholder: "#7a7c92"
  glass-fill: "rgba(255, 255, 255, 0.045)"
  glass-fill-raised: "rgba(255, 255, 255, 0.08)"
  hairline: "rgba(255, 255, 255, 0.1)"
  hairline-strong: "rgba(255, 255, 255, 0.2)"
  signal-violet: "#6d5cf0"
  signal-violet-pressed: "#5f4de3"
  soft-violet: "#9d8cff"
  lavender-ink: "#d9d3ff"
  tick-lavender: "#c3b9ff"
  periwinkle-focus: "#a9b8ff"
  periwinkle-link: "#c6d0ff"
  live-mint: "#5ff0b0"
  live-mint-text: "#9df5cf"
  error-rose: "#ff8fa3"
  error-rose-text: "#ffb3c1"
  chrome-dot-blue: "#a9c4ff"
  chrome-dot-lilac: "#c6a4ff"
  chrome-dot-pink: "#f7b2e6"
  chrome-dot-cyan: "#7df3e1"
typography:
  display:
    fontFamily: "Sora, ui-sans-serif, system-ui, sans-serif"
    fontSize: "clamp(2.6rem, 5.6vw, 4.4rem)"
    fontWeight: 600
    lineHeight: 1.04
    letterSpacing: "-0.035em"
  headline:
    fontFamily: "Sora, ui-sans-serif, system-ui, sans-serif"
    fontSize: "clamp(2rem, 4vw, 3rem)"
    fontWeight: 600
    lineHeight: 1.08
    letterSpacing: "-0.03em"
  title-lg:
    fontFamily: "Sora, ui-sans-serif, system-ui, sans-serif"
    fontSize: "clamp(1.75rem, 2.8vw, 2.3rem)"
    fontWeight: 600
    lineHeight: 1.1
    letterSpacing: "-0.03em"
  title:
    fontFamily: "Sora, ui-sans-serif, system-ui, sans-serif"
    fontSize: "1.3rem"
    fontWeight: 600
    lineHeight: 1.25
    letterSpacing: "-0.015em"
  body-lead:
    fontFamily: "Manrope, ui-sans-serif, system-ui, -apple-system, Segoe UI, sans-serif"
    fontSize: "1.25rem"
    fontWeight: 400
    lineHeight: 1.55
  body:
    fontFamily: "Manrope, ui-sans-serif, system-ui, -apple-system, Segoe UI, sans-serif"
    fontSize: "1rem"
    fontWeight: 400
    lineHeight: 1.65
  label:
    fontFamily: "Manrope, ui-sans-serif, system-ui, -apple-system, Segoe UI, sans-serif"
    fontSize: "0.8rem"
    fontWeight: 600
    lineHeight: 1.4
  button:
    fontFamily: "Manrope, ui-sans-serif, system-ui, -apple-system, Segoe UI, sans-serif"
    fontSize: "0.95rem"
    fontWeight: 600
    lineHeight: 1
  mono:
    fontFamily: "JetBrains Mono, ui-monospace, Consolas, monospace"
    fontSize: "0.8rem"
    fontWeight: 400
    lineHeight: 1.4
    fontFeature: "tnum"
rounded:
  tick: "7px"
  chip: "12px"
  control-sm: "13px"
  inset: "14px"
  control: "16px"
  panel-sm: "18px"
  nav: "20px"
  card: "22px"
  panel: "24px"
  feature: "28px"
  pill: "999px"
spacing:
  gutter: "clamp(1rem, 4vw, 2.5rem)"
  container: "1200px"
  chip-gap: "0.5rem"
  stack: "1rem"
  grid-gap: "1.25rem"
  card-body: "1.35rem"
  card: "1.75rem"
  section-head: "2.25rem"
  section: "clamp(5rem, 9vw, 7.5rem)"
components:
  button-primary:
    backgroundColor: "{colors.signal-violet}"
    textColor: "#ffffff"
    typography: "{typography.button}"
    rounded: "{rounded.control}"
    padding: "0 1.5rem"
    height: "3.25rem"
  button-primary-hover:
    backgroundColor: "{colors.signal-violet-pressed}"
    textColor: "#ffffff"
  button-glass:
    backgroundColor: "{colors.glass-fill}"
    textColor: "{colors.text-bright}"
    typography: "{typography.button}"
    rounded: "{rounded.control}"
    padding: "0 1.5rem"
    height: "3.25rem"
  button-glass-hover:
    backgroundColor: "{colors.glass-fill-raised}"
  button-sm:
    rounded: "{rounded.control-sm}"
    padding: "0 1.15rem"
    height: "2.75rem"
  filter-pill:
    backgroundColor: "rgba(255, 255, 255, 0.05)"
    textColor: "{colors.text-bright}"
    rounded: "{rounded.pill}"
    padding: "0 1.2rem"
    height: "2.6rem"
  filter-pill-active:
    backgroundColor: "{colors.signal-violet}"
    textColor: "#ffffff"
    rounded: "{rounded.pill}"
  role-badge:
    backgroundColor: "{colors.signal-violet}"
    textColor: "#ffffff"
    rounded: "{rounded.pill}"
    padding: "0 0.9rem"
    height: "2rem"
  status-badge:
    backgroundColor: "rgba(10, 10, 18, 0.6)"
    textColor: "{colors.text-bright}"
    rounded: "{rounded.pill}"
    padding: "0 0.65rem"
    height: "1.75rem"
  tag:
    backgroundColor: "rgba(255, 255, 255, 0.04)"
    textColor: "{colors.text-body}"
    rounded: "{rounded.pill}"
    padding: "0.25rem 0.7rem"
  skill-chip:
    textColor: "{colors.text-bright}"
    rounded: "{rounded.pill}"
    padding: "0 1rem 0 0.8rem"
    height: "2.6rem"
  input:
    backgroundColor: "rgba(10, 10, 18, 0.45)"
    textColor: "{colors.text-bright}"
    typography: "{typography.body}"
    rounded: "{rounded.inset}"
    padding: "0.85rem 1rem"
  glass-card:
    backgroundColor: "{colors.glass-fill}"
    textColor: "{colors.text-body}"
    rounded: "{rounded.panel}"
    padding: "{spacing.card}"
  project-card:
    backgroundColor: "{colors.glass-fill}"
    rounded: "{rounded.card}"
    padding: "{spacing.card-body}"
  nav-bar:
    backgroundColor: "rgba(14, 14, 24, 0.55)"
    textColor: "{colors.text-body}"
    rounded: "{rounded.nav}"
    padding: "0 0.75rem 0 1.25rem"
    height: "4.25rem"
  nav-bar-phone:
    backgroundColor: "rgba(10, 10, 18, 0.9)"
    height: "4rem"
  back-to-top:
    backgroundColor: "rgba(14, 14, 24, 0.72)"
    textColor: "{colors.text-bright}"
    size: "3rem"
  back-to-top-hover:
    backgroundColor: "{colors.signal-violet}"
---

# Design System: Harsh Patel · AI Developer

## Overview

**Creative North Star: "The Lit Glass Console"**

A near-black room (#0a0a12) washed by three soft, out-of-focus light fields (violet top-left, blue right, pink low-centre), with every panel cut from the same frosted glass. The glass is quiet: a 4.5–7.5% white fill, a 10% hairline, an 18px backdrop blur and a single inset highlight on the top edge. Against that hush, one solid violet does all the pointing. Colour is light in this world, not paint: it lives in the aurora, in the stage glow behind the particle robot, in the cursor light that follows the pointer across a card, and in the violet glow a card gives off when it is picked up.

Density is calm and editorial. Content sits in a 1200px column with generous section spacing, large Sora headlines tracked tight, and Manrope body copy in a soft grey that reserves near-white for headings and emphasis. The signature object is the hero "app window": a glass stage with window chrome (three tinted dots, a mono path title, a pill tag), a perspective grid floor, a canvas particle robot and three floating glass skill chips.

Motion is soft and physical: content rises and un-blurs into place on scroll, cards lift on intent, project logos tilt, links draw their underline, and the primary button passes a band of light across itself. Everything respects reduced motion.

**Key Characteristics:**
- Dark glass on #0a0a12 under soft violet / blue / pink light fields.
- One solid accent violet for every action and selected state; no gradient fills on controls.
- Soft violet type for the single highlighted phrase, the logo stroke and monograms.
- Large radii (12–28px) and full pills; hairline borders, never heavy outlines.
- Depth from blur, hairlines and an inset top highlight; shadows appear only as violet glow on state.
- Sora display, Manrope body, JetBrains Mono only for machine text.

## Colors

A cool near-black ground lit by tinted light, with one saturated violet as the only solid accent.

### Primary
- **Signal Violet** (`signal-violet`): the one solid accent fill. Primary buttons ("Hire me", "View my work", "Send message"), the active project-filter pill, the role badge, the "Answer" node of the request-flow diagram, the 2px scroll progress bar, the back-to-top button on hover, and a service glyph square while its card is hovered. Darkens to **Pressed Violet** (`signal-violet-pressed`) on button hover. Its translucent forms carry state: 16% fill with a 55% border for monogram squares, 18% fill with a 55% soft-violet border for hovered chips, and 55–80% for the card glow and logo drop-shadow.
- **Soft Violet** (`soft-violet`): a voice, not a fill. The highlighted headline phrase ("AI agents"), the HP logo stroke, monogram letters on education cards, the email link underline, and (at 38%) the border of a lifted card.

### Secondary
- **Periwinkle Focus** (`periwinkle-focus`): focus rings (2px outline, 3px offset), input focus border with an 18% 4px halo, the 13% cursor light inside cards, the open-source status dot, and text selection at 35%.
- **Periwinkle Link** (`periwinkle-link`): hover colour of project text links.
- **Lavender Ink** (`lavender-ink`) and **Tick Lavender** (`tick-lavender`): text and icon colour sitting on violet-tinted squares (current-role monogram, highlight ticks).

### Tertiary
- **Live Mint** (`live-mint`, text `live-mint-text`): status only. The "Live" dot, the "Current" pill (10% fill, 30% border), and the copied state of the copy-email button.
- **Error Rose** (`error-rose`, text `error-rose-text`): invalid input border and form error message.
- **Window-chrome dots** (`chrome-dot-blue`, `chrome-dot-lilac`, `chrome-dot-pink`, plus `chrome-dot-cyan` on the first stage chip): the last surviving trace of the iridescent palette. Used only as the three app-window dots, the stage-chip dots, and the private status dot (lilac).

### Neutral
- **Night Ink** (`night-ink`): page ground, theme colour, scrollbar track, phone nav bar at 90%.
- **Panel Ink** (`panel-ink`): base of the desktop nav (55%), mobile menu (96%), stage chips (70%) and back-to-top (72%).
- **Text Bright** (`text-bright`): headings, emphasis, button text on glass, input text.
- **Text Body** (`text-body`): default body copy and nav links.
- **Text Muted** (`text-muted`): dates, captions, footnotes, "uses" lines.
- **Glass Fill / Raised** (`glass-fill`, `glass-fill-raised`) and **Hairline / Strong** (`hairline`, `hairline-strong`): the glass material and every divider. Strong hairlines outline interactive glass (glass buttons, pills, inputs, glyph squares).

### Named Rules
**The One Violet Rule.** Signal Violet is the only solid accent fill on the page, and it always means "act here" or "this is selected". If a new element wants a coloured fill and is not an action or selected state, it stays glass.

**The No Gradient Controls Rule.** Buttons, pills, badges, nodes and bars are flat solid fills. Gradients exist only as light: the aurora, the stage glow, the cursor light, the primary button's passing sweep, and the fading seam on the contact panel's top edge.

**The Soft Violet Is Type Rule.** Soft Violet colours words and strokes, never surfaces. One highlighted phrase per headline at most.

## Typography

**Display Font:** Sora (with ui-sans-serif, system-ui)
**Body Font:** Manrope (with ui-sans-serif, system-ui, -apple-system, Segoe UI)
**Label/Mono Font:** JetBrains Mono (with ui-monospace, Consolas)

**Character:** Sora's geometric, slightly technical forms carry the headlines at weight 600 with tight negative tracking; Manrope keeps long passages warm and open at a relaxed 1.65 line height.

### Hierarchy
- **Display** (Sora 600, `display`): the hero headline only, balanced across three lines.
- **Headline** (Sora 600, `headline`): section titles (Services, Featured projects, About me, Journey); contact uses a slightly smaller clamp (2rem to 2.75rem).
- **Title Large** (Sora 600, `title-lg`): the featured project title.
- **Title** (Sora 600, 1.3–1.45rem, line height 1.2–1.25, tracking -0.015 to -0.02em): card, service, role and education titles.
- **Body Lead** (Manrope 400, `body-lead`, Text Bright): the opening paragraph of About; hero sub runs clamp(1.05rem, 1.5vw, 1.175rem) at 44ch.
- **Body** (Manrope 400, `body`): default copy, capped at 40–60ch.
- **Label** (Manrope 500–600, 0.75–0.85rem): status badges, tags, fact labels. Sentence case, no tracking, no uppercase.
- **Mono** (JetBrains Mono 400, 0.78–0.8rem, tabular figures): role dates and the app-window path title only.

### Named Rules
**The Mono for Machines Rule.** JetBrains Mono appears only where a machine would print: dates and the window URL/path. Never for headings, labels or decoration.

**The Tight Display Rule.** Every Sora heading at 1.3rem and above carries negative tracking (-0.015em to -0.035em) and `text-wrap: balance`.

## Layout

A single 1200px column with a fluid gutter (`gutter`), sections spaced by `section` and opened by a section head (title left, optional filters or intro right, 2.25rem below). Grids use a 1.25rem gap throughout.

- **Hero:** two columns (1.05fr / 0.95fr) collapsing to one at 960px; copy left, the tilted app-window stage right (aspect 11/12, max 600px tall).
- **Services:** three columns, two at 641–900px (last card spans), one below 641px.
- **Projects:** one wide feature panel (1.15fr diagram stage / 1fr body, stacked under 900px), then a three-column card grid (two under 900px, one under 600px).
- **About:** 7fr text / 5fr profile card, stacked under 900px.
- **Journey:** each role is a wide glass panel split 17rem meta / flexible body, stacked under 820px; education in a two-up grid.
- **Contact:** one large glass panel, 5fr intro / 7fr form, stacked under 900px; the form is two columns, one under 560px.
- **Footer:** 1.4fr brand plus three link columns, two columns under 860px.

## Elevation & Depth

Depth comes from the glass itself, not from shadows. Every panel is frosted glass over the aurora: a top-to-bottom white fill from 7.5% to 2.5%, a 10% hairline, `blur(18px) saturate(1.25)` and a 1px inset white highlight on the top edge. Surfaces are flat at rest. Shadows appear only as a response to state, and they are violet light, not dark drop shadows. The phone menu is the one dark ambient shadow.

### Shadow Vocabulary
- **Glass top light** (`box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.08)`): every glass panel.
- **Primary button glow** (`box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.18), 0 6px 18px -8px rgba(109, 92, 240, 0.8)`): solid violet buttons at rest.
- **Lifted card glow** (`box-shadow: 0 22px 44px -26px rgba(109, 92, 240, 0.6)`): any card on hover or focus-within, paired with a 4px lift (2px for the wide feature) and a 38% soft-violet border.
- **Logo float** (`filter: drop-shadow(0 8px 22px rgba(109, 92, 240, 0.55))`): transparent project logos; 0.8 opacity and 26px blur when the card is hovered.
- **Input focus halo** (`box-shadow: 0 0 0 4px rgba(169, 184, 255, 0.18)`).
- **Menu drop** (`box-shadow: 0 18px 40px -16px rgba(0, 0, 0, 0.8)`): the opened mobile menu only.

### Named Rules
**The Glass Is the Material Rule.** Every container is the same frosted glass. Do not invent a second panel material; vary only radius and padding.

**The Glow on Intent Rule.** Nothing glows at rest except the primary button. Hover and focus-within lift a card 4px and give it a violet glow and border; reduced motion keeps the colour change and drops the movement.

## Shapes

Soft, generous corners scaled to the object: 7px ticks, 12px chips, 13–16px buttons and icon squares, 14px inputs and flow nodes, 18–20px menus and nav, 22px project cards, 24px panels, 28px for the two largest panels (feature project, contact). Badges, tags, filters, skill chips and the copy button are full pills; the back-to-top button and status dots are circles. Borders are always 1px hairlines; internal dividers are hairline rules between card art and body, and between fact columns. The app-window's dots, mono title and pill tag are the one recurring "device" silhouette.

## Components

### Buttons
Confident and flat; the light does the talking.
- **Shape:** gently rounded rectangles (`control`, 16px; `control-sm`, 13px for the compact nav size), 3.25rem tall (2.75rem compact).
- **Primary:** solid Signal Violet, white Manrope 600 text, optional 16px line icon. On hover it darkens, rises 1px, and a 110-degree band of 28% white light sweeps left to right (0.7s). Pressed: 1px down, 99% scale.
- **Glass:** glass fill, strong hairline, Text Bright, 12px backdrop blur; hover raises the fill to 8% and the border to 32%.
- **Icon motion:** arrow icons nudge 2px toward their direction on hover.

### Chips and Pills
- **Filter pills:** 2.6rem pills on a 5% white fill with a strong hairline; hover 10%. The selected filter is solid Signal Violet with white 600 text. On phones the row scrolls horizontally without a scrollbar.
- **Skill chips:** 2.6rem pills (2.25rem inside the profile card) with a brand mark or line icon in #dfe3ff and Text Bright label.
- **Tags:** small pills, 4% fill, hairline, Text Body at 0.8rem.
- **Chip hover (skills and tags):** border turns 55% soft violet, fill becomes 18% Signal Violet, text brightens, chip rises 2px.
- **Status badge:** 1.75rem pill on 60% night ink with a hairline and a coloured 0.45rem dot (mint live, periwinkle open-source, lilac private).
- **Role badge:** solid Signal Violet pill, white 600 text. "Current" pill is mint-tinted; duration pill is a plain hairline pill.

### Cards / Containers
- **Corner Style:** 24px panels, 22px project cards, 28px feature and contact panels.
- **Background:** glass (see Elevation). Project-card logo strips use a 2% white wash.
- **Shadow Strategy:** flat at rest; lifted card glow on hover or focus-within.
- **Border:** 10% hairline, turning 38% soft violet when lifted.
- **Internal Padding:** 1.75rem for service and profile cards, 1.35rem for project-card bodies, clamp(1.5rem, 3vw, 2.25rem) for role panels.
- **Cursor light:** cards that opt in show a 22rem periwinkle radial light (13%) that follows the pointer, fading in over 0.35s.

### Project Cards (signature)
Plain dark glass, no coloured art panel. A 6.5rem top strip lays out side by side: the project's own transparent logo floating at 4rem on the left with a violet drop-shadow, the status badge on the right. A hairline separates the body: Sora title, three-line clamped description, muted tech line, then text links pinned to the bottom. On hover the card lifts and the logo scales to 108% and tilts -4 degrees.

### Featured Project Panel
A wide glass panel: the left stage holds a vertical request-flow diagram (Question, Agent, Retriever + Tools, Answer) built from 14px night-ink nodes with 20% hairline outlines joined by 1px lines; only the Answer node is solid Signal Violet. The right body carries a static status badge, the large title, a three-column fact row divided by hairlines, tags and a muted private-code note.

### Inputs / Fields
- **Style:** 14px corners, 45% night-ink fill, strong hairline, Text Bright Manrope 1rem, placeholder #7a7c92, labels in Text Body 0.85rem above.
- **Focus:** border turns Periwinkle Focus with an 18% 4px halo; no outline.
- **Error:** border Error Rose; message in Error Rose Text.

### Navigation
- **Desktop:** a sticky glass bar floating 0.875rem from the top, 4.25rem tall, 20px corners, 55% panel ink. HP monogram logo (soft-violet stroke) and name left, centred links (Text Body, 0.95rem/500, 10px hover pill at 6% white that also marks the current section), glass "Resume" and primary "Hire me" on the right.
- **Tablet (900px and below):** links collapse to a 2.75rem menu button opening a 96% panel-ink menu with full-width rows.
- **Phone (640px and below):** the bar becomes a solid edge-to-edge strip pinned to the very top (90% night ink, bottom hairline only, no radius), the glass Resume button hides.
- **Scroll progress:** a 2px Signal Violet bar across the top edge scales with scroll.

### Hero App Window (signature)
A glass stage tilted toward the pointer (perspective 1200px). Window chrome: three 0.65rem dots (blue, lilac, pink), a mono path title in Text Body, a hairline pill tag. Inside: violet and blue radial glows, a perspective grid floor in 50% periwinkle lines fading upward, the particle robot canvas, and three floating glass chips (70% panel ink, 10px blur, coloured dot) naming skills.

### Links, Back to Top, Copy Email
- **Text links:** an underline slides in from the left on hover (1px, 0.35s); project links also shift to Periwinkle Link.
- **Email link:** Sora, permanently underlined in 55% soft violet, thickening to a 2px solid soft-violet line on hover. Beside it, a pill copy button that tints violet on hover and turns mint with a check when copied.
- **Back to top:** a 3rem glass circle (2.75rem on phones) fixed bottom-right, fading in after scrolling; hover fills Signal Violet and nudges the arrow up.

### Icons
Lucide-style line icons, 1.75px stroke, round caps, inline SVG symbols; brand marks (Simple Icons) as masked monochrome glyphs only in the built-with row and skill chips. Service icons sit in 14px glass squares that turn Signal Violet and rotate -6 degrees when their card is hovered.

## Do's and Don'ts

### Do:
- **Do** use Signal Violet (#6d5cf0) as the only solid accent fill, and only for actions and selected states.
- **Do** build every container from the one frosted glass recipe: 7.5%→2.5% white fill, 10% hairline, blur(18px) saturate(1.25), inset top highlight.
- **Do** keep project cards plain dark glass with the transparent logo floating left on a violet drop-shadow and the status badge right.
- **Do** give every card the shared interaction: 4px lift, 38% soft-violet border and violet glow on hover and focus-within.
- **Do** colour exactly one headline phrase in Soft Violet (#9d8cff).
- **Do** reveal content by rising 26px and un-blurring from 6px with cubic-bezier(0.16, 1, 0.3, 1), and drop all movement under reduced motion.
- **Do** keep JetBrains Mono for dates and window/URL chrome only.

### Don't:
- **Don't** put gradient fills on buttons, pills, badges, nodes or bars; the user removed them.
- **Don't** introduce a second accent fill colour or tint card art panels with colour.
- **Don't** use dark drop shadows for elevation; depth is glass, and glow is violet and state-driven.
- **Don't** use Soft Violet as a background or Signal Violet as body text.
- **Don't** use the window-chrome dot colours (blue, lilac, pink, cyan) anywhere outside window chrome, stage chips and status dots.
- **Don't** set labels in uppercase with wide tracking, and don't stack a small category or kicker label above a heading; carry category in the filter or the meta line instead.
