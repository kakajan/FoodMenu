# منوی دیجیتال — FoodMenu

Elevate your restaurant's presence with a beautiful Persian digital menu crafted for speed, readability, and conversion.

این منو برای «غذای سنتی گلین» طراحی شده است — یک صفحهٔ تک‌صفحه‌ای چشم‌نواز با تایپوگرافی فارسی، رنگ برند گرم و کارت‌های منو با تاکید بر خوانایی و اقدام به خرید/اشتراک‌گذاری.

---

## Why this menu converts

- Bold, emotive hero that immediately communicates brand (big headline + overlay background).  
- Readable Persian typography (Vazirmatn) for local authenticity and best UX.  
- Carefully tuned color palette (brand-red) for appetite appeal and CTAs.  
- Card-based menu layout for scannability on mobile and tablet.  
- Built with Tailwind-friendly CSS so you can iterate quickly.

---

## Features (taken from the site)

- Full RTL support and Persian text content
- Large hero with background image + dark overlay for contrast
- Animated hero title and CTA
- Card-based menu with dish name, description and price
- Share button per item (pre-wired data attributes)
- Preloader for polished first-impression

---

## Quick Start — Build & Preview (developer-friendly)

This repository uses the Tailwind workflow and a minimal PostCSS setup. The project expects `src/input.css` as the build input and outputs a bundled `dist/output.css`.

1. Install dependencies:

```bash
npm install
```

2. Build the CSS once:

```bash
npm run build:css
# (this runs Tailwind CLI: reads ./src/input.css and writes ./dist/output.css)
```

3. Watch for changes during development:

```bash
npm run watch:css
```

4. Open `index.html` in a browser or serve the folder with a static server. (Five Server / Live Server recommended for quick local preview.)

---

## How to customize

- Colors & theme: The project exposes the brand palette via CSS variables in `src/input.css`. If you're using Tailwind utilities, add the same palette to `tailwind.config.cjs` under `theme.extend.colors` so utility classes (e.g., `bg-brand-red-500`) are generated.
- Fonts: The site uses Vazirmatn via Google Fonts for native Persian rendering. To switch fonts, update the Google Fonts link in `index.html` and `--font-sans` in `src/input.css`.
- Images: Hero background is defined inline in `index.html` header styles — swap the Unsplash URL for your hero photography for instant brand lift.

---

## Marketing tips to increase conversions

1. Use high-quality food photography in the hero and card thumbnails.  
2. Add limited-time badges (e.g., "پیشنهاد امروز") on cards to create urgency.  
3. Make the share button trigger a native Web Share when possible — it's already present as a button with data attributes.  
4. Add structured data (JSON-LD) for local business + menu items to appear in rich results.  

---

## Accessibility & RTL notes

- Page includes RTL layout and Persian language attributes.  
- Ensure contrast ratios meet WCAG AA by checking text over hero/floors.  
- Use `translate="no"` on `<html>` (or the `google` meta tag) to prevent automatic translation altering UX.

---

## Files of interest

- `index.html` — the full landing page and menu markup (hero, menu cards, animations).  
- `src/input.css` — Tailwind input + CSS variables and helper utilities.  
- `tailwind.config.cjs` — project-level Tailwind theme (if present).  
- `postcss.config.cjs` — PostCSS loader configuration.

---

## Next steps I recommend (marketing + developer)

1. Add analytics and UTM-tagged links for CTA tracking.  
2. Add A/B test of hero copy and CTA color (brand-red vs. an accent).  
3. Add structured JSON-LD for menu items and local business contact.  
4. If you want Tailwind utilities for the brand palette, I can add the colors to `tailwind.config.cjs` and re-run the build.

---

## Contact & support

If you want, I can:

- Add the brand palette to `tailwind.config.cjs` and generate full Tailwind utilities.  
- Create a production-ready build script and a tiny Node/Express static server for preview.  
- Write a short marketing copy variants (3 headlines + 3 CTAs) to run A/B tests.

Tell me which next step you want and I’ll implement it.

---

Licensed under the project `LICENSE` file.
# FoodMenu