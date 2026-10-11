---
name: Ecclesiastical Editorial
colors:
  surface: '#fafaf4'
  surface-dim: '#dadad5'
  surface-bright: '#fafaf4'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f4f4ef'
  surface-container: '#eeeee9'
  surface-container-high: '#e8e8e3'
  surface-container-highest: '#e2e3de'
  on-surface: '#1a1c19'
  on-surface-variant: '#544244'
  inverse-surface: '#2f312e'
  inverse-on-surface: '#f1f1ec'
  outline: '#867274'
  outline-variant: '#d9c1c3'
  surface-tint: '#954553'
  primary: '#591726'
  on-primary: '#ffffff'
  primary-container: '#762d3b'
  on-primary-container: '#fa97a6'
  inverse-primary: '#ffb2bc'
  secondary: '#715b2d'
  on-secondary: '#ffffff'
  secondary-container: '#fddfa4'
  on-secondary-container: '#776132'
  tertiary: '#003815'
  on-tertiary: '#ffffff'
  tertiary-container: '#035123'
  on-tertiary-container: '#7ec389'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffd9dd'
  primary-fixed-dim: '#ffb2bc'
  on-primary-fixed: '#3e0213'
  on-primary-fixed-variant: '#772e3c'
  secondary-fixed: '#fddfa4'
  secondary-fixed-dim: '#e0c38a'
  on-secondary-fixed: '#261a00'
  on-secondary-fixed-variant: '#574417'
  tertiary-fixed: '#abf3b5'
  tertiary-fixed-dim: '#90d79a'
  on-tertiary-fixed: '#00210a'
  on-tertiary-fixed-variant: '#055224'
  background: '#fafaf4'
  on-background: '#1a1c19'
  surface-variant: '#e2e3de'
typography:
  display-lg:
    fontFamily: EB Garamond
    fontSize: 2.5rem
    fontWeight: '400'
    lineHeight: 3rem
    letterSpacing: -0.015em
  display-lg-mobile:
    fontFamily: EB Garamond
    fontSize: 2rem
    fontWeight: '400'
    lineHeight: 2.5rem
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: EB Garamond
    fontSize: 1.75rem
    fontWeight: '500'
    lineHeight: 2.25rem
    letterSpacing: -0.01em
  headline-md:
    fontFamily: EB Garamond
    fontSize: 1.375rem
    fontWeight: '500'
    lineHeight: 1.875rem
  scripture-verse:
    fontFamily: EB Garamond
    fontSize: 1.25rem
    fontWeight: '400'
    lineHeight: 2rem
    letterSpacing: 0.01em
  title-md:
    fontFamily: Geist
    fontSize: 1.0625rem
    fontWeight: '600'
    lineHeight: 1.5rem
    letterSpacing: -0.01em
  title-sm:
    fontFamily: Geist
    fontSize: 0.9375rem
    fontWeight: '600'
    lineHeight: 1.375rem
  body-lg:
    fontFamily: Geist
    fontSize: 1rem
    fontWeight: '400'
    lineHeight: 1.625rem
  body-md:
    fontFamily: Geist
    fontSize: 0.875rem
    fontWeight: '400'
    lineHeight: 1.375rem
  label-md:
    fontFamily: Geist
    fontSize: 0.75rem
    fontWeight: '500'
    lineHeight: 1rem
    letterSpacing: 0.06em
  label-sm:
    fontFamily: Geist
    fontSize: 0.6875rem
    fontWeight: '500'
    lineHeight: 0.875rem
    letterSpacing: 0.08em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-tablet: 1.5rem
  gutter-desktop: 2rem
  margin: 1.25rem
  margin-tablet: 2rem
  margin-desktop: 3rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.25rem
---

## Brand & Style

This design system embodies quiet dignity, pastoral warmth, and high literary refinement. Designed for St. Peter's Catholic Parish in Ibadan, Nigeria, the interface balances generational reverence with modern digital utility. The target audience spans multi-generational parishioners—from youth lectors to senior community elders—demanding supreme legibility, measured spacing, and friction-free navigation.

The aesthetic philosophy draws directly from contemporary editorial book design and fine liturgical publication. Rather than leaning on overt ornamentation or digital kitsch, visual gravitas is achieved through disciplined typographic hierarchy, spacious layout architecture, and physical-grade tactile restraint. The emotional tone evokes the quiet sanctity of a sunlit parish interior: peaceful, steady, welcoming, and devout.

## Colors

The palette relies on organic, pigment-inspired tones that evoke illuminated manuscripts, natural linen, and liturgical vestments:

- **Canvas & Background (`#FAF9F6`)**: Warm ivory setting the base mood of unbleached parchment, softening eye strain during long prayer reading sessions.
- **Surface Elevation 1 (`#FFFFFF`)**: Pure crisp white for primary cards, prayer sheets, and modular content containers.
- **Surface Elevation 2 (`#F2F0EA`)**: Warm ivory-tinted neutral for secondary groupings, subtle segmented controls, and liturgical calendars.
- **Primary Text (`#20221F`)**: Deep charcoal offering stark contrast against ivory surfaces without the clinical harshness of absolute black.
- **Secondary & Muted Text (`#777873`)**: Warm neutral slate for scripture attributions, timestamps, and metadata.
- **Ecclesiastical Burgundy (`#762D3B`)**: Primary accent used sparingly for active tab bars, key spiritual actions, and cardinal feast indicators.
- **Antique Gold (`#B49A65`)**: Secondary accent reserved for fine liturgical lines, cross glyphs, and solemn feast banners.
- **Structural Borders (`#E9E6DF`)**: Soft neutral hairline rules defining structure without creating harsh visual breaks.

