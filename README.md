# SiteGround — Prototype (Home + WordPress landing)

A static, front-end prototype of two responsive marketing pages, built as a portfolio
piece. Hand-built hero sections (custom CSS, including a layered "mirror glass" effect)
composed with production-style page layout.

**Live demo:** _add the GitHub Pages URL here once deployed_

## Pages
- **`index.html`** — Home / hero + services. Its primary CTAs link to the WordPress page.
- **`wordpress/index.html`** — WordPress hosting landing page. Logo links back to the home page.

## Structure
```
index.html              # home page
wordpress/index.html    # WordPress landing page
assets/                 # home-page CSS, images, UI script
wordpress/assets/       # landing-page CSS, images, UI script
.nojekyll               # serve files as-is on GitHub Pages
```

## Notes
- Pure static HTML/CSS/JS — no build step. Open `index.html` or serve the folder.
- Third-party analytics, cookie-consent, and live-chat scripts were removed for the demo;
  the interactive UI bundle (navigation, accordions) is kept.
