# AMSC Performance — Brand & Design Guidelines

> This document is the canonical brand reference for Claude Design and any AI design tool pointed at this repository. Follow every rule here without exception.

---

## Who AMSC Is

AMSC Performance is East and Central Africa's premier sports performance institution, based in Nairobi, Kenya. Founded and led by Arnold (ACE Certified Sports Performance Specialist), AMSC delivers elite sport-specific strength and conditioning, late-stage return-to-play rehabilitation, and team performance consultation.

AMSC operates four verticals:
- **AMSC Performance** — training delivery
- **AMSC Metrics** — proprietary athlete monitoring platform
- **AMSC Combine** — athlete testing and benchmarking
- **Adjacent ventures** — Fuel by AMSC, Mavuno Basket

---

## The Core Rule

> *AMSC is the coach in the corner. The athlete is always the protagonist.*

Every design decision must honour this:
- The athlete's name is always **larger** than the AMSC logo
- The athlete's achievement is always the **headline**
- AMSC's role is always **framing**, never competing
- Data and metrics belong to the **athlete**, not the brand

---

## Colour Palette

| Token | Hex | Role |
|---|---|---|
| `--amsc-red` | `#a60a08` | Primary accent — see Red Budget below |
| `--amsc-deep-red` | `#820b0b` | Hover states, secondary red |
| `--amsc-black` | `#000000` | Full-bleed backgrounds |
| `--amsc-surface` | `#1a1a1a` | Card surfaces, panels |
| `--amsc-divider` | `#222222` | Borders, separators, grid lines |
| `--amsc-muted` | `#555555` | Tertiary labels, disabled states |
| `--amsc-grey` | `#d3d3d3` | Subtext, labels, secondary info |
| `--amsc-off-white` | `#f5f5f8` | All primary text on dark |

**No other colours are permitted.** No gold, green, blue, or partner brand colours in AMSC-primary layouts.

### The Red Budget

Every layout gets **one dominant red moment** — and only one. The dominant red is the thing the eye must land on first.

**Dominant red — pick exactly ONE per layout:**
- Red-backed headline highlight (a key phrase on a solid red bar)
- The single hero metric in red (one number, one layout)
- One CTA element (button or download tag)

**Structural red — quiet and functional, does NOT count against the budget:**
- Eyebrow labels and category tags
- Thin bars and dividers (2–4px)
- Card top-borders
- Quote left-borders (3px)
- Performance deltas `▲ +12%`

**The squint test:** if you squint and more than one red element fights to be "the point," you've overspent. Pull one back to structural, or remove it.

**Red never appears on:**
- Large background fills — red is an accent and a bar, never a panel fill
- Body text
- Decorative elements with no function
- Multiple competing dominant elements on the same layout

---

## Logos

### Two Marks Only
The full wordmark **AMSC PERFORMANCE** is primary. The C-stopwatch icon is the standalone symbol — use it as a watermark, app/profile mark, or where the full wordmark won't fit.

### File Reference
All marks live in the [`/logos`](logos) folder as transparent PNGs (2084×2084). Naming: `amsc-[mark]-[colourway].png`.

| File | Mark | Colourway | Use on |
|---|---|---|---|
| `logos/amsc-wordmark-black-red.png` | Wordmark | Black + red accent | **Primary** — light / neutral backgrounds |
| `logos/amsc-icon-black-red.png` | Icon | Black + red accent | **Primary / favicon** — light / neutral |
| `logos/amsc-wordmark-red.png` | Wordmark | All red | Dark / black / photo backgrounds |
| `logos/amsc-icon-red.png` | Icon | All red | Dark / black / photo backgrounds |
| `logos/amsc-wordmark-black.png` | Wordmark | All black | Mono — light backgrounds, print |
| `logos/amsc-icon-black.png` | Icon | All black | Mono — light backgrounds, print |
| `logos/amsc-wordmark-red-black.png` | Wordmark | Red + black accent | Alternate — light / neutral |
| `logos/amsc-icon-red-black.png` | Icon | Red + black accent | Alternate — light / neutral |

**Gap:** there is no off-white knock-out version for placing the logo directly on a red bar or a busy mid-tone photo. On dark layouts use the all-red mark; an off-white version should be added when available.

### Colour Rule
On dark backgrounds use the all-red mark. On light/neutral backgrounds use the black+red primary (or all-black mono). Off-white (`#f5f5f8`) on red bars or busy photography once that version exists. Never any other colour. Never a gradient.

### Clear Space
Keep clear space around the wordmark equal to the height of the "C" icon. Nothing — text, photo edges, other logos — intrudes into that zone.

### Minimum Size
Wordmark never below 90px wide on screen. Social: logo width ≈ 15–20% of canvas max. Presentations: 10–15% of slide width. Icon never below 24px.

### Logo Placement
- Social: top-left or top-right corner
- Documents and reports: bottom-left or bottom-right
- Always in its own clean zone — never over a busy photo area without a dark gradient or backing panel

### Never
Never stretch, rotate, recolour outside the two approved versions, add effects (shadow/glow/bevel), or place the red mark on a red or mid-tone background where contrast fails.

