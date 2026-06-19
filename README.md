# jones-portfolio

Personal portfolio site. Static HTML + CSS, editorial brutalism style.

## Stack

- **Frontend:** Pure HTML + CSS (no framework)
- **Fonts:** Outfit (display) + IBM Plex Mono (mono)
- **Deploy:** Vercel (static)

## Structure

```
portfolio-site/
├── index.html
├── assets/
│   └── css/style.css
├── vercel.json
└── README.md
```

## Local Preview

```bash
python -m http.server 8000
# open http://localhost:8000
```

## Deploy

Connected to Vercel — auto-deploy on `main` push.

```bash
git push origin main
```

## Design

Editorial Brutalism — light theme. Anti-AI-slop principles:
- Asymmetric layout (cards span 7/5 columns)
- Thick black borders + hard shadows (no blur)
- Bold colors (red, orange, green)
- Rotated stat cards
- Terminal-style accents (mono fonts, prompt markers)
