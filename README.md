# Color Picker & Converter Web App

A rich, single-page **color picker and color converter** web app. Pick colors from an interactive canvas or type values directly, convert between color formats, generate designer palettes, build CSS gradients, simulate color-blindness vision, and save your favorite palettes — all in the browser, no sign-up.

**Live demo:** https://girishlade111.github.io/Color-Picker-Converter-Web-App/

## Features

- **Interactive color picker canvas** — click/touch to select any color, with hue, saturation, lightness, and alpha sliders
- **Multi-format conversion** — convert instantly between HEX, RGB, HSL, HSV, CMYK, and named colors
- **Palette generators** — one click generates complementary, analogous, triadic, and monochromatic palettes
- **CSS gradient builder** — linear/radial gradients with adjustable angle; copies the ready-to-paste CSS code
- **Saved palettes** — name and save palettes, persisted locally for reuse
- **Color history** — recently picked colors stay available during your session
- **Color-blindness simulator** — preview colors under protanopia, deuteranopia, tritanopia, and achromatopsia
- **Click-to-copy** — copy any value with a toast confirmation
- **Dark & light themes** — toggleable UI theme
- **Fully responsive** — works on desktop and touch devices

## Tech Stack

- HTML5, CSS3, vanilla JavaScript (no framework, no build step)
- [Tailwind CSS](https://tailwindcss.com) via CDN
- [Font Awesome 6](https://fontawesome.com) icons
- [Inter](https://fonts.google.com/specimen/Inter) typeface from Google Fonts
- LocalStorage for saved palettes and theme preference

## Quick Start

No install needed — it is plain static files.

```bash
git clone https://github.com/girishlade111/Color-Picker-Converter-Web-App.git
cd Color-Picker-Converter-Web-App
# just open index.html in a browser, or serve it:
npx serve .
```

## Project Structure

```
Color-Picker-Converter-Web-App/
├── index.html   # entire app: markup, styles, and script in one file
└── README.md
```

## Deployment

Hosted free on GitHub Pages from the `main` branch (repo root). Any static host (Netlify, Cloudflare Pages, Vercel) works the same way — drop the files in and publish.

## Built by

Built by [Girish Lade](https://ladestack.in) — part of the LadeStack collection of free web tools.
