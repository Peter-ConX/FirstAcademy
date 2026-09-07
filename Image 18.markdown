---
name: Firsts Academy Design System
colors:
  surface: '#f9f9ff'
  surface-dim: '#c8dbff'
  surface-bright: '#f9f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f0f3ff'
  surface-container: '#e7eeff'
  surface-container-high: '#dee8ff'
  surface-container-highest: '#d5e3ff'
  on-surface: '#001b3c'
  on-surface-variant: '#5b403f'
  inverse-surface: '#183153'
  inverse-on-surface: '#ecf1ff'
  outline: '#8f6f6e'
  outline-variant: '#e4bebc'
  surface-tint: '#bb152c'
  primary: '#b7102a'
  on-primary: '#ffffff'
  primary-container: '#db313f'
  on-primary-container: '#fffbff'
  inverse-primary: '#ffb3b1'
  secondary: '#426900'
  on-secondary: '#ffffff'
  secondary-container: '#b3f35e'
  on-secondary-container: '#456e00'
  tertiary: '#7a5500'
  on-tertiary: '#ffffff'
  tertiary-container: '#996c00'
  on-tertiary-container: '#fffbff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad8'
  primary-fixed-dim: '#ffb3b1'
  on-primary-fixed: '#410007'
  on-primary-fixed-variant: '#92001c'
  secondary-fixed: '#b5f560'
  secondary-fixed-dim: '#9bd847'
  on-secondary-fixed: '#112000'
  on-secondary-fixed-variant: '#304f00'
  tertiary-fixed: '#ffdea9'
  tertiary-fixed-dim: '#ffba27'
  on-tertiary-fixed: '#271900'
  on-tertiary-fixed-variant: '#5e4100'
  background: '#f9f9ff'
  on-background: '#001b3c'
  surface-variant: '#d5e3ff'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 48px
    fontWeight: '800'
    lineHeight: 56px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '800'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
  body-lg:
    fontFamily: Be Vietnam Pro
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Be Vietnam Pro
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-bold:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '700'
    lineHeight: 20px
  button-text:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '700'
    lineHeight: 24px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
  stack-sm: 12px
  stack-md: 24px
  stack-lg: 48px
---

## Brand & Style
The design system is built to inspire confidence and curiosity in young learners (under 17s) while maintaining a high level of professional trust for parents. The aesthetic is **Modern Playful**, blending energetic colors with a structured, clean layout. 

The visual narrative centers on "Achievement and Growth," utilizing bold geometry and a vibrant palette derived from the brand's identity. We lean into a **Modern / Tactile** hybrid style: high-contrast elements, generous whitespace, and "squishy" interactive components that feel physical and rewarding to click. The mood is optimistic, welcoming, and high-energy.

## Colors
The palette is rooted in the core logo colors but optimized for digital accessibility. 
- **Primary (Academy Red):** Used for primary actions, critical alerts, and brand-heavy sections.
- **Secondary (Growth Green):** Used for success states, progress indicators, and "Go" actions.
- **Tertiary (Bright Yellow):** Used for accents, badges, and highlighting achievements/stars.
- **Surface & Neutrals:** We use a bright white base for maximum clarity. The neutral color is a deep navy rather than pure black to keep the interface feeling "premium" and academic rather than industrial.

Avoid over-saturation by balancing vibrant primary blocks with 60% white space.

## Typography
We utilize **Plus Jakarta Sans** for headlines to provide a soft, geometric, and friendly character that feels modern. For long-form reading and body text, **Be Vietnam Pro** is selected for its exceptional legibility and contemporary warmth.

Key Principles:
- **Exaggerated Scale:** High contrast between display titles and body text to guide young readers.
- **Bold Weights:** Use 700 and 800 weights frequently for headers to maintain the "Academy" authority.
- **Tight Letter Spacing:** Applied to large displays to create a "sticker" or "badge" effect common in playful branding.

## Layout & Spacing
The design system uses a **Fluid Grid** model with a base-8 rhythm. 

- **Desktop:** 12-column grid with 64px side margins. Max-width container of 1280px.
- **Tablet:** 8-column grid with 32px side margins.
- **Mobile:** 4-column grid with 16px side margins.

**The "Breathable" Rule:** To keep parents from feeling overwhelmed and children from feeling bored, we use "Stack-LG" (48px) for vertical separation between distinct content sections. Vertical rhythm should be generous to allow the vibrant colors and rounded shapes to "pop."

## Elevation & Depth
Depth is created through **Tonal Layers** and **Friendly Shadows**. We avoid harsh, black shadows in favor of tinted, diffused shadows.

- **Level 1 (Cards/Buttons):** A soft shadow tinted with the neutral navy color (`rgba(29, 53, 87, 0.08)`) with a 4px Y-offset and 12px blur.
- **Level 2 (Hover/Active):** The Y-offset increases to 8px and blur to 20px, creating a "lifting" effect.
- **The "Inner" Press:** Interactive elements like buttons use a slight inner shadow on click to simulate a physical button being pressed.
- **Navigation:** The sticky navigation bar uses a subtle 10% opacity border on its bottom edge rather than a shadow, keeping the top of the page clean.

## Shapes
We adopt the **Rounded** (Level 2) shape language. 
- **Standard UI (Inputs, Small Buttons):** 0.5rem (8px).
- **Cards & Containers:** 1rem (16px).
- **Hero Elements & Featured Chips:** 1.5rem (24px) or Pill-shaped.

Circular elements (icons inside circles, profile avatars) are encouraged to reinforce the "Shield/Medal" motif found in the Academy logo.

## Components

### Buttons
- **Primary:** Solid Red background, White text. Bold weight. 8px corner radius. Features a 2px bottom "border-shadow" of a darker red to give it a 3D tactile feel.
- **Secondary:** Outline style using Growth Green or Bright Yellow for "Reward" actions.

### Cards
- White background with a 1px soft gray border. 
- 16px corner radius.
- Always include a "hover state" where the card lifts (Shadow Level 2) and the border changes to the Primary Red.

### Sticky Navigation Bar
- **Surface:** Pure White or 95% translucent blur.
- **Height:** 80px.
- **Elements:** Logo on the left, pill-shaped navigation links in the center, and a "Join Now" Primary Button on the far right. 
- **Behavior:** On scroll, the bar adds a fine 1px line at the bottom in `#E1E4E8`.

### Input Fields
- Large tap targets (minimum 48px height).
- Background set to a very light neutral gray (`#F8F9FA`).
- On focus, the border transitions to Primary Red with a soft red outer glow (halo).

### Progress Chips
- Pill-shaped tags used for "Lesson Completed" or "New Task."
- Use Secondary Green for completion and Tertiary Yellow for "In Progress."