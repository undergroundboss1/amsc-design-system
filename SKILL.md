---
name: amsc-brand-design
version: 3.0
owner: AMSC Performance
last_updated: 2026-05
description: Reusable design system skill for creating all AMSC Performance branded content — social media, PDFs, presentations, graphics, and digital products across all AMSC verticals (Performance, Metrics, Combine, Fuel, Mavuno Basket). Use this file at the start of every AMSC design session to ensure consistency, brand accuracy, and design quality across all outputs.
---

## 0. HOW TO USE THIS SKILL

Load this file at the start of any AMSC design task. Before generating output:
1. Identify the content type (social, PDF, presentation, graphic, digital)
2. Identify the content goal (authority, athlete spotlight, education, data, brand awareness)
3. Apply the Layout Decision Framework (Section 4) to select Sparse or Dense
4. Apply the Photography Mode Framework (Section 5) if images are involved
5. For all athlete content — apply the Athlete Content System (Section 11) first
6. For all captions and copy — apply the Caption System (Section 8.4)
7. Follow all brand rules in Sections 2 and 3 without exception
8. Select the appropriate design engine from Section 12 before starting execution

Do not guess. Do not improvise brand elements. If in doubt, refer back to this file.

**Skill hierarchy for AMSC design work:**
```
amsc-brand-design   → defines visual identity and brand rules (non-negotiable foundation)
ui-ux-pro-max       → informs interface patterns for digital products (applied on top)
design engine       → executes the output (Section 12)
```
`ui-ux-pro-max` never overrides brand rules. It answers questions this skill doesn't ask —
how dashboards behave, interaction patterns, onboarding flows, empty states, mobile density.
This skill answers what everything should look like. Both must be active for digital product work.

---

## 1. BRAND OVERVIEW

### 1.1 Who AMSC Is
AMSC Performance is East and Central Africa's premier sports performance institution,
based in Nairobi, Kenya. Founded and led by Arnold (ACE Certified Sports Performance
Specialist), AMSC delivers elite sport-specific strength and conditioning, late-stage
return-to-play rehabilitation, and team performance consultation.

AMSC operates four verticals:
- **AMSC Performance** — training delivery
- **AMSC Metrics** — proprietary athlete monitoring platform
- **AMSC Combine** — athlete testing and benchmarking
- **Adjacent ventures** — Fuel by AMSC, Mavuno Basket

### 1.2 Brand Philosophy — The Core Rule
> *AMSC is the coach in the corner. The athlete is always the protagonist.*

AMSC exists to arm athletes to accomplish what they didn't know they could.
This is not a brand that overshadows. It supports, equips, and elevates.

Every design decision must honour this:
- The athlete's name is always larger than the AMSC logo
- The athlete's achievement is always the headline
- AMSC's role is always framing, never competing
- Data and metrics belong to the athlete, not the brand

### 1.3 Brand Positioning
| What lesser brands do | What AMSC does |
|---|---|
| "Look at our athletes" | "Look at this athlete" |
| Brand logo dominant | Athlete name dominant |
| Brand claims the result | Athlete owns the result |
| Performance as product | Performance as relationship |
| Data as brand proof | Data as athlete proof |
| Commentary over results | Results speak for themselves |

**The AMSC Content Equation:**
```
Real photo + Real data + Athlete's own words
= Content that doesn't feel like marketing
```

This is the north star for all athlete content.
The system is invisible. The athlete is undeniable.

### 1.4 Design Philosophy
- **Precision** — every element earns its place
- **Simplicity** — remove until it breaks, then add one thing back
- **Structure** — visible hierarchy at a glance
- **Discipline** — no decorative elements, no visual noise
- **Elite standard** — the design itself signals the level of the work

### 1.5 Visual Reference Brands
Use these brands as calibration references — not to copy, but to sense-check quality:
- **Altis** — authority through proof, academic minimalism, credentials as design
- **EXOS** — high-performance system feel, everything looks intentional
- **Volt Athletics** — software-edge, data-forward, structured
- **Whoop** — data integrated with real life, dark precision, metrics feel human
- **Momentous** — best-in-class web editorial, sparse, typographic, confident

---

## 2. VISUAL SYSTEM

### 2.1 Color Palette

| Role | Name | Hex | Usage |
|---|---|---|---|
| Primary Accent | AMSC Red | `#a60a08` | Accent only — see rules below |
| Dark Red | Deep Red | `#820b0b` | Hover states, secondary red moments |
| Base | Black | `#000000` | Full-bleed backgrounds |
| Surface | Near-Black | `#1a1a1a` | Card surfaces, panel backgrounds |
| Primary Text | Off-White | `#f5f5f8` | All primary text on dark backgrounds |
| Secondary Text | Light Grey | `#d3d3d3` | Subtext, labels, secondary info |
| Muted | Dark Grey | `#555555` | Tertiary labels, disabled states |
| Divider | Subtle Grey | `#222222` | Borders, separators, grid lines |

**No other colours are permitted in AMSC content.**
Do not introduce brand colours from partner organisations into AMSC-primary layouts.

### 2.2 Red Usage Rules — CRITICAL

Red is an accent colour. It is surgical, not decorative.

**Red appears on:**
- Eyebrow labels and category tags (e.g. `ATHLETE SPOTLIGHT · BASKETBALL`)
- The single most important metric or data point per layout
- Divider lines and ruled separators
- Performance deltas and improvement indicators
- The one keyword in a headline that must land hardest
- Active states and highlights in digital products
- Left-border quote indicators
- CTA elements (buttons, download tags) — one per layout maximum

**Red never appears on:**
- Large background fills (exception: cover pages — see below)
- Body text
- Decorative elements with no functional purpose
- Multiple competing elements on the same layout
- Partner or athlete branding zones

**Cover page exception:**
On the cover of a major document (proposal, report, deck), red may appear more
prominently — a full-width bar, a large ruled line, a dominant graphic element.
The cover is a brand moment, not an information zone. This exception does not
carry into interior pages.

### 2.3 Typography

