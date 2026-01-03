# Marc Engelen Interior - Codebase Index

## Overview
Interior design consultation landing page (Dutch). No build process required - vanilla HTML + Tailwind CSS via CDN.

## Files
| File | Description |
|------|-------------|
| `index.html` | Main landing page - hero section, 3 pricing tiers (Design/Luxury/High-End), features, process overview, CTAs |
| `quiz.html` | Style quiz page with Typeform integration placeholder |
| `voorbeelden.html` | Portfolio/examples gallery page |
| `img/Marc Engelen.jpg` | Personal photo |
| `img/Logo ME Studio Online.png` | Logo image |

## Tech Stack
- **HTML5** - Semantic markup
- **Tailwind CSS** - Via CDN (no build step)
- **JavaScript** - Minimal, Tailwind config only

## Design System

### Colors
- Dark Charcoal: `rgb(37, 35, 34)` - Primary text
- Warm Gray: `rgb(220, 215, 210)` - Secondary text
- Warm Gray Light: `rgb(240, 238, 235)` - Light accents
- Accent Warm: `rgb(200, 190, 180)` - Highlights

### Custom Classes
- `.section-padding` - Responsive section spacing
- `.fade-in` - Entrance animation (0.8s)
- `.hover-scale` - Interactive hover effect (1.02x)

## GitHub Pages Deployment

1. Push code to `main` branch
2. Go to **Settings → Pages**
3. Under "Build and deployment":
   - Source: **Deploy from a branch**
   - Branch: **main** / **/(root)**
4. Click Save
5. Site will be available at: `https://<username>.github.io/<repo>/`

No build process needed - GitHub Pages serves the HTML files directly.