### Icon as Watermark
The C-stopwatch icon may sit large and faded (4–8% opacity) in the background of brand frames, bleeding off an edge. One watermark per layout, behind content, never overlapping focal text. Adds institutional weight without spending the red budget.

---

## Typography — Three-Font System

Each font has one role. They do not overlap.

### Font 1 — Oswald (Authority)
**Commands. Structures. Establishes hierarchy.**

- Use for: all headlines, section headings, subheadings, eyebrow labels, navigation, slide titles, category tags
- Always uppercase
- Google Fonts: Oswald 400/500/600/700
- CSS: `font-family: 'Oswald', sans-serif`

| Level | Weight | Size | Case | Tracking |
|---|---|---|---|---|
| Display | 700 | 48–96px | Uppercase | 0 |
| H1 | 700 | 32–48px | Uppercase | 0 |
| H2 | 600 | 20–28px | Uppercase | 0 |
| Eyebrow | 600 | 10–12px | Uppercase | 0.18–0.22em |

### Font 2 — Antonio (Data & Editorial)
**Presents. Clarifies. Makes numbers land.**

- Use for: all metric numbers, combine scores, performance data, stat callouts, table values, delta indicators
- Numbers lead always — label below or beside, never before
- Google Fonts: Antonio 400/500/700
- CSS: `font-family: 'Antonio', sans-serif`

| Level | Weight | Size | Case |
|---|---|---|---|
| Metric Large | 700 | 36–56px | — |
| Metric Small | 500–700 | 18–28px | — |
| Data Label | 400 | 12–16px | Mixed |

### Font 3 — Barlow (Support)
**Explains. Contextualises. Reads.**

- Use for: all body copy, captions, quotes, athlete descriptions, supporting text, footnotes
- Always sentence case — never all caps
- Line height: 1.6–1.8
- Google Fonts: Barlow 300/400/500/600/700
- CSS: `font-family: 'Barlow', sans-serif`

| Level | Weight | Size | Case | Tracking |
|---|---|---|---|---|
| Body | 400 | 12–16px | Sentence | 0 |
| Caption | 400–500 | 9–11px | Uppercase | 0.12–0.16em |
| Quote | 400 italic | 12–14px | Sentence | 0 |

---

## Spacing — 8px Base Grid

All spacing uses multiples of 8px:

| Token | Value | Use |
|---|---|---|
| `--space-1` | 8px | Icon gap, tight spacing |
| `--space-2` | 16px | Component internal padding, gutters |
| `--space-3` | 24px | Card padding, section gap |
| `--space-4` | 32px | Between components |
| `--space-5` | 40px | Slide margins |
| `--space-6` | 48px | Major section breaks |
| `--space-8` | 64px | Between layout zones |
| `--space-12` | 96px | Hero sections, full-bleed padding |

**Corner radius:** 0px for layouts and full-bleed zones. 2px for tags and eyebrow pills. 4px maximum for UI elements. No `border-radius: 9999px` on any element.

**Border weight:** 0.5px for dividers and cards. 2px red for section accent bars. 4px red maximum for cover/hero bars.

---

## Layout System

### Sparse Layout
Use when: brand awareness, campaign content, athlete reveals, cover slides.
- Maximum 3 competing elements
- Dominant negative space is intentional — do not fill it
- One metric maximum
- Headline font: maximum size, generous

### Dense Layout
Use when: performance reports, combine results, proposals, dashboards.
- Every zone of the layout must be working
- Hierarchy: headline → metrics → supporting data → source
- Metric numbers are the visual anchors — make them large

### Hybrid Layout
Sparse hero zone on top + dense data zone at bottom.
- The most powerful AMSC format for athlete spotlights
- Example: athlete photo top 72% / stat bar bottom 28%

---

## Signature Elements — The AMSC Look

Four named design devices that define the AMSC visual language:

**01 — Red Horizontal Bars as Structure**
Narrow, contained, full-width red bars as structural dividers — the tagline strip, eyebrow bars, section separators. Height stays limited (a strip, never a panel). This is structural red: it organises, it doesn't compete. Red as a large background surface is still forbidden.

**02 — Red-Backed Headline Highlight**
One key phrase sits on a solid red bar inside the headline: `BUILT AROUND [YOUR SQUAD.]` where the bracketed phrase is red-backed. This is the dominant red moment — it expresses the budget, it doesn't break it. One highlight per layout, on the single most important phrase.

**03 — Stopwatch Watermark**
The C-stopwatch icon, large and faded (4–8% opacity), bleeding off an edge of a brand frame. Institutional weight without competing for attention. One per layout, behind content, never overlapping focal text.

**04 — Founder Portrait on the Close**
Arnold's portrait is permitted on closing and contact frames only — the human signature behind the institution. Never on content, proof, or methodology slides.

---

## The Four Social Templates

### Template 1 — The Result Post
- Goal: communicate a real result
- Photo: Hero mode (competitive environment)
- Layout: Hybrid — athlete photo dominant (72%) + stat bar (28%)
- Red on: the single defining number in the stat bar