AMSC uses a deliberate three-font system. Each font has one role. They do not overlap.

---

**Font Location — Local Files**
All three fonts are stored locally at:
`Documents/AMSC Performance Brand/`

When working in any design environment (Canva, Figma, HTML, PPTX):
- Load fonts from this folder first before defaulting to Google Fonts
- If the local font files are unavailable in the output environment,
  use Google Fonts as the fallback source:
  - Oswald: `https://fonts.google.com/specimen/Oswald`
  - Antonio: `https://fonts.google.com/specimen/Antonio`
  - Barlow: `https://fonts.google.com/specimen/Barlow`

---

**Font 1 — Oswald (Authority)**
> Commands. Structures. Establishes hierarchy.

Use for: all headlines, section headings, subheadings, eyebrow labels, navigation,
slide titles, document headers, category tags.

Why Oswald: condensed but not compressed — it carries institutional weight without
aggression. The font of coaching systems, elite sports organisations, performance
institutions. Sits comfortably next to Altis and EXOS.

Google Fonts: `https://fonts.google.com/specimen/Oswald`
Canva: available natively
CSS: `font-family: 'Oswald', sans-serif;`

---

**Font 2 — Antonio (Data & Editorial)**
> Presents. Clarifies. Makes numbers land.

Use for: all metric numbers, combine scores, performance data, stat callouts,
table values, data labels, report figures, delta indicators.

Why Antonio: editorial precision with a slightly wider stance than Oswald — gives
data breathing room without losing structure. Numbers in Antonio feel measured and
intentional, not clinical. Closest to the Momentous / Whoop data aesthetic.

Google Fonts: `https://fonts.google.com/specimen/Antonio`
Canva: available natively
CSS: `font-family: 'Antonio', sans-serif;`

---

**Font 3 — Barlow (Support)**
> Explains. Contextualises. Reads.

Use for: all body copy, captions, quotes, athlete descriptions, supporting text,
footnotes, form labels, UI microcopy.

Why Barlow: humanist, clean, and highly legible at small sizes. Shares DNA with
the condensed styles above without competing. The font that makes the system
feel complete rather than cold.

Google Fonts: `https://fonts.google.com/specimen/Barlow`
Canva: available natively
CSS: `font-family: 'Barlow', sans-serif;`

---

**Type Hierarchy:**

| Level | Font | Weight | Size | Case | Tracking |
|---|---|---|---|---|---|
| Display | Oswald | 700 | 48–96px | Uppercase | 0 |
| H1 | Oswald | 700 | 32–48px | Uppercase | 0 |
| H2 | Oswald | 600 | 20–28px | Uppercase | 0 |
| Eyebrow | Oswald | 600 | 10–12px | Uppercase | 0.18–0.22em |
| Metric Large | Antonio | 700 | 36–56px | — | 0 |
| Metric Small | Antonio | 500 | 18–28px | — | 0 |
| Data Label | Antonio | 400 | 12–16px | Mixed | 0 |
| Body | Barlow | 400 | 12–16px | Sentence | 0 |
| Caption | Barlow | 400–500 | 9–11px | Uppercase | 0.12–0.16em |
| Quote | Barlow | 400 | 12–14px | Sentence | 0 |

---

**Typography Rules:**
- Oswald headlines are always uppercase — no exceptions
- Antonio data is mixed case — follow the natural form of the number or label
- Barlow body is always sentence case — never all caps
- Line height on display type: 0.9–1.0 — headlines stack tight and powerful
- Line height on body: 1.6–1.8 — copy breathes and reads cleanly
- Letter spacing on Oswald eyebrows: 0.18em–0.22em minimum
- Never use a fourth typeface — three fonts is the complete system
- Never use decorative, script, or novelty fonts in any AMSC output
- Never use Oswald for body copy — it is a display and label font only
- Never use Antonio for headlines — it is a data and editorial font only
- The combination of Oswald authority + Antonio precision + Barlow clarity
  is the AMSC typographic voice — do not break it

### 2.4 Layout Principles

**Base grid:** All layouts use a structured column grid.
- Social (1:1): 12-column grid, 16px gutters
- Social (9:16): 6-column grid, 16px gutters
- PDF / Document: 12-column grid, 20px margins, 16px gutters
- Presentation slide: 12-column grid, 40px margins

**Spacing system:** Use multiples of 8px for all spacing decisions.
`8 · 16 · 24 · 32 · 40 · 48 · 64 · 80 · 96`

**Corner radius:** Minimal. Maximum 4px on UI elements. Zero on full-bleed zones.
AMSC design is structured and precise — avoid rounded aesthetics.

**Border weight:** 0.5px–1px on all dividers and separators. Never heavier unless
used as a deliberate red accent bar (2–4px maximum).

---

## 3. BRAND PRESENCE RULES

### 3.1 Logo Placement
The AMSC logo must always be:
- **Legible** — never placed over a busy area of a photo without a clear zone
- **Present** — always included in every piece of content
- **Quiet** — small, confident, never competing with the athlete

**Preferred positions:**
- Top-left or top-right corner (social, presentations)
- Bottom-left or bottom-right (documents, reports)
- Always in its own clean zone — white space, dark panel, or isolated from photo noise

**Logo sizing:**
- Social media: logo width ≈ 15–20% of canvas width maximum
- Presentations: logo width ≈ 10–15% of slide width
- Never scale the logo to be the dominant element on any layout

**Logo colour usage:**
- On dark backgrounds: white or red version
- On light backgrounds: black or dark version
- Never place the logo directly over a mid-tone photo without a backing panel or
  sufficient contrast zone

### 3.2 Brand Handle
`@amscperformance` appears on documents and presentations only.

**Use on:**
- PDFs — cover page and closing page
- Presentations — cover slide and closing slide
- Printed materials — proposals, reports, flyers
- Any format where the platform context is not inherently known

**Do not use on:**
- Instagram posts (square or carousel)
- Instagram Stories
- Any native social media format — the platform already carries the handle context
  Adding it to social content is redundant and clutters the layout

