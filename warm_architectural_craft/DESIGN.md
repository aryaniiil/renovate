---
name: Warm Architectural Craft
colors:
  surface: '#f9f9f7'
  surface-dim: '#dadad8'
  surface-bright: '#f9f9f7'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f4f4f2'
  surface-container: '#eeeeec'
  surface-container-high: '#e8e8e6'
  surface-container-highest: '#e2e2e1'
  on-surface: '#1a1c1b'
  on-surface-variant: '#4d4540'
  inverse-surface: '#2f3130'
  inverse-on-surface: '#f1f1ef'
  outline: '#7f7570'
  outline-variant: '#d0c4be'
  surface-tint: '#635d5a'
  primary: '#221e1b'
  on-primary: '#ffffff'
  primary-container: '#383330'
  on-primary-container: '#a39b97'
  inverse-primary: '#cec5c0'
  secondary: '#685c55'
  on-secondary: '#ffffff'
  secondary-container: '#edddd3'
  on-secondary-container: '#6c6059'
  tertiary: '#211f1a'
  on-tertiary: '#ffffff'
  tertiary-container: '#37342f'
  on-tertiary-container: '#a19c95'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#eae1dc'
  primary-fixed-dim: '#cec5c0'
  on-primary-fixed: '#1f1b18'
  on-primary-fixed-variant: '#4b4642'
  secondary-fixed: '#f0dfd6'
  secondary-fixed-dim: '#d3c3ba'
  on-secondary-fixed: '#221a14'
  on-secondary-fixed-variant: '#4f453e'
  tertiary-fixed: '#e8e1d9'
  tertiary-fixed-dim: '#ccc6be'
  on-tertiary-fixed: '#1e1b16'
  on-tertiary-fixed-variant: '#4a4640'
  background: '#f9f9f7'
  on-background: '#1a1c1b'
  surface-variant: '#e2e2e1'
typography:
  display:
    fontFamily: Inter
    fontSize: 56px
    fontWeight: '600'
    lineHeight: 64px
    letterSpacing: -0.03em
  display-mobile:
    fontFamily: Inter
    fontSize: 36px
    fontWeight: '600'
    lineHeight: 44px
    letterSpacing: -0.025em
  headline-lg:
    fontFamily: Inter
    fontSize: 40px
    fontWeight: '600'
    lineHeight: 48px
    letterSpacing: -0.03em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '500'
    lineHeight: 36px
    letterSpacing: -0.025em
  headline-sm:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '500'
    lineHeight: 28px
    letterSpacing: -0.02em
  editorial-accent:
    fontFamily: Newsreader
    fontSize: 24px
    fontWeight: '400'
    lineHeight: 32px
  editorial-accent-lg:
    fontFamily: Newsreader
    fontSize: 44px
    fontWeight: '400'
    lineHeight: 52px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: -0.01em
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
    letterSpacing: -0.005em
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
  label-md:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 18px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.04em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-sm: 1rem
  gutter-lg: 2rem
  margin: 2rem
  margin-sm: 1rem
  margin-lg: 4rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system serves high-end home renovation, bespoke joinery, and interior remodeling projects, merged seamlessly with the precision, density, and polish of modern elite SaaS products. The aesthetic merges tactile architectural materials (limestone, milled timber, linen, cast bronze) with crisp digital product craftsmanship (micro-interactions, structured bento surfaces, sub-pixel borders, refined status telemetry).

### Emotional Intention
- **Grounded Tactility:** Instills deep trust, tangible permanence, and architectural authenticity through warm stone neutrals and earthy undertones.
- **Engineered Precision:** Balances artisanal warmth with razor-sharp layouts, disciplined alignment, tight tracking, and structured milestone tracking reminiscent of high-end productivity tools.
- **Understated Elegance:** Eliminates overt ornamentation in favor of generous negative space, translucent glass layering, and deliberate typography hierarchy.

### Design Movement & Approach
The interface blends **Architectural Warm Minimalism** with **Modern Tactile SaaS**. It features subtle frosted surfaces (`backdrop-filter: blur()`), structural hairline dividers, soft pill-shaped interactive anchors, and editorial serif callouts alongside dense, information-rich bento grids.

## Colors

The palette is derived directly from mineral, stone, lime-wash, and aged timber surfaces. Rather than cold digital grays, all neutrals are warm-tinted to evoke physical material finishes.

