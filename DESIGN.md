---
name: Elite Authority Transformation
colors:
  surface: '#16130b'
  surface-dim: '#16130b'
  surface-bright: '#3d392f'
  surface-container-lowest: '#110e07'
  surface-container-low: '#1f1b13'
  surface-container: '#231f17'
  surface-container-high: '#2e2a21'
  surface-container-highest: '#39342b'
  on-surface: '#eae1d4'
  on-surface-variant: '#d1c5af'
  inverse-surface: '#eae1d4'
  inverse-on-surface: '#343027'
  outline: '#99907b'
  outline-variant: '#4d4635'
  surface-tint: '#ecc246'
  primary: '#ecc246'
  on-primary: '#3d2e00'
  primary-container: '#c9a227'
  on-primary-container: '#4b3a00'
  inverse-primary: '#755b00'
  secondary: '#c6c6c6'
  on-secondary: '#303030'
  secondary-container: '#474747'
  on-secondary-container: '#b5b5b5'
  tertiary: '#c6c6c7'
  on-tertiary: '#2f3131'
  tertiary-container: '#a6a7a7'
  on-tertiary-container: '#3b3d3d'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffe08e'
  primary-fixed-dim: '#ecc246'
  on-primary-fixed: '#241a00'
  on-primary-fixed-variant: '#584400'
  secondary-fixed: '#e2e2e2'
  secondary-fixed-dim: '#c6c6c6'
  on-secondary-fixed: '#1b1b1b'
  on-secondary-fixed-variant: '#474747'
  tertiary-fixed: '#e2e2e2'
  tertiary-fixed-dim: '#c6c6c7'
  on-tertiary-fixed: '#1a1c1c'
  on-tertiary-fixed-variant: '#454747'
  background: '#16130b'
  on-background: '#eae1d4'
  surface-variant: '#39342b'
  surface-deep: '#0A0A0A'
  gold-light: '#E5C86C'
  gold-dark: '#8C6D15'
  neutral-gray: '#1A1A1A'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 72px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 40px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-xl:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-xl-mobile:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-md:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '500'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '300'
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
    lineHeight: '1.2'
    letterSpacing: 0.2em
  button:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.1em
spacing:
  section-padding-desktop: 160px
  section-padding-mobile: 80px
  gutter: 24px
  container-max-width: 1140px
  stack-space: 32px
---

## Brand & Style
The design system is engineered to evoke a sense of high-tier exclusivity, discipline, and profound personal transformation. Targeting high-achievers who feel stagnant, the visual language prioritizes authority through a "Luxury Minimalist" aesthetic. 

The strategy utilizes high-contrast visuals—deep blacks and brilliant whites—to symbolize the clarity found after leaving the "autopilot" fog. Gold accents are used sparingly but intentionally to represent value, achievement, and the "FAR" standard. The overall feel is editorial, clean, and uncompromising, positioning the training not as a mass-market course, but as a premium invitation-only journey.

## Colors
This design system defaults to a **dark mode** experience to maximize the feeling of exclusivity and focus. 

- **Primary Gold (#C9A227):** Reserved for calls to action, progress indicators, and critical highlights. It represents the "Golden Ratio" of a life under control.
- **Pure Black (#000000):** Used for primary backgrounds to create a "void" effect, allowing content to emerge with maximum impact.
- **Pure White (#FFFFFF):** Used for primary typography to ensure razor-sharp legibility and a clean, high-contrast look.
- **Surface Tones:** Dark grays are used to create subtle separation between content sections without breaking the immersive dark atmosphere.

## Typography
The typographic hierarchy creates an editorial rhythm. **Playfair Display** provides the "voice" of the brand—authoritative, classical, and sophisticated. It should be used for all major psychological hooks and section titles. 

**Inter** handles the functional "direction." It is set with generous line heights and slight letter spacing in body text to ensure the reading experience feels effortless and premium. 

Large display sizes should use tighter letter spacing for a more "locked-in" look, while labels and buttons use wide tracking to emphasize a modern, clean aesthetic.

## Layout & Spacing
The layout follows a **fixed grid** philosophy with extreme vertical breathing room. Sections are separated by large paddings to force the user to slow down and digest the message—reflecting the move away from "autopilot."

- **Desktop:** A 12-column grid with a narrow central container (max 1140px) to keep line lengths readable.
- **Whitespace:** Use "intentional voids." Do not feel the need to fill the sides of the screen. 
- **Alignment:** Primarily center-aligned for impact headers, and left-aligned for long-form narrative content to maintain a journal-like quality.

## Elevation & Depth
In this design system, depth is achieved through **Tonal Layering** and **Subtle Outlines** rather than heavy shadows.

- **Surface Levels:** The base is #000000. Secondary containers (like cards or form areas) use #0A0A0A.
- **Borders:** Use ultra-thin (1px) borders in either low-opacity white (10%) or a subtle gold gradient to define sections without adding visual weight.
- **Glow:** Occasionally, a very soft, large-radius gold glow (background blur) may be used behind primary elements to simulate a "halo" or spotlight effect, signifying transformation.

## Shapes
The shape language is strictly **Sharp (0px)**. 

Curves are perceived as soft or casual. This design system uses hard 90-degree angles to communicate precision, discipline, and structural integrity. Every element—from buttons to input fields to images—must maintain a sharp, architectural edge. This reinforces the concept of "taking control" and "direction."

## Components
### Buttons
Primary buttons are the hallmark of the system. They use a solid Gold (#C9A227) background with Black text. Hover states should involve a slight "shimmer" effect or a shift to a lighter gold. Secondary buttons use a transparent background with a 1px gold border.

### Input Fields
Forms should feel like high-end stationery. Use a bottom-border only (1px white) or a very dark gray box. Labels sit above the field in `label-caps` style. Focus states should transition the bottom border to Gold.

### Cards & Containers
Containers for "The Pain" or "Results" should be simple black blocks with a thin Gold left-border (accent line) to guide the eye downward, symbolizing progress.

### Progress Indicators
For the "90-day journey," use a minimalist linear timeline. It should be a thin gray line that turns gold as the user scrolls, visually representing the path of transformation.

### Imagery
Photography should be high-contrast, moody, and professional. Use black-and-white images with gold overlays or high-key lighting to maintain the luxury atmosphere.