**When used:**
Placement: top-right or bottom-right corner — never mid-layout
Style: Barlow, 400 weight, off-white `#f5f5f8`, uppercase, tracked at 0.12em
Size: same as eyebrow caption text — never larger than the logo

### 3.3 Tagline
**"Home to Elite Sports Performance"**
Use on covers, brand awareness content, and closing slides/pages.
Do not use on every piece — reserve it for brand moments.

---

## 4. LAYOUT DECISION FRAMEWORK

Before designing any layout, answer: **What is this content trying to do?**

### Use SPARSE when:
- The message needs to land with impact — one idea, one feeling
- Content type: brand awareness social post, cover slide, hero section, campaign graphic
- The audience needs to *feel* something — identity, aspiration, belonging
- The photo is the primary storytelling device
- Example pieces: "Built for Speed" post, campaign covers, athlete name reveals

**Sparse layout rules:**
- Maximum 3 design elements competing for attention
- Dominant negative space is intentional — do not fill it
- One metric maximum if data is present
- Headline font size: maximum, generous
- AMSC branding: top corner, minimal, legible

### Use DENSE when:
- Data is the story — metrics, scores, comparisons, timelines
- Content type: athlete report, performance PDF, combine results, proposal, dashboard
- The audience needs to *analyze* — coaches, partners, scouts, institutions
- Multiple data points must coexist without hierarchy confusion
- Example pieces: Ogechi stat post, combine reports, Hillcrest proposal slides

**Dense layout rules:**
- Every zone of the layout must be working — no wasted space
- Clear information hierarchy: headline → metrics → supporting data → source
- Use grid lines and subtle separators to organize zones
- Metric numbers are the visual anchors — make them large
- AMSC branding: present in header or footer bar, legible, quiet

### Hybrid layouts:
Some content requires both — a sparse hero zone on top,
a dense data zone anchored at the bottom.
Example: Ogechi post (cinematic photo top 75% / stat bar bottom 25%)
This is the most powerful AMSC format for athlete spotlights. Use it deliberately.

---

## 5. PHOTOGRAPHY FRAMEWORK

### 5.1 The Core Rule
The athlete is always the protagonist. AMSC is always the system behind them.
Photography must honour the athlete's story, not illustrate AMSC's services.

### 5.2 The Three Photography Modes

**MODE 1 — HERO**
> The athlete IS the content.

- Full bleed photo, dark base, athlete facing camera or in peak action
- Used for: athlete spotlights, high-profile event features, credibility posts
- Treatment: high contrast, dark vignette on lower third, subject sharp
- Text placement: bottom-weighted — name large, metrics in footer bar
- Example: Derrick Ogechi post

**MODE 2 — ATMOSPHERE**
> The photo sets the tone. Type tells the story.

- Full bleed photo, treated as background — darker, less detail
- Used for: brand awareness, campaign content, motivational posts
- Treatment: dark overlay (40–60% opacity black), subject may be partially obscured
- Text placement: dominant, left-aligned, large display type over photo
- Example: "Built for Speed" post

**MODE 3 — DOCUMENTARY**
> Raw training footage. Real over polished.

- Training environment photos — tracks, courts, gyms, outdoor sessions
- Used for: ongoing work content, process posts, behind-the-scenes
- Treatment: minimal — colour grade only, no heavy overlays
- Text placement: anchored bottom or side panel, clean data zone
- Example: Simani block start content

### 5.3 Photo Composition Rules
- **Framing must be intentional** — the crop must communicate the moment's energy
  - Block start = coil, tension, explosive potential
  - Post-game = exhaustion, triumph, raw emotion
  - Training = focus, work, discipline
- Never use a photo where the athlete's face or dominant body line is cropped
  without deliberate artistic intent
- Avoid photos where the background competes with or distracts from the subject
- If the photo background is busy (streets, crowds, mixed environment) — apply
  a dark vignette or panel to isolate the athlete

### 5.4 Photo + Branding Coexistence Rule
The AMSC logo must always have a clean zone.
If the photo bleeds into the logo position — add a subtle dark gradient,
a translucent panel, or relocate the logo to an unobstructed area.
The logo must always be legible. It must never be loud.

---

## 6. CONTENT FRAMEWORKS

### 6.1 Social Media Post (1:1 — Square)

AMSC uses four distinct athlete content templates for social posts.
Each template has a defined purpose. Select the template before designing.

---

**TEMPLATE 1 — THE RESULT POST**
*The athlete achieved something. This is the proof.*

Purpose: Communicate a real result — competition outcome, ranking, transfer, milestone.
Photography mode: Hero — athlete in their competitive environment.
Layout: Hybrid — athlete photo dominant, stat bar anchored at bottom.

```
[ FULL BLEED ATHLETE PHOTO — competitive environment ]
┌─────────────────────────────────┐
│ AMSC logo [top-left, quiet]     │
│                                 │
│      [PHOTO DOMINATES]          │
│                                 │
│ EYEBROW · SPORT                 │  ← Oswald, red pill, tracked
│ ATHLETE                         │  ← Oswald 700, massive, white
│ NAME                            │
│ Club · Position                 │  ← Barlow, grey
│ ─────────────────────────────── │  ← 0.5px rule
│ [#]   [RESULT]   [METRIC]       │  ← Antonio, large — numbers lead
│ label  label      label         │  ← Barlow, 9px, muted, tracked
└─────────────────────────────────┘
```

Red accent: the single defining number of this result.
Caption template: See Section 8.4 — Result Post caption.

---

**TEMPLATE 2 — THE PROCESS POST**
*The work is ongoing. This is what it looks like.*

Purpose: Show training in progress — sessions, testing, coaching moments.
Photography mode: Documentary — real environment, unposed.
Layout: Split — photo left 55%, data panel right 45%.

