---
name: Blush Editorial Tech
colors:
  surface: '#f9f9ff'
  surface-dim: '#cfdaf2'
  surface-bright: '#f9f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f0f3ff'
  surface-container: '#e7eeff'
  surface-container-high: '#dee8ff'
  surface-container-highest: '#d8e3fb'
  on-surface: '#111c2d'
  on-surface-variant: '#574048'
  inverse-surface: '#263143'
  inverse-on-surface: '#ecf1ff'
  outline: '#8b7079'
  outline-variant: '#debec8'
  surface-tint: '#b4136d'
  primary: '#b10e6b'
  on-primary: '#ffffff'
  primary-container: '#d23284'
  on-primary-container: '#fffbff'
  inverse-primary: '#ffb0cd'
  secondary: '#a43073'
  on-secondary: '#ffffff'
  secondary-container: '#fc79bd'
  on-secondary-container: '#76014e'
  tertiary: '#60596c'
  on-tertiary: '#ffffff'
  tertiary-container: '#797185'
  on-tertiary-container: '#fffbff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffd9e4'
  primary-fixed-dim: '#ffb0cd'
  on-primary-fixed: '#3e0022'
  on-primary-fixed-variant: '#8c0053'
  secondary-fixed: '#ffd8e7'
  secondary-fixed-dim: '#ffafd3'
  on-secondary-fixed: '#3d0026'
  on-secondary-fixed-variant: '#85145a'
  tertiary-fixed: '#e9def5'
  tertiary-fixed-dim: '#cdc2d9'
  on-tertiary-fixed: '#1e1929'
  on-tertiary-fixed-variant: '#4a4456'
  background: '#f9f9ff'
  on-background: '#111c2d'
  surface-variant: '#d8e3fb'
typography:
  display-xl:
    fontFamily: Playfair Display
    fontSize: 56px
    fontWeight: '600'
    lineHeight: 64px
    letterSpacing: -0.02em
  display-xl-mobile:
    fontFamily: Playfair Display
    fontSize: 36px
    fontWeight: '600'
    lineHeight: 44px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 40px
    fontWeight: '500'
    lineHeight: 48px
    letterSpacing: -0.015em
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 28px
    fontWeight: '500'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Playfair Display
    fontSize: 28px
    fontWeight: '500'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 13px
    fontWeight: '600'
    lineHeight: 18px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.04em
  code-sm:
    fontFamily: JetBrains Mono
    fontSize: 13px
    fontWeight: '450'
    lineHeight: 20px
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
  margin: 3rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
  space-2xl: 4rem
---

## Brand & Style

This design system expresses a refined synthesis between editorial couture and high-craft frontend engineering. Designed for a modern developer portfolio, the interface trades sterile tech minimalism for warm sophistication, tactility, and editorial grace.

The visual style is **Soft Editorial Glassmorphism**:
- Ultra-delicate frosted surfaces over luminous rose-mist backdrops.
- Expressive editorial serif typography paired with hyper-legible, geometric sans-serif workhorse type for technical content.
- Restrained, luminous pink highlights functioning as intentional focal accents rather than overwhelming visual noise.
- Tactile, micro-diffused depth that feels airy, precise, and bespoke.

## Colors

The palette establishes an airy, ambient light foundation complemented by high-contrast slate neutrals and expressive rose accents.

### Color Roles
- **Primary Accent (`#EC4899`)**: High-intent interactive moments, primary CTAs, active status indicators, and selected tab markers.
- **Secondary Accent (`#F472B6`)**: Hover transitions, soft gradient endpoints, decorative ambient glows, and icon highlights.
- **Tertiary Accent (`#F3E8FF`)**: Lavender-rose tint used for badge fills, code block tints, and subtle hover halos.
- **Neutral Dark (`#1E293B` / `#0F172A`)**: Editorial headlines, high-contrast readable body copy, and primary icons.
- **Neutral Muted (`#64748B`)**: Secondary copy, publication dates, repository metadata, and helper text.
- **Canvas Base (`#FFF1F2` transitioning to `#FDF2F8` and `#FFFFFF`)**: Warm cream-rose background providing subtle warmth and eliminating sterile starkness.
- **Delicate Borders (`#FCE7F3`)**: Sub-pixel and translucent borders providing structural framing without visual heaviness.

## Typography

The type system blends literary editorial cadence with precision engineering legibility:
- **Headings & Display**: Set in `Playfair Display`. It commands focus for project hero titles, personal ethos statements, and major section intros.
- **Body & Controls**: Set in `Plus Jakarta Sans`. Its geometric clarity ensures dense technical narratives, architecture explanations, and interactive labels remain legible and fresh.
- **Inline Code & Syntax**: Set in `JetBrains Mono` to cleanly display tech stacks, terminal outputs, and implementation metrics.

