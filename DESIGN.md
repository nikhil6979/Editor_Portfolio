---
name: Cinematic Noir
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
  on-surface-variant: '#c6c6cd'
  inverse-surface: '#e0e3e5'
  inverse-on-surface: '#2d3133'
  outline: '#909097'
  outline-variant: '#45464d'
  surface-tint: '#bec6e0'
  primary: '#bec6e0'
  on-primary: '#283044'
  primary-container: '#0f172a'
  on-primary-container: '#798098'
  inverse-primary: '#565e74'
  secondary: '#ffb3b6'
  on-secondary: '#68001a'
  secondary-container: '#cc003c'
  on-secondary-container: '#ffdcdc'
  tertiary: '#7bd0ff'
  on-tertiary: '#00354a'
  tertiary-container: '#001a27'
  on-tertiary-container: '#008abb'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#dae2fd'
  primary-fixed-dim: '#bec6e0'
  on-primary-fixed: '#131b2e'
  on-primary-fixed-variant: '#3f465c'
  secondary-fixed: '#ffdada'
  secondary-fixed-dim: '#ffb3b6'
  on-secondary-fixed: '#40000c'
  on-secondary-fixed-variant: '#920028'
  tertiary-fixed: '#c4e7ff'
  tertiary-fixed-dim: '#7bd0ff'
  on-tertiary-fixed: '#001e2c'
  on-tertiary-fixed-variant: '#004c69'
  background: '#101415'
  on-background: '#e0e3e5'
  surface-variant: '#323537'
typography:
  headline-xl:
    fontFamily: Anton
    fontSize: 96px
    fontWeight: '400'
    lineHeight: 100%
  headline-lg:
    fontFamily: Anton
    fontSize: 48px
    fontWeight: '400'
    lineHeight: 110%
  headline-lg-mobile:
    fontFamily: Anton
    fontSize: 32px
    fontWeight: '400'
    lineHeight: 110%
  title-md:
    fontFamily: Space Grotesk
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 120%
    letterSpacing: 0.1em
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 160%
  body-sm:
    fontFamily: Hanken Grotesk
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 150%
  label-caps:
    fontFamily: Space Grotesk
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 100%
    letterSpacing: 0.2em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  container-max: 1280px
  gutter: 24px
  margin-mobile: 20px
  margin-desktop: 64px
  section-gap: 120px
---

## Brand & Style

The design system is built on a "Cinematic Noir" aesthetic, optimized for high-impact portfolios and creative showcases. It evokes a sense of professional intensity, modernism, and drama. The style blends elements of **Modern Minimalism** with **Vaporwave-inspired lighting**, using deep shadows and localized radial glows to create a sense of three-dimensional space within a digital environment. 

The target audience is high-tier creative professionals who require a UI that acts as a stage for their work—bold, confident, and authoritative. It prioritizes high-contrast focal points, aggressive typography, and a "gaming-interface" level of polish that feels both technical and artistic.

## Colors

The color strategy is "Deep Space High-Contrast." The foundation is a rich, near-black navy blue that provides more depth than pure black. 

- **Primary:** A deep, atmospheric midnight blue used for backgrounds and base surfaces.
- **Accent (Crimson):** A high-energy red used sparingly for branding elements and high-priority status indicators.
- **Accent (Electric Blue):** A glowing cyan-blue used for interactive states, highlighting selected navigation items, and radial background gradients.
- **Typography:** Stark white or light grey for maximum legibility against the dark canvas.

Backgrounds should utilize subtle radial gradients (light source: Top-Left or Center) using the tertiary color at 5-10% opacity to create a "spotlight" effect on content.

## Typography

This design system employs a "Type-as-Image" philosophy. Large, condensed headings dominate the hierarchy, creating an editorial feel. 

- **Headlines:** Use **Anton** for a bold, impactful, and industrial look. Headlines should almost always be uppercase with tight line-height to maximize visual weight.
- **Secondary Titles:** Use **Space Grotesk** for technical, wide-set titles. The contrast between the condensed Anton and wide Space Grotesk creates a sophisticated tension.
- **Body & Captions:** **Hanken Grotesk** provides a clean, modern, and highly legible counterpoint to the aggressive display faces.

Avoid using italics. Use weight and tracking (letter-spacing) to create hierarchy instead.

## Layout & Spacing

The design system utilizes a **Fixed Grid** on desktop and a **Fluid Grid** on mobile. The layout is inspired by luxury magazine spreads, characterized by generous vertical spacing and intentional asymmetry.

- **Grid:** A 12-column grid system with wide gutters (24px) to allow content to breathe.
- **Rhythm:** Vertical spacing is aggressive (120px+ between major sections) to ensure each piece of content feels like a singular "event."
- **Alignment:** Content often uses a "Center-Weighted" or "Split-Screen" approach, where imagery sits on one side and technical data sits on the other.
- **Mobile Adaptivity:** On mobile, columns collapse to a single stack. Headlines scale down significantly to prevent awkward word-breaks in the condensed typeface.

## Elevation & Depth

Depth is achieved through **localized lighting and tonal layering** rather than traditional drop shadows.

- **Glow Effects:** Instead of shadows, use "Outer Glows" or "Backdrop Blurs" with the tertiary blue color to indicate active or elevated states.
- **Glassmorphism:** Navigation bars and overlays use high-blur (20px+) backgrounds with a subtle white border (1px at 10% opacity) to simulate frosted glass.
- **Spotlight:** Key imagery should have a faint radial gradient behind it, making the subject appear as if it is being projected onto the screen.
- **Tonal Tiers:** The base background is the darkest. Cards and containers are 5% lighter, creating a subtle lift without breaking the "Noir" mood.

## Shapes

The shape language is "Structural Softness." While the typography is sharp and aggressive, the UI containers use a **Rounded (0.5rem)** base to maintain a modern, premium feel.

- **Primary Elements:** 0.5rem (8px) radius for standard cards and input fields.
- **Interaction Elements:** Pill-shaped (100px) buttons and tags to contrast against the rectangular grid.
- **Clipping Masks:** Portraits and featured graphics should alternate between sharp rectangles and organic, asymmetrical circular masks to break the monotony of the grid.

## Components

### Buttons & Interaction
- **Primary Button:** Pill-shaped, solid white or tertiary blue with dark text. No shadow; use a subtle outer glow on hover.
- **Ghost Button:** Pill-shaped with a 1px border. Text in uppercase Space Grotesk.

### Cards
- **Project Card:** Edge-to-edge imagery with a 1px inner stroke. Information is revealed on hover using a glassmorphic overlay that slides from the bottom.

### Inputs
- **Field Style:** Underline-only or subtly filled dark containers. Focus state is indicated by a color change in the label to the tertiary blue.

### Navigation
- **Active State:** A pill-shaped background highlight using the tertiary blue at low opacity, or a small glowing dot below the menu item.

### Chips & Tags
- Small, uppercase labels with high letter-spacing. Use the secondary red for "New" or "Hot" items, and the tertiary blue for category filters.