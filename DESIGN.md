---
name: Sodbridge Academy
colors:
  surface: '#fbf8ff'
  surface-dim: '#d2d8ff'
  surface-bright: '#fbf8ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f2ff'
  surface-container: '#ececff'
  surface-container-high: '#e4e7ff'
  surface-container-highest: '#dde1ff'
  on-surface: '#10193d'
  on-surface-variant: '#4c4354'
  inverse-surface: '#262e53'
  inverse-on-surface: '#f0efff'
  outline: '#7e7386'
  outline-variant: '#cfc2d7'
  surface-tint: '#8225dc'
  primary: '#7404ce'
  on-primary: '#ffffff'
  primary-container: '#8e36e8'
  on-primary-container: '#f4e5ff'
  inverse-primary: '#dbb8ff'
  secondary: '#006e22'
  on-secondary: '#ffffff'
  secondary-container: '#68fc7a'
  on-secondary-container: '#007324'
  tertiary: '#4a5068'
  on-tertiary: '#ffffff'
  tertiary-container: '#636881'
  on-tertiary-container: '#e6e9ff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#efdbff'
  primary-fixed-dim: '#dbb8ff'
  on-primary-fixed: '#2b0052'
  on-primary-fixed-variant: '#6600b7'
  secondary-fixed: '#6eff7e'
  secondary-fixed-dim: '#4ce264'
  on-secondary-fixed: '#002105'
  on-secondary-fixed-variant: '#005318'
  tertiary-fixed: '#dce1ff'
  tertiary-fixed-dim: '#c0c5e2'
  on-tertiary-fixed: '#151a30'
  on-tertiary-fixed-variant: '#40465d'
  background: '#fbf8ff'
  on-background: '#10193d'
  surface-variant: '#dde1ff'
  surface-deep: '#04091E'
  electric-violet: '#8E36E8'
  growth-green: '#16BE45'
  text-muted: '#7B83AD'
  bg-offwhite: '#F8F9FC'
typography:
  display-lg:
    fontFamily: Sora
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Sora
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Sora
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Sora
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
  headline-md:
    fontFamily: Sora
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-lg:
    fontFamily: Hanken Grotesk
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Hanken Grotesk
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
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
  margin-mobile: 16px
  margin-desktop: 40px
---

## Brand & Style

The design system is built for a premier Nigerian tech education platform, balancing global technical excellence with local cultural vibrancy. The brand personality is **aspirational, energetic, and authoritative**. It aims to evoke a sense of "Limitless Growth" and "Modern Mastery" in students and professionals.

The design style is a blend of **Corporate Modern** and **High-Contrast Bold**. It utilizes a clean, professional structure to establish trust with industry partners, while employing high-impact typography and vibrant "electric" color accents to resonate with a youthful, tech-savvy audience. The interface uses generous whitespace and crisp structural lines to manage complex information, ensuring the learning experience feels organized and high-end.

## Colors

The palette is anchored by **Electric Violet**, a color representing innovation and modern technology. This is paired with **Growth Green**, which serves as a vibrant success indicator and primary action accent, reflecting the professional advancement of the students.

**Surface Deep** (#04091E) is used for high-contrast headers and navigation footers to ground the design in professionalism. **Text Muted** provides a soft contrast for secondary information, ensuring that even data-heavy screens remain legible and stress-free. The system defaults to a light mode with an off-white background to maintain an open, academic atmosphere, using dark mode sections selectively for impact (e.g., hero banners or coding environments).

## Typography

This design system uses **Sora** for headings to project a geometric, futuristic, and bold image. Its wide characters feel welcoming yet technical. For body text and functional UI labels, **Hanken Grotesk** is chosen for its exceptional clarity and modern, sharp aesthetic.

Hierarchies are strictly enforced:
- **Display styles** are reserved for hero sections and key marketing messages.
- **Headline styles** should use tighter letter spacing to maintain a "locked-in" professional look.
- **Body text** utilizes a generous line height (1.5x) to facilitate long-form reading in course modules.
- **Labels** are often used in All-Caps for metadata or section tags to distinguish them from body content.

## Layout & Spacing

The layout follows a **Fluid Grid** system within a max-width container of 1280px. A standard 12-column grid is used for desktop, collapsing to 4 columns for mobile devices. 

Spacing is based on an **8px linear scale**. 
- **Desktop:** 24px gutters provide significant breathing room between course cards and dashboard widgets. 
- **Mobile:** Margins are reduced to 16px to maximize screen real estate, while maintaining touch-target safety.
- **Vertical Rhythm:** Sections should be separated by large padding (80px to 120px) to maintain a premium, editorial feel that avoids visual clutter.

## Elevation & Depth

Visual hierarchy is established primarily through **Tonal Layers** and **Low-Contrast Outlines**. 
- **Levels 0-1:** Use a subtle border (1px solid, #E2E8F0) for cards and input containers on light backgrounds.
- **Levels 2+:** For interactive elements like modals or active dropdowns, use an "Ambient Shadow"—a soft, diffused shadow tinted with a hint of the Primary Violet (e.g., `box-shadow: 0 12px 32px rgba(142, 54, 232, 0.08)`).
- **Surface Depth:** Use the "Surface Deep" color for high-impact footer or sidebar backgrounds to create a clear structural distinction between navigation and content.

## Shapes

The shape language is **Rounded**, conveying a friendly and approachable learning environment. 
- **Standard UI (Inputs, Buttons):** 0.5rem (8px) radius.
- **Large Components (Course Cards, Hero Images):** 1rem (16px) radius.
- **Badges/Chips:** Pill-shaped (fully rounded) to contrast with the more structured rectangular cards.

This consistent rounding softens the "tech" edge, making the academy feel accessible to beginners while remaining sharp enough for professionals.

## Components

### Buttons
- **Primary:** Solid Electric Violet with white text. High-contrast, 8px border radius.
- **Secondary:** Outlined with Growth Green or Electric Violet.
- **Ghost:** Minimal padding, used for "Learn More" or tertiary actions.

### Cards (Courses/Programs)
Cards should feature a top-heavy visual (image or icon) with a 16px padding for internal content. Titles should use `headline-md`. Include a subtle 1px border that darkens on hover.

### Inputs & Form Fields
Fields use a light gray background (#F1F5F9) with no border until focused. On focus, they transition to a 2px Electric Violet border with a soft glow. Labels sit above the field using `label-lg`.

### Chips & Tags
Used for course categories (e.g., "Frontend", "Data Science"). Use a subtle tint of the primary color with 10% opacity as the background, and the full-strength color for the text.

### Progress Indicators
Used in the Student Dashboard. These should exclusively use **Growth Green** to provide positive reinforcement of the student's journey.

### Navigation
The top navigation bar should be sticky, utilizing a slight backdrop-blur (10px) to maintain a modern, glass-like feel without distracting from the main content.