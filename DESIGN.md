---
name: Aeronautical Excellence
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#393939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1c1b1b'
  surface-container: '#201f1f'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353534'
  on-surface: '#e5e2e1'
  on-surface-variant: '#c6c6cd'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#909097'
  outline-variant: '#45464c'
  surface-tint: '#c0c6db'
  primary: '#c0c6db'
  on-primary: '#293041'
  primary-container: '#0b1221'
  on-primary-container: '#777d90'
  inverse-primary: '#575e70'
  secondary: '#e9c176'
  on-secondary: '#412d00'
  secondary-container: '#604403'
  on-secondary-container: '#dab36a'
  tertiary: '#c4c7ca'
  on-tertiary: '#2d3134'
  tertiary-container: '#101316'
  on-tertiary-container: '#7b7e81'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#dce2f8'
  primary-fixed-dim: '#c0c6db'
  on-primary-fixed: '#151b2b'
  on-primary-fixed-variant: '#404758'
  secondary-fixed: '#ffdea5'
  secondary-fixed-dim: '#e9c176'
  on-secondary-fixed: '#261900'
  on-secondary-fixed-variant: '#5d4201'
  tertiary-fixed: '#e0e2e6'
  tertiary-fixed-dim: '#c4c7ca'
  on-tertiary-fixed: '#191c1f'
  on-tertiary-fixed-variant: '#44474a'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353534'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 64px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 40px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-md:
    fontFamily: Playfair Display
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
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.08em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 20px
  margin-desktop: 64px
  section-gap: 120px
---

## Brand & Style
The design system is engineered to evoke the atmosphere of a private terminal lounge: quiet, exclusive, and meticulously curated. It targets high-net-worth individuals and corporate flight departments who value discretion, speed, and bespoke service. 

The aesthetic leans into **Minimalism** blended with **Corporate Modern** refinements. By utilizing a "Dark Mode by Default" philosophy, the UI mimics high-end physical environments—cockpit instrumentation, luxury automotive interiors, and night-time hangars. Visual cues are understated; luxury is signaled through generous whitespace (negative space), precision alignment, and a restrained use of metallic accents rather than overt ornamentation.

## Colors
The palette is anchored in deep, atmospheric tones to provide a sense of stability and authority.
- **Primary (Midnight Navy):** Used for primary backgrounds and deep structural elements.
- **Secondary (Warm Gold):** Reserved for high-value actions, signature borders, and interactive highlights. Use sparingly to maintain its premium impact.
- **Tertiary (Brushed Platinum):** Used for secondary text, icons, and subtle dividers to provide a metallic, technical contrast.
- **Neutral (Matte Black):** The base canvas for the entire interface, providing the ultimate "ink" depth for content to emerge from.

## Typography
The typography system relies on a high-contrast pairing between a traditional serif and a functional sans-serif. 
- **Playfair Display** provides the "Editorial" voice. It is used for headlines and quotes to instill a sense of heritage and bespoke service.
- **Inter** handles the "Technical" voice. It is used for all UI labels, aircraft specifications, and body copy to ensure maximum legibility and a modern, efficient feel.
- **Letter Spacing:** Increase tracking for all uppercase labels (e.g., flight status, price categories) to 8% to enhance the "luxury watch" aesthetic.

## Layout & Spacing
The layout follows a **Fixed Grid** model on desktop to maintain a cinematic, controlled composition. 
- **Desktop:** 12-column grid with a 1280px max-width container. Margins are intentionally wide (64px) to create a "letterboxed" luxury feel.
- **Mobile:** 4-column fluid grid.
- **Rhythm:** Use an 8px base unit. Section vertical spacing is intentionally aggressive (120px+) to ensure the content never feels crowded, reflecting the spaciousness of a private cabin.

## Elevation & Depth
This design system avoids heavy drop shadows in favor of **Tonal Layers** and **Low-contrast Outlines**.
- **Surfaces:** Use `#1A1A1A` (Charcoal) for cards or containers sitting atop the `#121212` base.
- **Borders:** Define depth using 1px solid strokes in `#E5E7EB` at 10% opacity. For "active" states, use the Warm Gold at 40% opacity.
- **Subtle Glow:** Instead of a traditional shadow, high-priority elements (like the "Book Now" CTA) may use a very soft, 20px blur of the primary color to create a subtle ambient lift.

## Shapes
The shape language is "Soft" yet disciplined. While fully rounded "pills" feel too casual for aviation, sharp 0px corners feel too aggressive. A consistent 4px (0.25rem) radius is applied to buttons and inputs, while larger components like aircraft cards use 8px (0.5rem) to suggest precision engineering.

## Components
- **Buttons:** Primary buttons are solid Warm Gold with Matte Black text. Secondary buttons are "Ghost" style—transparent with a Brushed Platinum border.
- **Aircraft Cards:** Must feature high-aspect-ratio photography. Technical specs (range, pax, speed) should be displayed in Inter (label-sm) with 50% opacity Tertiary color.
- **Skeleton Screens:** Use a shimmering gradient from `#1A1A1A` to `#242424` to represent loading states without breaking the dark aesthetic.
- **Contact Form:** Use "Underline" style inputs instead of boxed fields to maintain an elegant, minimal footprint. Labels float above the line in Gold when active.
- **Filter Chips:** Small, rectangular chips with 2px radius. Active state is indicated by a Platinum border and a 2px Gold dot indicator.