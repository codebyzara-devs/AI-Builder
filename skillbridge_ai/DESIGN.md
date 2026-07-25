---
name: SkillBridge AI
colors:
  surface: '#faf8ff'
  surface-dim: '#d9d9e5'
  surface-bright: '#faf8ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f3fe'
  surface-container: '#ededf9'
  surface-container-high: '#e7e7f3'
  surface-container-highest: '#e1e2ed'
  on-surface: '#191b23'
  on-surface-variant: '#434655'
  inverse-surface: '#2e3039'
  inverse-on-surface: '#f0f0fb'
  outline: '#737686'
  outline-variant: '#c3c6d7'
  surface-tint: '#0053db'
  primary: '#004ac6'
  on-primary: '#ffffff'
  primary-container: '#2563eb'
  on-primary-container: '#eeefff'
  inverse-primary: '#b4c5ff'
  secondary: '#565e74'
  on-secondary: '#ffffff'
  secondary-container: '#dae2fd'
  on-secondary-container: '#5c647a'
  tertiary: '#943700'
  on-tertiary: '#ffffff'
  tertiary-container: '#bc4800'
  on-tertiary-container: '#ffede6'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dbe1ff'
  primary-fixed-dim: '#b4c5ff'
  on-primary-fixed: '#00174b'
  on-primary-fixed-variant: '#003ea8'
  secondary-fixed: '#dae2fd'
  secondary-fixed-dim: '#bec6e0'
  on-secondary-fixed: '#131b2e'
  on-secondary-fixed-variant: '#3f465c'
  tertiary-fixed: '#ffdbcd'
  tertiary-fixed-dim: '#ffb596'
  on-tertiary-fixed: '#360f00'
  on-tertiary-fixed-variant: '#7d2d00'
  background: '#faf8ff'
  on-background: '#191b23'
  surface-variant: '#e1e2ed'
typography:
  display:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-sm:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
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
    fontWeight: '500'
    lineHeight: 20px
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 4px
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px
  xl: 32px
  2xl: 48px
  3xl: 64px
  container-max: 1280px
  gutter: 24px
---

## Brand & Style

The design system is engineered to evoke high trust, professional growth, and technological intelligence. It targets ambitious professionals and enterprise HR teams who require a reliable, high-end environment for skill management and career trajectory planning.

The visual style is **Corporate / Modern** with a focus on precision and clarity. It utilizes high-quality typography and generous whitespace to reduce cognitive load. The aesthetic leans into a "refined functionalism," where every element serves a purpose. The interface uses subtle depth and layered surfaces to create a structured hierarchy, ensuring the user feels in control of their professional data.

## Colors

The palette is anchored by a high-trust **Primary Blue**, used for action-oriented elements and brand identity. The **Secondary Navy** provides a professional foundation for text and navigation, ensuring high readability and a grounded feel.

Functional colors for success and warning are utilized sparingly to indicate status without overwhelming the user experience. The background strategy uses a very light gray-blue to reduce eye strain and distinguish the "app canvas" from elevated white surface containers (cards and panels).

## Typography

This design system uses **Inter** exclusively to maintain a systematic, utilitarian, and modern feel. The typeface’s high x-height and neutral character make it ideal for data-heavy SaaS dashboards.

- **Headlines:** Use tighter letter spacing and semi-bold weights to establish a strong visual anchor.
- **Body:** Uses standard weights with comfortable line heights to ensure long-form text and skill descriptions are highly readable.
- **Labels:** Small labels use an uppercase transform with increased tracking to differentiate them from body text in metadata contexts.

## Layout & Spacing

The layout follows a **Fluid Grid** model with fixed maximum constraints for desktop viewing to prevent line lengths from becoming unreadable. 

- **Grid:** A 12-column grid is used for desktop (breakpoints at 1024px+), 8-column for tablet (768px - 1023px), and 4-column for mobile (<767px).
- **Rhythm:** An 8px linear scale (with 4px increments for tight micro-adjustments) governs all margins and padding. 
- **Application:** Use 24px (lg) for standard container padding and 16px (md) for internal component spacing.

## Elevation & Depth

This design system employs **Tonal Layers** combined with **Ambient Shadows** to create a structured, professional hierarchy.

- **Base Layer:** The light gray-blue background (`#F8FAFC`) acts as the foundation.
- **Surface Layer:** Cards and primary containers use a pure white background with a subtle `1px` border in `#E2E8F0`.
- **Shadows:** Use extremely soft, low-opacity shadows (e.g., `0px 4px 12px rgba(15, 23, 42, 0.05)`) to lift interactive cards and modals without making the UI feel heavy or cluttered.
- **Interactive Depth:** On hover, cards should slightly increase their shadow spread and lift (Y-axis) by 2px to provide tactile feedback.

## Shapes

The shape language is **Rounded**, strike a balance between friendly approachability and professional rigor.

- **Components:** Standard buttons and input fields use 8px (`0.5rem`) rounding.
- **Large Containers:** Content cards and modals use 16px (`1rem`) rounding to soften the overall interface.
- **Icons:** Use Lucide-style icons with a 2px stroke width and rounded caps/joins to align with the UI's geometry.

## Components

- **Buttons:** Primary buttons use a solid `#2563EB` fill with white text. Secondary buttons use a white fill with a `#E2E8F0` border and navy text. Use 12px top/bottom and 24px left/right padding.
- **Input Fields:** Use a 1px border (`#E2E8F0`). On focus, the border transitions to the primary color with a soft 3px outer glow (ring).
- **Cards:** White background, 1px border, 16px rounding. Include a 24px internal padding. Card headers should use `headline-sm` with a light separator line.
- **Chips / Badges:** Used for skills and tags. Use a subtle tinted background (e.g., 10% opacity of the primary color) with high-contrast text and a more aggressive rounding (pill-style).
- **Lists:** Clean rows with 16px vertical padding, separated by subtle `1px` dividers. Include chevron-right icons for navigable list items.
- **Navigation:** A persistent sidebar on desktop using the dark navy secondary color for high contrast, or a clean top-bar with active state indicators using a bottom-border in the primary blue.