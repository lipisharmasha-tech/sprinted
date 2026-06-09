# SprintED Design System Documentation

## Overview
This document captures the complete design system reverse-engineered from the SprintED educational platform website. The design follows a professional, modern aesthetic with a dark color palette accented by blue and orange highlights.

---

## 1. Color Palette

### Primary Colors
```css
--primary-blue: #2563eb;      /* Primary action color */
--primary-orange: #f97316;    /* Accent/brand color */
```

### Background Colors
```css
/* Dark Backgrounds */
--bg-slate-950: #020617;      /* Footer, darkest background */
--bg-slate-900: #0f172a;      /* Dark sections, headers */
--bg-slate-800: #1e293b;      /* Secondary dark buttons */

/* Light Backgrounds */
--bg-white: #ffffff;          /* Main content background */
--bg-slate-50: #f8fafc;       /* Card backgrounds, light sections */
--bg-orange-50: #fff7ed;      /* Light orange section */
--bg-gray-50: #f1f5f9;        /* Subtle background variation */
```

### Text Colors
```css
--text-primary: #0f172a;      /* Primary headings, dark text */
--text-secondary: #475569;    /* Body text, medium emphasis */
--text-tertiary: #64748b;     /* De-emphasized text */
--text-muted: #94a3b8;        /* Muted text, secondary info */
--text-light: #cbd5e1;        /* Light text on dark backgrounds */
--text-white: #ffffff;        /* White text */
```

### Accent Colors
```css
--accent-orange-light: #fb923c;   /* Light orange accent */
--accent-orange-dark: #ea580c;    /* Dark orange accent */
--accent-blue-dark: #1e3a8a;      /* Dark blue accent */
--accent-blue-darker: #172554;    /* Darker blue variant */
--accent-purple: #9333ea;         /* Purple accent */
```

### Border Colors
```css
--border-slate-200: #e2e8f0;      /* Primary border color */
--border-slate-100: #f1f5f9;      /* Light borders */
--border-slate-700: #334155;      /* Dark borders */
--border-blue-200: #dbeafe;       /* Blue tinted borders */
--border-orange-200: #fed7aa;     /* Orange tinted borders */
--border-slate-900: #0f172a;      /* Very dark borders */
--border-transparent-slate: rgba(226, 232, 240, 0.6); /* Semi-transparent */
--border-transparent-blue: rgba(239, 246, 255, 0.6);  /* Semi-transparent blue */
```

---

## 2. Typography

### Font Families
```css
--font-primary: 'Plus Jakarta Sans', sans-serif;
--font-mono: 'Azeret Mono', monospace;
```

### Font Weights
```css
--font-regular: 400;      /* Plus Jakarta Sans Regular */
--font-medium: 500;       /* Plus Jakarta Sans Medium */
--font-semibold: 600;     /* Plus Jakarta Sans SemiBold */
--font-bold: 700;         /* Plus Jakarta Sans Bold */
--font-extrabold: 800;    /* Plus Jakarta Sans ExtraBold */
--font-italic: italic;    /* Plus Jakarta Sans Italic */
```

### Font Sizes & Line Heights

#### Display/Hero Text
```css
--text-3xl: 48px;         /* line-height: 48px */
--text-2xl: 36px;         /* line-height: 40px */
--text-xl: 30px;          /* line-height: 36px */
--text-lg: 24px;          /* line-height: 32px */
```

#### Body Text
```css
--text-base: 16px;        /* line-height: 24px */
--text-sm: 14px;          /* line-height: 20px or 22.75px */
--text-xs: 12px;          /* line-height: 16px or 19.5px */
```

#### Headings
```css
--text-md: 18px;          /* line-height: 28px */
--text-lg-heading: 20px;  /* line-height: 28px */
```

### Letter Spacing
```css
--tracking-tighter: -1.2px;    /* Large headlines */
--tracking-tight: -0.9px;      /* Medium headlines */
--tracking-normal: -0.5px;     /* Body headlines */
--tracking-wide: 0.35px;       /* Table headers */
--tracking-wider: 0.6px;       /* Small caps */
--tracking-widest: 0.7px;      /* Uppercase labels */
--tracking-ultra: 1.2px;       /* All caps headers */
```

### Typography Patterns

