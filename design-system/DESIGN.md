---
name: ICYUNV Store
colors:
  surface: '#131314'
  surface-dim: '#131314'
  surface-bright: '#3a393a'
  surface-container-lowest: '#0e0e0f'
  surface-container-low: '#1c1b1c'
  surface-container: '#201f20'
  surface-container-high: '#2a2a2b'
  surface-container-highest: '#353436'
  on-surface: '#e5e2e3'
  on-surface-variant: '#baccb0'
  inverse-surface: '#e5e2e3'
  inverse-on-surface: '#313031'
  outline: '#85967c'
  outline-variant: '#3c4b35'
  surface-tint: '#2ae500'
  primary: '#efffe3'
  on-primary: '#053900'
  primary-container: '#39ff14'
  on-primary-container: '#107100'
  inverse-primary: '#106e00'
  secondary: '#ffb0d0'
  on-secondary: '#63003c'
  secondary-container: '#ff43a9'
  on-secondary-container: '#570034'
  tertiary: '#f9fafa'
  on-tertiary: '#2f3131'
  tertiary-container: '#dddddd'
  on-tertiary-container: '#606162'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#79ff5b'
  primary-fixed-dim: '#2ae500'
  on-primary-fixed: '#022100'
  on-primary-fixed-variant: '#095300'
  secondary-fixed: '#ffd8e6'
  secondary-fixed-dim: '#ffb0d0'
  on-secondary-fixed: '#3d0023'
  on-secondary-fixed-variant: '#8c0057'
  tertiary-fixed: '#e2e2e2'
  tertiary-fixed-dim: '#c6c6c7'
  on-tertiary-fixed: '#1a1c1c'
  on-tertiary-fixed-variant: '#454747'
  background: '#131314'
  on-background: '#e5e2e3'
  surface-variant: '#353436'
typography:
  display-xl:
    fontFamily: Bebas Neue
    fontSize: 56px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: 0.04em
  display-xl-mobile:
    fontFamily: Bebas Neue
    fontSize: 42px
    fontWeight: '700'
    lineHeight: 42px
    letterSpacing: 0.04em
  headline-lg:
    fontFamily: Bebas Neue
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 38px
    letterSpacing: 0.05em
  headline-lg-mobile:
    fontFamily: Bebas Neue
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 30px
    letterSpacing: 0.05em
  headline-md:
    fontFamily: Bebas Neue
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 26px
    letterSpacing: 0.06em
  body-lg:
    fontFamily: Space Grotesk
    fontSize: 16px
    fontWeight: '500'
    lineHeight: 24px
    letterSpacing: -0.01em
  body-md:
    fontFamily: Space Grotesk
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0em
  body-sm:
    fontFamily: Space Grotesk
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
    letterSpacing: 0em
  label-lg:
    fontFamily: JetBrains Mono
    fontSize: 13px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.08em
  label-md:
    fontFamily: JetBrains Mono
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.1em
  label-xs:
    fontFamily: JetBrains Mono
    fontSize: 9px
    fontWeight: '700'
    lineHeight: 12px
    letterSpacing: 0.14em
spacing:
  gutter: 0.75rem
  gutter-desktop: 1.5rem
  margin: 1rem
  margin-desktop: 2.5rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system targets an unapologetic, subcultural streetwear community steeped in high-octane digital nightlife, limited-run product drops, and underground cyber aesthetics. The visual narrative combines raw brutalism with acid-punk electrics: an interface that feels less like a conventional boutique and more like an unauthorized industrial supply terminal hacked under ultraviolet rave lighting.

The experience commands urgency, exclusivity, and anti-corporate grit. Layouts are severe, punctuated by dense typographic hierarchies, razor-sharp geometric framing, and intentional friction. Visual cues reference rave flyers, spec sheets, tactical military gear labeling, and warehouse rave wristbands. Subtle structural glitches and electric illumination deliver an unmistakably raw, visceral tension.

## Colors

The palette operates under absolute darkness, utilizing layered near-blacks and charcoals to allow hyper-saturated toxic pigments to sear across the viewport.

- **Primary (`#39FF14` — Toxic Volt):** Used for critical calls to action, active states, real-time inventory statuses, and tactical confirm triggers.
- **Secondary (`#FF2EA6` — Shock Magenta):** Deployed for urgent alert conditions, drop timers, high-scarcity microcopy, and hyper-contrast visual tags.
- **Surface Foundations:**
  - Base canvas: `#0A0A0B` (Pitch Void)
  - Primary container / elevated surface: `#141416` (Smoked Charcoal)
  - Interactive raised panels / borders: `#1A1A1D` (Carbon Basalt)
- **Typographic Tones:**
  - Dominant contrast: `#FFFFFF` (Stark White) for high-impact display headlines and crucial data.
  - Secondary contrast: `#8E8E93` (Cool Alloy) for technical metadata, inactive states, and supporting prose.
- **Accent Rules:** Neon accents are never blended into gradients across backgrounds; they exist strictly as surgical razor strikes, hairline dividers, focal points, and deliberate high-intensity status lamps.

## Typography

Typography establishes an abrasive tension between raw, towering display forms and cold industrial data tags.

- **Headlines (`Bebas Neue`):** Always transformed to uppercase. Set dense, condensed leadings to maximize typographic mass. Titles must feel printed onto steel shipping containers or spray-painted over billboards.
- **Editorial & Body (`Space Grotesk`):** Provides sharp, mechanical grotesque character without losing mobile legibility. Maintains a technical tone for product descriptions and editorial drop notes.
- **Metadata, Timers & Telemetry (`JetBrains Mono`):** All inventory quantities, countdown drop sequences, SKU indices, wash tags, prices, and sizing matrices are rendered in monospaced glyphs with tracked letterforms.