### Template 2 — The Process Post
- Goal: show training in progress
- Photo: Documentary mode (real session, unposed)
- Layout: Split — photo 55% left, data panel 45% right
- Red on: the lead metric number only

### Template 3 — The Athlete Speaks Post
- Goal: athlete testimony in their own words
- Photo: Hero or Documentary
- Layout: Sparse — photo dominant, quote anchored at bottom with red left border
- Red on: the metric the athlete references in their quote
- Rule: use exact quotes only — never paraphrase

### Template 4 — The Data Story Post
- Goal: before/after transformation
- Photo: optional — data is the visual
- Layout: Dense — dark background, structured comparison grid
- Red on: the → delta arrow between before and after numbers

---

## Photography — Three Modes

### Mode 1 — Hero
The athlete IS the content. Full bleed, high contrast, dark vignette on lower third. Text bottom-weighted. Use for athlete spotlights and event features.

### Mode 2 — Atmosphere
The photo sets tone. Type tells the story. Dark overlay 40–60% opacity. Dominant display type over photo. Use for brand awareness and campaign content.

### Mode 3 — Documentary
Raw training footage. Real over polished. Minimal treatment — colour grade only. Data panel alongside. Use for process posts and behind-the-scenes.

### Signature Grade — Selective Desaturation
The AMSC cover grade: the hero athlete stays in full colour while surrounding players are desaturated to near-black-and-white. Isolates the protagonist and carries the protagonist rule into the photography itself. Use on covers and athlete spotlights where one figure must dominate a busy frame.

This is a photo-edit technique applied before the image enters a template — not a layout rule. When the hero cannot be cleanly isolated, fall back to Mode 1 Hero with a dark vignette instead.

---

## Caption System

### Universal Rules
- Lead with the number, never the label
- Maximum 3 lines of copy
- No exclamation marks
- No adjectives that aren't data
- Athlete name is always the last or only attribution
- AMSC never claims the result — the athlete does
- No motivational filler: no "beast mode", "crushing it", "on fire"

### Template Captions

**Result Post:**
```
[NUMBER]. [What it represents in one phrase].
[One sentence — what the athlete did].
[Athlete name]. [Club / Event].
```

**Process Post:**
```
[What we measured]. [What we found].
[One behaviour that drove the result].
[Athlete name] is building something.
```

**Athlete Speaks Post:**
```
"[Exact athlete quote referencing a specific number or result]"
— [Athlete name], [Title / Club]
```

**Data Story Post:**
```
[Before number] became [after number].
[Time period]. [How — one phrase].
This is what the work produces.
```

---

## Components

### Eyebrow Labels
- Font: Oswald 600
- Size: 10–12px
- Case: Uppercase
- Tracking: 0.18–0.22em
- Colour: always red (`#a60a08`)
- Border radius: 1px (pill version) or bare text

### Metric Display
- Font: Antonio 700 for the number, Barlow for the label
- Number first, always — label follows beneath or beside
- Red on the single most important metric per layout

### Stat Bar
- 3 cells maximum
- Background: `#222` gap between cells
- Cell background: `#1a1a1a`
- One cell gets the red accent number — all others off-white

### Quote Block
- 3px red left border
- Barlow 400 italic for quote text
- Barlow 400 uppercase tracked for attribution

### Buttons
- Font: Oswald 600, uppercase, 0.14em tracking
- Primary: red fill (`#a60a08`), hover deep red (`#820b0b`)
- Ghost: transparent, 0.5px off-white border
- Border radius: 1px
- One CTA per layout maximum

---

## Key Athletes (as of 2026)

| Athlete | Sport | Club | Key Fact |
|---|---|---|---|
| Derrick Ogechi | Basketball | Nairobi City Thunder | Captain, BAL Africa, zero games missed |
| Simani Regau | Sprint (100m/200m) | — | Kenya #7, 10.3s PB |
| Mohammed Bajaber | Football | Simba FC (Tanzania) | KPL Champion, Kenya National Team, Kenya #7 |

---

## Brand Assets

- Logo on dark: `logos/amsc-wordmark-red.png` (all red)
- Logo on light: `logos/amsc-wordmark-black-red.png` (black + red, primary) or `logos/amsc-wordmark-black.png` (mono)
- Icon / favicon: `logos/amsc-icon-black-red.png` (light) · `logos/amsc-icon-red.png` (dark)
- Full asset library: [`/logos`](logos) — see File Reference under Logos
- Instagram: @amscperformance
- Location: The Courtyard, Vanga Rd, Nairobi, Kenya
- Contact: admin@amscperformance.com

---

## Reference Brands (calibration only — do not copy)

Use these to sense-check quality:
- **Altis** — authority through proof, academic minimalism
- **EXOS** — high-performance system feel, everything intentional
- **Whoop** — data integrated with real life, dark precision, metrics feel human
- **Momentous** — best-in-class web editorial, sparse, typographic, confident

---

*AMSC Performance Design System v3.0 — June 2026*