```
┌──────────────────┬──────────────────┐
│                  │ AMSC logo        │  ← Oswald, opacity 70%
│  [DOCUMENTARY    │                  │
│   PHOTO —        │ EYEBROW          │  ← Oswald, red, tracked
│   TRAINING       │ [METRIC NAME]    │  ← Oswald, white, H2
│   SESSION]       │ [NUMBER]         │  ← Antonio, 700, dominant
│                  │                  │
│                  │ [context line]   │  ← Barlow, grey, 1 sentence
│                  │ [METRIC 2]       │  ← Antonio, smaller
│                  │ [label 2]        │  ← Barlow, muted
│                  │                  │
│                  │ [LOCATION TAG]   │  ← Oswald, red border tag
└──────────────────┴──────────────────┘
```

Red accent: the lead metric number only.
Caption template: See Section 8.4 — Process Post caption.

---

**TEMPLATE 3 — THE ATHLETE SPEAKS POST**
*The athlete owns the claim. AMSC never speaks for them.*

Purpose: Athlete testimony — their words, their numbers, their story.
Photography mode: Hero or Documentary — athlete's choice of environment.
Layout: Sparse — photo dominant, quote anchored at bottom.

```
[ FULL BLEED ATHLETE PHOTO ]
┌─────────────────────────────────┐
│ AMSC logo [top-left]            │
│                                 │
│        [PHOTO DOMINATES]        │
│                                 │
│ ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ │  ← 0.5px rule
│ │ "Quote in athlete's own words │  ← Red 2px left border
│ │  referencing their result."   │  ← Barlow italic, white
│                                 │
│ ATHLETE NAME                    │  ← Oswald, white
│ Club · Title                    │  ← Barlow, grey
│ [KEY METRIC]                    │  ← Antonio, red — the number quoted
└─────────────────────────────────┘
```

Red accent: the metric the athlete references in their quote.
Rule: Never add AMSC commentary after the quote. The athlete is the last word.
Caption template: See Section 8.4 — Athlete Speaks caption.

---

**TEMPLATE 4 — THE DATA STORY POST**
*Before and after. The numbers tell the whole story.*

Purpose: Show measurable improvement over time — combine scores, performance deltas.
Photography mode: None required — data is the visual.
Layout: Dense — dark background, structured data grid, no photo needed.

```
┌─────────────────────────────────┐
│ AMSC logo [top-left]            │
│ EYEBROW · PERIOD                │  ← Oswald, red, tracked
│                                 │
│ ATHLETE NAME                    │  ← Oswald 700, white, dominant
│ Sport · Programme               │  ← Barlow, grey
│ ─────────────────────────────── │
│ BEFORE          AFTER           │  ← Oswald, muted / Oswald, white
│ [Number]   →   [Number]         │  ← Antonio large, → in red
│ [label]        [label]          │  ← Barlow, muted
│                                 │
│ [Second metric comparison]      │  ← Same structure, smaller
│ [Third metric comparison]       │
│ ─────────────────────────────── │
│ [One summary line]              │  ← Barlow, grey, italic
└─────────────────────────────────┘
```

Red accent: the delta arrow → between before and after numbers.
Caption template: See Section 8.4 — Data Story caption.

---

**AMSC Data Hierarchy for athlete content:**

| Data type | What it is | How to present it |
|---|---|---|
| Combine Score | Overall performance rating | Lead metric — Antonio large, one decimal |
| Delta | Improvement from baseline | Red accent — always as change, not absolute |
| Event result | Real competition outcome | Hero stat — what the training built toward |
| Training metric | Session-level data | Supporting context — smaller, beneath lead |
| Availability | Games played, sessions completed | Proof metric — "0 games missed" format |

**The data integration rule:**
Every metric shown must have a human anchor — a photo, a quote, or a real event.
Data without context is a spreadsheet. Data with context is a story.

### 6.2 Instagram Story (9:16)

```
┌─────────────────┐
│ AMSC logo       │  ← Top-left, clean zone or dark panel
│                 │
│                 │
│  [FULL BLEED    │
│   ATHLETE       │
│   PHOTO]        │
│                 │
│                 │
│ FIRST NAME      │  ← Oswald, white, massive
│ LAST NAME       │  ← Oswald, red, massive
│ ─────────────── │
│ 10.3  #7  2026  │  ← Antonio, three metrics
│ label label lbl │  ← Barlow caption row, tracked, muted
└─────────────────┘
```

### 6.3 PDF / Document Structure

**Page hierarchy:**
1. **Cover** — Brand moment. Sparse. Athlete or campaign photo. Red accent bar permitted.
2. **Executive Summary** — Dense. Key data front-loaded. One page.
3. **Section Openers** — Sparse. Large section title. Dark background. Red rule.
4. **Content Pages** — Dense. Data, copy, structured zones. Grid-locked.
5. **Data Pages** — Dense. Tables, metrics, charts. Clean, no decoration.
6. **Closing Page** — Sparse. Tagline. Logo. Contact. Clean.

**Document rules:**
- Page numbers: bottom-right, Barlow, muted grey
- Header bar: AMSC logo left, document title right, 0.5px bottom rule
- Section labels: red eyebrow above every major section heading
- All tables: 0.5px borders, alternating `#1a1a1a` / `#0d0d0d` row fills
- Charts and data visualisations: dark background, red as primary data colour,
  grey for secondary series

### 6.4 Presentation Slide Structure

**Slide types:**

| Type | Layout | Purpose |
|---|---|---|
| Cover | Sparse | Brand moment, topic, event |
| Section opener | Sparse | Transition between major sections |
| Data slide | Dense | Metrics, results, comparisons |
| Proof slide | Hybrid | Athlete photo + stats side by side |
| Quote slide | Sparse | Athlete or partner testimony |
| Closing | Sparse | CTA, contact, tagline |

**Slide rules:**
- Slide title: always top-left, Oswald, uppercase
- Slide number: bottom-right, muted, small
- AMSC logo: bottom-left or top-right, consistent across deck
- Maximum 3 points per content slide — if more, split into two slides
- Never use default presentation template elements (clip art, generic shapes,
  gradient fills, drop shadows)

### 6.5 Graphic Compositions (Standalone)

