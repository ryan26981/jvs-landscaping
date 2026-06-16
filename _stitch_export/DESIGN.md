---
name: Terraform Professional
colors:
  surface: '#f7f9fb'
  surface-dim: '#d8dadc'
  surface-bright: '#f7f9fb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f4f6'
  surface-container: '#eceef0'
  surface-container-high: '#e6e8ea'
  surface-container-highest: '#e0e3e5'
  on-surface: '#191c1e'
  on-surface-variant: '#434843'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eff1f3'
  outline: '#737973'
  outline-variant: '#c3c8c1'
  surface-tint: '#4d6453'
  primary: '#061b0e'
  on-primary: '#ffffff'
  primary-container: '#1b3022'
  on-primary-container: '#819986'
  inverse-primary: '#b4cdb8'
  secondary: '#80552c'
  on-secondary: '#ffffff'
  secondary-container: '#fec391'
  on-secondary-container: '#794e26'
  tertiary: '#0c1728'
  on-tertiary: '#ffffff'
  tertiary-container: '#212c3d'
  on-tertiary-container: '#8893a8'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d0e9d4'
  primary-fixed-dim: '#b4cdb8'
  on-primary-fixed: '#0b2013'
  on-primary-fixed-variant: '#364c3c'
  secondary-fixed: '#ffdcc1'
  secondary-fixed-dim: '#f5bb89'
  on-secondary-fixed: '#2e1600'
  on-secondary-fixed-variant: '#653e17'
  tertiary-fixed: '#d8e3fa'
  tertiary-fixed-dim: '#bcc7dd'
  on-tertiary-fixed: '#111c2c'
  on-tertiary-fixed-variant: '#3c475a'
  background: '#f7f9fb'
  on-background: '#191c1e'
  surface-variant: '#e0e3e5'
typography:
  h1:
    fontFamily: Montserrat
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  h1-mobile:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
  h2:
    fontFamily: Montserrat
    fontSize: 36px
    fontWeight: '600'
    lineHeight: '1.3'
  h3:
    fontFamily: Montserrat
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Open Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Open Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-caps:
    fontFamily: Montserrat
    fontSize: 14px
    fontWeight: '700'
    lineHeight: '1.0'
    letterSpacing: 0.05em
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
  margin-mobile: 16px
  stack-lg: 80px
  stack-md: 48px
---

## Brand & Style
The design system is engineered to project the reliability of heavy machinery and the precision of master horticulture. The brand personality is **Professional, Earthy, and Reliable**, targeting homeowners and property managers who value long-term quality over quick fixes.

The visual style follows a **Modern Corporate** aesthetic with a **Tactile** edge. It avoids the "grit" of construction in favor of the "polish" of high-end landscaping. The UI prioritizes high-trust signals: structured layouts, ample white space to breathe, and a color palette that feels rooted in the physical environment of Fairport, NY.

## Colors
The palette is derived from natural elements found in professional landscaping.
- **Primary (Deep Forest Green):** Used for headers, navigation, and primary brand elements to establish authority and a connection to nature.
- **Secondary (Warm Wood Brown):** Used for accents, iconography, and decorative borders to provide organic warmth.
- **Tertiary (Slate Gray):** Used for secondary text and structural elements like dividers to ground the design.
- **Action (Sunshine Yellow):** A high-visibility accent reserved exclusively for Call-to-Action buttons and urgent alerts, ensuring critical paths are never missed.
- **Backgrounds:** Clean white (#FFFFFF) is the primary canvas, with Neutral Slate (#F8FAFC) used for section staggering to maintain high readability.

## Typography
The typography strategy creates a clear hierarchy between "Strength" and "Information."
- **Headlines:** Montserrat is used for its geometric stability and architectural feel. Heavy weights are preferred for main titles to convey the "solid" nature of hardscaping.
- **Body:** Open Sans provides an approachable, highly legible experience for service descriptions and testimonials. Its neutral character prevents the UI from feeling overly aggressive.
- **Labels:** Uppercase Montserrat labels are used for category tags and small eyebrows to maintain a professional, organized structure.

## Layout & Spacing
This design system utilizes a **Fixed Grid** model for desktop to ensure content remains centered and professional, transitioning to a fluid model for mobile.

- **Grid:** A 12-column grid with 24px gutters.
- **Vertical Rhythm:** Sections are separated by significant vertical padding (80px on desktop) to allow high-quality imagery to feel "premium" rather than cluttered.
- **Responsive Behavior:** On tablet, margins increase to 32px. On mobile, the 12-column grid collapses to a single-column stack with 16px side margins.

## Elevation & Depth
Depth is used sparingly to signify quality and "layering" (mimicking a physical landscape). 
- **Surfaces:** Use Tonal Layers. Cards sit on the background with a soft, diffused shadow (0px 4px 20px rgba(0,0,0,0.05)) to suggest they are "resting" on the surface.
- **Interaction:** On hover, cards should lift slightly (0px 10px 30px rgba(0,0,0,0.1)) to provide tactile feedback.
- **Overlays:** Use subtle background blurs (8px) for mobile navigation menus to keep the user oriented within the lush photography of the site.

## Shapes
The shape language balances "engineered" and "organic."
- **Corner Radius:** A standard 0.5rem (8px) radius is applied to all primary components (buttons, input fields, cards). This avoids the harshness of 90-degree angles while maintaining a sense of structural integrity.
- **Imagery:** Photos should use the same 8px radius to feel integrated into the UI.
- **Icons:** Use "rounded" variant icons rather than "sharp" to match the friendly yet professional tone.

## Components
- **Buttons:** Primary CTA buttons use the Sunshine Yellow background with Deep Forest Green text for maximum contrast. Secondary buttons use an outlined style with Forest Green.
- **Cards:** Service cards feature a top-aligned high-resolution image, a 1px Slate Gray border, and a 24px internal padding for text content.
- **Input Fields:** Use a subtle Slate Gray border (1px) that thickens and changes to Forest Green on focus. Labels should always be visible above the field.
- **Chips/Tags:** Used for service categories (e.g., "Hardscaping," "Lawn Care"). These use light tinted backgrounds of Forest Green with dark green text.
- **Lists:** Service checklists should use a custom "Check" icon in Warm Wood Brown to reinforce the earthy theme.
- **Imagery Component:** A "Before/After" slider component is highly recommended to showcase the transformative nature of the services.