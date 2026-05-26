---
name: Aura Narrative
colors:
  surface: '#faf9f8'
  surface-dim: '#dadad9'
  surface-bright: '#faf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f4f3f2'
  surface-container: '#eeeeed'
  surface-container-high: '#e9e8e7'
  surface-container-highest: '#e3e2e1'
  on-surface: '#1a1c1c'
  on-surface-variant: '#444748'
  inverse-surface: '#2f3130'
  inverse-on-surface: '#f1f0f0'
  outline: '#747878'
  outline-variant: '#c4c7c7'
  surface-tint: '#5f5e5e'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#1c1b1b'
  on-primary-container: '#858383'
  inverse-primary: '#c8c6c5'
  secondary: '#6c5c47'
  on-secondary: '#ffffff'
  secondary-container: '#f3dcc2'
  on-secondary-container: '#70604b'
  tertiary: '#735c00'
  on-tertiary: '#ffffff'
  tertiary-container: '#cca730'
  on-tertiary-container: '#4f3e00'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e5e2e1'
  primary-fixed-dim: '#c8c6c5'
  on-primary-fixed: '#1c1b1b'
  on-primary-fixed-variant: '#474746'
  secondary-fixed: '#f5dfc5'
  secondary-fixed-dim: '#d8c3aa'
  on-secondary-fixed: '#251a0a'
  on-secondary-fixed-variant: '#534431'
  tertiary-fixed: '#ffe088'
  tertiary-fixed-dim: '#e9c349'
  on-tertiary-fixed: '#241a00'
  on-tertiary-fixed-variant: '#574500'
  background: '#faf9f8'
  on-background: '#1a1c1c'
  surface-variant: '#e3e2e1'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 64px
    fontWeight: '400'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 40px
    fontWeight: '400'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '400'
    lineHeight: '1.3'
  headline-sm:
    fontFamily: Playfair Display
    fontSize: 24px
    fontWeight: '400'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: 0.01em
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-caps:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1.0'
    letterSpacing: 0.1em
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1.4'
rounded:
  sm: 0.5rem
  DEFAULT: 1rem
  md: 1.5rem
  lg: 2rem
  xl: 3rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1440px
  gutter: 32px
  margin-desktop: 64px
  margin-mobile: 20px
  section-gap: 120px
---

## Brand & Style
This design system is built for high-end, luxury e-commerce environments where the product is treated as art. The brand personality is quiet, confident, and sophisticated, favoring an editorial aesthetic over traditional retail clutter. 

The visual style is **Ultra-Minimalist** with a focus on expansive whitespace, allowing imagery to breathe. It leverages high-contrast structural elements and refined typography to evoke a sense of "digital silk"—smooth, premium, and effortless. The target audience values exclusivity, craftsmanship, and a frictionless, serene shopping experience.

## Colors
The palette is rooted in a soft, non-clinical off-white (`#fcfbfa`) that provides a warm, paper-like foundation. Dark charcoal (`#1a1a1a`) is used for primary text and structural borders to ensure high legibility and a sharp, high-contrast finish. 

Soft taupe and subtle gold are used sparingly as accents for micro-interactions, active states, or premium indicators (e.g., "Exclusive" tags). All secondary colors must maintain a low saturation to prevent the interface from distracting from product photography.

## Typography
The typographic hierarchy relies on the contrast between the timeless, high-contrast strokes of **Playfair Display** and the functional clarity of **Inter**. 

Headlines should use ample leading and slight negative letter-spacing to appear as cohesive units. Body text is set with generous line heights to enhance the "airy" feel of the design system. The `label-caps` style is specifically reserved for navigation, product categories, and metadata to provide a structured, architectural feel to the layout.

## Layout & Spacing
The layout follows a **fixed-width central container** for desktop, ensuring that editorial content remains composed and intentional. We utilize a 12-column grid with wide 32px gutters to prevent visual crowding.

Spacing is governed by a strict 8px base unit, but luxury is expressed through the intentional use of "oversized" margins. Large sections should be separated by a minimum of 120px (`section-gap`) to signify a change in narrative. On mobile, margins shrink to 20px, but vertical rhythm remains expansive to encourage scrolling.

## Elevation & Depth
This design system avoids heavy shadows and traditional skeuomorphism. Depth is achieved through **Tonal Layering** and **High-Contrast Outlines**.

1.  **Surfaces:** The primary background is the off-white base. Modal overlays or elevated cards use the same color but are defined by a crisp 1px solid border in charcoal or a very subtle taupe.
2.  **Backdrop:** Glassmorphism is used exclusively for the navigation bar—a high-density blur with 90% opacity of the base color—to maintain context while scrolling.
3.  **Active States:** Elevation is signaled by a shift in border weight (from 1px to 2px) or a subtle color fill change, rather than a shadow cast.

## Shapes
The shape language is a juxtaposition of sharp, architectural containers and organic, fluid interactive elements. 

Structural components like image containers, input fields, and dividers use sharp 0px corners to maintain a "grid-heavy" editorial look. However, all primary calls-to-action (buttons) and tags use a **Pill-shaped (3)** radius. This creates a clear visual distinction between "content" and "action," making the interface intuitive despite its minimalist aesthetic.

## Components
- **Primary Buttons:** Full pill-shaped, charcoal background with white Inter text. On hover, they should transition fluidly to a soft taupe or expand slightly in width.
- **Product Cards:** No borders or shadows. The product image sits on a subtle taupe background. Typography (Product Name and Price) is center-aligned beneath the image using `headline-sm` and `label-md`.
- **Navigation:** A minimal, sticky top bar. Links use `label-caps`. The "Cart" icon is a simple stroke-based icon with a numerical badge that only appears when items are present.
- **Input Fields:** Bottom-border only (1px charcoal). Labels float above in `label-caps` when active. No background fill unless in an error state.
- **Editorial Sections:** Large-scale imagery spanning 8/12 columns with text blocks occupying the remaining 4 columns, utilizing `display-lg` typography for an immersive storytelling effect.
- **Chips/Tags:** Pill-shaped with a 1px taupe border and `label-caps` text. Used for sizes, colors, or category filters.