For infographics, combine results graphics, report covers, and event materials:

- Establish a clear **anchor point** — the most important element (athlete name,
  key metric, event title) placed first in visual hierarchy
- Build outward from the anchor — supporting elements in descending size
- Use grid lines as invisible structure — content should feel organised even
  without visible borders
- Red appears once per graphic as the dominant accent moment
- AMSC logo and handle always present — top zone or bottom zone, never mid-layout

---

## 7. DESIGN RULES

### 7.1 Always Do
- Establish visual hierarchy before placing any element
- Make the athlete's name or achievement the largest text on athlete content
- Keep AMSC branding legible, quiet, and consistently placed
- Use red once — on the element that matters most
- Apply the correct photography mode before treating any image
- Ensure the logo has a clean, unobstructed zone
- Use negative space deliberately — empty space is not wasted space in sparse layouts
- Anchor dense layouts with a strong metric number
- Test the layout at a glance: can the hierarchy be read in under 2 seconds?

### 7.2 Never Do
- Use red as a fill on large background zones (outside cover exceptions)
- Place the AMSC logo over a busy photo zone without a contrast fix
- Make the AMSC brand larger or more dominant than the athlete's name
- Use more than two typefaces in one layout
- Add decorative elements that carry no information
- Use gradients, drop shadows, or glows on text
- Use light or grey backgrounds on athlete photo content — kills the cinematic feel
- Crop an athlete's face or key body line without clear artistic intent
- Use all-caps on body text
- Introduce colours outside the AMSC palette

### 7.3 Quality Test
Before finalising any output, ask:
1. Can I identify the most important element within 2 seconds?
2. Is the athlete clearly the protagonist?
3. Is the AMSC logo legible but not competing?
4. Is red used in exactly one dominant zone?
5. Does the layout feel like it belongs next to Altis, EXOS, or Momentous?
6. Would this embarrass or elevate the AMSC brand?

If any answer is unsatisfactory — revise before delivering.

---

## 8. TONE & VOICE

### 8.1 Brand Voice Principles
- **Direct** — say exactly what needs to be said, nothing more
- **Instructional** — precision over persuasion
- **Performance-focused** — every word earns its place
- **Confident without arrogance** — the work speaks, not the brand
- **No fluff** — eliminate adjectives that don't add information

### 8.2 Copy Patterns

**Headline patterns:**
- `[VERB] FOR [OUTCOME].` → Built for Speed. Trained for Pressure.
- `[NUMBER] + [ACHIEVEMENT]` → 0 Games Missed. 5× National Tours.
- `[ATHLETE NAME]` alone as a headline — let the name carry the weight

**Eyebrow label patterns:**
- `CATEGORY · SPORT` → Athlete Spotlight · Basketball
- `CONTEXT · YEAR` → Kenya 2026 · Sprint
- `EVENT · LOCATION` → AMSC Combine · Nairobi

**Avoid:**
- Exclamation marks
- Emojis in designed content
- Motivational filler ("crushing it", "on fire", "beast mode")
- Passive constructions
- Long sentences in headlines — maximum 5 words

### 8.3 Data as Copy
When presenting athlete metrics, lead with the number — not the label.
`10.3` then `100M PB` below.
Never: `100M Personal Best: 10.3 seconds`
The number is the story. The label is the context.

---

### 8.4 Caption System — Athlete Content

Each of the four athlete content templates (Section 6.1) has a dedicated
caption structure. Apply the matching caption every time.

**Universal caption rules — apply to all four templates:**
- Lead with the number, never the label
- Maximum 3 lines of copy — precision over persuasion
- No exclamation marks — confidence doesn't need them
- No adjectives that aren't data — "incredible" means nothing, "10.3" means everything
- The athlete's name is always the last or only attribution line
- AMSC never claims the result — the athlete does
- No motivational filler — no "beast mode", "crushing it", "on fire"

---

**CAPTION 1 — Result Post**

Structure:
```
[NUMBER]. [What it represents in one word or phrase].
[One sentence — what the athlete did to get there].
[Athlete name]. [Club / Event / Context].
```

Example — Simani Regau:
```
10.3. Kenya's fastest this season.
Eight weeks. One system. Zero shortcuts.
Simani Regau. 2026 Kenya Sprint Rankings.
```

Example — Mohammed Bajaber:
```
KPL Champion. Then Simba FC.
The body was ready. The data said so.
Mohammed Bajaber. Built at AMSC.
```

---

**CAPTION 2 — Process Post**

Structure:
```
[What we measured]. [What we found].
[One behaviour that drove the result].
[Athlete name] is building something.
```

Example:
```
Acceleration. Up 12% in six weeks.
Three sessions a week. Same track. Different athlete.
Mohammed Bajaber is building something.
```

Example — training session content:
```
Force. Measured. Applied. Repeated.
This is what sport-specific conditioning looks like.
The work continues. Nairobi, Kenya.
```

---

**CAPTION 3 — Athlete Speaks Post**

Structure:
```
"[Athlete quote — their words, their numbers, nothing added]"
— [Athlete name], [Title / Club]
```

Rules:
- Never paraphrase the athlete — use their exact words
- Never add AMSC commentary after the dash attribution
- The quote must reference a specific number or result
- If no quote is available — do not use this template

Example — Derrick Ogechi:
```
"Best condition of my whole professional career.
AMSC played a vital role — zero games missed."
— Derrick Ogechi, Nairobi City Thunder Captain
```

---

**CAPTION 4 — Data Story Post**

Structure:
```
[Before number] became [after number].
[Time period]. [How — one phrase].
This is what the work produces.
```

Example:
```
74 became 91.
Eight weeks. Sport-specific conditioning.
This is what the work produces.
```

Example — multi-metric:
```
Slower. Weaker. Less available.
Then AMSC Metrics found the gaps.
The numbers changed. So did the season.
[Athlete name]. [Sport]. [Club].
```

---