## Layout & Spacing

The layout is grounded in a 12-column responsive fluid grid with an upper bound container constraint of `1280px` to maintain optimal line-lengths and editorial breathing room.

- **Desktop (1024px+)**: 12 columns, `1.5rem` (`24px`) gutters, `3rem` (`48px`) margins. Deep section paddings (`space-2xl`) frame case studies with editorial weight.
- **Tablet (768px - 1023px)**: 8 columns, `1.25rem` (`20px`) gutters, `2rem` (`32px`) margins. Sidebar navigation collapses to a sticky top-bar blur capsule.
- **Mobile (< 768px)**: 4 columns, `1rem` (`16px`) gutters, `1.25rem` (`20px`) margins. Interactive cards collapse into unified single-column flow with tightened vertical gaps (`space-lg`).

## Elevation & Depth

Visual depth is conveyed through low-opacity glassmorphism, surface translucency, and rose-tinted ambient micro-shadows rather than heavy drop-shadows.

### Layering Rules
- **Layer 0 (Background Canvas)**: Subtle ambient mesh gradient pairing `#FFF1F2` and `#FDF2F8`.
- **Layer 1 (Frosted Glass Panels)**: `rgba(255, 255, 255, 0.72)` background with `16px` backdrop-filter blur and an inset border of `1px solid rgba(252, 231, 243, 0.85)`.
- **Layer 2 (Elevated Interactive Cards & Modals)**: `rgba(255, 255, 255, 0.90)` background, `20px` backdrop-filter blur, supported by an ambient shadow: `0 10px 30px -10px rgba(236, 72, 153, 0.08), 0 2px 6px -2px rgba(30, 41, 59, 0.03)`.
- **Layer 3 (Floating Nav & Menus)**: `rgba(255, 255, 255, 0.85)` background with `1px solid rgba(254, 205, 232, 0.6)`, `24px` backdrop blur, and `0 20px 40px -15px rgba(236, 72, 153, 0.12)`.

## Shapes

The shape hierarchy employs balanced curvature (`roundedness: 2`), delivering soft tactile edges that complement the blush palette while preserving architectural cleanliness:
- Base panels, interactive code cards, and modal frames use `1rem` (`rounded-lg`).
- Feature showcases and portfolio display cards use `1.5rem` (`rounded-xl`).
- Tech stack tags, interactive badges, avatar rings, and floating action triggers use full pill curvature (`9999px`) to offset rectangular card geometry.

## Components

### Buttons
- **Primary**: Solid `#EC4899` fill, `#FFFFFF` label text, `0.5rem` border radius, subtle hover elevation shift to `#DB2777` with `0 8px 20px -4px rgba(236, 72, 153, 0.35)`.
- **Secondary / Glass**: Background `rgba(255, 255, 255, 0.8)`, border `1px solid #FCE7F3`, text `#1E293B`. Hover shifts to background `rgba(253, 242, 248, 0.9)` and border `#F472B6`.
- **Ghost**: Transparent background, text `#1E293B`, subtle pink highlight line on hover with 150ms ease.

### Badges & Tech Stack Chips
- Pill-shaped (`rounded-full`), height `26px`, padding `0.25rem 0.75rem`.
- Background `rgba(243, 232, 255, 0.65)`, border `1px solid rgba(236, 72, 153, 0.2)`.
- Text style `label-sm`, color `#9D174D` with mono icons or logo glyphs sized to `12px`.

### Project Cards
- Surface `rgba(255, 255, 255, 0.75)` with `16px` backdrop-filter blur, border `1px solid #FCE7F3`.
- Internal padding `space-lg` to `space-xl`.
- Interactive transition: on hover, translateY by `-3px` with shadow expanding to `0 14px 34px -8px rgba(236, 72, 153, 0.12)` and border tint shifting toward `#F472B6`.

### Inputs & Contact Fields
- Background `rgba(255, 255, 255, 0.85)`, border `1px solid #FCE7F3`, text `#1E293B`, placeholder `#94A3B8`.
- Focus state: border color `#EC4899`, outline none, ring of `3px rgba(236, 72, 153, 0.15)`.

### Code Showcase & Metrics Strips
- Inset containers with background `rgba(253, 242, 248, 0.45)`, border `1px dashed #FCE7F3`.
- Typography styled with `code-sm`, syntax tokens shaded with dark slate `#1E293B` and hot blush `#EC4899`.