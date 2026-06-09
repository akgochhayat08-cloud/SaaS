---
name: SaaS Core
colors:
  surface: '#0b1326'
  surface-dim: '#0b1326'
  surface-bright: '#31394d'
  surface-container-lowest: '#060e20'
  surface-container-low: '#131b2e'
  surface-container: '#171f33'
  surface-container-high: '#222a3d'
  surface-container-highest: '#2d3449'
  on-surface: '#dae2fd'
  on-surface-variant: '#c7c4d7'
  inverse-surface: '#dae2fd'
  inverse-on-surface: '#283044'
  outline: '#908fa0'
  outline-variant: '#464554'
  surface-tint: '#c0c1ff'
  primary: '#c0c1ff'
  on-primary: '#1000a9'
  primary-container: '#8083ff'
  on-primary-container: '#0d0096'
  inverse-primary: '#494bd6'
  secondary: '#ddb7ff'
  on-secondary: '#490080'
  secondary-container: '#6f00be'
  on-secondary-container: '#d6a9ff'
  tertiary: '#ffb783'
  on-tertiary: '#4f2500'
  tertiary-container: '#d97721'
  on-tertiary-container: '#452000'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e1e0ff'
  primary-fixed-dim: '#c0c1ff'
  on-primary-fixed: '#07006c'
  on-primary-fixed-variant: '#2f2ebe'
  secondary-fixed: '#f0dbff'
  secondary-fixed-dim: '#ddb7ff'
  on-secondary-fixed: '#2c0051'
  on-secondary-fixed-variant: '#6900b3'
  tertiary-fixed: '#ffdcc5'
  tertiary-fixed-dim: '#ffb783'
  on-tertiary-fixed: '#301400'
  on-tertiary-fixed-variant: '#703700'
  background: '#0b1326'
  on-background: '#dae2fd'
  surface-variant: '#2d3449'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 64px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.04em
  display-lg-mobile:
    fontFamily: Inter
    fontSize: 40px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
    letterSpacing: -0.02em
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
  label-sm:
    fontFamily: Geist
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1.0'
    letterSpacing: 0.05em
  mono-code:
    fontFamily: Geist
    fontSize: 14px
    fontWeight: '400'
    lineHeight: '1.5'
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 16px
  section-gap-lg: 120px
  section-gap-md: 80px
---

## Brand & Style

The design system is rooted in the "Sophisticated Tech" aesthetic, blending the systematic rigor of enterprise software with the fluid, high-end feel of modern AI platforms. It aims to evoke a sense of absolute reliability, precision, and forward-thinking innovation.

The style is **Corporate Modern with Glassmorphism accents**. It prioritizes a high-contrast environment to ensure data density remains readable while using subtle gradients and translucent layers to soften the industrial edges. The visual narrative focuses on "clarity through depth," utilizing a dark-mode first approach for high-performance tools, while maintaining a clean, accessible light mode for administrative tasks.

## Colors

The palette is anchored by a deep navy and charcoal foundation to provide a "limitless" canvas feel. 

- **Primary & Secondary:** An Electric Indigo and Vibrant Purple duo used for primary actions and brand-heavy moments like hero sections. These are often applied as linear gradients (Indigo to Purple) to signify movement and intelligence.
- **Neutral:** A range of Slate and Navy tones. The background uses the darkest shade (#020617) to provide maximum contrast for white text.
- **Surface Strategy:** Surfaces are layered using "Slate-900" (#0F172A). In dark mode, borders should use a slightly lighter "Slate-800" to define boundaries without heavy shadows.

## Typography

This design system utilizes **Inter** for its neutral, highly legible characteristics across all UI and body copy. For technical metadata and labels, **Geist** is introduced to provide a precise, developer-friendly "tech" feel.

- **Display Text:** Large headlines use heavy weights (700) and tight letter spacing to create a commanding presence in hero sections.
- **Body Copy:** Maintains a generous line height (1.5 - 1.6) to ensure long-form documentation and dashboard data remain digestible.
- **Hierarchical Contrast:** Use "Slate-400" for secondary body text and "White" for primary headlines to create a clear visual path.

## Layout & Spacing

The layout follows a **Fixed Grid** philosophy for marketing pages and a **Fluid Flex** model for application dashboards.

- **Desktop:** 12-column grid with a 1280px max-width. Gutters are fixed at 24px to maintain breathability between feature cards.
- **Sectioning:** Vertical rhythm is aggressive. Hero sections and major feature transitions use 120px gaps to signal a change in narrative.
- **Dashboards:** Sidebars are fixed at 280px, with the remaining content area expanding fluidly. Padding within dashboard "widgets" should be a consistent 24px (3x base).

## Elevation & Depth

Depth is achieved through **Tonal Layering** and **Subtle Glows** rather than traditional heavy shadows.

1.  **Level 0 (Background):** #020617.
2.  **Level 1 (Cards/Sidebar):** #0F172A with a 1px solid border of #1E293B.
3.  **Level 2 (Modals/Popovers):** #1E293B with a "Soft Indigo" ambient glow (0px 20px 40px rgba(99, 102, 241, 0.1)).
4.  **Glassmorphism:** Use a `backdrop-filter: blur(12px)` with a `background: rgba(15, 23, 42, 0.8)` for sticky navigation bars and floating tooltips to maintain context of the content beneath.

## Shapes

The design system utilizes **Rounded** corners to balance the "sharpness" of the high-contrast palette. 

- **Small Components:** Checkboxes and small tags use `rounded-sm` (4px).
- **Standard UI:** Buttons, input fields, and standard cards use `rounded-md` (8px).
- **Featured Elements:** Pricing tables and Hero CTA buttons use `rounded-xl` (24px) or full pill shapes to draw the eye.

## Components

### Buttons
- **Primary:** Linear gradient (Indigo to Purple), white text, 8px radius. On hover, increase the brightness of the gradient.
- **Secondary:** Transparent background with a 1px Slate-700 border.
- **Ghost:** No border or background; text turns white on hover with a subtle Slate-800 background fill.

### Feature Grids
Cards should have a subtle 1px top-border highlight (lighter than the side borders) to simulate a light source. Icons within cards should use a "faded-out" version of the primary color as a background circular "blob."

### Pricing Tables
The "Recommended" tier should be scaled 1.05x and feature a 2px primary-to-secondary gradient border. The price point should use `display-lg` typography for maximum impact.

### Input Fields
Dark backgrounds (#020617) with 1px Slate-800 borders. On focus, the border transitions to Primary Indigo with a 2px outer glow.

### Chips/Tags
Small, Geist-font labels with a low-opacity Indigo background (e.g., `rgba(99, 102, 241, 0.1)`) and solid Indigo text.