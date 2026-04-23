---
name: Threshold
description: Design system for AI x EI Conference 2026 — the moment education reclaims its AI narrative from Big Tech.
colors:
  background: "#08090d"
  surface: "#0f1117"
  surface-dim: "#08090d"
  surface-bright: "#1c1e2a"
  surface-container-lowest: "#05060a"
  surface-container-low: "#111320"
  surface-container: "#161825"
  surface-container-high: "#1c1e2a"
  surface-container-highest: "#252836"
  on-surface: "#e6e8f8"
  on-surface-variant: "#9296b0"
  inverse-surface: "#e6e8f8"
  inverse-on-surface: "#1c1e2a"
  outline: "#3a3d52"
  outline-variant: "#252836"
  primary: "#f4c430"
  on-primary: "#190e00"
  primary-container: "#3d2e00"
  on-primary-container: "#fde68a"
  primary-fixed: "#ffe082"
  primary-fixed-dim: "#f4c430"
  inverse-primary: "#6b4d00"
  secondary: "#38d9d9"
  on-secondary: "#002828"
  secondary-container: "#004444"
  on-secondary-container: "#9fffff"
  tertiary: "#c4b5fd"
  on-tertiary: "#2e1065"
  tertiary-container: "#4c1d95"
  on-tertiary-container: "#ede9fe"
  error: "#f87171"
  on-error: "#7f1d1d"
  error-container: "#991b1b"
  on-error-container: "#fecaca"
  surface-tint: "#f4c430"
typography:
  display-xl:
    fontFamily: Space Grotesk
    fontSize: 80px
    fontWeight: "800"
    lineHeight: 86px
    letterSpacing: -0.04em
  display-lg:
    fontFamily: Space Grotesk
    fontSize: 60px
    fontWeight: "700"
    lineHeight: 66px
    letterSpacing: -0.03em
  headline-lg:
    fontFamily: Space Grotesk
    fontSize: 40px
    fontWeight: "700"
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Space Grotesk
    fontSize: 28px
    fontWeight: "600"
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Space Grotesk
    fontSize: 20px
    fontWeight: "600"
    lineHeight: 28px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: "400"
    lineHeight: 30px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: "400"
    lineHeight: 26px
  label-lg:
    fontFamily: Space Grotesk
    fontSize: 13px
    fontWeight: "600"
    lineHeight: 18px
    letterSpacing: 0.12em
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: "600"
    lineHeight: 16px
    letterSpacing: 0.08em
  mono:
    fontFamily: "JetBrains Mono"
    fontSize: 13px
    fontWeight: "400"
    lineHeight: 22px
rounded:
  sm: 4px
  DEFAULT: 6px
  md: 10px
  lg: 14px
  xl: 20px
  2xl: 28px
  full: 9999px
spacing:
  unit: 8px
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px
  xl: 40px
  2xl: 64px
  slide-pad-x: 72px
  slide-pad-y: 52px
components:
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-primary}"
    typography: "{typography.label-lg}"
    rounded: "{rounded.md}"
    height: 44px
    padding: 0 20px
  button-primary-hover:
    backgroundColor: "{colors.primary-fixed}"
  button-ghost:
    backgroundColor: rgba(244, 196, 48, 0.08)
    textColor: "{colors.primary}"
    typography: "{typography.label-lg}"
    rounded: "{rounded.md}"
    height: 40px
    padding: 0 16px
  button-ghost-hover:
    backgroundColor: rgba(244, 196, 48, 0.15)
  card-surface:
    backgroundColor: "{colors.surface-container}"
    textColor: "{colors.on-surface}"
    rounded: "{rounded.lg}"
    padding: "{spacing.lg}"
  card-glass:
    backgroundColor: rgba(244, 196, 48, 0.04)
    textColor: "{colors.on-surface}"
    rounded: "{rounded.xl}"
    padding: "{spacing.lg}"
  card-glass-accent:
    backgroundColor: rgba(56, 217, 217, 0.06)
    textColor: "{colors.on-surface}"
    rounded: "{rounded.xl}"
    padding: "{spacing.lg}"
  card-danger:
    backgroundColor: rgba(248, 113, 113, 0.06)
    textColor: "{colors.on-surface}"
    rounded: "{rounded.xl}"
    padding: "{spacing.lg}"
  card-success:
    backgroundColor: rgba(74, 222, 128, 0.06)
    textColor: "{colors.on-surface}"
    rounded: "{rounded.xl}"
    padding: "{spacing.lg}"
  chip-primary:
    backgroundColor: rgba(244, 196, 48, 0.12)
    textColor: "{colors.primary}"
    rounded: "{rounded.full}"
    padding: 3px 12px
  chip-secondary:
    backgroundColor: rgba(56, 217, 217, 0.1)
    textColor: "{colors.secondary}"
    rounded: "{rounded.full}"
    padding: 3px 12px
  chip-danger:
    backgroundColor: rgba(248, 113, 113, 0.1)
    textColor: "{colors.error}"
    rounded: "{rounded.full}"
    padding: 3px 12px
  chip-success:
    backgroundColor: rgba(74, 222, 128, 0.1)
    textColor: "#4ade80"
    rounded: "{rounded.full}"
    padding: 3px 12px
  eyebrow:
    textColor: "{colors.secondary}"
    typography: "{typography.label-lg}"
  code-block:
    backgroundColor: "{colors.surface-container-lowest}"
    textColor: "{colors.on-surface}"
    rounded: "{rounded.md}"
    padding: "{spacing.md}"
  input-field:
    backgroundColor: "{colors.surface-container-lowest}"
    textColor: "{colors.on-surface}"
    typography: "{typography.body-md}"
    rounded: "{rounded.md}"
    padding: 10px 14px
  input-field-focus:
    backgroundColor: "{colors.surface-container-lowest}"
    textColor: "{colors.on-surface}"
