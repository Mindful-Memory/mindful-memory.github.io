# mindful-memory.com

Public website for Mindful Memory LLC, served by GitHub Pages from the `main` branch root
(custom domain in `CNAME`).

## Stack

Plain HTML + CSS in a single `index.html` with inline styles. No build step, no
dependencies, no JavaScript. Fonts load from Google Fonts (Zilla Slab for headings to
match the wordmark, Inter for body text).

Preview locally:

```
python3 -m http.server 8000
```

## Layout

```
index.html                 the whole site: markup + inline CSS
assets/logo.png            wordmark, dark ink on transparent (light backgrounds)
assets/logo-light.png      wordmark recolored for dark backgrounds
assets/mark.png            brain-and-chip mark only (+ mark-light.png)
assets/favicon.png         256px favicon built from the mark
assets/hero.svg            hand-drawn hero illustration (chip + neural graph + shield)
assets/og.jpg              1200x630 social preview
assets/highbyte.png        partner logo
assets/team/*.jpg          leadership portraits, 640px square JPEG
CNAME .nojekyll robots.txt sitemap.xml
```

Sections in page order: hero, `#solutions`, `#team`, `#partners`, `#contact`.
Copy was migrated from the previous GoDaddy site.