### Palette Architecture
- **Canvas Base (`#ededeb`):** Warm limestone canvas used for top-level pages and default backgrounds.
- **Canvas Muted / Alternate (`#dcdbd6`):** Secondary structural foundation for full-width alternating sections, recess panels, and docked drawers.
- **Card Surface (`rgba(255, 255, 255, 0.60)`):** Frosted chalk overlay providing luminous separation over canvas tones with backdrop blur.
- **Border & Hairline Divider (`#c9c7c3`):** High-precision 1px architectural joints and container bounding boxes.
- **Soft Accent / Pill Chips (`#beafa6`):** Sandstone buff for interactive chip fills, progress tracks, and ambient badges.
- **Muted & Iconographic (`#928d86`):** Architectural graphite for non-critical vector icons, metadata glyphs, and disabled states.
- **Secondary / Metadata Text (`#736d66`):** Weathered clay for timestamps, captions, secondary specs, and inline labels.
- **Body Text (`#49463f`):** Dark peat bronze; high readability without the harsh contrast of pure black.
- **Primary Action (`#383330`):** Deep smoked timber for high-intent primary pill buttons, dark hero callouts, and key focus rings.
- **Headings & Display (`#1b1a15`):** Charcoal umber delivering confident, commanding typographic hierarchy.

## Typography

The typographic hierarchy balances structural precision with editorial literary poise.

- **Primary Structure (`Inter`):** Drives all major display titles, headings, structural metrics, and body composition. All headings adopt a tightened negative tracking (`-0.02em` to `-0.03em`) and medium/semibold weights (`500` to `600`) to evoke technical rigor.
- **Editorial Accents (`Newsreader` Italic):** Employed sparingly for high-touch narrative phrases, curated material notes, and editorial emphasis within headlines (e.g., *"Precision craftsmanship, **built for generations**"*).
- **Body Copy:** Standardized at `16px` with a generous `1.6` line-height (`26px`) rendered in Peat Bronze (`#49463f`) to ensure effortless scanning across multi-paragraph design briefs and renovation scopes.

## Layout & Spacing

Layouts are anchored on a structured, responsive Bento Grid architecture that prioritizes modular content grouping, clear rhythm, and clean proportions.

### Grid & Composition Rules
- **Desktop (12 Columns, Max Width 1360px):** 12-column layout with `2rem` (32px) gutters and `4rem` (64px) outer margin padding. Used for modular bento layouts (combining 4-col, 8-col, and 6-col cards).
- **Tablet (8 Columns, 768px - 1024px):** 8-column layout with `1.5rem` (24px) gutters and `2rem` (32px) outer margins. Multi-column bento blocks compress into paired 4-column blocks.
- **Mobile (4 Columns, < 768px):** 4-column fluid layout with `1rem` (16px) gutters and `1rem` (16px) outer margins. Bento grids reflow cleanly into single vertical stacks.

### Spacing Rhythm
- **Micro Gaps (`space-xs`, `space-sm`):** Reserved for chip internal padding, icon-to-label separation, and tabular metric stacks.
- **Component Padding (`space-md`, `space-lg`):** Governs card interior padding (`24px` to `32px`), form control spacing, and docked navigation items.
- **Section Transitions (`space-xl` and higher):** Enforces airy, uncrowded separation (`40px` to `80px`) between milestone phases, material swatch collections, and architectural galleries.

## Elevation & Depth

Visual depth is achieved through physical material layering, translucent surfaces, and warm ambient light rather than artificial dark drop shadows.

### Elevation Levels

1. **Flat Canvas (`Elevation 0`):**
   - Direct surface of the `#ededeb` page base. Zero shadow. Used for section backdrops, subtle dividers, and full-bleed masonry imagery.

2. **Translucent Bento Surfaces (`Elevation 1`):**
   - Background: `rgba(255, 255, 255, 0.60)` with a `backdrop-filter: blur(12px)`.
   - Border: `1px solid #c9c7c3`.
   - Shadow: Warm ambient diffusion `0 4px 20px -2px rgba(56, 51, 48, 0.04), 0 2px 6px -1px rgba(56, 51, 48, 0.02)`.
   - Used for primary cards, schedule milestone panels, and client review modules.

3. **Floating UI / Navigation Layer (`Elevation 2`):**
   - Background: `rgba(237, 237, 235, 0.82)` with `backdrop-filter: blur(16px)`.
   - Border: `1px solid rgba(201, 199, 195, 0.80)`.
   - Shadow: `0 12px 32px -4px rgba(56, 51, 48, 0.08), 0 4px 12px -2px rgba(56, 51, 48, 0.03)`.
   - Used for sticky top navigation bars, interactive architectural toolbars, and floating progress widgets.

