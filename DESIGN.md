---
name: Artisanal Harvest
colors:
  surface: '#fdf9f3'
  surface-dim: '#dddad4'
  surface-bright: '#fdf9f3'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f7f3ed'
  surface-container: '#f1ede7'
  surface-container-high: '#ebe8e2'
  surface-container-highest: '#e6e2dc'
  on-surface: '#1c1c18'
  on-surface-variant: '#4d444b'
  inverse-surface: '#31302d'
  inverse-on-surface: '#f4f0ea'
  outline: '#7e747c'
  outline-variant: '#cfc3cc'
  surface-tint: '#755377'
  primary: '#331736'
  on-primary: '#ffffff'
  primary-container: '#4a2c4d'
  on-primary-container: '#ba94bb'
  inverse-primary: '#e3b9e3'
  secondary: '#7d5700'
  on-secondary: '#ffffff'
  secondary-container: '#ffc55f'
  on-secondary-container: '#755100'
  tertiary: '#1b2500'
  on-tertiary: '#ffffff'
  tertiary-container: '#303b0f'
  on-tertiary-container: '#98a66f'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffd6fe'
  primary-fixed-dim: '#e3b9e3'
  on-primary-fixed: '#2c1030'
  on-primary-fixed-variant: '#5b3c5e'
  secondary-fixed: '#ffdeaa'
  secondary-fixed-dim: '#f5bd58'
  on-secondary-fixed: '#271900'
  on-secondary-fixed-variant: '#5f4100'
  tertiary-fixed: '#dbe9ac'
  tertiary-fixed-dim: '#bfcd92'
  on-tertiary-fixed: '#161f00'
  on-tertiary-fixed-variant: '#404b1e'
  background: '#fdf9f3'
  on-background: '#1c1c18'
  surface-variant: '#e6e2dc'
  fig-purple: '#4A2C4D'
  amber-accent: '#D9A441'
  paper-white: '#FAF6F0'
  ink-black: '#221E1F'
typography:
  display-lg:
    fontFamily: Literata
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Literata
    fontSize: 36px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Literata
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-sm:
    fontFamily: Literata
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
  label-md:
    fontFamily: Hanken Grotesk
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.05em
  price-tag:
    fontFamily: Literata
    fontSize: 20px
    fontWeight: '600'
    lineHeight: '1'
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  container-max: 1100px
  gutter: 24px
  margin-mobile: 16px
  stack-sm: 8px
  stack-md: 24px
  stack-lg: 64px
---

## Brand & Style

The design system is built to evoke the sensory experience of a high-end neighborhood café: the warmth of fresh bread, the richness of roasted coffee, and the quiet dignity of artisanal craft. It targets two distinct personas—the local passerby seeking a welcoming space and the professional office manager looking for reliable quality.

The chosen design style is **Modern Minimalist with Tactile accents**. It leverages heavy whitespace and premium typography to reflect a "plainspoken" and sophisticated brand voice. The interface stays out of the way of the content, using high-quality photography and structural clarity to build trust, while subtle organic textures and warm tones prevent the "corporate" feel typical of larger chains.

## Colors

The palette is rooted in natural, earthy tones that mimic the cafe's physical environment. 

- **Primary (Deep Fig Purple):** Used for branding, navigation headers, and structural elements. It provides a sophisticated, "roast-like" depth.
- **Secondary (Warm Amber):** Reserved strictly for primary calls to action, highlights, and interactive cues. It must never be used for body text to ensure maximum legibility.
- **Background (Warm Off-White):** A "paper-like" base that reduces eye strain and feels more approachable than a clinical pure white.
- **Text (Near-Black):** A high-contrast ink color for all communication, ensuring the "dry-humoured" and plainspoken copy is easily digestible.

## Typography

The typography pairing reflects the "Filter" and "Fig" aspects of the brand—precision meets organic character.

- **Headlines:** Uses *Literata*. Its transitional serif qualities provide a "literary" and "established" feel, perfect for the founding story and the craft of roasting.
- **Body & Labels:** Uses *Hanken Grotesk*. This is a clean, contemporary sans-serif that ensures high legibility for menu items and logistical information like opening hours.
- **Rhythm:** Large display type should be used sparingly for impact (Hero sections). Body copy maintains a generous line height (1.6) to support the relaxed, "stay as long as you like" vibe.

## Layout & Spacing

The layout philosophy is **Mobile-First Fixed-Fluid**. On mobile devices, content lives in a single column with tight 16px margins to maximize screen real estate for essential info like addresses. On desktop, the layout expands to a maximum of 1100px, utilizing a 12-column grid.

- **Vertical Rhythm:** Use large 64px gaps between major sections to emphasize a calm, unhurried browsing experience.
- **Menu System:** Use a 1-column list on mobile and a maximum 2-column "split" on desktop.
- **Catering Grid:** Packages should stack vertically on mobile and transition to a 3-column horizontal flex row on desktop for easy side-by-side comparison.

## Elevation & Depth

This design system avoids heavy shadows in favor of **Tonal Layering**. 

Depth is communicated through subtle shifts in background color and thin, low-contrast borders. Photography acts as the primary "window" into the space, providing visual richness. 
- **Surfaces:** Most content sits flat on the Warm Off-White background. 
- **Cards:** Use a very thin (1px) border of Deep Fig Purple at 10% opacity to define boundaries for catering packages or founder profiles.
- **Interaction:** A subtle, soft ambient shadow (low blur, low spread) may be applied to the primary "Find us" or "Order catering" buttons upon hover to provide a tactile, "pressable" feel.

## Shapes

The shape language is **Soft (0.25rem)**. While the brand is artisanal and organic, it also prides itself on the precision of roasting and "filtering." 

- **Buttons:** Use soft-rounded corners (4px) to feel friendly but structured.
- **Images:** Photography should use the same 4px radius to maintain a consistent visual container.
- **Interactive Elements:** Checkboxes for dietary filters should remain slightly rounded to avoid the harshness of sharp 90-degree angles.

## Components

### Buttons
- **Primary:** Background: Warm Amber; Text: Near-Black; Weight: 600. Used only for "Find us" and "Order catering."
- **Secondary/Plain:** Text-only links in Deep Fig Purple with a subtle underline. Used for "Menu" links and footer navigation.

### Menu Items
List-based components with the item name and price on a single line, separated by a dotted leader (tab leader) or simple whitespace. Dietary markers (V, VG, GF) should appear as small, high-contrast labels in Deep Fig Purple immediately following the item name.

### Catering Cards
Simple vertical containers with a Headline-sm for the package name, followed by the price in `price-tag` style. Feature lists within cards should use a simple bullet or a small check icon in Primary color.

### Input Fields (Catering Enquiry)
When an email is triggered, ensure the subject line is pre-filled. If a contact form is later added, fields should use a 1px border in Near-Black (20% opacity) with a solid Warm Off-White background.

### Information Table (Visit Page)
The opening hours table should be stripped of all vertical borders. Use horizontal dividers in 10% Deep Fig Purple. Today's hours should be highlighted with a subtle background tint of Warm Amber at 5% opacity.