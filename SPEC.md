# rhystic.ai Landing Page Specification

## Project Overview
- **Project name**: rhystic.ai landing page
- **Type**: Single-page marketing website
- **Core functionality**: Showcase rhystic.ai company with retro-futuristic Y2K aesthetic
- **Target users**: Tech-savvy visitors, potential clients, investors

## UI/UX Specification

### Layout Structure
- **Header**: Fixed navigation with logo, nav links, CTA button
- **Hero**: Full viewport intro with animated text, glitch effects
- **Features**: Grid of service/product highlights
- **About**: Company mission section
- **Contact**: Call-to-action with email
- **Footer**: Minimal footer with links

### Visual Design

#### Color Palette (Acid Y2K)
- **Background Dark**: `#0a0a0a` (near black)
- **Primary Acid Green**: `#39ff14` (neon green)
- **Hot Pink**: `#ff073a` (neon red/pink)
- **Electric Cyan**: `#00fff7` (cyan)
- **Acid Yellow**: `#ccff00` (yellow-green)
- **Purple**: `#bf00ff` (electric purple)
- **White**: `#ffffff`
- **Gray**: `#1a1a1a`, `#333333`

#### Typography
- **Primary Font**: "VT323" (monospace pixel font) - headings
- **Secondary Font**: "Share Tech Mono" - body text
- **Hero Title**: 72px-120px, glitch animation
- **Section Titles**: 48px
- **Body**: 18px

#### Spacing
- Section padding: 100px vertical
- Container max-width: 1200px
- Grid gap: 30px

#### Visual Effects
- Scanline overlay effect
- CRT screen curvature (subtle)
- Glitch text animations
- Pixelated borders
- Gradient borders with neon colors
- Hover glow effects
- Floating geometric shapes
- Terminal-style cursor blinking

### Components

#### Navigation
- Transparent background, becomes solid on scroll
- Logo with pixel styling
- Links: Features, About, Contact
- CTA button with neon border glow

#### Hero Section
- Large animated title: "RHYSTIC.AI"
- Subtitle with typing effect
- Glitch animation on load
- Floating cassette/terminal graphics (CSS)
- Scroll indicator

#### Feature Cards
- Dark card with neon gradient border
- Icon (CSS-drawn or emoji)
- Title and description
- Hover: border glow intensifies

#### Button Styles
- Solid border with neon color
- Transparent background
- Hover: fill with color, text inverts
- Active: slight scale down

### Responsive Breakpoints
- Desktop: > 1024px
- Tablet: 768px - 1024px
- Mobile: < 768px

## Functionality Specification

### Core Features
1. Smooth scroll navigation
2. Glitch text animations on hero
3. Typing effect for tagline
4. Scroll-triggered animations
5. Interactive hover states
6. Scanline CRT effect overlay

### User Interactions
- Click nav links → smooth scroll to section
- Hover cards → glow effect
- Hover buttons → color fill animation

## Acceptance Criteria
- [ ] Page loads with glitch animation
- [ ] Navigation is fixed and functional
- [ ] All sections visible and styled
- [ ] Hover effects work on all interactive elements
- [ ] Responsive on mobile/tablet
- [ ] CRT/scanline effect visible
- [ ] Fonts load correctly