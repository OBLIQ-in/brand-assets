# Obliq Brand Assets & Design Kit 🎨

Official brand assets, logos, color guidelines, typography, and product screenshots for [Obliq](https://obliq.in).

---

## 📁 Repository Structure

```
brand-assets/
├── logos/
│   ├── obliq-logo-dark.svg     ← Primary dark-mode logo (Charcoal + Lime + Periwinkle)
│   ├── obliq-logo-light.svg    ← Primary light-mode logo (Cream + Charcoal)
│   └── obliq-icon.svg          ← Square icon / avatar / favicon
├── palette/
│   └── tokens.json             ← Hex, RGB, and CSS variable definitions
├── screenshots/
│   └── README.md               ← Checklist & specs for product UI screenshots (#18, #19, #20)
├── imagery/
│   └── README.md               ← Guidelines for illustrations, banners & marketing graphics
└── README.md                   ← Brand guidelines & documentation
```

---

## 🎨 Color Palette

Extracted from the Framer marketing site and synchronized with the Next.js design system:

| Swatch | Color Name | Hex | CSS Variable | Purpose |
| :--- | :--- | :--- | :--- | :--- |
| ![#f5f0e8](https://via.placeholder.com/15/f5f0e8/000000?text=+) | **Cream** | `#f5f0e8` | `--obliq-cream` | Primary text, clean canvas background |
| ![#e8e0cc](https://via.placeholder.com/15/e8e0cc/000000?text=+) | **Cream Dark** | `#e8e0cc` | `--obliq-cream-dark` | Muted text, subtle borders |
| ![#c8f560](https://via.placeholder.com/15/c8f560/000000?text=+) | **Lime** | `#c8f560` | `--obliq-lime` | Primary brand accent, CTAs, highlight pills |
| ![#dffb8c](https://via.placeholder.com/15/dffb8c/000000?text=+) | **Lime Light** | `#dffb8c` | `--obliq-lime-light` | Button hover states, glow effects |
| ![#7b8cde](https://via.placeholder.com/15/7b8cde/000000?text=+) | **Periwinkle** | `#7b8cde` | `--obliq-periwinkle` | Secondary accent, status badges, `.in` |
| ![#aab4ee](https://via.placeholder.com/15/aab4ee/000000?text=+) | **Periwinkle Light** | `#aab4ee` | `--obliq-periwinkle-light` | Periwinkle highlight glows |
| ![#1a1a2e](https://via.placeholder.com/15/1a1a2e/000000?text=+) | **Charcoal** | `#1a1a2e` | `--obliq-charcoal` | Page background, high-contrast buttons |
| ![#16213e](https://via.placeholder.com/15/16213e/000000?text=+) | **Charcoal 2** | `#16213e` | `--obliq-charcoal-2` | Elevated surface layers, cards |
| ![#2d3561](https://via.placeholder.com/15/2d3561/000000?text=+) | **Slate** | `#2d3561` | `--obliq-slate` | Card outlines, dividers |
| ![#6b7280](https://via.placeholder.com/15/6b7280/000000?text=+) | **Muted** | `#6b7280` | `--obliq-muted` | Secondary metadata & captions |

---

## 🔤 Typography

- **Headings & Display**: `Plus Jakarta Sans`, sans-serif (Weights: 600, 700, 800)
- **Body & Interface**: `Inter`, system-ui, sans-serif (Weights: 400, 500)
- **Wordmark & Monospace**: `'Courier New'`, monospace (Logo pixel-box style)

---

## 📌 Logo Usage Guidelines

### Do's:
- Maintain original aspect ratio when scaling.
- Use `obliq-logo-dark.svg` against dark surfaces (`#1a1a2e` / `#16213e`).
- Use `obliq-logo-light.svg` against light surfaces (`#f5f0e8` / `#ffffff`).
- Provide adequate breathing room around the logo.

### Don'ts:
- Do not stretch, distort, or rotate the logo.
- Do not alter the font or outline width of the logo box.
- Do not place dark logos on low-contrast dark backgrounds without container styling.

---

## 📸 Screenshots Checklist

See [`screenshots/README.md`](./screenshots/README.md) for the active list of required UI screenshots to be dropped in for issues **#18**, **#19**, and **#20** in [obliq-website](https://github.com/OBLIQ-in/OBLIQ-Website).

---

## 📄 License

Assets and logos in this repository are © 2026 [Obliq](https://obliq.in).  
Permitted for use in official Obliq open-source projects, community documentation, and affiliated marketing.