**Hashtag guidance:**
AMSC content does not rely on volume hashtags. Use a maximum of 5, all specific:
- `#AMSCPerformance` — always included
- `#AMSCMetrics` — when data is the primary content
- `#AMSCCombine` — when combine scores are shown
- One sport-specific tag — `#KenyaFootball`, `#EastAfricaSprints`, `#BALAfrica`
- One location tag — `#Nairobi` or `#Kenya`

Never use generic fitness hashtags — `#gains`, `#grind`, `#hustle`, `#fitness`.
They undermine the elite positioning.

---

## 9. DECISION-MAKING GUIDELINES

When designing AMSC content, think in this order:

**Step 1 — Identify the protagonist**
Who or what is this content about? If it features an athlete, they lead.
If it is pure brand content, the message leads. Never AMSC itself.

**Step 2 — Identify the goal**
What must the viewer feel or know after seeing this?
- Feel inspired → Sparse, atmosphere photo, dominant headline
- Know the athlete's achievement → Hybrid, hero photo, stat bar
- Understand the data → Dense, metrics grid, structured layout
- Trust AMSC's credibility → Proof elements — named athletes, real numbers

**Step 3 — Select the layout mode**
Apply the Layout Decision Framework (Section 4).
Sparse / Dense / Hybrid — commit to one before placing elements.

**Step 4 — Place the anchor**
Every layout has one anchor — the largest, most important element.
Place it first. Build everything else around it.

**Step 5 — Apply red once**
Identify the single most important element that red should hit.
Apply it. Do not apply red to anything else on that layout.

**Step 6 — Check branding**
Is the logo legible and in a clean zone?
Is the handle present?
Is the tagline needed here?

**Step 7 — Run the quality test**
Apply all seven questions from Section 7.3 before delivering.

---

## 10. AMSC ASSET REFERENCE

### 10.1 Logo Files
| File | Description | Use on |
|---|---|---|
| Logo-01.png | Black on black | Internal / embossed |
| Logo-02.png | Red on black full logo | Dark backgrounds — primary |
| Logo-05.png | All black | Light backgrounds |
| Logo-13.png | Black with red accent | Neutral backgrounds |
| Logo-14.png | C-clock icon, red on black | Icon usage, app, favicon |

### 10.2 Contact & Handle
- Email: amscperformance@gmail.com
- Phone: +254 796 677 414
- Instagram: @amscperformance
- Location: The Courtyard, Vanga Rd, Nairobi, Kenya

### 10.3 Key Athletes (as of 2026)
- **Derrick Ogechi** — Nairobi City Thunder, National Team Captain, BAL Africa League
- **Simani Regau** — Sprint (100m / 200m), Kenya 2026 Rank #7, 10.3s PB
- **Mohammed Bajaber** — Explosive Forward, Simba FC (Tanzania), Kenya National Team, Kenya Premier League Champion, Kenya #7

---

## 11. ATHLETE CONTENT COMMUNICATION SYSTEM

This section governs how AMSC presents athletes across all content formats.
It is inspired by how WHOOP integrates data seamlessly into athlete lifestyle content —
adapted specifically for AMSC's brand philosophy, East African context, and athlete roster.

### 11.1 The Core Principle

> Data belongs to the athlete. AMSC provides the system. The athlete tells the story.

WHOOP never says "our data helped this athlete."
The athlete says it themselves — through their numbers.
AMSC operates the same way.

The goal of every piece of athlete content is to make three things true simultaneously:
1. The viewer sees the athlete as the protagonist
2. The data feels human — connected to a real moment, not a spreadsheet
3. AMSC's presence is felt but never stated

### 11.2 The Three Content Contexts

Every athlete content piece exists in one of three contexts.
Identify the context before selecting the template.

**CONTEXT A — Competition**
The athlete performed in a high-stakes environment.
The result is the story. The data validates it.
Use: Template 1 (Result Post) or Template 3 (Athlete Speaks)
Photo: Hero mode — athlete in the competitive environment
Data: Event result, ranking, milestone

**CONTEXT B — Training**
The work is ongoing. The process is the story.
Use: Template 2 (Process Post)
Photo: Documentary mode — real session, unposed
Data: Session metrics, training load, improvement indicators

**CONTEXT C — Transformation**
The athlete is measurably different from when they started.
The delta is the story. The comparison makes it real.
Use: Template 4 (Data Story Post)
Photo: Optional — data can stand alone
Data: Before/after comparison, combine scores, delta percentages

### 11.3 Data Presentation Standards

**The number always comes first.**
Never label then number. Always number then label.

```
CORRECT:   10.3          WRONG:   100m PB: 10.3s
           100m PB                (label leads, number buried)
```

**Deltas are always shown as change, never absolute.**
```
CORRECT:   ▲ +12%        WRONG:   91 (up from 74)
           Acceleration           (context buried in brackets)
```

**Three metrics maximum per layout.**
More than three creates noise. Pick the three that tell the complete story:
1. The headline metric — what defines this moment
2. The context metric — what explains the headline
3. The proof metric — what makes it undeniable

**Real numbers only.**
Never estimate, approximate, or generalise a metric in designed content.
If the exact number is unavailable — do not show a metric. Show a quote instead.

### 11.4 Photo and Data Coexistence Rules

When photo and data appear together, they must support each other — not compete.

**Photo carries the emotion. Data carries the proof.**

| Photo shows | Data should show |
|---|---|
| Athlete in competition | Competition result |
| Athlete training | Training metric |
| Athlete post-result | Career milestone |
| Athlete lifestyle moment | Availability / consistency metric |

**The data should feel like it was captured at the same moment as the photo.**
If the photo is from a night match — the data shown should be from that match or that season.
If the photo is from a training session — the data should be from that training cycle.
Mismatched data and photo context destroys credibility.

### 11.5 The Athlete Voice Standard

When the athlete's words appear in content, the following rules apply:

- Use exact quotes — never paraphrase
- The quote must reference a specific result or experience
- The quote is always the dominant text element when present
- AMSC never adds commentary after the athlete's quote
- The metric referenced in the quote must appear visually in the layout

