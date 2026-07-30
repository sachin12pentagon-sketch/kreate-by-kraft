---
name: Organic Editorial Luxury
colors:
  surface: '#fcf9f8'
  surface-dim: '#dcd9d9'
  surface-bright: '#fcf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f0eded'
  surface-container-high: '#eae7e7'
  surface-container-highest: '#e4e2e1'
  on-surface: '#1b1c1c'
  on-surface-variant: '#434840'
  inverse-surface: '#303030'
  inverse-on-surface: '#f3f0f0'
  outline: '#747870'
  outline-variant: '#c4c8be'
  surface-tint: '#4e6448'
  primary: '#3e5338'
  on-primary: '#ffffff'
  primary-container: '#556b4e'
  on-primary-container: '#d1ebc6'
  inverse-primary: '#b5ceab'
  secondary: '#755847'
  on-secondary: '#ffffff'
  secondary-container: '#ffd8c2'
  on-secondary-container: '#7a5c4b'
  tertiary: '#793c21'
  on-tertiary: '#ffffff'
  tertiary-container: '#965336'
  on-tertiary-container: '#ffdbce'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d1eac6'
  primary-fixed-dim: '#b5ceab'
  on-primary-fixed: '#0d2009'
  on-primary-fixed-variant: '#374c32'
  secondary-fixed: '#ffdbc8'
  secondary-fixed-dim: '#e5bfa9'
  on-secondary-fixed: '#2b1709'
  on-secondary-fixed-variant: '#5b4131'
  tertiary-fixed: '#ffdbcd'
  tertiary-fixed-dim: '#ffb598'
  on-tertiary-fixed: '#360f00'
  on-tertiary-fixed-variant: '#71361b'
  background: '#fcf9f8'
  on-background: '#1b1c1c'
  surface-variant: '#e4e2e1'
typography:
  display-lg:
    fontFamily: EB Garamond
    fontSize: 64px
    fontWeight: '500'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: EB Garamond
    fontSize: 40px
    fontWeight: '500'
    lineHeight: '1.2'
  headline-lg:
    fontFamily: EB Garamond
    fontSize: 48px
    fontWeight: '500'
    lineHeight: '1.2'
  headline-md:
    fontFamily: EB Garamond
    fontSize: 32px
    fontWeight: '500'
    lineHeight: '1.3'
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
    lineHeight: '1.2'
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
  section-gap-desktop: 120px
  section-gap-mobile: 64px
  container-max: 1280px
  gutter: 24px
---

## Brand & Style

This design system embodies a **Modern Editorial** aesthetic, specifically tailored for luxury hospitality. It draws heavy inspiration from Kinfolk-style minimalism, prioritizing "breathing room," tactile warmth, and an artisanal sensibility. The emotional response should be one of sophisticated calm and welcoming exclusivity.

The visual narrative is driven by:
- **Minimalist Luxury:** Stripping away the unnecessary to focus on high-quality imagery and refined typography.
- **Organic Warmth:** Moving away from "tech-cold" minimalism by using a palette of linen, earth, and foliage.
- **Editorial Layouts:** Asymmetrical compositions and diverse image aspect ratios that mimic a premium coffee-table book.
- **Tactile Softness:** Subdued shadows and gentle corner radii that make digital interactions feel physical and grounded.

## Colors

The palette is rooted in an earthy, organic spectrum that reflects natural materials like clay, walnut wood, and forest flora.

- **Primary (Dark Olive):** Used for growth, vitality, and primary CTAs. It represents the botanical elements of the hospitality experience.
- **Secondary (Walnut):** Reserved for grounding elements, heritage text, and accents that require a sense of permanence.
- **Tertiary (Terracotta):** An accent color used sparingly to draw attention to warm highlights or seasonal offerings.
- **Neutral (Charcoal):** Provides high-contrast legibility for body text and structural icons.
- **Background Tiers:** The system uses `#F8F5F0` as the primary canvas, with `#F3EEE7` serving as a subtle "sectioning" color to create rhythm without the use of harsh lines.

## Typography

The typography strategy balances the classical authority of **EB Garamond** (as a high-quality alternative to Cormorant) with the functional clarity of **Inter**.

- **Serif (Headlines):** Used for all emotive storytelling and section headers. High-contrast and elegant.
- **Sans-Serif (Body & UI):** Inter is used for maximum readability in descriptions, menus, and functional labels.
- **Hierarchy:** Large display sizes should use tighter letter spacing to maintain an "editorial" feel, while small labels should be tracked out for a premium, intentional look.

## Layout & Spacing

The layout follows a **Fluid Grid** model with generous margins to enforce the luxury narrative. 

- **Desktop:** A 12-column grid with a max-width of 1280px. Section vertical spacing is intentionally high (120px+) to ensure users focus on one story at a time.
- **Mobile:** A 4-column grid with 20px margins. 
- **Rhythm:** Use an 8px base unit for internal component spacing.
- **Composition:** Encourage "breaking the grid" with images that overlap or vary in width (e.g., a 7-column image paired with a 4-column text block) to maintain the editorial feel.

## Elevation & Depth

Hierarchy is achieved through **Tonal Layers** and **Ambient Shadows** rather than heavy borders.

- **Soft Shadows:** Use very low opacity (5-8%) with a large blur radius (30px+) and a slight Y-offset to mimic natural light hitting a matte surface.
- **Depth Tiers:**
  - **Level 0 (Base):** `#F8F5F0`
  - **Level 1 (Section/Card):** `#F3EEE7` or pure White with a soft shadow.
  - **Level 2 (Interactive):** Lifted state with increased shadow spread.
- **Glassmorphism:** Use sparingly for navigation overlays or image captions to maintain a sense of lightness and transparency.

## Shapes

The design system utilizes **Rounded** corners to soften the formal nature of the serif typography.

- **Primary Radius:** 0.5rem (8px) for standard cards and buttons.
- **Large Radius:** 1.5rem (24px) for featured imagery or distinct section containers.
- **Pill Shapes:** Used exclusively for tags, chips, and specific secondary buttons to provide visual variety.

## Components

### Buttons
- **Primary:** Solid Dark Olive (#556B4E) with White text. Rounded corners (8px). High-density padding (16px 32px).
- **Secondary:** Transparent with a 1px Walnut (#6A4E3D) border. 
- **Text Link:** Walnut text with a subtle underline that expands on hover.

### Cards
- Cards should feature a 1px border in a shade slightly darker than the background (#E8E2D9) or a very soft ambient shadow.
- Content inside cards must have generous padding (minimum 24px).

### Input Fields
- Subtle background (#F3EEE7) with no border until focused.
- Focused state uses a 1.5px Dark Olive bottom border.

### Chips & Tags
- Used for categories (e.g., "Fine Dining", "Specialty Coffee"). 
- Pill-shaped with a light background and Walnut text at the `label-sm` spec.

### Lists
- Menu items should use a "dotted leader" style to connect item names to prices, maintaining the classic bistro/editorial aesthetic.