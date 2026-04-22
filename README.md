# Settantatré — Restaurant Website

A modern, artisan Italian pasta café website ready to deploy on GitHub Pages.

## Pages

| File | Page |
|------|------|
| `index.html` | Home — Hero, daily special, heritage section, product gallery |
| `menu.html` | Menu — Fresh pasta, small plates, dolci, wine list |
| `about.html` | About — Story, ingredients, philosophy, partners |
| `book.html` | Book — Reservation form, contacts, map |

## File Structure

```
settantatre-website/
├── index.html
├── menu.html
├── about.html
├── book.html
├── css/
│   └── style.css        ← Shared global styles
├── js/
│   └── main.js          ← Shared JavaScript (nav, transitions, form)
└── README.md
```

## Deploy to GitHub Pages

1. **Create a new GitHub repository** (e.g. `settantatre`)
2. **Upload all files** — keep the folder structure exactly as above
3. **Go to** Settings → Pages
4. **Source:** Deploy from branch → `main` → `/ (root)`
5. **Save** — your site will be live at `https://YOUR-USERNAME.github.io/settantatre/`

### Quick deploy via Git CLI

```bash
git init
git add .
git commit -m "Initial commit — Settantatré website"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/settantatre.git
git push -u origin main
```

Then enable GitHub Pages in your repo settings.

## Tech Stack

- **HTML5** — semantic, accessible markup
- **Tailwind CSS** — loaded via CDN (no build step needed)
- **Google Fonts** — Newsreader (serif) + Plus Jakarta Sans
- **Material Symbols** — icon set via Google Fonts CDN
- **Vanilla JS** — zero dependencies, ~60 lines

## Customization

- **Colors:** Edit the `tailwind.config` block inside any HTML file (they share the same token set)
- **Restaurant info:** Search & replace `Via del Corso 73`, `+39 06 1234 5678`, and `Settantatré`
- **Images:** Replace the `lh3.googleusercontent.com` URLs with your own hosted images
- **Global styles:** `css/style.css`
- **JS behaviour:** `js/main.js`
