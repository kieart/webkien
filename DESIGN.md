---
name: Synthetic Dimensions
colors:
  surface: '#131315'
  surface-dim: '#131315'
  surface-bright: '#39393b'
  surface-container-lowest: '#0e0e10'
  surface-container-low: '#1c1b1d'
  surface-container: '#201f21'
  surface-container-high: '#2a2a2c'
  surface-container-highest: '#353437'
  on-surface: '#e5e1e4'
  on-surface-variant: '#b9cacb'
  inverse-surface: '#e5e1e4'
  inverse-on-surface: '#313032'
  outline: '#849495'
  outline-variant: '#3b494b'
  surface-tint: '#00dbe9'
  primary: '#dbfcff'
  on-primary: '#00363a'
  primary-container: '#00f0ff'
  on-primary-container: '#006970'
  inverse-primary: '#006970'
  secondary: '#ebb2ff'
  on-secondary: '#520072'
  secondary-container: '#b600f8'
  on-secondary-container: '#fff6fc'
  tertiary: '#fff5de'
  on-tertiary: '#3b2f00'
  tertiary-container: '#fed639'
  on-tertiary-container: '#715d00'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#7df4ff'
  primary-fixed-dim: '#00dbe9'
  on-primary-fixed: '#002022'
  on-primary-fixed-variant: '#004f54'
  secondary-fixed: '#f8d8ff'
  secondary-fixed-dim: '#ebb2ff'
  on-secondary-fixed: '#320047'
  on-secondary-fixed-variant: '#74009f'
  tertiary-fixed: '#ffe179'
  tertiary-fixed-dim: '#eac324'
  on-tertiary-fixed: '#231b00'
  on-tertiary-fixed-variant: '#554500'
  background: '#131315'
  on-background: '#e5e1e4'
  surface-variant: '#353437'
typography:
  display-lg:
    fontFamily: Sora
    fontSize: 72px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Sora
    fontSize: 40px
    fontWeight: '800'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Sora
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-md-mobile:
    fontFamily: Sora
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-sm:
    fontFamily: Geist
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1'
    letterSpacing: 0.05em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  container-max: 1440px
  gutter: 24px
  margin-desktop: 80px
  margin-mobile: 20px
  section-gap: 120px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
---

## Brand & Style

The brand identity is built for a high-end 3D artist and educator, targeting digital creatives, studio recruiters, and aspiring motion designers. The aesthetic is **High-Tech Minimalism** mixed with **Glassmorphism**, evoking the precision of 3D rendering software interfaces while maintaining a premium gallery feel.

The emotional response should be one of "Technical Mastery" and "Boundless Creativity." By utilizing a dark, atmospheric base with vibrant, light-emitting accents, the UI mimics a dark-mode viewport where the art is the primary light source. Visuals are treated with cinematic respect—large margins, intentional whitespace (or "darkspace"), and smooth motion transitions.

## Colors

The palette is rooted in a "Deep Space" theme. The primary background is a near-black (`#050505`) to ensure 3D renders pop with maximum contrast. 

- **Primary (Electric Cyan):** Used for primary actions, progress bars for courses, and active states. It represents the "wireframe" or technical side of the craft.
- **Secondary (Neon Purple):** Used for accents, hover states, and rare highlights to add depth and a "synthwave" sophistication.
- **Surface Tones:** Use varying shades of dark gray (`#16161A`) to define containers without breaking the dark immersion.
- **Text:** Pure white is reserved for headings. Body text should be slightly desaturated (`#A0A0AB`) to reduce eye strain in the dark environment.

## Typography

The typography strategy balances futuristic geometry with high-performance legibility. 

- **Headings:** **Sora** provides a wide, geometric stance that feels engineered and modern. Use tight letter-spacing for large display type to create a "blocky" high-impact look.
- **Body:** **Hanken Grotesk** offers a clean, contemporary feel that stays readable even at smaller sizes during long course descriptions.
- **Technical Labels:** **Geist** is used for metadata, buttons, and UI labels. Its monospaced-adjacent proportions reinforce the "software tool" aesthetic of the 3D industry.

## Layout & Spacing

The layout follows a **Fluid Grid** with generous outer margins to simulate an art gallery environment. 

- **Desktop:** A 12-column grid with 24px gutters. Content is often offset or asymmetrical to create a dynamic, modern feel. 
- **Course/Gallery View:** Uses a "Masonry" or strict "Aspect Ratio Grid" to showcase 3D renders without cropping.
- **Vertical Rhythm:** Sections are separated by large gaps (`120px`) to allow the work to breathe. Elements within cards use a tight 8px/16px scale to maintain a crisp, technical density.
- **Mobile:** Shifts to a 4-column grid with 20px margins. Section gaps scale down to 64px.

## Elevation & Depth

This design system utilizes **Glassmorphism** to create a sense of layering within a 3D space.

- **Background Blurs:** Navigation bars and modal overlays use a 20px backdrop-blur with a 10% white tint.
- **Depth Hierarchy:** 
    - **Level 0 (Base):** Deep black background.
    - **Level 1 (Cards):** Slightly lighter gray (`#16161A`) with a subtle 1px border (`#FFFFFF10`).
    - **Level 2 (Active/Hover):** Inner glows using the primary cyan color at 5% opacity to simulate light emission from the element.
- **Shadows:** Avoid heavy black shadows; instead, use "Colored Ambient Glows" (e.g., a faint cyan outer blur) for primary call-to-action buttons.

## Shapes

The shape language is **Soft (0.25rem - 0.75rem)**. While 3D software often feels "sharp," the soft rounding adds a premium, tactile quality that makes the UI feel more approachable and modern.

- **Cards & Inputs:** Use `rounded-lg` (0.5rem) for a balanced look.
- **Buttons:** Use `rounded-lg` for standard actions. Icons within buttons should remain crisp.
- **Feature Images:** Use `rounded-xl` (0.75rem) to frame 3D renders, giving them a "screen-within-a-screen" appearance.

## Components

### Buttons
- **Primary:** Solid Cyan (`#00F0FF`) with black text. On hover, add a cyan outer glow.
- **Secondary:** Ghost style with a 1px white border at 20% opacity. Text is white.
- **Tertiary/System:** Geist font, all caps, with a small leading icon (e.g., a "+" or "→").

### Cards (Course & Portfolio)
- **Style:** Background blur with a 1px top-down gradient border (White at top, transparent at bottom).
- **Image:** Should occupy 70% of the card height. 
- **Content:** Typography should be minimal—Project Title in Sora, Category in Geist.

### Input Fields
- **Base:** Dark background (`#0A0A0C`), bottom-only border (1px white at 20% opacity).
- **Focus:** Border color shifts to Primary Cyan with a subtle 2px bottom glow.

### Chips/Badges
- **Technical Tags:** Small, `rounded-sm`, Geist font. Background is dark with Cyan or Purple text to indicate software used (e.g., "Octane", "Blender").

### Course Progress
- Use a "Neon Tube" style progress bar—a thin 2px line with a 4px blur glow of the same color trailing the progress head.