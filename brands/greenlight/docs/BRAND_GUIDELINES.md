# GreenLight Brand Guidelines

> *Illuminate Your Path Forward*

## Overview

GreenLight is a forward-thinking media brand focused on sustainable innovation, environmental storytelling, and green technology coverage. Our visual identity reflects our commitment to a brighter, more sustainable future.

---

## Brand Essence

### Mission
To illuminate the path toward sustainable living by making green technology and environmental progress accessible, engaging, and inspiring for everyone.

### Vision
A world where sustainable choices are the default, powered by informed communities who understand and embrace green innovation.

### Values
- **Optimism** - We lead with solutions and celebrate progress
- **Clarity** - We make complex topics accessible
- **Integrity** - We're honest about challenges while inspiring action
- **Innovation** - We embrace new ideas and technologies

---

## Color Palette

### Primary Colors

| Color | Hex | Usage |
|-------|-----|-------|
| **GreenLight Green** | `#00C853` | Primary brand color - CTAs, headers, brand emphasis |
| **Dark Green** | `#00962F` | Hover states, text on light backgrounds |

### Secondary Colors

| Color | Hex | Usage |
|-------|-----|-------|
| **Mint** | `#B9F6CA` | Light accents, backgrounds, cards |
| **Forest** | `#1B5E20` | Footer backgrounds, deep emphasis sections |

### Accent Colors

| Color | Hex | Usage |
|-------|-----|-------|
| **Leaf** | `#76FF03` | Highlights, notifications, energy elements |
| **Sun** | `#FFD600` | Warmth accent, optimistic messaging, solar themes |

### Neutral Colors

| Color | Hex | Usage |
|-------|-----|-------|
| **White** | `#FFFFFF` | Backgrounds, text on dark surfaces |
| **Light Gray** | `#F5F5F5` | Section backgrounds, dividers |
| **Dark Gray** | `#212121` | Body text, headings |
| **Black** | `#000000` | High contrast elements |

---

## Typography

### Primary Typeface: Inter
Used for headings, navigation, and calls-to-action.

```css
font-family: 'Inter', system-ui, -apple-system, sans-serif;
```

**Available Weights:** Regular (400), Medium (500), SemiBold (600), Bold (700)

### Secondary Typeface: Source Sans Pro
Used for body text, paragraphs, and captions.

```css
font-family: 'Source Sans Pro', 'Helvetica Neue', Arial, sans-serif;
```

**Available Weights:** Regular (400), SemiBold (600)

### Monospace: JetBrains Mono
Used for code snippets, technical content, and data displays.

```css
font-family: 'JetBrains Mono', Consolas, Monaco, monospace;
```

### Type Scale

| Name | Size | Use Case |
|------|------|----------|
| xs | 0.75rem (12px) | Captions, labels |
| sm | 0.875rem (14px) | Secondary text |
| base | 1rem (16px) | Body text |
| lg | 1.125rem (18px) | Lead paragraphs |
| xl | 1.25rem (20px) | Small headings |
| 2xl | 1.5rem (24px) | Section headings |
| 3xl | 1.875rem (30px) | Page headings |
| 4xl | 2.25rem (36px) | Hero text |
| 5xl | 3rem (48px) | Display text |
| 6xl | 3.75rem (60px) | Large display |

---

## Voice & Tone

### Brand Voice Characteristics
- **Optimistic** - Focus on solutions and progress
- **Informative** - Provide real value and knowledge
- **Forward-thinking** - Embrace innovation and change
- **Accessible** - Avoid jargon, be inclusive

### Writing Principles

1. **Lead with solutions, not problems**
   - *Instead of:* "Climate change is destroying our planet"
   - *Try:* "New solar technology is making clean energy more accessible than ever"

2. **Make sustainability approachable**
   - Break down complex topics into digestible insights
   - Use relatable examples and everyday language

3. **Celebrate progress, encourage action**
   - Highlight wins, both big and small
   - Include actionable takeaways for readers

4. **Be honest about challenges while inspiring hope**
   - Acknowledge difficulties without doom-scrolling
   - Balance reality with optimism

---

## Logo Usage

### Clear Space
Maintain a minimum clear space around the logo equal to the height of the "G" in GreenLight.

### Minimum Size
- **Digital:** 120px width minimum
- **Print:** 1 inch width minimum

### Color Variations
1. **Primary:** GreenLight Green (#00C853) on white/light backgrounds
2. **Reversed:** White on dark/green backgrounds
3. **Monochrome:** Black for single-color applications

### Don'ts
- Don't stretch or distort the logo
- Don't rotate the logo
- Don't apply effects (shadows, gradients, etc.)
- Don't place on busy backgrounds without sufficient contrast
- Don't change the logo colors outside approved palette
- Don't add outlines or borders

---

## Imagery

### Photography Style
- **Natural lighting** - Bright, optimistic
- **Green spaces** - Nature, plants, sustainable environments
- **Technology** - Clean, modern, innovative
- **People** - Diverse, authentic, engaged with sustainability

### Illustration Style
- Clean, modern line work
- Limited color palette from brand colors
- Geometric and organic shapes combined
- Emphasis on growth and progress themes

---

## Social Media

### Handles
- Twitter/X: [@GreenLightMedia](https://twitter.com/GreenLightMedia)
- Instagram: [@greenlight.media](https://instagram.com/greenlight.media)
- LinkedIn: [greenlight-media](https://linkedin.com/company/greenlight-media)

### Hashtags
- `#GreenLight` - Primary brand hashtag
- `#SustainableFuture` - Vision-aligned content
- `#GreenTech` - Technology coverage
- `#EcoInnovation` - Innovation stories

---

## Implementation

### CSS Custom Properties
Import the design tokens from `tokens.css` for consistent implementation:

```css
@import 'brands/greenlight/tokens.css';

.button-primary {
  background-color: var(--gl-green);
  color: var(--gl-white);
  font-family: var(--gl-font-primary);
  font-weight: var(--gl-font-weight-semibold);
  border-radius: var(--gl-radius-md);
  padding: var(--gl-space-3) var(--gl-space-6);
  transition: background-color var(--gl-transition-fast);
}

.button-primary:hover {
  background-color: var(--gl-dark-green);
}
```

### JSON Data
The complete brand definition is available in `brand.json` for programmatic access.

---

## Contact

For brand-related questions or asset requests, contact the BlackRoad-Media design team.

---

*Last updated: December 2025*
*Version: 1.0.0*
