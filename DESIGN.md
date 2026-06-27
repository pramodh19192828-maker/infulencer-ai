---
name: Vibrant Professional
colors:
  surface: '#faf8ff'
  surface-dim: '#d2d9f4'
  surface-bright: '#faf8ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f3ff'
  surface-container: '#eaedff'
  surface-container-high: '#e2e7ff'
  surface-container-highest: '#dae2fd'
  on-surface: '#131b2e'
  on-surface-variant: '#4a4455'
  inverse-surface: '#283044'
  inverse-on-surface: '#eef0ff'
  outline: '#7b7487'
  outline-variant: '#ccc3d8'
  surface-tint: '#732ee4'
  primary: '#630ed4'
  on-primary: '#ffffff'
  primary-container: '#7c3aed'
  on-primary-container: '#ede0ff'
  inverse-primary: '#d2bbff'
  secondary: '#0051d5'
  on-secondary: '#ffffff'
  secondary-container: '#316bf3'
  on-secondary-container: '#fefcff'
  tertiary: '#8f1e62'
  on-tertiary: '#ffffff'
  tertiary-container: '#ae397b'
  on-tertiary-container: '#ffdce9'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#eaddff'
  primary-fixed-dim: '#d2bbff'
  on-primary-fixed: '#25005a'
  on-primary-fixed-variant: '#5a00c6'
  secondary-fixed: '#dbe1ff'
  secondary-fixed-dim: '#b4c5ff'
  on-secondary-fixed: '#00174b'
  on-secondary-fixed-variant: '#003ea8'
  tertiary-fixed: '#ffd8e7'
  tertiary-fixed-dim: '#ffafd3'
  on-tertiary-fixed: '#3d0026'
  on-tertiary-fixed-variant: '#85145a'
  background: '#faf8ff'
  on-background: '#131b2e'
  surface-variant: '#dae2fd'
typography:
  headline-xl:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '800'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
  headline-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 14px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 4px
  xs: 8px
  sm: 16px
  md: 24px
  lg: 40px
  xl: 64px
  gutter: 16px
  margin-mobile: 20px
  max-width-desktop: 1280px
---

## Brand & Style

The design system is engineered for a high-growth Micro-Influencer marketplace, bridging the gap between professional enterprise reliability and the energetic pulse of the creator economy. The brand personality is "Professional Creative"—highly functional and organized, yet bursting with the kinetic energy of digital trendsetters. 

The visual style blends **Modern Minimalism** with **Tactile Depth**. It uses expansive whitespace to ensure clarity for business owners while employing vibrant color accents and smooth transitions to engage creators. The emotional response should be one of confidence, momentum, and seamless connection. Elements are clean and systematic, but never static.

## Colors

The palette is anchored by **Electric Purple (#7C3AED)**, symbolizing the creative spark and brand authority. **Cobalt Blue (#2563EB)** serves as a reliable secondary anchor for transactional elements and navigation, reinforcing trust. A tertiary **Pink (#F472B6)** is reserved for high-action highlights like "Live" status indicators or trending tags.

The neutral scale utilizes a deep navy-slate for text to maintain better readability and a softer aesthetic than pure black. Backgrounds should primarily stay white (#FFFFFF) or extremely light slate (#F8FAFC) to let user-generated content and creator portfolios remain the focal point.

## Typography

The design system utilizes **Inter** for all roles to achieve a systematic, "tech-forward" feel. The hierarchy relies on significant weight contrast—using Extra Bold (800) for primary marketing headlines and Semi Bold (600) for UI labels.

Tighten letter-spacing on larger headlines to create a more impactful, editorial appearance. For mobile, headline sizes are aggressively scaled down to ensure that profile names and campaign titles do not wrap awkwardly. Body copy maintains a generous line height to ensure legibility during long browsing sessions of creator bios.

## Layout & Spacing

This design system uses a **Fluid Grid** approach with an 8px base unit. 

- **Desktop:** 12-column grid, 1280px max-width, 24px gutters.
- **Tablet:** 8-column grid, 16px gutters.
- **Mobile:** 4-column grid, 20px side margins, 16px gutters.

The rhythm is defined by generous internal padding within cards (24px) to ensure the interface feels premium and breathable. Navigation on mobile should prioritize a bottom-tab bar for the primary app-like experience, while desktop utilizes a persistent top-nav with a secondary sidebar for dashboard views.

## Elevation & Depth

Hierarchy is established through **Ambient Shadows** and **Tonal Layering**. 

1. **Base:** The background surface is #F8FAFC.
2. **Surface:** Cards and containers sit on #FFFFFF with a very soft, diffused shadow: `0px 4px 20px rgba(15, 23, 42, 0.05)`.
3. **Elevated:** Interactive elements like hovered cards or primary buttons use a more pronounced shadow: `0px 10px 25px rgba(124, 58, 237, 0.15)`, subtly tinted with the primary purple color.

Avoid heavy borders; use subtle 1px strokes in #E2E8F0 only when elements need separation on identical background colors.

## Shapes

The design system adopts a **Rounded** shape language to feel modern and approachable. 

- **Standard Elements:** 0.5rem (8px) radius for buttons and input fields.
- **Containers:** 1rem (16px) radius for profile cards, campaign modules, and modal overlays.
- **Avatars:** Strictly circular to distinguish people (influencers) from objects (campaigns/cards).

This consistency in curvature ensures that even data-heavy screens feel friendly rather than institutional.

## Components

### Buttons
- **Primary:** Electric Purple background, White text. High-emphasis for "Apply to Campaign" or "Hire."
- **Secondary:** White background, Cobalt Blue border and text. Used for "Message" or "View Profile."
- **Ghost:** No border, Slate text. Used for secondary navigation or "Cancel" actions.

### Cards
Creator cards are the core component. They feature a high-resolution header image, a circular avatar overlapping the image/content boundary, and a statistics grid (Followers, Engagement) using **Label-MD** typography.

### Input Fields
Inputs use a 1px border (#E2E8F0). On focus, the border transitions to Electric Purple with a 2px outer glow. Labels always sit above the field in **Label-SM** for maximum clarity.

### Chips & Tags
Used for "Niches" (e.g., Beauty, Tech). These use a light tint of the Primary color (10% opacity) with the full-strength color for the text, maintaining a soft but colorful aesthetic.

### Progress Indicators
For campaign milestones, use a thick Cobalt Blue bar with a rounded end-cap, showing clear status from "Contract Signed" to "Post Live."