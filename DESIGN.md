---
name: Warm Editorial Minimalism
colors:
  surface: '#faf9f6'
  surface-dim: '#dbdad7'
  surface-bright: '#faf9f6'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f4f3f1'
  surface-container: '#efeeeb'
  surface-container-high: '#e9e8e5'
  surface-container-highest: '#e3e2e0'
  on-surface: '#1a1c1a'
  on-surface-variant: '#4a4640'
  inverse-surface: '#2f312f'
  inverse-on-surface: '#f2f1ee'
  outline: '#7b766f'
  outline-variant: '#ccc6bd'
  surface-tint: '#605e5c'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#1c1b1a'
  on-primary-container: '#868382'
  inverse-primary: '#cac6c4'
  secondary: '#825338'
  on-secondary: '#ffffff'
  secondary-container: '#fdbe9d'
  on-secondary-container: '#794b31'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#131e11'
  on-tertiary-container: '#7a8875'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e6e2df'
  primary-fixed-dim: '#cac6c4'
  on-primary-fixed: '#1c1b1a'
  on-primary-fixed-variant: '#484645'
  secondary-fixed: '#ffdbca'
  secondary-fixed-dim: '#f7b997'
  on-secondary-fixed: '#321201'
  on-secondary-fixed-variant: '#673c23'
  tertiary-fixed: '#d9e7d1'
  tertiary-fixed-dim: '#bdcbb6'
  on-tertiary-fixed: '#131e11'
  on-tertiary-fixed-variant: '#3e4a3a'
  background: '#faf9f6'
  on-background: '#1a1c1a'
  surface-variant: '#e3e2e0'
typography:
  display:
    fontFamily: Newsreader
    fontSize: 4.5rem
    fontWeight: '400'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-mobile:
    fontFamily: Newsreader
    fontSize: 2.75rem
    fontWeight: '400'
    lineHeight: '1.15'
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Newsreader
    fontSize: 3rem
    fontWeight: '400'
    lineHeight: '1.2'
    letterSpacing: -0.015em
  headline-lg-mobile:
    fontFamily: Newsreader
    fontSize: 2rem
    fontWeight: '400'
    lineHeight: '1.25'
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Newsreader
    fontSize: 2rem
    fontWeight: '400'
    lineHeight: '1.3'
    letterSpacing: 0em
  headline-sm:
    fontFamily: Newsreader
    fontSize: 1.5rem
    fontWeight: '400'
    lineHeight: '1.35'
    letterSpacing: 0em
  body-lg:
    fontFamily: Newsreader
    fontSize: 1.125rem
    fontWeight: '400'
    lineHeight: '1.7'
    letterSpacing: 0.01em
  body-md:
    fontFamily: Manrope
    fontSize: 0.9375rem
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: 0.01em
  body-sm:
    fontFamily: Manrope
    fontSize: 0.8125rem
    fontWeight: '400'
    lineHeight: '1.5'
    letterSpacing: 0.01em
  label-lg:
    fontFamily: Manrope
    fontSize: 0.875rem
    fontWeight: '500'
    lineHeight: '1.4'
    letterSpacing: 0.04em
  label-md:
    fontFamily: Manrope
    fontSize: 0.75rem
    fontWeight: '600'
    lineHeight: '1.4'
    letterSpacing: 0.08em
  label-sm:
    fontFamily: Manrope
    fontSize: 0.6875rem
    fontWeight: '600'
    lineHeight: '1.3'
    letterSpacing: 0.1em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 4rem
  margin-tablet: 2rem
  margin-mobile: 1.25rem
  space-xs: 0.375rem
  space-sm: 0.75rem
  space-md: 1.25rem
  space-lg: 2.25rem
  space-xl: 4rem
---

## Brand & Style

This design system embodies the quiet poetry, timeless romance, and architectural sensibility of high-end wedding and landscape photography based in Porto, Portugal. It addresses discerning couples, gallery curators, and editorial publications seeking artful, intentional imagery over commercial trends.

The visual ethos blends **Minimalism** with **Editorial Print Design**:
- Generous, deliberate negative space that treats the digital viewport as a tactile photography monograph.
- Unhurried, poetic pacing allowing photography to command presence without visual competition.
- Warm, tactile organic minimalism inspired by Porto's granite architecture, terracotta roofs, and coastal Atlantic light.
- Restraint over decoration: subtle hairline divisions, asymmetrical compositions, and meticulously measured typographic rhythm replace loud interface tropes.

## Colors

The palette draws directly from traditional Portuguese masonry, aged parchment, and sun-warmed earth:

- **Primary (`#1C1B1A`)**: A deep, velvety charcoal ink used for high-contrast typography, primary actions, and hairline framing. Avoid pure black to maintain a softer, photographic baseline.
- **Secondary (`#A36F52`)**: A sun-baked terracotta ochre, reserved for focal accent moments, editorial curation badges, and interactive active states.
- **Tertiary (`#6D7A68`)**: A muted maritime olive/sage inspired by coastal flora, used sparingly for auxiliary tags, subtle highlights, and secondary categorization.
- **Neutral (`#FAF9F6`)**: Warm alabaster off-white acting as the primary canvas. Layered with `#F3F1EC` (warm stone) for structural surface containers, alternating editorial bands, and card backdrops.

Surfaces rely on natural shifts between `#FAF9F6` and `#F3F1EC` rather than hard drop shadows. Text elements should use `#1C1B1A` for primary reading and `#65635F` for metadata, captions, and secondary body copy.

## Typography

The typographical voice establishes tension between literary romance and modernist restraint:

