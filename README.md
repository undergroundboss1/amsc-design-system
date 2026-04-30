# AMSC Performance — Design System

> **For Claude Design:** Start with `guidelines.md` for all brand rules, then `index.html` for visual component references. Use `tokens.css` for exact design token values.

---

## What This Repository Contains

| File | Purpose |
|---|---|
| `index.html` | Interactive design system — colours, typography, spacing, all components, all 4 social templates, caption system, photography modes, brand rules |
| `guidelines.md` | Complete brand and design rules in plain text — the authoritative reference for AI design tools |
| `tokens.css` | CSS custom properties — all design tokens as a standalone importable file |

---

## Quick Reference

### Colours
| Name | Hex | Use |
|---|---|---|
| AMSC Red | `#a60a08` | Primary accent — one use per layout |
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

---

## How to Use with Claude Design

Point Claude Design at this repository. When generating any AMSC design:

1. Read `guidelines.md` for brand rules
2. Reference `index.html` to see component specifications
3. Import `tokens.css` for exact CSS values
4. Apply the correct social template from the four defined in `guidelines.md`
5. Run the 6-point quality check before finalising

---

## The Four Social Templates

| Template | When | Layout |
|---|---|---|
| Result Post | After a competition result or milestone | Hybrid: photo 72% + stat bar 28% |
| Process Post | During a training cycle | Split: photo 55% / data panel 45% |
| Athlete Speaks | When a genuine quote is available | Sparse: photo dominant + quote bar |
| Data Story | After an AMSC programme cycle | Dense: before/after comparison grid |

---

*AMSC Performance Design System v2.0 — April 2026*
*Home to Elite Sports Performance*
