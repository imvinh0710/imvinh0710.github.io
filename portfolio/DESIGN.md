---
name: Obsidian Cipher
colors:
  surface: '#131317'
  surface-dim: '#131317'
  surface-bright: '#39393d'
  surface-container-lowest: '#0e0e12'
  surface-container-low: '#1b1b1f'
  surface-container: '#1f1f23'
  surface-container-high: '#2a292e'
  surface-container-highest: '#353439'
  on-surface: '#e4e1e7'
  on-surface-variant: '#d4c0d7'
  inverse-surface: '#e4e1e7'
  inverse-on-surface: '#303034'
  outline: '#9d8ba0'
  outline-variant: '#514255'
  surface-tint: '#ecb2ff'
  primary: '#ecb2ff'
  on-primary: '#520071'
  primary-container: '#bd00ff'
  on-primary-container: '#ffffff'
  inverse-primary: '#9900cf'
  secondary: '#d3fbff'
  on-secondary: '#00363a'
  secondary-container: '#00eefc'
  on-secondary-container: '#00686f'
  tertiary: '#c6c5d4'
  on-tertiary: '#2f303b'
  tertiary-container: '#757583'
  on-tertiary-container: '#ffffff'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#f8d8ff'
  primary-fixed-dim: '#ecb2ff'
  on-primary-fixed: '#320047'
  on-primary-fixed-variant: '#74009f'
  secondary-fixed: '#7df4ff'
  secondary-fixed-dim: '#00dbe9'
  on-secondary-fixed: '#002022'
  on-secondary-fixed-variant: '#004f54'
  tertiary-fixed: '#e2e1f1'
  tertiary-fixed-dim: '#c6c5d4'
  on-tertiary-fixed: '#1a1b26'
  on-tertiary-fixed-variant: '#454652'
  background: '#131317'
  on-background: '#e4e1e7'
  surface-variant: '#353439'
typography:
  display-lg:
    fontFamily: Geist
    fontSize: 64px
    fontWeight: '800'
    lineHeight: 72px
    letterSpacing: -0.04em
  headline-lg:
    fontFamily: Geist
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Geist
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  code-sm:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
  label-caps:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.1em
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
  margin-mobile: 16px
  margin-desktop: 64px
  section-gap: 120px
---

## Brand & Style

The design system is engineered for a Computer Science and AI student’s digital portfolio. It communicates a narrative of precision, intelligence, and the "dark mode" aesthetic favored by developers. The brand personality is enigmatic yet highly functional—think of an encrypted terminal or a high-end IDE.

The visual style is a blend of **Minimalism** and **Glassmorphism**, set against a deep, non-distracting background. It uses transparency and blurring to simulate depth, mirroring the layered complexity of neural networks and software architecture. The aesthetic is "Cyber-Sophisticated," avoiding the clichéd neon-overload of 80s retrowave in favor of a mature, tech-oriented look.

- **Primary Audience:** Recruiters in Big Tech, AI researchers, and open-source collaborators.
- **Emotional Response:** Trust in technical competence, curiosity about the "unseen" logic, and a sense of premium quality.

## Colors

The palette is rooted in an ultra-dark environment to minimize eye strain and maximize the impact of data visualizations.

- **Deep Charcoal & Midnight:** The foundation. Use `#050505` for the absolute background and `#121217` for cards and floating surfaces.
- **Neon Accents:** 
    - **Electric Purple (#BD00FF):** Used for primary actions, branding elements, and AI-related features. It represents the "mysterious" and creative side of logic.
    - **Cyber Teal (#00F0FF):** Used for secondary highlights, success states, and code-related tags. It represents clarity and technical precision.
- **Grayscale:** Use high-purity whites (`#FFFFFF`) for headers and muted grays (`#9494B8`) for secondary body text to maintain hierarchy without sacrificing the dark aesthetic.

## Typography

The typography strategy focuses on legibility and technical rigor. 

1.  **Geist (Headlines):** A modern, geometric sans-serif that feels engineered. Use tight tracking on larger display sizes to create a sleek, "cipher" look.
2.  **Inter (Body):** The workhorse for readability. Its neutral tone ensures that project descriptions and research summaries are easy to digest.
3.  **JetBrains Mono (Data/Labels):** Employed for small labels, tags, and snippets of code. This font immediately signals a background in computer science.

**Scaling:** On mobile devices, display type scales down significantly to prevent awkward word breaks, while body text remains consistent at 16px for accessibility.

## Layout & Spacing

This design system utilizes a **Fixed Grid** on desktop and a **Fluid Grid** on mobile.

- **Grid Model:** A 12-column system for desktop (1280px max-width) with 24px gutters. Elements should align to the grid to maintain a "structured code" feel.
- **Rhythm:** An 8px base unit governs all spacing.
- **Sectioning:** Large vertical gaps (120px+) between portfolio sections (e.g., between "Projects" and "Research") create a sense of focus and room to breathe, preventing the dark theme from feeling claustrophobic.
- **Reflow:** On mobile, the grid collapses to 4 columns. Margins shrink to 16px to maximize screen real estate for content.

## Elevation & Depth

Hierarchy is established through **Tonal Layering** and **Glassmorphism**, rather than heavy shadows.

- **Base Layer:** `#050505` (The Void).
- **Surface Layer:** `#121217`. Use this for cards and containers. Apply a subtle 1px border using a low-opacity white (`rgba(255, 255, 255, 0.1)`) to define edges.
- **Interactive Depth:** When a card is hovered, it should utilize a **Backdrop Blur** (20px) and a subtle inner glow of the primary color (`#BD00FF`) at 10% opacity.
- **Floating Elements:** Modals and tooltips should appear as "frosted glass" (semi-transparent background with high blur), making them feel like they are floating above the logic layer.

## Shapes

The shape language is **Soft (0.25rem)**. 

While the aesthetic is tech-oriented, purely sharp edges (0px) can feel too aggressive. A small radius (4px to 8px) provides a modern, "hardware-milled" feel similar to premium laptops or mobile devices. 

- **Standard Buttons/Inputs:** 4px radius.
- **Project Cards:** 8px (rounded-lg) to distinguish major content blocks.
- **Chips/Status Tags:** 100px (Pill-shaped) to provide a soft contrast to the otherwise rigid grid.

## Components

- **Buttons:** 
    - *Primary:* Solid Electric Purple with white text. No shadow; use a subtle outer glow on hover.
    - *Ghost:* Transparent background with a Cyber Teal border and text. 
- **Project Cards:** Deep charcoal background with the 1px subtle border. On hover, the border transitions to a gradient of Purple to Teal.
- **Input Fields:** Darker than the surface layer, with the label in `label-caps` typography. The focus state uses a 1px Cyber Teal glow.
- **Code Blocks:** Use a distinct background (`#000000`) with syntax highlighting that matches the primary/secondary neon palette. Use `JetBrains Mono`.
- **Progress Indicators (AI/Skills):** Thin, sleek bars using the Cyber Teal color, with a "pulse" animation to signify active processing.
- **Chips:** Small, pill-shaped tags for tech stacks (e.g., "Python", "PyTorch"). Use secondary color text on a low-opacity teal background.