- **Headlines & Narrative (`Newsreader`)**: Evokes luxury bookbinding and print journals. Italicize key conceptual words within large displays sparingly to inject intimacy (e.g., *the* Light in Douro).
- **Body & Functional UI (`Manrope`)**: Provides crisp, architectural legibility. Its geometric proportions ground technical information (apertures, dates, locations, booking procedures) without competing with the photography.
- **Labels & Micro-copy**: Rendered in uppercase with widened tracking (`0.08em` to `0.1em`) to create clean captioning systems reminiscent of museum placards.

## Layout & Spacing

The layout follows a fluid 12-column grid anchored by expansive margins, reflecting fine-art photo monographs:

- **Desktop (1024px+)**: 12 columns with `1.5rem` gutters and generous `4rem` outer canvas margins. Images and text freely offset to produce deliberate asymmetry (e.g., a 7-column landscape paired beside a 4-column contextual caption).
- **Tablet (768px - 1023px)**: 8 columns with `1.5rem` gutters and `2rem` margins. Editorial pairings stack gracefully into vertical duos.
- **Mobile (< 768px)**: 4 columns with `1rem` gutters and `1.25rem` margins. Full bleed or near full bleed imagery ensures immersive scale on compact screens.

Spacing rhythm enforces contemplation: vertical section buffers frequently expand to double the `space-xl` token (`8rem`) to isolate projects and give photography space to breathe.

## Elevation & Depth

This design system avoids drop shadows and simulated light sources. Visual hierarchy and elevation are communicated through pure editorial mechanics:

- **Tonal Layering**: Depth is achieved by placing `#FAF9F6` cards and photo plates against `#F3F1EC` ground planes, or vice-versa.
- **Hairline Outlines**: Boundaries are defined by delicate `1px` solid borders in `#1C1B1A` at 12% opacity (`rgba(28, 27, 26, 0.12)`). Active or focused borders scale up to terracotta `#A36F52` at 60% opacity.
- **Overlapping Elements**: Slight visual overlap (e.g., caption block crossing the bottom edge of a portrait plate by 24px) creates an organic sense of physical sheets laid on a work table.
- **Backdrop Overlays**: Modal galleries and full-screen viewports utilize a 92% opaque `#FAF9F6` wash paired with a gentle CSS blur (`backdrop-filter: blur(8px)`), keeping subtle ambient awareness of the underlying gallery.

## Shapes

The shape system utilizes soft, barely perceptible corner softening (`0.25rem` / `4px`), striking a balance between the crisp trim of fine-art photo prints and digital comfort:

- **Images & Hero Containers**: `roundedness: 1` (`4px`) or sharp `0px` depending on frame type. Never employ heavy rounded corners that soften the artistic discipline of the photograph.
- **Cards, Sheets & Overlays**: `rounded-lg` (`0.5rem` / `8px`) maintains subtle organic tactility without appearing playful or bubbly.
- **Interactive Buttons & Badges**: Retain `0.25rem` (`4px`) radii; pill-shaped surfaces are prohibited to preserve editorial structure.

## Components

### Buttons
- **Primary**: Solid `#1C1B1A` background, `#FAF9F6` text, `4px` radius. Hover shifts to `#A36F52` with smooth 250ms transition. Padding: `0.75rem 1.75rem`. Text: `label-md` uppercase.
- **Secondary (Editorial Outline)**: Transparent background, `1px` border in `rgba(28, 27, 26, 0.25)`, `#1C1B1A` text. Hover shifts border and text to `#A36F52`.
- **Text Link**: Inline `#1C1B1A` with a continuous `1px` underline offset by `4px`. Hover transitions underline color to `#A36F52`.

### Chips & Category Filters
- Compact horizontal list with `0.5rem` gaps.
- Unselected: Transparent background, `1px` border `rgba(28, 27, 26, 0.12)`, text `#65635F`, `label-sm` uppercase.
- Selected: Background `#F3F1EC`, border `1px` solid `#1C1B1A`, text `#1C1B1A`.

### Testimonial Cards
- Structured as warm stone `#F3F1EC` panels or transparent containers bounded by top and bottom hairline borders.
- Client quotes set in `Newsreader` italic (`headline-sm` or `body-lg`).
- Attribution details (couple names, wedding venue, city) set in `Manrope` (`label-md` and `body-sm`) in `#65635F`.
- Include an optional small `1:1` portrait or ring detail thumbnail with `4px` corner radius.

### Pricing & Package Tables
- Minimalist open table layout with zero vertical column dividers.
- Horizontal dividers: `1px` solid `rgba(28, 27, 26, 0.12)`.
- Header row: `label-sm` uppercase in `#65635F` with `space-md` bottom padding.
- Data cells: `body-md` in `#1C1B1A` with generous vertical padding (`1.25rem 0`).
- Accent column (recommended investment tier) highlighted with a delicate `#FAF9F6` pill container or `#A36F52` heading label.

### Form Inputs
- Minimal single-line bottom border or 4-sided `1px` border `rgba(28, 27, 26, 0.2)` on `#FAF9F6` background.
- Focus state: Border color transitions to `#A36F52` without glowing box-shadows.
- Labels: `label-sm` floating or stacked above in uppercase tracking. Placeholder text rendered in muted `#8E8B85`.

### Checkboxes & Radio Buttons
- Custom square (`4px` radius) or circle controls bounded by `1px` solid `#1C1B1A`.
- Active state fills with `#1C1B1A` carrying an inner off-white mark.

### Image Plates & Captions
- Image containers feature an optional ultra-fine `1px` inset border `rgba(250, 249, 246, 0.4)` to define bright highlights.
- Photo metadata caption: Placed directly below with `space-xs` gap, set in `label-sm` uppercase with date, camera details, or geographical coordinates in `#65635F`.