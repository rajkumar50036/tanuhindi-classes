---
name: Premium Indian EdTech
colors:
  surface: '#fefccf'
  surface-dim: '#dedcb1'
  surface-bright: '#fefccf'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f8f6c9'
  surface-container: '#f2f0c4'
  surface-container-high: '#eceabe'
  surface-container-highest: '#e6e5b9'
  on-surface: '#1d1d03'
  on-surface-variant: '#554336'
  inverse-surface: '#323214'
  inverse-on-surface: '#f5f3c7'
  outline: '#887364'
  outline-variant: '#dbc2b0'
  surface-tint: '#8f4e00'
  primary: '#8f4e00'
  on-primary: '#ffffff'
  primary-container: '#ff9933'
  on-primary-container: '#693800'
  inverse-primary: '#ffb77a'
  secondary: '#b22b1d'
  on-secondary: '#ffffff'
  secondary-container: '#fe624e'
  on-secondary-container: '#650000'
  tertiary: '#735c00'
  on-tertiary: '#ffffff'
  tertiary-container: '#d3ae36'
  on-tertiary-container: '#544200'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdcc2'
  primary-fixed-dim: '#ffb77a'
  on-primary-fixed: '#2e1500'
  on-primary-fixed-variant: '#6d3a00'
  secondary-fixed: '#ffdad4'
  secondary-fixed-dim: '#ffb4a8'
  on-secondary-fixed: '#410000'
  on-secondary-fixed-variant: '#8f0f07'
  tertiary-fixed: '#ffe088'
  tertiary-fixed-dim: '#e9c349'
  on-tertiary-fixed: '#241a00'
  on-tertiary-fixed-variant: '#574500'
  background: '#fefccf'
  on-background: '#1d1d03'
  surface-variant: '#e6e5b9'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 56px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
  title-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  hindi-display:
    fontFamily: Noto Serif
    fontSize: 1.2em
    fontWeight: '500'
    lineHeight: '1.5'
  label-caps:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '700'
    lineHeight: '1'
    letterSpacing: 0.1em
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
  margin-desktop: 64px
  margin-tablet: 32px
  margin-mobile: 20px
---

## Brand & Style

This design system is built to balance the warmth of Indian cultural heritage with the precision of modern educational technology. The brand personality is scholarly, premium, and welcoming, aiming to evoke a sense of "Modern Gurukul"—where traditional language learning meets high-end digital experiences.

The visual style utilizes **Glassmorphism** to create depth and lightness against a warm, paper-like background. The interface avoids cold, clinical whites in favor of ivory and cream tones, suggesting a premium, tactile quality. Cinematic lighting in photography—characterized by soft golden hour glows and shallow depth of field—complements the Saffron and Maroon palette to create an aspirational atmosphere for students.

## Colors

The palette is rooted in the "Saffron and Maroon" traditional Indian aesthetic but refined for digital legibility. 

- **Primary (Saffron):** Reserved strictly for high-priority Call-to-Actions (CTAs), progress indicators, and active states. It represents energy and the "fire of knowledge."
- **Secondary (Dark Maroon):** Used for primary typography, borders, and sophisticated brand accents. It provides the necessary weight and authority to the scholarly content.
- **Background (Light Cream):** This replaces pure white for the main canvas to reduce eye strain and provide a "luxury stationary" feel. Pure white is used sparingly for card interiors or specific glass highlights.
- **Accents:** Gold tints (#D4AF37) may be used for achievement badges and "Pro" tier features.

## Typography

This design system employs a dual-language typographic strategy. **Plus Jakarta Sans** provides a modern, high-end geometric feel for headlines, while **Inter** ensures maximum readability for dense educational content and course materials.

**Hindi Integration:**
When Devanagari script is used (e.g., for vocabulary words or quotes), **Noto Serif** is the designated font to provide a classic, authoritative literary feel. Use `hindi-display` for pull-out quotes or lesson headers to create a beautiful visual contrast between the sans-serif English UI and the serifed Hindi content. 

Maroon is the default color for headlines to maintain a sophisticated, grounded aesthetic.

## Layout & Spacing

The layout utilizes a **12-column fixed grid** for desktop and a **4-column fluid grid** for mobile. Spacing follows an 8px rhythmic scale to ensure consistent proportions across all components.

- **Desktop:** Large margins (64px) and wide gutters (24px) create an "editorial" feel with plenty of whitespace.
- **Mobile:** Margins shrink to 20px, and vertical spacing between cards is increased to emphasize the individual glassmorphic layers.
- **Content Width:** Lessons and articles are constrained to a maximum of 720px for optimal line length and reading speed.

## Elevation & Depth

This design system uses a "Layered Glass" approach to depth. 

1.  **Level 0 (Base):** The Light Cream (#FFFDD0) background.
2.  **Level 1 (Cards):** Glassmorphic surfaces with a 12px-20px backdrop blur and a 1px semi-transparent white border. Shadows are extremely soft (15% opacity Maroon tint) to avoid a "dirty" look.
3.  **Level 2 (Modals/Popovers):** Deeper blurs (40px) and a slightly thicker 2px Maroon border at 10% opacity to distinguish high-priority interactions.

**Shadow Character:**
Instead of neutral greys, shadows use a faint Maroon tint (`rgba(128, 0, 0, 0.08)`). This keeps the shadows warm and aligned with the "Paper and Ink" aesthetic.

## Shapes

The shape language is purposefully **Rounded (0.5rem / 8px)** to feel approachable yet modern. 

- **Standard Components:** 8px radius (Buttons, Input fields).
- **Glass Cards:** 16px radius (Large containers, Course cards).
- **Imagery:** Soft-cropped with 24px radius to mimic the cinematic, premium feel.

Avoid sharp corners entirely, as they conflict with the "soft lighting" and "welcoming" brand ethos.

## Components

### Buttons
- **Primary:** Saffron background with white text. High-contrast, bold, and slightly elevated with a soft shadow.
- **Secondary:** Maroon outline (2px) with Maroon text. Transparent background to allow the Cream canvas to show through.
- **Tertiary:** Text-only in Maroon with a Saffron underline on hover.

### Cards (Glassmorphism)
Course cards use a semi-transparent white background with a `backdrop-filter: blur(12px)`. A 1px border of `rgba(255, 255, 255, 0.4)` creates the "edge" of the glass. 

### Input Fields
Inputs use a white background with a 1px Maroon-tinted border. On focus, the border thickens to 2px Saffron, and a soft Saffron outer glow (4px) is applied.

### Progress Indicators
Progress bars use a Maroon track with a Saffron "fill" to represent the student's journey.

### Imagery Accents
Use subtle Indian patterns (like Jali or Mandala motifs) as low-opacity watermarks (3-5% Maroon) behind glass layers to reinforce the cultural context without cluttering the UI.