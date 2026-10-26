---
name: Quiet Architectural Luxury
colors:
  surface: '#fbf9f5'
  surface-dim: '#dbdad6'
  surface-bright: '#fbf9f5'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3ef'
  surface-container: '#efeeea'
  surface-container-high: '#eae8e4'
  surface-container-highest: '#e4e2de'
  on-surface: '#1b1c1a'
  on-surface-variant: '#494740'
  inverse-surface: '#30312e'
  inverse-on-surface: '#f2f0ed'
  outline: '#7a776f'
  outline-variant: '#cbc6bd'
  surface-tint: '#605e5b'
  primary: '#010101'
  on-primary: '#ffffff'
  primary-container: '#1d1c1a'
  on-primary-container: '#878481'
  inverse-primary: '#cac6c2'
  secondary: '#6e5c39'
  on-secondary: '#ffffff'
  secondary-container: '#f6ddb0'
  on-secondary-container: '#72603d'
  tertiary: '#010100'
  on-tertiary: '#ffffff'
  tertiary-container: '#1e1c16'
  on-tertiary-container: '#88847b'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e6e2de'
  primary-fixed-dim: '#cac6c2'
  on-primary-fixed: '#1c1b19'
  on-primary-fixed-variant: '#484644'
  secondary-fixed: '#f8dfb3'
  secondary-fixed-dim: '#dbc499'
  on-secondary-fixed: '#261a01'
  on-secondary-fixed-variant: '#554524'
  tertiary-fixed: '#e8e2d8'
  tertiary-fixed-dim: '#cbc6bc'
  on-tertiary-fixed: '#1e1b16'
  on-tertiary-fixed-variant: '#4a463f'
  background: '#fbf9f5'
  on-background: '#1b1c1a'
  surface-variant: '#e4e2de'
typography:
  display:
    fontFamily: EB Garamond
    fontSize: 96px
    fontWeight: '400'
    lineHeight: 94px
    letterSpacing: -0.02em
  display-mobile:
    fontFamily: EB Garamond
    fontSize: 48px
    fontWeight: '400'
    lineHeight: 50px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: EB Garamond
    fontSize: 64px
    fontWeight: '400'
    lineHeight: 68px
    letterSpacing: -0.015em
  headline-lg-mobile:
    fontFamily: EB Garamond
    fontSize: 36px
    fontWeight: '400'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: EB Garamond
    fontSize: 40px
    fontWeight: '400'
    lineHeight: 46px
  headline-sm:
    fontFamily: EB Garamond
    fontSize: 28px
    fontWeight: '400'
    lineHeight: 34px
  body-lg:
    fontFamily: Inter
    fontSize: 17px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: -0.005em
  body-md:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
  eyebrow:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.14em
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 18px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.08em
rounded:
  sm: 0.5rem
  DEFAULT: 1rem
  md: 1.5rem
  lg: 2rem
  xl: 3rem
  full: 9999px
spacing:
  gutter: 2rem
  margin: 3.5rem
  space-xs: 0.5rem
  space-sm: 1rem
  space-md: 1.5rem
  space-lg: 2.5rem
  space-xl: 4rem
  space-2xl: 8.75rem
---

## Brand & Style

This design system channels an atmosphere of quiet luxury, architectural rigor, and cinematic stillness tailored for high-end residential renovation. The visual language favors editorial restraint over ornamentation, mirroring physical architectural materials like lime-wash plaster, honed stone, and patinated metals.

- **Tone & Atmosphere:** Poised, monolithic, warm, and highly curated. Interfaces must evoke the tactile calm of a private gallery or a bespoke architectural monograph.
- **Visual Aesthetic:** Minimalist editorial combined with tactile structure. Compositions rely on asymmetric balance, generous structural negative space, and disciplined hairline frameworks rather than heavy drop shadows or structural volume.
- **Imagery Art Direction:** Cinematic, medium-format architectural photography featuring natural side-light, deep shadows, and genuine material textures. Media surfaces are dominant anchors within the composition.

## Colors

The palette is derived from raw, unlacquered interior finishes and mineral surfaces:

- **Warm White (`#FAF8F4`):** Canvas base, evocative of polished microcement and natural plaster.
- **Bone (`#EFEBE4`):** Secondary surface background used for cards, inset panels, and structural grouping.
- **Charcoal (`#1D1C1A`):** Primary tone for high-contrast typography, primary actions, and solid framing.
- **Champagne (`#CDB68C`):** Subdued metallic accent used sparingly for hairline borders, focused states, and key interactive highlights. Hairline rules always render this tone at `rgba(205, 182, 140, 0.4)`.
- **Muted (`#77736B`):** Secondary text and subtle informational metadata, providing clear hierarchy while maintaining a soft, non-jarring contrast.

## Typography

The type system balances classical serif proportions with precise, modernist sans-serif utility.

