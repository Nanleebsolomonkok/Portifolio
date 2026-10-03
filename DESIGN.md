---
name: Obsidian Emerald Engine
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#3a3939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1c1b1b'
  surface-container: '#201f1f'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353534'
  on-surface: '#e5e2e1'
  on-surface-variant: '#bccbb9'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#869585'
  outline-variant: '#3d4a3d'
  surface-tint: '#4ae176'
  primary: '#4be277'
  on-primary: '#003915'
  primary-container: '#22c55e'
  on-primary-container: '#004b1e'
  inverse-primary: '#006e2f'
  secondary: '#4edea3'
  on-secondary: '#003824'
  secondary-container: '#00a572'
  on-secondary-container: '#00311f'
  tertiary: '#7cd0ff'
  on-tertiary: '#00354a'
  tertiary-container: '#2eb7f2'
  on-tertiary-container: '#00455f'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#6bff8f'
  primary-fixed-dim: '#4ae176'
  on-primary-fixed: '#002109'
  on-primary-fixed-variant: '#005321'
  secondary-fixed: '#6ffbbe'
  secondary-fixed-dim: '#4edea3'
  on-secondary-fixed: '#002113'
  on-secondary-fixed-variant: '#005236'
  tertiary-fixed: '#c4e7ff'
  tertiary-fixed-dim: '#7bd0ff'
  on-tertiary-fixed: '#001e2c'
  on-tertiary-fixed-variant: '#004c69'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353534'
typography:
  display-hero:
    fontFamily: Space Grotesk
    fontSize: 56px
    fontWeight: '700'
    lineHeight: 64px
    letterSpacing: -0.03em
  display-hero-mobile:
    fontFamily: Space Grotesk
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Space Grotesk
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Space Grotesk
    fontSize: 26px
    fontWeight: '600'
    lineHeight: 34px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Space Grotesk
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Space Grotesk
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 26px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: -0.005em
  body-md:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0em
  body-sm:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Space Grotesk
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.06em
  code-sm:
    fontFamily: JetBrains Mono
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: -0.01em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 4rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
  space-2xl: 4rem
  space-3xl: 6rem
---

## Brand & Style

This design system establishes a high-conviction, authoritative technical presence tailored for elite academic admissions committees and FAANG technical recruiters. It communicates mathematical rigour, architectural engineering maturity, and vibrant African momentum.

### Aesthetic Foundation
- **Linear & Vercel Utility Meets Academic Precision:** Deep layered dark surfaces, crisp sub-pixel borders, frosted translucency, and structured structural data layouts.
- **Tone & Mood:** Cerebral, understated, sovereign, and razor-sharp. It eschews generic portfolio animations in favor of calibrated micro-interactions, low-latency responsiveness, and dense, content-first narratives.
- **Target Audience Response:** Evaluators must immediately sense technical depth, high taste, precision craftsmanship, and unshakeable competence.

## Colors

The palette is engineered specifically for deep-dark displays, optimizing legibility, contrast, and cognitive focus.

### Palette Architecture
- **Primary Emerald (`#22C55E`):** Represents vitality, algorithmic precision, and growth. Applied strictly to focal points, active state indicators, pipeline completion tags, and interactive primary actions.
- **Secondary Mint (`#10B981`):** A slightly deeper, blue-shifted green for structural badges, chart metrics, and interactive hover shifts.
- **Tertiary Cyan (`#38BDF8`):** Reserved for citations, external paper links, neural model benchmarks, and tokenized syntax highlights.
- **Obsidian Dark Canvas (`#0A0A0A`):** The foundational absolute base canvas.

### Surface Tiers
- **Canvas Base:** `#0A0A0A`
- **Surface Elevation 1 (Card/Container):** `rgba(17, 17, 17, 0.75)` with backdrop filter.
- **Surface Elevation 2 (Raised Modals / Flyouts):** `#161616`
- **Surface Elevation 3 (Hover States & Chips):** `rgba(34, 197, 94, 0.08)`

### Text Contrast Tiers
- **Text Primary:** `#F3F4F6` (95% neutral white) for high-focus reading.
- **Text Secondary:** `#9CA3AF` (Muted cool gray) for metadata, captions, and secondary copy.
- **Text Code/Accent:** `#86EFAC` (Soft emerald tint) for inline constants and parameters.
- **Border Ghost:** `rgba(255, 255, 255, 0.08)` default, transitioning to `rgba(34, 197, 94, 0.35)` on hover.

