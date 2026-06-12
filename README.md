# Bösger Digital – Brand Colors

An interactive brand identity reference page for **Bösger Digital**, available at [colors.boesger.com](https://colors.boesger.com).

## Contents

The page documents the visual identity of Bösger Digital and includes:

- **Color palette** – All brand colors with HEX values, click to copy to clipboard
- **Backgrounds** – Layered background colors from Deep to Elevated
- **Accent colors** – Primary cyan accents and their variants
- **Typography** – Font families and sizes
- **Assets** – Logos and other brand materials available for download

## Color Palette

| Token | HEX | Usage |
|---|---|---|
| `--bg-deep` | `#000D1C` | Deepest background level |
| `--bg-base` | `#001222` | Base background |
| `--bg-surface` | `#062237` | Card surfaces |
| `--bg-elevated` | `#124061` | Elevated elements |
| `--accent` | `#01BFFB` | Primary color / CTA |
| `--accent-light` | `#6BDFF1` | Light accent |
| `--accent-deep` | `#058FC1` | Dark accent |
| `--accent-muted` | `#336D91` | Muted accent / labels |
| `--text-primary` | `#FFFFFF` | Primary text |
| `--text-body` | `#C0F6FC` | Body text |
| `--text-muted` | `#336D91` | Secondary text |

## Usage

The page is a static `index.html` file plus an `assets/` folder containing the logo, icon and background images – no build process, no dependencies. All color values live directly in the HTML (visible text, `data-*` attributes, JSON-LD and a JSON data island), so no JavaScript is required to read them – JS only powers the click-to-copy interactions.

```bash
# Serve locally (recommended – the click-to-copy-image feature needs HTTP)
npx serve .

# Or just open the file to view it
open index.html
```

## Deployment

The page is hosted via **GitHub Pages**. The CNAME `colors.boesger.com` is configured in the `CNAME` file.

Changes pushed to the `main` branch are published automatically.

## License

© Bösger Digital. All rights reserved.
