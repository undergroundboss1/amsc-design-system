# AMSC Performance — Design System

> **For Claude Design:** Start with `guidelines.md` for all brand rules, then `index.html` for visual component references. Use `tokens.css` for exact design token values. `SKILL.md` is the full skill file — upload it at project start to give Claude Design complete brand context.

---

## What This Repository Contains

| File | Purpose |
|---|---|
| `index.html` | Interactive design system v3.0 — colours, typography, logos, spacing, components, templates, brand rules, photography |
| `guidelines.md` | Complete brand and design rules in plain text — the authoritative reference for AI design tools |
| `tokens.css` | CSS custom properties — all design tokens as a standalone importable file |
| `SKILL.md` | Full AMSC brand skill — upload into Claude Design at project start |
| `amsc_design_system_v3.html` | Embeddable design system fragment — same content as index.html, no doctype wrapper |
| `logos/` | Logo asset library — 8 transparent PNGs (icon + wordmark × 4 colourways) |

---

## Logo Assets

The [`/logos`](logos) folder holds the full mark set as transparent PNGs (2084×2084). Naming: `amsc-[mark]-[colourway].png`.

| Colourway | Wordmark | Icon | Use on |
|---|---|---|---|
| Black + red (**primary**) | `amsc-wordmark-black-red.png` | `amsc-icon-black-red.png` | Light / neutral backgrounds, favicon |
| All red | `amsc-wordmark-red.png` | `amsc-icon-red.png` | Dark / black / photo backgrounds |
| All black (mono) | `amsc-wordmark-black.png` | `amsc-icon-black.png` | Light backgrounds, print |
| Red + black (alt) | `amsc-wordmark-red-black.png` | `amsc-icon-red-black.png` | Light / neutral backgrounds |

No off-white knock-out version exists yet — use the all-red mark on dark layouts until one is added.

---

## Quick Reference

### Colours
| Name | Hex | Use |
|---|---|---|
| AMSC Red | `#a60a08` | Primary accent — one dominant use per layout |
| Deep Red | `#820b0b` | Hover states |
| Black | `#000000` | Full-bleed backgrounds |
| Surface | `#1a1a1a` | Cards, panels |
| Off-White | `#f5f5f8` | All primary text |
| Grey | `#d3d3d3` | Subtext, labels |

### Fonts
| Font | Role | Use for |
|---|---|---|
| Oswald | Authority | Headlines, eyebrows, labels — always uppercase |
| Antonio | Data | All metrics, numbers, deltas |
| Barlow | Support | Body copy, captions, quotes |

### The Core Rule
> The athlete is always the protagonist. AMSC is always the coach in the corner.

### The Red Budget
Every layout gets **one dominant red moment**. Pick one: a red-backed headline highlight, a single hero metric in red, or one CTA. Structural red (bars, eyebrows, dividers, deltas, quote borders) is separate and doesn't count against the budget.

---

## How to Use with Claude Design

Point Claude Design at this repository. When generating any AMSC design:

1. Upload `SKILL.md` at project start — this gives Claude Design full brand context automatically
2. Read `guidelines.md` for brand rules
3. Reference `index.html` to see component specifications
4. Import `tokens.css` for exact CSS values
5. Apply the correct social template from the four defined in `guidelines.md`
6. Run the 6-point quality check before finalising

---

## The Four Social Templates

| Template | When | Layout |
|---|---|---|
| Result Post | After a competition result or milestone | Hybrid: photo 72% + stat bar 28% |
| Process Post | During a training cycle | Split: photo 55% / data panel 45% |
| Athlete Speaks | When a genuine quote is available | Sparse: photo dominant + quote bar |
| Data Story | After an AMSC programme cycle | Dense: before/after comparison grid |

---

## v3.0 Additions

- **Logos tab** — logo asset slots, two-mark system, clear space rules, icon watermark spec
- **The Red Budget** — dominant vs structural red distinction, squint test
- **Signature Elements** — four named AMSC design devices (red bars, headline highlight, stopwatch watermark, founder portrait)
- **Selective Desaturation** — the AMSC cover grade explained in Photography

---

*AMSC Performance Design System v3.0 — June 2026*
*Home to Elite Sports Performance*