## Layout & Spacing

A mobile-first rigid fluid system structured to prioritize rapid single-thumb navigation, drop-queue responsiveness, and modular technical panels.

- **Mobile Viewport (320px – 767px):** 4-column fluid matrix. Canvas margin is locked at `1rem` (`16px`) with compact `0.75rem` (`12px`) gutters to maximize edge-to-edge product photography and raw visual density.
- **Tablet & Desktop Viewport (768px+):** Scales up to an 8-column (tablet) and 12-column (desktop) layout with `2.5rem` margins and `1.5rem` gutters. Content centers within a maximum content boundary of `1280px` to maintain focused storefront tension without sprawling emptiness.
- **Structural Rhythm:** Spacing adopts aggressive 4px/8px incremental shifts. Vertical cadences alternate between tight technical metadata clusters (`space-xs` and `space-sm`) and pronounced spatial breaks (`space-xl`) between distinct collection archives.

## Elevation & Depth

This design system avoids soft, natural skeuomorphic shadows. Depth is communicated strictly through planar starkness, structural offset highlights, and toxic ambient glows.

- **Surface Layering:** Stacking occurs through tonal shifts from canvas pitch black (`#0A0A0B`) to elevated surface charcoal (`#141416`), topped by modular interaction panels (`#1A1A1D`).
- **Hairline Framing:** Components gain definition through razor 1px borders (`#1A1A1D` for passive modules; `#39FF14` or `#FF2EA6` for active/focus states).
- **Hard Offset Drops:** Interactive elements mimic physical brutalist cut-outs using zero-blur offset hard drop-shadows: `2px 2px 0px 0px #39FF14` or `2px 2px 0px 0px #FF2EA6`.
- **Neon Atmospheric Glow:** Critical live states (e.g., active drop buttons, urgent ticker counters) utilize a concentrated outer luminescence: `0px 0px 14px -2px rgba(57, 255, 20, 0.45)` for green and `0px 0px 14px -2px rgba(255, 46, 166, 0.45)` for magenta.

## Shapes

The primary structural geometry is uncompromisingly zero-radius (`0px`), celebrating brutalist cutouts, sharp borders, and technical modular packaging.

- **Primary Elements:** Buttons, modal trays, cards, tabs, and input surfaces feature razor-sharp rectangular corners (`0px`).
- **Exception for Scarcity & Drop Pills:** Status tags denoting real-time warehouse limits (e.g., "ONLY 4 LEFT", "VAULT LOCKED") leverage hyper-pill silhouettes (`9999px` border-radius) to create stark morphological contrast against the rigid rectilinear framing of the rest of the interface.
- **Cyberpunk Chamfers:** Specialized card headers and primary checkout action buttons allow 45-degree corner clip paths (cut-corners at `8px`), emphasizing hardware and tactical apparel labels.

## Components

### Buttons
- **Primary Cyber-Trigger:** Full-width mobile CTA. Background `#39FF14`, text `#0A0A0B`, font `Bebas Neue` (uppercase, tracked), sharp `0px` corners. Active press creates an immediate `2px 2px 0px 0px #FFFFFF` mechanical offset without tween delay.
- **Secondary Drop Action:** Background `#141416`, 1px border `#39FF14`, text `#39FF14`. On press, fills to solid `#39FF14` with `#0A0A0B` text.
- **Destructive / Vault Action:** Background `#FF2EA6`, text `#FFFFFF`, hard 2px `#0A0A0B` inner outline, accompanied by outer magenta glow.

### Scarcity Badges & Drop Pills
- Rendered with rounded pill contours (`9999px`) to immediately disrupt the brutalist grid.
- Magenta Scarcity: Background `rgba(255, 46, 166, 0.15)`, 1px border `#FF2EA6`, text `#FF2EA6`, font `JetBrains Mono` (`label-xs`). Includes a pulsing dot indicator.
- Live Inventory Chip: Background `rgba(57, 255, 20, 0.12)`, 1px border `#39FF14`, text `#39FF14`.

### Streetwear Technical Tags & SKU Labels
- Compact rectangular modules (`0px` radius) positioned at the top-right of image viewports.
- Black fill `#0A0A0B` with 1px border `#1A1A1D`, displaying mono-spaced telemetry (e.g., `BATCH: 009 // ARCHIVE_SPEC`).

### Product Cards
- Container built from `#141416` with a default hairline border in `#1A1A1D`.
- Edge-to-edge imagery with minimal padding. Product titles styled in `headline-md` (`Bebas Neue`), prices set in bold `Space Grotesk` in `#39FF14`, and collection indices formatted in muted mono alloy (`#8E8E93`).

### Input Fields & Selectors
- Background `#0A0A0B`, lower border only or full razor border in `#1A1A1D`, font `Space Grotesk` (`body-md`).
- Focus state instantly swaps the border to `#39FF14` accompanied by a mono micro-label hovering above in `#39FF14`.

### Checkboxes & Segmented Size Selectors
- Size selectors are flat square tiles (`0px` border-radius). Inactive: `#141416` background, `#8E8E93` border and text. Active: `#39FF14` solid background, `#0A0A0B` text. Out-of-stock sizes have diagonal hairline strike-throughs with `#1A1A1D` fill.

### Mobile Bottom Navigation Bar
- Fixed docking station pinned to the base of the viewport (`height: 64px`), backed by `#0A0A0B` with a solid 1px top border of `#1A1A1D`.
- 4-item split: `DROP`, `CATALOG`, `VAULT`, `BAG [0]`.
- Active item displays an electric `#39FF14` upper marker notch (2px height) and bright `#FFFFFF` label; inactive items rest in muted `#8E8E93`.