4. **Modals & Material Drawers (`Elevation 3`):**
   - Background: `#ededeb`.
   - Border: `1px solid #c9c7c3`.
   - Shadow: `0 24px 48px -8px rgba(27, 26, 21, 0.12), 0 8px 16px -4px rgba(27, 26, 21, 0.04)`.
   - Used for finish selection sheets, blueprint preview modals, and quote detail sheets.

## Shapes

The design system establishes a deliberate dialogue between architectural precision (geometry, 1px joints) and human-friendly softness (large radiuses and full pill geometry).

### Shape Mapping
- **Primary & Secondary Buttons / Badges / Chips:** Fully pill-shaped (`border-radius: 9999px`) to create clear, tactile call-to-action anchors that stand out against rectangular bento layouts.
- **Bento Cards & Containers:** Standardized at `20px` to `24px` radius (`rounded-xl` equivalent). This provides an organic softness resembling milled oak or tumbled limestone slabs.
- **Inputs & Form Controls:** `10px` to `12px` roundedness to provide structured, purposeful interaction areas.
- **Image Frames & Architectural Cutouts:** Match card radiuses (`20px`) with subtle interior inset hairline borders (`box-shadow: inset 0 0 0 1px rgba(0, 0, 0, 0.06)`).

## Components

### Buttons
- **Primary Pill:** Background `#383330`, text `#ededeb`, border `none`, border-radius `9999px`. Padding `12px 24px`. Hover: background `#1b1a15`, subtle upward translation (`-1px`).
- **Secondary Ghost Pill:** Background `rgba(255, 255, 255, 0.50)`, text `#1b1a15`, border `1px solid #c9c7c3`, border-radius `9999px`. Hover: background `rgba(255, 255, 255, 0.90)`, border-color `#928d86`.
- **Subtle Action Pill:** Background `transparent`, text `#49463f`. Hover: background `#dcdbd6`.

### Cards & Bento Cells
- **Default Card:** Surface `rgba(255, 255, 255, 0.60)` over `#ededeb`, `backdrop-filter: blur(12px)`, border `1px solid #c9c7c3`, border-radius `22px`, padding `28px`.
- **Featured / Dark Bento Card:** Surface `#383330`, border `1px solid rgba(255, 255, 255, 0.10)`, text `#ededeb`, secondary text `#beafa6`, border-radius `22px`.

### Chips & SaaS Telemetry Badges
- **Status Chip:** Background `#beafa6` (at 30% alpha for neutral states), text `#383330`, border `1px solid rgba(190, 175, 166, 0.60)`, border-radius `9999px`, padding `4px 12px`, font size `11px`, uppercase, tracking `0.04em`.
- **Active Phase Indicator:** Contains a pulsing 6px dot (`#383330` or subtle sage green) followed by phase title (e.g., *"PHASE 02: STRUCTURAL FRAMING"*).

### Inputs & Form Fields
- **Text Inputs:** Surface `rgba(255, 255, 255, 0.70)`, border `1px solid #c9c7c3`, text `#1b1a15`, placeholder `#928d86`, border-radius `12px`, padding `12px 16px`. Focus state: border-color `#383330` with `box-shadow: 0 0 0 3px rgba(56, 51, 48, 0.12)`.
- **Textarea:** Same tokens, minimum height `120px`, consistent padding and typography.

### Checkboxes & Radios
- **Control Element:** 18px square (checkbox) or circle (radio), border `1.5px solid #928d86`, background `rgba(255, 255, 255, 0.50)`.
- **Selected State:** Background `#383330`, border-color `#383330`, inner checkmark in `#ededeb`.

### Lists & Scope Tables
- **Specification Row:** Hairline divider border-bottom `1px solid #c9c7c3`. Padding `16px 0`. Left: title (`Inter 500, #1b1a15`). Right: value or status pill (`#736d66`).
- **Interactive List Row:** Hover transitions background to `rgba(255, 255, 255, 0.40)` with rounded corner inset margins.

### Specialized Architectural SaaS Components
- **Floating Project HUD:** Docked bottom pill menu showing active remodel phase, budget delta ticker, and instant designer callback button.
- **Material Swatch Card:** Aspect ratio 1:1 image frame with overlaid bottom glass badge detailing timber grade, quarry origin, and lead-time tag.