- **Headlines & Display:** Set in high-contrast, graceful serif styling to mirror bespoke editorial layouts. Tight negative leading on large display sizes creates architectural density and gravitas.
- **Body:** Inter at `17px` provides exceptional legibility against warm background tints without drawing attention away from imagery.
- **Eyebrows & Overlines:** Always set to `12px` uppercase with strict `0.14em` tracking in either Charcoal or Muted tones. Never mix tracking values across functional labels.

## Layout & Spacing

Layouts conform to a 12-column symmetrical grid structured by wide margins and deliberate breathing room.

- **Vertical Cadence:** Section blocks maintain a standard vertical padding of `140px` (`8.75rem` / `space-2xl`) on desktop, dropping to `80px` on tablet and `56px` on mobile. Negative space is treated as an active material element, never compressed unnecessarily.
- **Breakpoints:**
  - **Desktop (1440px+):** 12 columns, 32px gutters, 56px canvas margins. Maximum content boundary capped at 1600px.
  - **Tablet (768px – 1439px):** 8 columns, 24px gutters, 40px canvas margins.
  - **Mobile (< 768px):** 4 columns, 16px gutters, 20px canvas margins.
- **Asymmetric Offsets:** Hero imagery and architectural project case studies should regularly span 7 to 8 columns, leaving 4 to 5 columns of pure negative space or single-column narrative text blocks.

## Elevation & Depth

Spatial layering is strictly tonal and planar, avoiding drop shadows or physical skeuomorphism:

- **Tonal Stepping:** Depth is achieved by placing Bone (`#EFEBE4`) containers onto Warm White (`#FAF8F4`) canvas fields, or through high-contrast Charcoal (`#1D1C1A`) monolithic blocks.
- **Hairline Dividers:** Surface planes and section boundaries are defined by sharp 1px borders rendered in champagne at 40% opacity (`rgba(205, 182, 140, 0.4)`).
- **Overlays & Drawers:** High-order modal states and navigation panels use a full-bleed backdrop blur (`backdrop-filter: blur(12px)`) tinted with Warm White at 85% opacity (`rgba(250, 248, 244, 0.85)`).
- **No Cast Shadows:** Dynamic shadows are forbidden across standard surfaces, preserving a crisp, graphic, and architectural finish.

## Shapes

The geometric architecture uses high, intentional curvature contrasts:

- **Image Containers:** Formed with a distinctive `32px` corner radius. This gives architectural photography a refined, framed aperture quality.
- **Cards & Sub-Containers:** Compact utility panels, specs sheets, and cards carry a `20px` radius.
- **Interactive Controls:** All buttons, status indicators, and pill badges carry full-radius ends (`9999px`).
- **Dividers & Borders:** Formed strictly with unbroken 1px hairlines without terminal rounding.

## Components

### Buttons
- **Primary:** Pill silhouette (`9999px`), Charcoal (`#1D1C1A`) background, Warm White (`#FAF8F4`) text. Padding: `16px 36px`. Typography: `label-md`. Hover transitions to Champagne (`#CDB68C`) text with subtle scale `1.01`.
- **Secondary / Outline:** Pill silhouette, transparent background, solid 1px hairline border in `rgba(205, 182, 140, 0.4)`. Text in Charcoal. Hover state fills background with Bone (`#EFEBE4`).
- **Text Action:** Unbordered, `eyebrow` styling with an underline offset of `6px` in Champagne.

### Cards & Inset Panels
- **Small / Spec Cards:** Bone (`#EFEBE4`) background, `20px` border radius, 1px border in `rgba(205, 182, 140, 0.4)`. Interior padding: `32px`.
- **Project Feature Cards:** Large full-bleed image container with `32px` corner radius, floating metadata block positioned at the base or offset into the adjacent grid column.

### Inputs & Form Controls
- **Text Inputs:** Minimalist flat presentation. Transparent background with a single 1px bottom border in `rgba(205, 182, 140, 0.4)`. Padding: `16px 0`. Focus state deepens border color to solid Charcoal (`#1D1C1A`) without focus rings. Placeholder text set in Muted (`#77736B`).
- **Checkboxes & Radios:** Sharp minimalist lines. Checkboxes use an unfilled square with a 1px border; checked state presents a solid Charcoal square inset. Radio circles use a centered dot indicator.

### Chips & Metadata Tags
- **Pill Badges:** Pill shape (`9999px`), padding `6px 16px`. Background Bone (`#EFEBE4`), text Charcoal (`#1D1C1A`). Typography: `eyebrow` (12px uppercase, `0.14em` tracking).

### Architectural Spec Sheets & Material Lists
- Striped or bordered rows separated by 1px champagne hairlines (`rgba(205, 182, 140, 0.4)`). Left side displays material code or category in `eyebrow`, right side displays the specification title in `body-lg`.