#### Hero Heading
```css
font-family: Plus Jakarta Sans;
font-weight: 800 (ExtraBold);
font-size: 48px;
line-height: 48px;
letter-spacing: -1.2px;
color: #ffffff;
```

#### Section Heading (Large)
```css
font-family: Plus Jakarta Sans;
font-weight: 800 (ExtraBold);
font-size: 36px;
line-height: 40px;
letter-spacing: -0.9px;
color: #0f172a;
```

#### Section Heading (Medium)
```css
font-family: Plus Jakarta Sans;
font-weight: 800 (ExtraBold);
font-size: 30px;
line-height: 36px;
color: #0f172a;
```

#### Subsection Heading
```css
font-family: Plus Jakarta Sans;
font-weight: 800 (ExtraBold);
font-size: 24px;
line-height: 32px;
color: #0f172a or #172554 or #ea580c;
```

#### Card Title
```css
font-family: Plus Jakarta Sans;
font-weight: 700 (Bold);
font-size: 18px;
line-height: 28px;
color: #0f172a;
```

#### Label/Overline (Uppercase)
```css
font-family: Plus Jakarta Sans;
font-weight: 700 (Bold) or 600 (SemiBold);
font-size: 14px or 12px;
line-height: 20px or 16px;
letter-spacing: 0.7px or 0.6px or 1.2px;
text-transform: uppercase;
color: varies (#1e3a8a, #ea580c, #94a3b8)
```

#### Body Text
```css
font-family: Plus Jakarta Sans;
font-weight: 400 (Regular) or 500 (Medium);
font-size: 16px or 14px;
line-height: 24px or 20px or 22.75px;
color: #475569 or #64748b or #94a3b8;
```

#### Small Text
```css
font-family: Plus Jakarta Sans;
font-weight: 600 (SemiBold) or 400 (Regular);
font-size: 12px;
line-height: 16px or 19.5px;
color: #64748b or #94a3b8;
```

#### Button Text
```css
font-family: Plus Jakarta Sans;
font-weight: 700 (Bold);
font-size: 14px;
line-height: 20px;
color: #ffffff;
```

---

## 3. Spacing System

### Gap Values
```css
--gap-1: 4px;
--gap-1-5: 6px;
--gap-2: 8px;
--gap-3: 12px;
--gap-3-1: 12.5px;
--gap-4: 16px;
--gap-8: 32px;
```

### Common Spacing Patterns
- Card spacing: `gap-1-5` (6px) between title and description
- List spacing: `gap-2` (8px) between list items
- Section spacing: `gap-3` or `gap-3-1` (12-12.5px)
- Grid columns: `gap-8` (32px) between columns
- Layout sections: 32px, 64px, 80px, 96px vertical spacing

---

## 4. Border Radius

```css
--radius-sm: 9999px;      /* Fully rounded (pills, badges, avatars) */
--radius-md: 12px;        /* Buttons, small cards, badges */
--radius-lg: 16px;        /* Large cards, containers */
```

### Usage
- **9999px**: Circular elements (avatars, icon backgrounds), pill-shaped badges
- **12px**: Buttons, input fields, small cards, tags
- **16px**: Large cards, major content containers

---

## 5. Shadows

### Button Shadows
```css
/* Primary Blue Button */
--shadow-blue: 
  0px 8px 10px 0px rgba(37, 99, 235, 0.2),
  0px 20px 25px 0px rgba(37, 99, 235, 0.2);

/* Primary Orange Button */
--shadow-orange: 
  0px 8px 10px 0px rgba(249, 115, 22, 0.2),
  0px 20px 25px 0px rgba(249, 115, 22, 0.2);
```

### Card Shadows
```css
/* Standard Card Shadow */
--shadow-card: 
  0px 2px 4px -2px rgba(0, 0, 0, 0.1),
  0px 4px 6px -1px rgba(0, 0, 0, 0.1);

/* Large Container Shadow */
--shadow-container: 
  0px 8px 10px -6px rgba(0, 0, 0, 0.1),
  0px 20px 25px -5px rgba(0, 0, 0, 0.1);
```

### Inset Shadows
```css
/* Subtle Inset Shadow */
--shadow-inset: inset 0px 2px 4px 0px rgba(0, 0, 0, 0.05);
```

### Drop Shadows
```css
/* Icon/Badge Drop Shadow */
--shadow-drop: 
  0px 2px 2px rgba(0, 0, 0, 0.1),
  0px 4px 3px rgba(0, 0, 0, 0.1);
```