## Typography

Typographic scale is structured around a deliberate dual-engine pairing:
- **EB Garamond** acts as the liturgical and literary voice. It governs holy scripture, daily missal readings, feast titles, and pastoral letters. The larger line-height on `scripture-verse` reproduces the natural breathing cadence required during devotional reflection.
- **Geist** handles the operational interface: mass scheduling, parish notices, confession queues, buttons, and navigation controls. Its neutral geometry ensures immediate comprehension across high-sunlight outdoor conditions in Ibadan.

Labels and liturgical dates utilize slight letter-spacing (`0.06em` to `0.08em`) set in small-caps or uppercase for traditional liturgical clarity.

## Layout & Spacing

The layout is built around a single-column, distraction-free reading canvas for mobile devices, expanding into a balanced 6-column grid for tablets and a centered 12-column reading vessel on desktop viewports.

- **Mobile Viewports (<640px)**: 1-column reading rail with an edge margin of `1.25rem`. Content stacks sequentially to foster meditative scrolling without competing sidebars.
- **Tablet Viewports (640px–1024px)**: 6-column fluid structure with `1.5rem` gutters and `2rem` margins. Splits liturgical readings and side parish reflections cleanly.
- **Desktop Viewports (>1024px)**: Max reading container constrained to 780px for spiritual reading and 1080px for administrative parish dashboards, centered with ample negative space to preserve the publication feel.

Vertical rhythm follows an 8px base grid, using generous component padding (`space-lg`) to prevent density anxiety.

## Elevation & Depth

Visual hierarchy rejects artificial floating shadows in favor of editorial surface stacking and crisp hairline borders:

- **Surface Tiers**: Base background sits at `#FAF9F6`. Active liturgical modules, scripture passages, and announcements rest on pure white (`#FFFFFF`) cards. Secondary interactive fields (search, audio controls, input trays) sit on `#F2F0EA`.
- **Low-Contrast Outlines**: Cards, modal sheets, and list groupings are bound by a 1px solid border in `#E9E6DF`.
- **Subtle Ambient Grounding**: When a floating modal, prayer audio player, or bottom action drawer surfaces, it utilizes a deeply diffused, warm-tinted shadow: `0 8px 30px rgba(32, 34, 31, 0.05)`, preserving an organic, paper-stacked impression without synthetic glow.

## Shapes

The design system adopts a conservative, book-like geometry with subtle rounding (`roundedness: 1`). 

- Default elements (input fields, buttons, small status chips) use `0.25rem` (4px).
- Cards, prayer panels, and liturgical reading modules use `rounded-lg` (`0.5rem` / 8px).
- Modals, action sheets, and parish alert surfaces use `rounded-xl` (`0.75rem` / 12px).

Rounded corners soften the UI just enough to feel warm and human, avoiding overly playful pill-shapes or harsh brutalist points.

## Components

### Buttons
- **Primary**: Solid ecclesiastical burgundy (`#762D3B`) with white text. High-contrast, unadorned, 44px min-touch height, styled with subtle `0.25rem` corner radius.
- **Secondary**: Crisp white background with `#E9E6DF` hairline border, text rendered in `#20221F`.
- **Ghost/Tertiary**: No border or background; text in `#762D3B` or `#777873` with an active state tint of `#F2F0EA`.

### Scripture & Missal Cards
- Pure white container (`#FFFFFF`) with a 1px `#E9E6DF` frame.
- Scriptural readings lead with a liturgical rubric pill (e.g., "FIRST READING" or "THE HOLY GOSPEL") rendered in `label-sm` tracking with `#B49A65` (antique gold).
- Scripture body is set in EB Garamond with generous line spacing and charcoal ink tone.

### Liturgical Status Chips & Badges
- Compact indicators used for seasons (Advent, Lent, Ordinary Time).
- Subtle background in `#F2F0EA`, 1px border matching season tone or `#E9E6DF`, text set in uppercase `label-sm` Geist font.

### Lists & Mass Schedules
- Clean stacked list items bounded by `1px` top and bottom hairline borders (`#E9E6DF`).
- Mass times set in Geist Semibold (`#20221F`), accompanied by language tags (e.g., "English", "Yorùbá") in `label-sm` muted charcoal.

### Input Fields & Search
- Surface set to `#FFFFFF` with `#E9E6DF` outline. Focus state swaps border to muted burgundy (`#762D3B`) with zero heavy rings. Placeholder text rendered in `#777873`.

### Parish Audio / Rosary Player Tray
- Anchored bottom bar floating over content with a 1px top border and warm ambient shadow. Houses playback controls, progress line in antique gold (`#B49A65`), and prayer title in Geist medium.