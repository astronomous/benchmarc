# Marc Engelen Interior Landing Page

Een moderne, responsieve landing page voor Marc Engelen Interior - online interieuradvies op maat.

## Features

- ✨ Clean, minimalistisch design geïnspireerd op moderne interieurontwerpen
- 🎨 Custom kleurenpalet met natuur-geïnspireerde tinten
- 📱 Volledig responsive (mobile-first)
- 🚀 Gebouwd met Tailwind CSS via CDN
- 🎯 Meerdere call-to-actions naar de stijlquiz
- ⚡ Snelle laadtijd, geen build proces nodig

## Kleuren

- **Cream**: #F5F1E8 - Hoofdachtergrond
- **Sand**: #E8DCC8 - Accent achtergrond
- **Sage**: #A8B5A0 - Secundaire accent
- **Forest**: #4A5D4E - Primaire CTA kleur
- **Charcoal**: #2C2C2C - Tekst

## GitHub Pages Deployment

### Optie 1: Via GitHub Interface

1. Push deze code naar je GitHub repository
2. Ga naar Settings → Pages
3. Selecteer de branch (main of monrovia)
4. Selecteer root (/) als source folder
5. Klik op Save
6. Je site is beschikbaar op: `https://[username].github.io/[repo-name]/`

### Optie 2: Via Command Line

```bash
# Push je code
git add .
git commit -m "Add Marc Engelen Interior landing page"
git push origin main

# Enable GitHub Pages (via gh CLI)
gh repo edit --enable-pages --pages-branch main
```

## Lokaal Testen

Open gewoon `index.html` in je browser. Omdat we Tailwind via CDN gebruiken, werkt alles direct zonder build stap.

## Typeform Integratie

De quiz pagina (`quiz.html`) is klaar voor je Typeform embed. Er zijn twee opties:

### Optie 1: Embedded Typeform (aanbevolen)
1. Ga naar je Typeform en klik op "Share"
2. Kies "Embed in a webpage"
3. Kopieer de embed code
4. Open `quiz.html` en vervang de placeholder (regel ~95) met je embed code

Voorbeeld:
```html
<div data-tf-widget="YOUR_FORM_ID" style="width:100%;height:600px;"></div>
<script src="//embed.typeform.com/next/embed.js"></script>
```

### Optie 2: Popup Typeform
Als je liever een popup gebruikt, vervang de placeholder met:
```html
<button data-tf-popup="YOUR_FORM_ID" class="border border-warm-gray-light text-warm-gray-light px-16 py-5 text-sm letter-spacing-wider uppercase hover:bg-warm-gray-light hover:text-dark-charcoal transition-all duration-400">
    Start de Quiz
</button>
<script src="//embed.typeform.com/next/embed.js"></script>
```

## Aanpassingen

### Content
- Update de teksten in de HTML direct
- Alle content is in het Nederlands

### Kleuren
- Pas de kleuren aan in het `tailwind.config` object (regel 10-18)
- Gebruik de custom kleuren met class names zoals `bg-warm-gray`

### Secties
De pagina bestaat uit:
1. Header met sticky navigatie
2. Hero sectie met hoofdboodschap
3. "Hoe werkt het" - 3 stappen
4. Quiz CTA (groot, prominent)
5. Benefits sectie (4 voordelen)
6. Over sectie
7. Final CTA
8. Footer

## Browser Support

Werkt in alle moderne browsers:
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers

## Performance

- Tailwind CSS via CDN: ~50KB (gecached door meeste bezoekers)
- Geen extra JavaScript dependencies
- Optimale Core Web Vitals scores