---

## 6. Components

### 6.1 Buttons

#### Primary Button (Blue)
```css
background: #2563eb;
color: #ffffff;
height: 50px;
padding: 0 24px;
border-radius: 12px;
font-weight: 700 (Bold);
font-size: 14px;
line-height: 20px;
box-shadow: 0px 8px 10px 0px rgba(37, 99, 235, 0.2),
            0px 20px 25px 0px rgba(37, 99, 235, 0.2);
```

#### Primary Button (Orange)
```css
background: #f97316;
color: #ffffff;
height: 50px;
padding: 0 24px;
border-radius: 12px;
font-weight: 700 (Bold);
font-size: 14px;
line-height: 20px;
box-shadow: 0px 8px 10px 0px rgba(249, 115, 22, 0.2),
            0px 20px 25px 0px rgba(249, 115, 22, 0.2);
```

#### Secondary Button (Dark)
```css
background: #1e293b;
color: #ffffff;
height: 50px;
padding: 0 25px;
border-radius: 12px;
border: 1px solid #334155;
font-weight: 700 (Bold);
font-size: 14px;
line-height: 20px;
```

**Button Pattern:**
- All buttons include icon on the left (12-22.5px width, positioned at left: ~12-25px)
- Button text positioned at left: 24-25px from edge
- Icons are white SVG paths

### 6.2 Cards

#### Standard Card (Light)
```css
background: #f8fafc;
border: 1px solid #e2e8f0 or rgba(226, 232, 240, 0.6);
border-radius: 12px or 16px;
padding: 22px or 26px;
```

#### Content Card (White)
```css
background: #ffffff;
border: 1px solid #e2e8f0;
border-radius: 16px;
box-shadow: 0px 2px 4px -2px rgba(0, 0, 0, 0.1),
            0px 4px 6px -1px rgba(0, 0, 0, 0.1);
```

#### Card Structure
- Title: Bold, 14px, #0f172a
- Description: Regular/SemiBold, 12px, #475569, 6px gap from title
- Common heights: 64px, 80px, 100px

### 6.3 Badges/Pills

#### Icon Badge (Circular)
```css
background: #f97316 or #1e3a8a or #0f172a;
width: 48px or 96px;
height: 48px or 96px;
border-radius: 9999px;
box-shadow: inset 0px 2px 4px 0px rgba(0, 0, 0, 0.05);
drop-shadow: 0px 2px 2px rgba(0, 0, 0, 0.1),
             0px 4px 3px rgba(0, 0, 0, 0.1);
```

#### Label Badge
```css
background: rgba(239, 246, 255, 0.6);
border: 1px solid #dbeafe;
border-radius: 12px;
padding: ~10px 20px;
height: 42px;
font-weight: 700 (Bold);
font-size: 12px;
line-height: 16px;
color: #1e3a8a;
```

### 6.4 Avatar/Initial Circles

```css
/* Large Avatar */
width: 96px;
height: 96px;
border-radius: 9999px;
background: #1e3a8a or #0f172a or #f97316;
text (initials): Bold, 24px, line-height 32px, white;
box-shadow: inset 0px 2px 4px 0px rgba(0, 0, 0, 0.05);
```

### 6.5 Section Headers

#### Section with Overline Pattern
```html
<Overline> - SemiBold/Bold, 14px, uppercase, tracking 0.7px, accent color
<Heading> - ExtraBold, 30-36px, tracking -0.9px, #0f172a
<Description> - Medium, 14px, #64748b
```

---

## 7. Layout & Grid

### Container Widths
```css
--container-7xl: 1280px;    /* Main content container */
--container-5xl: 1024px;    /* Section content */
--container-4xl: 896px;     /* Narrow sections */
--container-full: 1425px;   /* Full page width */
```

### Grid Patterns
- **2-column grid**: 32px gap between columns
- **3-column grid**: 32px gap between columns
- **4-column grid**: 32px gap between items

### Common Column Widths
- Narrow column: ~280px
- Medium column: ~336px, ~384px
- Wide column: ~500px
- Full-width grid items: ~1022px, ~1120px, ~1216px

---

## 8. Borders

### Border Widths
```css
--border-default: 1px;
```

### Border Styles
- **Top border**: `border-t: 1px solid [color]`
- **Bottom border**: `border-b: 1px solid [color]`
- **All borders**: `border: 1px solid [color]`