**The sequence of authority in athlete content:**
```
1. The photo (the athlete's presence)
2. The quote (the athlete's voice)
3. The data (the athlete's proof)
4. The name (the athlete's identity)
--- [AMSC logo, quiet, present] ---
```

AMSC is always last. Always smallest. Always there.

### 11.6 Content Frequency and Mix

For a consistent, credible athlete content presence, follow this mix:

| Template | Frequency | Purpose |
|---|---|---|
| Result Post | After every major event or milestone | Authority — proof of level |
| Process Post | 2× per training cycle | Depth — show the system working |
| Athlete Speaks | When a genuine quote is available | Trust — the athlete validates AMSC |
| Data Story | After each AMSC programme cycle | Credibility — measurable transformation |

Never post data without context. Never post context without data.
The two always travel together.

### 11.7 The AMSC vs WHOOP Translation

| WHOOP does | AMSC equivalent |
|---|---|
| Recovery score overlay on lifestyle photo | Combine score overlay on training photo |
| HRV reading paired with morning routine | Session metric paired with court/track moment |
| Athlete shares their own WHOOP data | Athlete shares their AMSC Metrics result |
| Before/after behavioural data posts | Before/after combine score comparisons |
| Third parties post the data themselves | Athletes post their AMSC results organically |
| App UI screenshot as the design element | AMSC Metrics data as the design element |
| "Zero games missed" as a brand proof | "Zero games missed" as an athlete proof |

The difference: WHOOP is the hero of their own data.
AMSC is never the hero. The athlete always is.

---

---

## 12. DESIGN EXECUTION STACK

This section governs which tools to use to execute AMSC design work and how to use them
together. The brand rules in Sections 1–11 are always the foundation. The tools below
are the production engines that execute against those rules.

### 12.1 Tri-Engine Architecture

AMSC design uses three execution engines in a defined priority order.
The choice of engine depends on the task, the required output format, and the need
to compare output quality across tools.

---

**ENGINE 1 — Claude Design (Primary)**
*claude.ai/design — powered by Claude Opus 4.7*

Best for: athlete social content, marketing assets, presentations, campaign graphics,
landing pages, interactive prototypes, pitch decks, one-pagers.

Capabilities relevant to AMSC:
- Conversational design generation from natural language briefs
- Design system integration — upload this skill file at project start so every
  generated output inherits the AMSC brand automatically
- Inline commenting for targeted refinement
- Custom sliders for spacing, colour, and typography adjustments
- Export to PDF, PPTX, HTML, Canva
- Direct handoff to Claude Code for AMSC Metrics / Combine implementation

**How to use Claude Design for AMSC work:**
```
Step 1 — Create a project, upload this SKILL.md as design system context
Step 2 — Describe the output using AMSC template language:
          "Template 1 Result Post — Mohammed Bajaber, Simba FC transfer,
           Hero photo mode, hybrid layout, KPL Champion as headline metric"
Step 3 — Iterate via chat using brand vocabulary from this skill
Step 4 — Use inline comments for element-level adjustments
Step 5 — Export to required format or hand off to Claude Code
```

---

**ENGINE 2 — Stitch MCP (Secondary)**
*Used directly inside Claude Code sessions — no browser required*

Best for: rapid UI screen generation, AMSC Metrics mockups, AMSC Combine interfaces,
design system variant generation, in-session design work without switching tools.

Key tools:
- `create_design_system` — encode AMSC tokens (colours, type, spacing) as a reusable system
- `generate_screen_from_text` — generate screens from AMSC template descriptions
- `apply_design_system` — enforce AMSC brand on any generated screen
- `generate_variants` — iterate across athletes, formats, or layout modes
- `edit_screens` — refine output

**When to use Stitch over Claude Design:**
- You are already working inside a Claude Code session
- The task is a digital product screen rather than marketing content
- You need to generate multiple variants quickly for comparison
- You do not need the full Claude Design canvas experience

---

**ENGINE 3 — Figma (Tertiary)**
*Used via Figma MCP + figma:* skills*

Best for: component libraries, design tokens, precise developer handoff, production-ready
component documentation, Code Connect mappings between Figma and codebase.

Skills required:
- `figma:figma-use` — mandatory prerequisite, always invoke first
- `figma:figma-generate-design` — generate brand-compliant layouts
- `figma:figma-generate-library` — build the AMSC component library
- `figma:figma-implement-design` — Figma → production code
- `figma:figma-code-connect` — map Figma components to codebase components

**When to use Figma over the other engines:**
- Building or maintaining the AMSC master component library
- Producing developer handoff specs for AMSC Metrics or Combine
- Precise design token documentation (variables, colour styles, text styles)
- Any output that will be handed directly to a developer as a Figma file

---

### 12.2 Comparison Workflow

When output quality needs to be evaluated across engines, run the same brief
through all three and judge using `design:design-critique` as the scoring layer.

```
Brief                    Engines                    Judge
─────────────────────────────────────────────────────────
Same AMSC brief  →  Claude Design output  ─┐
Same AMSC brief  →  Stitch MCP output     ─┼→  design:design-critique
Same AMSC brief  →  Figma output          ─┘   (Section 7.3 quality test)
                                                    ↓
                                          Best output wins
                                                    ↓
                                          design:design-handoff
```

**What to compare:**
- Brand compliance — does it match Sections 2 and 3 without deviation?
- Hierarchy clarity — 2-second test (Section 7.3, Question 1)
- Athlete protagonist rule — is the athlete the dominant element?
- Red discipline — one accent zone only
- Export quality — does it hold at actual output dimensions?

The engine that wins on a given content type becomes the default for that type.
Document your findings so future sessions default to the right engine faster.

---

### 12.3 Supporting Skill Stack

These skills support all three engines. Load them as needed — they do not replace
this skill, they augment it.