## Typography

Typography establishes an engineered, technical cadence across the interface.

- **Space Grotesk** governs all primary assertions, headings, impact metrics, and card titles, imparting a geometric, post-modern computing posture.
- **Inter** handles narrative exposition, case study problem spaces, and research writeups, ensuring pristine optical clarity down to small scales.
- **JetBrains Mono** serves technical tags, Git commit IDs, latency timings, runtime parameters, and mathematical proofs.

## Layout & Spacing

The layout is built upon an asymmetric, constrained 12-column grid system bounded at a maximum width of `1200px` for optimal reading scan lines.

### Structure & Responsive Rules
- **Desktop (>= 1024px):** Split-view layouts inspired by Brittany Chiang, pairing a sticky 5-column left panel (biography, live status, core indices, social handles) with a 7-column scrollable right stream (research papers, engineering case studies, academic milestones).
- **Tablet (768px - 1023px):** Fluid single column with a max reading measure of `680px`, section gaps collapse from `space-3xl` to `space-2xl`.
- **Mobile (< 768px):** Single-column stacked stream. Side navigation transforms into a bottom-floating glass dock. Margin shifts to `1.25rem` to maximize horizontal real estate.

## Elevation & Depth

Depth is established via frosted translucent planes and directional light refraction rather than standard heavy drop shadows.

### Glassmorphism & Light
- **Base Surfaces:** `rgba(17, 17, 17, 0.70)` with `backdrop-filter: blur(16px) saturate(180%)`.
- **Borders:** `1px solid rgba(255, 255, 255, 0.07)`.
- **Active / Hover State Glow:** On cursor hover, the border shifts to `rgba(34, 197, 94, 0.40)` paired with an ambient backlight:
  `box-shadow: 0 0 24px -4px rgba(34, 197, 94, 0.12), 0 8px 16px -6px rgba(0, 0, 0, 0.6)`.
- **Spotlight Gradient:** Cards utilize an interactive mouse-following radial overlay (`radial-gradient(400px circle at var(--mouse-x) var(--mouse-y), rgba(34, 197, 94, 0.06), transparent 80%)`).

## Shapes

The interface balances sharp industrial geometry with soft, modern touch surfaces.

- **Panels & Cards:** `12px` to `16px` border-radius (`rounded-lg` / `rounded-xl`).
- **Interactive Buttons & Badges:** `8px` (`rounded-base`) for crisp structural integrity.
- **Status Indicators & Avatars:** Fully circular (`rounded-full`) to contrast against rectilinear card grids.

## Components

### Interactive Elements & Cards
- **Project & Research Cards:** Frosted glass containers featuring top-right outbound micro-arrows (`↗`) that translate `+2px, -2px` on hover. Cards include an interactive radial cursor-glow, a subtle top hairline border (`rgba(255, 255, 255, 0.12)`), and embedded tag lists.
- **Buttons (Primary):** Solid `#22C55E` background with `#0A0A0A` bold text. Subtle inner glow (`inset 0 1px 0 rgba(255, 255, 255, 0.25)`). Focus states feature a `2px` offset emerald ring.
- **Buttons (Secondary / Ghost):** `rgba(255, 255, 255, 0.04)` fill, `1px solid rgba(255, 255, 255, 0.08)`, text `#F3F4F6`. Shifts to `rgba(34, 197, 94, 0.1)` on hover with emerald text.
- **Tech Stack & Academic Chips:** Built with JetBrains Mono, pill-shaped or soft-rounded (`rounded-md`), featuring low-opacity tint backgrounds (`rgba(34, 197, 94, 0.08)`), muted green borders (`rgba(34, 197, 94, 0.2)`), and text `#86EFAC`.

### Trust Signals & Data Displays
- **Live Status Beacon:** A pulsing radial pill indicator (`Available for Fall 2025 Master's / Google AI`) with an emerald core pinging via CSS keyframe ripples.
- **Research Citation / Metric Badges:** Dense monospaced rows with high contrast keys and muted values (e.g., `Top 1% Class Rank`, `NeurIPS Workshop Accepted`, `99.2% Test Accuracy`).
- **Code Snippet / Terminal Window:** Mac-style triple window dots in obsidian containers with copy-to-clipboard micro-states and syntax-highlighted ML pipeline pseudocode.