### Common Border Combinations
- Light cards: `1px solid rgba(226, 232, 240, 0.6)` or `#e2e8f0`
- Dark sections: `1px solid #0f172a`
- Dividers: `border-t: 1px solid #f1f5f9`

---

## 9. Icons

### Icon Sizing
- Small icons: 14px × 14px
- Medium icons: 16px × 16px, 18px × 18px
- Large icons: 22.5px × 18px

### Icon Colors
- On dark backgrounds: #475569 (slate)
- On light backgrounds: inherit from text
- In buttons: white (#ffffff)

### Icon Implementation
- SVG paths stored in separate file (svg-ukhdkfb5t5.ts)
- Rendered inline using `<svg>` with `viewBox` and `preserveAspectRatio="none"`
- Fill color controlled via CSS variable: `fill="var(--fill-0, [default-color])"`

---

## 10. Interactive States

### Opacity
```css
--opacity-disabled: 0.7;    /* Disabled elements */
--opacity-overlay: 0.1;     /* Background overlays */
```

### Pointer Events
```css
pointer-events: none;       /* Decorative/overlay elements */
```

### Aria Hidden
- Decorative borders and overlays: `aria-hidden="true"`

---

## 11. Background Patterns

### Gradient Background
```css
background-image: linear-gradient(163.652deg, rgb(15, 23, 42) 0%, rgb(30, 27, 75) 100%);
```

### Radial Gradient Overlay
```svg
<radialGradient id='grad' gradientUnits='userSpaceOnUse' cx='0' cy='0' r='10' 
  gradientTransform='matrix(71.25 20.9 -71.25 20.9 712.5 209)'>
  <stop stop-color='rgba(255,255,255,1)' offset='0.70711'/>
  <stop stop-color='rgba(0,0,0,0)' offset='0.70711'/>
</radialGradient>
```
Applied at 10% opacity over gradient backgrounds.

---

## 12. Tables/Comparison Grids

### Header Row
```css
background: #0f172a;
height: 60px;
font-size: 14px;
letter-spacing: 0.35px;
```

### Data Rows
```css
background: white;
border-top: 1px solid #f1f5f9;
height: 90-91px;
```

### Column Layout (3-column comparison)
- Left column (label): Bold, 14px, #0f172a
- Middle column: Bold, 12px, #1e3a8a (on blue badge background)
- Right column: Medium, 12px, #94a3b8

---

## 13. Content Sections

### Section Backgrounds
- **Primary sections**: white background
- **Alternate sections**: #f8fafc
- **Highlighted sections**: #fff7ed (orange tint)
- **Dark sections**: #020617, #0f172a
- **Gradient sections**: linear-gradient dark blue to purple

### Section Borders
- Top border: `1px solid #e2e8f0` or `#f1f5f9`
- Bottom border: `1px solid #fed7aa` (orange sections)

### Section Padding
- Vertical: 64px, 80px, 96px
- Horizontal: 32px (from container edge)

---

## 14. Footer

```css
background: #020617;
border-top: 1px solid #0f172a;
height: 278px;
```

### Footer Content Layout
- 4-column grid with 32px gap
- Column 1: Logo + description (280px wide)
- Columns 2-4: Link sections (280px wide each)

### Footer Typography
- Logo: ExtraBold, 20px, white (with orange "ED")
- Section headings: Bold, 12px, uppercase, tracking 0.6px, white
- Links: Regular, 12px, #94a3b8
- Description: Medium, 12px, #64748b
- Copyright: Medium, 12px, #475569

### Footer Divider
```css
border-top: 1px solid #0f172a;
height: 57px;
```

---

## 15. Brand Elements

### Logo Pattern
```
"Sprint" (white) + "ED" (orange #f97316)
Font: Plus Jakarta Sans ExtraBold
Size: 20px
Letter spacing: -0.5px
```

### Brand Colors Usage
- **Blue (#2563eb)**: Primary actions, CTAs, trust indicators
- **Orange (#f97316)**: Brand accent, highlights, secondary CTAs
- **Dark (#0f172a, #020617)**: Premium feel, contrast, headers/footers

---

## 16. Data Visualization

### Stat Card Pattern
```css
background: #f8fafc;
border: 1px solid #e2e8f0;
border-radius: 16px;
padding: 26px;
height: 64px;

/* Stat number */
font: ExtraBold 24px, line-height 32px;
color: #0f172a or #ea580c or #172554;

/* Stat description */
font: SemiBold 12px, line-height 16px;
color: #64748b;
gap: 4px;
```

---

## 17. Special Patterns

### Word Break
```css
word-break: break-word;
white-space: nowrap;
```
Applied to text containers for overflow control.

### Positioning Patterns
- Centered text: `transform: translateY(-50%)` with `top: 50%`
- Icon positioning: absolute with specific left/top values

### Flex Patterns
```css
/* Column layouts */
display: flex;
flex-direction: column;
align-items: start;
justify-content: center;
gap: [varies];

/* Row layouts */
display: flex;
flex-direction: row;
gap: 16px or 32px;
```

---

## 18. Accessibility Considerations

### Semantic Structure
- Proper heading hierarchy (H2 for main sections)
- `aria-hidden="true"` for decorative elements
- Pointer events disabled on decorative overlays

### Color Contrast
- Text maintains WCAG AA standards
- Dark text (#0f172a) on light backgrounds
- Light text (white) on dark backgrounds (#020617, #0f172a)

---

## 19. Design Tokens Summary

```css
/* Brand */
--brand-primary: #2563eb;
--brand-accent: #f97316;

/* Neutral Palette */
--neutral-50: #f8fafc;
--neutral-100: #f1f5f9;
--neutral-200: #e2e8f0;
--neutral-300: #cbd5e1;
--neutral-400: #94a3b8;
--neutral-500: #64748b;
--neutral-600: #475569;
--neutral-700: #334155;
--neutral-800: #1e293b;
--neutral-900: #0f172a;
--neutral-950: #020617;

/* Semantic Colors */
--color-success: [not defined in design]
--color-warning: #fb923c;
--color-error: [not defined in design]
--color-info: #1e3a8a;

/* Spacing Scale */
--space-1: 4px;
--space-2: 8px;
--space-3: 12px;
--space-4: 16px;
--space-6: 24px;
--space-8: 32px;
--space-16: 64px;
--space-20: 80px;
--space-24: 96px;

/* Typography Scale */
--text-xs: 12px;
--text-sm: 14px;
--text-base: 16px;
--text-lg: 18px;
--text-xl: 20px;
--text-2xl: 24px;
--text-3xl: 30px;
--text-4xl: 36px;
--text-5xl: 48px;

/* Line Heights */
--leading-tight: 16px;
--leading-snug: 20px;
--leading-normal: 24px;
--leading-relaxed: 28px;
--leading-loose: 32px;

/* Font Weights */
--weight-normal: 400;
--weight-medium: 500;
--weight-semibold: 600;
--weight-bold: 700;
--weight-extrabold: 800;

/* Radius */
--radius-sm: 12px;
--radius-md: 16px;
--radius-full: 9999px;

/* Shadows */
--shadow-sm: 0px 2px 4px -2px rgba(0, 0, 0, 0.1), 0px 4px 6px -1px rgba(0, 0, 0, 0.1);
--shadow-md: 0px 8px 10px -6px rgba(0, 0, 0, 0.1), 0px 20px 25px -5px rgba(0, 0, 0, 0.1);
--shadow-blue: 0px 8px 10px 0px rgba(37, 99, 235, 0.2), 0px 20px 25px 0px rgba(37, 99, 235, 0.2);
--shadow-orange: 0px 8px 10px 0px rgba(249, 115, 22, 0.2), 0px 20px 25px 0px rgba(249, 115, 22, 0.2);
```

---

## 20. Implementation Notes

### Font Loading
- Plus Jakarta Sans: ExtraBold, Medium, Bold, Regular, SemiBold, Italic
- Azeret Mono: Regular, Medium
- Load via Google Fonts or self-hosted

### Image Handling
- Icons: SVG paths, inline rendering
- Decorative elements: data URI SVG backgrounds
- Responsive: Use `preserveAspectRatio="none"` for flexible scaling

### Responsive Breakpoints
Based on container widths, the design appears to target:
- Desktop: 1280px+ (7xl container)
- Large screens: Full 1425px width

---

This design system represents a complete reverse-engineering of the SprintED educational platform design, capturing all colors, typography, spacing, components, and interaction patterns as they exist in the provided implementation.
