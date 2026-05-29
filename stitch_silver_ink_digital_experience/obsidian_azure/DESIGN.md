---
name: Obsidian & Azure
colors:
  surface: '#101415'
  surface-dim: '#101415'
  surface-bright: '#363a3b'
  surface-container-lowest: '#0b0f10'
  surface-container-low: '#191c1e'
  surface-container: '#1d2022'
  surface-container-high: '#272a2c'
  surface-container-highest: '#323537'
  on-surface: '#e0e3e5'
  on-surface-variant: '#bec7d4'
  inverse-surface: '#e0e3e5'
  inverse-on-surface: '#2d3133'
  outline: '#88919d'
  outline-variant: '#3f4852'
  surface-tint: '#98cbff'
  primary: '#98cbff'
  on-primary: '#003354'
  primary-container: '#00a3ff'
  on-primary-container: '#00375a'
  inverse-primary: '#00629d'
  secondary: '#bec6e0'
  on-secondary: '#283044'
  secondary-container: '#3f465c'
  on-secondary-container: '#adb4ce'
  tertiary: '#b7c8e1'
  on-tertiary: '#213145'
  tertiary-container: '#8e9eb6'
  on-tertiary-container: '#253549'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#cfe5ff'
  primary-fixed-dim: '#98cbff'
  on-primary-fixed: '#001d33'
  on-primary-fixed-variant: '#004a77'
  secondary-fixed: '#dae2fd'
  secondary-fixed-dim: '#bec6e0'
  on-secondary-fixed: '#131b2e'
  on-secondary-fixed-variant: '#3f465c'
  tertiary-fixed: '#d3e4fe'
  tertiary-fixed-dim: '#b7c8e1'
  on-tertiary-fixed: '#0b1c30'
  on-tertiary-fixed-variant: '#38485d'
  background: '#101415'
  on-background: '#e0e3e5'
  surface-variant: '#323537'
typography:
  display-lg:
    fontFamily: Hanken Grotesk
    fontSize: 72px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.04em
  display-lg-mobile:
    fontFamily: Hanken Grotesk
    fontSize: 40px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Hanken Grotesk
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
    letterSpacing: -0.02em
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: 0em
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: 0em
  label-caps:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1.0'
    letterSpacing: 0.1em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 20px
  section-padding-lg: 120px
  section-padding-sm: 64px
---

## Brand & Style

The design system is built for a premium digital agency, bridging the gap between high-end international SaaS aesthetics and the vibrant, forward-thinking energy of Ghana's tech landscape. The brand personality is **Visionary, Technical, and Architectural**.

The visual direction combines **Minimalism** with **Glassmorphism**. It utilizes deep, "inky" backgrounds to provide a canvas for vibrant electric blue accents and high-precision typography. The aesthetic is inspired by contemporary industry leaders like Linear and Stripe, characterized by extreme attention to detail, subtle gradients, and a sense of "digital craftsmanship." 

The emotional response should be one of absolute trust and technological superiority—positioning the agency as a premium partner that delivers world-class digital products.

## Colors

The palette is anchored in a dark-mode-first philosophy to evoke a sense of luxury and depth.

*   **Primary (Electric Blue):** Used sparingly for critical CTAs, active states, and high-impact highlights. It represents the "Ink" in the brand—vibrant and precise.
*   **Secondary (Deep Navy/Slate):** Forms the foundation of the UI. This is used for backgrounds and container levels, creating a sophisticated, low-fatigue environment.
*   **Neutrals:** High-contrast whites and soft grays are used for content legibility and subtle borders.
*   **Glows:** A specialized accent glow is used for background orbs and hover states to give the UI a sense of dimensionality.

## Typography

The typography system is engineered for technical clarity and editorial impact. 

**Hanken Grotesk** is used for display and headlines, providing a sharp, contemporary edge that feels "engineered." For body copy, **Inter** ensures maximum readability across all devices. A tertiary font, **JetBrains Mono**, is utilized for small metadata labels and technical details to reinforce the "agency" and "production" nature of the work.

Hierarchy is maintained through generous vertical rhythm and a clear distinction between tight, high-impact headings and spacious, readable body text.

## Layout & Spacing

This design system utilizes a **12-column fluid grid** for desktop and a **4-column grid** for mobile. The layout philosophy is centered on "Generous Whitespace," allowing the high-quality typography and glass elements to breathe.

*   **Desktop:** 1280px max-width container with 24px gutters.
*   **Spacing Rhythm:** All spacing follows an 8px base unit. 
*   **Sectioning:** High-impact sections should use significant vertical padding (120px+) to create a premium, unhurried pace. 
*   **Mobile Reflow:** For mobile, typography scales down and margins tighten to 20px, but the "breathable" feel is maintained through vertical stacking and increased line-height.

## Elevation & Depth

Hierarchy is established through **Glassmorphism** and **Tonal Layering** rather than traditional heavy shadows.

1.  **Base Layer:** The darkest background (#020617).
2.  **Surface Layer:** Semi-transparent navy backgrounds with a `backdrop-filter: blur(12px)`.
3.  **Outlines:** "Ghost borders" are essential. Use 1px solid borders with low opacity (e.g., `rgba(255, 255, 255, 0.08)`) to define card edges.
4.  **Luminous Depth:** Use subtle radial gradients (Electric Blue at 5-10% opacity) positioned behind key cards to create a "soft glow" effect, suggesting the light is emanating from the content itself.

## Shapes

The shape language is "Sophisticated Softness." We avoid sharp corners to keep the brand approachable, but we avoid the "bubbly" look of consumer apps. 

A standard **0.5rem (8px)** radius is the default for buttons and small inputs. Larger components like cards and sections use a **1rem (16px)** radius. This creates a geometric consistency that feels modern and architectural.

## Components

*   **Glass Cards:** The signature component. Feature a 1px border, a background blur of 12px-20px, and a subtle top-down linear gradient (slightly lighter at the top).
*   **Primary Buttons:** Solid Electric Blue with white or very dark navy text. Hover states should feature a subtle outer glow rather than a color change.
*   **Ghost Buttons:** Transparent background with a 1px slate border. Text remains white.
*   **Input Fields:** Deep navy backgrounds with a 1px border that glows Electric Blue on focus. Labels should use the `label-caps` typography style.
*   **Chips/Tags:** Small, pill-shaped elements using the monospaced font, utilizing high-contrast background tints (e.g., Electric Blue at 10% opacity with Electric Blue text).
*   **Progress Indicators:** Use ultra-thin 2px lines with the Electric Blue accent to maintain a "high-tech" precision look.