---
name: Mochi & Co. Aesthetic
colors:
  surface: '#fff8f6'
  surface-dim: '#f0d5c8'
  surface-bright: '#fff8f6'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fff1eb'
  surface-container: '#ffeae0'
  surface-container-high: '#fee3d6'
  surface-container-highest: '#f8ddd1'
  on-surface: '#261811'
  on-surface-variant: '#52443c'
  inverse-surface: '#3d2d25'
  inverse-on-surface: '#ffede6'
  outline: '#84746b'
  outline-variant: '#d7c3b8'
  surface-tint: '#87512d'
  primary: '#87512d'
  on-primary: '#ffffff'
  primary-container: '#ffb88c'
  on-primary-container: '#7a4624'
  inverse-primary: '#feb78b'
  secondary: '#3e6654'
  on-secondary: '#ffffff'
  secondary-container: '#beead3'
  on-secondary-container: '#436b58'
  tertiary: '#ae3123'
  on-tertiary: '#ffffff'
  tertiary-container: '#ffb6aa'
  on-tertiary-container: '#9e2519'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdbc8'
  primary-fixed-dim: '#feb78b'
  on-primary-fixed: '#311300'
  on-primary-fixed-variant: '#6b3a18'
  secondary-fixed: '#c0ecd5'
  secondary-fixed-dim: '#a5d0ba'
  on-secondary-fixed: '#002115'
  on-secondary-fixed-variant: '#264e3d'
  tertiary-fixed: '#ffdad4'
  tertiary-fixed-dim: '#ffb4a8'
  on-tertiary-fixed: '#410000'
  on-tertiary-fixed-variant: '#8c170e'
  background: '#fff8f6'
  on-background: '#261811'
  surface-variant: '#f8ddd1'
typography:
  display-price:
    fontFamily: Quicksand
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Quicksand
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Quicksand
    fontSize: 24px
    fontWeight: '700'
    lineHeight: '1.2'
  body-lg:
    fontFamily: Quicksand
    fontSize: 18px
    fontWeight: '600'
    lineHeight: '1.5'
  body-md:
    fontFamily: Quicksand
    fontSize: 16px
    fontWeight: '500'
    lineHeight: '1.5'
  label-bold:
    fontFamily: Quicksand
    fontSize: 14px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-lg-mobile:
    fontFamily: Quicksand
    fontSize: 28px
    fontWeight: '700'
    lineHeight: '1.2'
rounded:
  sm: 0.5rem
  DEFAULT: 1rem
  md: 1.5rem
  lg: 2rem
  xl: 3rem
  full: 9999px
spacing:
  base: 8px
  xs: 4px
  sm: 12px
  md: 24px
  lg: 32px
  xl: 48px
  gutter: 24px
  margin-edge: 32px
---

## Brand & Style
The design system for this dessert café POS focuses on a "Soft 3D" aesthetic—a blend of Neomorphism and tactile physicalism. It is designed to feel as soft and inviting as a mochi rice cake. The target audience is busy café staff who need high-contrast legibility, and customers who engage with the customer-facing display. 

The style utilizes deep, warm shadows and subtle inner glows to create a "squishy" tactile feel. Visuals are chunky, playful, and intentionally oversized to facilitate fast, error-free touch interactions in a fast-paced environment. The emotional response is one of warmth, friendliness, and sweetness.

## Colors
This design system uses a warm, high-contrast palette to ensure accessibility under bright café lighting.

- **Primary (Pastel Peach):** Used for main action buttons and active states.
- **Secondary (Mint):** Used for "Success" states, add-to-cart confirmations, and modifiers.
- **Accent (Deep Coral):** Reserved for destructive actions, alerts, or highlighting the "Total" price.
- **Neutral (Dark Brown):** Replaces black for all text and iconography to maintain a soft, organic feel.
- **Background (Warm Cream):** The base canvas for all screens, providing a softer contrast than pure white.

## Typography
The typography is centered on **Quicksand**, a rounded sans-serif that echoes the circular geometry of the brand. 

- **Weight Strategy:** Use 'Bold' (700) for all prices, totals, and product titles to ensure they pop. 
- **Readability:** Maintain generous line height for body text to prevent the rounded terminals from feeling cluttered.
- **Scale:** On mobile-sized customer displays, headlines scale down slightly, but price displays remain "Display" sized for maximum clarity.

## Layout & Spacing
The layout follows a **fluid grid** model with significant breathing room to emphasize the "Soft 3D" shapes.

- **Grid:** A 12-column grid for desktop/tablet POS terminals, collapsing to a single column for handheld mobile terminals.
- **Touch Targets:** All interactive elements maintain a minimum hit area of 48px, with preferred sizing of 64px for product cards.
- **Padding:** Use `md` (24px) for internal card padding to ensure text doesn't feel cramped against the highly rounded corners.

## Elevation & Depth
Elevation is achieved through a "Squishy-Morphic" technique. Instead of traditional flat shadows, use:

- **Soft 3D Extrusion:** Buttons and cards should have a 4px-8px bottom-heavy shadow (Color: `#3A2A22` at 10% opacity) and a subtle 2px top-inner highlight to simulate volume.
- **Active States:** When pressed, elements should "sink" by removing the outer shadow and applying a small inner shadow, simulating a physical press.
- **The Receipt:** The cart area uses a flat, high-contrast white background with a "torn paper" SVG mask at the top and bottom to contrast against the 3D product cards.

## Shapes
The shape language is "Hyper-Rounded." 

- **Standard Radius:** 24px minimum for all primary UI elements.
- **Product Cards:** Use a consistent `rounded-xl` (48px) to create a friendly, toy-like appearance.
- **Category Chips:** Use "Blob" shapes—asymmetrical rounded polygons—to differentiate categories from functional buttons.
- **Search Bars:** Always fully pill-shaped.

## Components

- **Product Cards:** Large, chunky containers with a centered image. The price is anchored at the bottom-right in a Deep Coral circle.
- **Category Chips:** Soft, organic "blob" shapes. The active category is filled with Pastel Peach, while inactive ones use a thin Dark Brown stroke.
- **Buttons:** All buttons are pill-shaped or extremely rounded. Primary buttons feature the 3D "squishy" shadow effect.
- **Input Fields:** Thick 2px Dark Brown borders with 24px corner radius. Focus state turns the border to Primary Pastel Peach.
- **The 'Receipt' Cart:** A vertical panel on the right with a white background. The top edge features a "zigzag" torn-paper effect. Items inside are listed with extra-bold prices.
- **Checkboxes/Radios:** Oversized circles. When checked, they fill with Mint and display a chunky Dark Brown checkmark.
- **Quantity Pickers:** A pill-shaped component with large "+" and "-" circles on either side of the number for easy thumb interaction.