| Skill | When to use |
|---|---|
| `ui-ux-pro-max` | All digital product work — AMSC Metrics, Combine, Fuel, Mavuno Basket |
| `design:design-system` | Formalising AMSC tokens for Figma variables or Stitch design system |
| `design:design-critique` | Judging any output against brand rules, especially in comparison runs |
| `design:design-handoff` | Generating developer specs from any engine's output |
| `design:accessibility-review` | WCAG audit on any AMSC digital product screen |
| `anthropic-skills:pptx` | Exporting directly to .pptx from any engine |
| `anthropic-skills:pdf` | Exporting directly to PDF from any engine |
| `anthropic-skills:web-artifacts-builder` | Building interactive web artifacts from Claude Design handoffs |
| `content-creator` | Generating captions and copy using the Section 8.4 caption system |
| `senior-frontend` | Implementing any engine's output as production code |

---

### 12.4 Engine Selection Guide

| Content type | Primary engine | Secondary | Notes |
|---|---|---|---|
| Athlete social post (1:1, 9:16) | Claude Design | Stitch | Use Section 6.1 template language in brief |
| Campaign graphic | Claude Design | Canvas design | Sparse layout, Hero photography mode |
| Presentation / deck | Claude Design | PPTX skill | Export to PPTX after generation |
| PDF document / proposal | Claude Design | PDF skill | Follow Section 6.3 page hierarchy |
| AMSC Metrics UI screen | Stitch | Claude Design | Use `ui-ux-pro-max` alongside |
| AMSC Combine interface | Stitch | Figma | Data-dense, apply dense layout rules |
| Component library | Figma | — | `figma:figma-generate-library` |
| Developer handoff | Figma | — | `figma:figma-implement-design` + `design:design-handoff` |
| Quality comparison | All three | — | Run Section 12.2 comparison workflow |

---

---

## 13. IMAGE GENERATION PROMPT MODIFIER

Use this section whenever an AI image needs to be generated or edited for AMSC.

**Workflow:**
1. Claude assembles the full prompt from this section (Base Modifier + Sport block + Mode block + specific brief)
2. Claude outputs it as a single copyable block in the chat
3. Arnold pastes it directly into ChatGPT (chat.openai.com) and runs it

No automation. No API. Claude builds the prompt — Arnold pastes it.
Do not improvise brand parameters — always assemble from the blocks below.

### 13.1 Base Modifier (Universal)

Prepend to every AMSC image generation prompt without exception:

```
dark background, deep black (#000000) base, AMSC red accent (#a60a08) used once
as a single dominant colour moment, editorial sports performance aesthetic,
cinematic lighting with strong directional shadows, Oswald Bold typography where
text is present, athlete as visual protagonist, Nike/NBA/EXOS visual language,
no gradients, no light backgrounds, no decorative elements, high contrast,
photorealistic, professional sports photography quality
```

### 13.2 Sport-Specific Additions

Append the relevant block after the base modifier based on athlete sport:

**Basketball**
```
basketball court environment or arena context, competitive intensity,
peak action or post-result raw emotion, Kenya basketball or BAL Africa League context
```

**Sprint / Track**
```
track and field environment, explosive starting position or peak velocity,
motion blur on background to emphasise speed, Kenya athletics aesthetic
```

**Football**
```
football pitch or training ground, dynamic positional play or aerial moment,
East African football context, kit-forward framing
```

### 13.3 Photography Mode Additions

Append the relevant block based on the Section 5 photography mode selected:

**MODE 1 — Hero**
```
full bleed athlete portrait, subject sharp and dominant, dark vignette on lower
third, competitive environment, athlete facing camera or in peak action
```

**MODE 2 — Atmosphere**
```
athlete partially abstracted, dark overlay treatment, large negative space
for typography, mood-forward composition
```

**MODE 3 — Documentary**
```
raw training footage aesthetic, real environment (track/court/gym),
unposed, authentic moment, minimal treatment
```

### 13.4 Usage Pattern

Assemble: `[Base Modifier] + [Sport block] + [Mode block] + [Specific brief]`

Output as a single copyable block for Arnold to paste into ChatGPT.

**Example output — Simani Regau sprint post, Hero mode:**

---
*Copy everything below this line into ChatGPT:*

dark background, deep black (#000000) base, AMSC red accent (#a60a08) used once as a single dominant colour moment, editorial sports performance aesthetic, cinematic lighting with strong directional shadows, Oswald Bold typography where text is present, athlete as visual protagonist, Nike/NBA/EXOS visual language, no gradients, no light backgrounds, no decorative elements, high contrast, photorealistic, professional sports photography quality, track and field environment, explosive starting position or peak velocity, motion blur on background to emphasise speed, Kenya athletics aesthetic, full bleed athlete portrait, subject sharp and dominant, dark vignette on lower third, competitive environment, athlete facing camera or in peak action, Simani Regau, Kenya sprinter, 100m block start, Nairobi 2026

---

### 13.5 What Not to Add

Never add to an AMSC image generation prompt:
- White or light backgrounds
- Gradient fills or lens flares
- Multiple red elements ("red shoes and red jersey and red background")
- Generic fitness/gym stock photo descriptors ("motivational", "inspiring", "powerful")
- Emoji or decorative overlay descriptions
- Any colour outside the AMSC palette

---

*This skill file is a living document. Update after every major design iteration,
new content format, or brand evolution decision.*
*Version 1.0 — Built in session with Arnold, April 2026.*
*Version 2.0 — Upgraded with Athlete Content Communication System, four social templates,*
*full caption system, data presentation standards, and WHOOP-inspired content framework.*
*April 2026.*
*Version 3.0 — Added Design Execution Stack (Section 12): tri-engine architecture*
*(Claude Design primary, Stitch secondary, Figma tertiary), comparison workflow,*
*supporting skill stack, engine selection guide, and ui-ux-pro-max integration.*
*May 2026.*
*Version 4.0 — Added Image Generation Prompt Modifier (Section 13): base modifier,*
*sport-specific additions, photography mode additions, usage pattern, and guard rules.*
*ChatGPT (GPT-4o) set as primary image generation tool, replacing Nano Banana.*
*May 2026.*
