# Week 2 – CSS Mastery | Juliet Adhiambo

**Live Site:** https://lykerjulie-cyber.github.io/Iyf-season10-week-02-lykerjulie-cyber/  
**Repo:** https://github.com/lykerjulie-cyber/Iyf-season10-week-02-lykerjulie-cyber

## Overview
Transformed Week 1 HTML portfolio into a responsive, styled website using CSS fundamentals, Flexbox, and mobile-first design principles.

## Tasks Completed

### Lesson 3: CSS Fundamentals
**3.1 CSS Setup & Reset**  
- External `styles.css` linked to all 4 pages
- CSS reset with `box-sizing: border-box`

**3.3 Typography System**  
- Google Fonts: Montserrat (headings) + Lato (body)
- Type scale: Major Third 1.250 ratio via CSS variables `--text-xs` to `--text-3xl`

**3.4 Color Scheme**  
- Primary palette: 6 shades of blue #0a3d62 to #aed6f1
- Accent: Red #e74c3c for CTAs
- All colors implemented as CSS custom properties

### Lesson 4: Layout & Responsive
**4.1 Flexbox**  
- Nav bar using `display: flex` with space-between layout
- Mobile: Nav stacks vertically using `flex-direction: column`

**4.3 Mobile-First Responsive**  
- Breakpoint: `@media (max-width: 768px)` 
- Tested at 320px, 768px, 1024px, 1440px - no horizontal scroll
- Headings scale down, buttons become full-width on mobile

**4.4 Polish & Accessibility**  
- Hover: Buttons lift 2px, cards lift 4px with enhanced shadow
- Transitions: `transition: all 0.2s ease` on interactive elements
- Focus: Form inputs show blue glow + 3px outline for keyboard users

## Components Built
1. **Buttons**: `.btn-primary`, `.btn-secondary`, `.btn-accent`
2. **Cards**: Project cards with image, title, description, CTA
3. **Forms**: Styled fieldset, inputs, select, textarea, red submit
4. **Layout**: Header/nav, main container, footer

## Notes
- Used Flexbox for all layouts instead of CSS Grid
- Completed Flexbox Froggy for flexbox practice
- All pages validate with no HTML/CSS errors