---

## Brand & Style

**Threshold** captures the precise moment that educational AI crosses from corporate dependency to community ownership — a liminal space between darkness and the first light of an eclipse.

The aesthetic is *Cosmic Editorial*: obsidian-dark surfaces, Space Grotesk geometric headlines, and a warm gold/amber primary accent that evokes the corona flash of the sun breaking through. Glassmorphism is used sparingly — only for cards that need to feel "floating" or interactive. The design should feel premium without being cold; confident without being arrogant.

The emotional register is: "You already have the power. Here's how to use it."

## Colors

The palette is built around a central metaphor: light breaking through darkness.

- **Primary (#f4c430 — Solar Gold):** The corona. Every important CTA, headline accent, and data point uses this colour. It represents knowledge, warmth, and the dawn of educator agency. Never use on light backgrounds.
- **Secondary (#38d9d9 — Atmospheric Teal):** The sky during totality — clear, technical, precise. Used for technical callouts, badges, and secondary interactive elements.
- **Tertiary (#c4b5fd — Deep Indigo):** The depth of space. Used sparingly for additional depth or decorative accents.
- **Background (#08090d):** Near-void black with a cool blue undertone. Creates maximum depth for the gold and teal to pop against.
- **Surface hierarchy:** Four surface levels stepping from `#08090d` to `#252836` create layered glass effects.

Gradient backgrounds on key slides: deep radial gradients from `tertiary-container` (#4c1d95) at the focal centre to `background` (#08090d) at the edges — the eclipse halo effect.

## Typography

Dual-font system: Space Grotesk anchors all headlines with a geometric, slightly technical personality. Inter handles body text with maximum legibility.

- **Hierarchy is critical:** `display-xl` for title slides only. `headline-lg` for slide headings. `headline-md` for card titles. `body-lg` for key prose. `body-md` for secondary prose.
- **Eyebrows:** Always Space Grotesk, `label-lg`, secondary colour, full uppercase, 0.12em letter spacing.
- **Code:** JetBrains Mono for all code snippets, muted syntax colouring.
- **Glow rule:** Apply a subtle primary-gold text-shadow (`0 0 40px rgba(244,196,48,0.3)`) to `display-xl` and `headline-lg` used on the darkest background slides.

## Layout & Spacing

Slides use an 8px base unit. Horizontal slide padding is 72px on desktop; vertical padding is 52px. Two-column grids use a 32px gap; three-column grids use a 24px gap. Cards within columns stack with a 16px gap.

Negative space is intentional: a crowded slide = a crowded mind. Prefer fewer, more impactful points per slide.

## Elevation & Depth

- **Level 0:** Raw background (#08090d)
- **Level 1:** Surface container for base cards
- **Level 2 (Glass):** `backdrop-filter: blur(16px)`, `background: rgba(244,196,48,0.04)`, `border: 1px solid rgba(244,196,48,0.12)` — primary glass
- **Level 3 (Glow):** Hover or active states emit an ambient glow using `box-shadow: 0 0 40px rgba(244,196,48,0.08), 0 8px 32px rgba(0,0,0,0.4)`

## Shapes

Consistent corner-radius scale applied across components. Cards at `rounded-xl` (20px). Buttons at `rounded-md` (10px). Chips at `rounded-full`. Code blocks at `rounded-md`. Never mix corner radius scales within the same visual group.

## Components

### Cards
Three card variants: `card-surface` (base, no glass), `card-glass` (gold-tinted glass, primary accent border), `card-glass-accent` (teal-tinted, secondary contexts). All cards share `rounded-xl` and `spacing.lg` padding.

### Buttons
Primary buttons use solid solar gold with dark text — maximum contrast. Ghost buttons use gold text on a translucent gold-tinted background. Both use Space Grotesk label-lg with generous letter spacing.

### Eyebrows & Labels
All section eyebrows: teal (`secondary`), Space Grotesk, uppercase, 0.12em tracking. They precede headlines and are 8px below the slide edge, 12px above the headline.

### Code Blocks
Dark container-lowest background, JetBrains Mono. Syntax: keywords in violet (#c792ea), strings in green (#c3e88d), comments in outline (#3a3d52), functions in cornflower (#82aaff), numbers in orange (#f78c6c).

## Do's and Don'ts

- **Do** use the primary gold accent only for genuinely important elements — not decoration
- **Do** let dark backgrounds breathe; resist the urge to fill every pixel
- **Do** pair every headline with an eyebrow in secondary/teal
- **Don't** use white text on gold backgrounds — always use `on-primary` (#190e00)
- **Don't** use more than two accent colours per slide
- **Don't** put code in a sans-serif font
