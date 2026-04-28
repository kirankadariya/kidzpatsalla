# 🇳🇵 Nepali Sikau — Learn Nepali

A fun, interactive Progressive Web App (PWA) for Nepali-American kids aged 5–8 to learn the Nepali language.

## ▶️ Run Locally

Just open `index.html` in any modern browser — no server or build step needed.

For PWA features (install prompt, offline), serve over HTTP:
```bash
npx serve .
# then open http://localhost:3000
```

## 📲 Install as App

Host the folder on any static host (Netlify, GitHub Pages, Vercel) and visit the URL on your phone. You'll see an "Add to Home Screen" / "Install" prompt automatically.

### Free hosting with Netlify Drop
1. Go to https://app.netlify.com/drop
2. Drag the `nepali-sikau/` folder onto the page
3. Get a free URL instantly — share it with anyone!

## 📁 Files

| File | Purpose |
|------|---------|
| `index.html` | The entire app — all HTML, CSS, JS in one file |
| `manifest.json` | PWA manifest — app name, icons, theme color |
| `sw.js` | Service worker — enables offline use |
| `icons/` | App icons in 8 sizes for all devices |
