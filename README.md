# Brand Kit

Brand guidelines, logos, and design assets for BlackRoad-Media brands.

## Brands

### GreenLight

*Illuminate Your Path Forward*

A forward-thinking media brand focused on sustainable innovation, environmental storytelling, and green technology coverage.

**Quick Links:**
- [Brand Guidelines](./brands/greenlight/docs/BRAND_GUIDELINES.md)
- [Logo Specifications](./brands/greenlight/docs/LOGO_SPECS.md)
- [Design Tokens (CSS)](./brands/greenlight/tokens.css)
- [Brand Definition (JSON)](./brands/greenlight/brand.json)

**Primary Colors:**
| Color | Hex | Preview |
|-------|-----|---------|
| GreenLight Green | `#00C853` | ![#00C853](https://via.placeholder.com/20/00C853/00C853.png) |
| Dark Green | `#00962F` | ![#00962F](https://via.placeholder.com/20/00962F/00962F.png) |
| Mint | `#B9F6CA` | ![#B9F6CA](https://via.placeholder.com/20/B9F6CA/B9F6CA.png) |
| Forest | `#1B5E20` | ![#1B5E20](https://via.placeholder.com/20/1B5E20/1B5E20.png) |

## Repository Structure

```
brand-kit/
├── brands/
│   └── greenlight/
│       ├── brand.json          # Complete brand definition
│       ├── tokens.css          # CSS custom properties
│       ├── assets/
│       │   ├── logos/          # Logo files (SVG, PNG)
│       │   └── icons/          # Icon assets
│       └── docs/
│           ├── BRAND_GUIDELINES.md
│           └── LOGO_SPECS.md
└── README.md
```

## Usage

### CSS Custom Properties

Import the design tokens in your project:

```css
@import 'brands/greenlight/tokens.css';

.my-button {
  background-color: var(--gl-green);
  color: var(--gl-white);
  font-family: var(--gl-font-primary);
}
```

### Programmatic Access

Load the brand definition in JavaScript/TypeScript:

```javascript
import brand from './brands/greenlight/brand.json';

console.log(brand.colors.primary.green.hex); // #00C853
console.log(brand.typography.primary.family); // Inter
```

## Contributing

This project is part of the BlackRoad-Media organization in the BlackRoad ecosystem.

### Adding a New Brand

1. Create a new directory under `brands/`
2. Add `brand.json` with the complete brand definition
3. Add `tokens.css` for CSS custom properties
4. Create `docs/` folder with guidelines and specifications
5. Add logo assets to `assets/logos/`

---

<div align="center">
  <sub>Part of <a href="https://github.com/BlackRoad-Media">BlackRoad-Media</a> • BlackRoad Ecosystem</sub>
</div>
