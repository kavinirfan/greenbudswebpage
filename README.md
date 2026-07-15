# Sathyam Homes — Landing Page

A single-file, fully animated landing page built for **Sathyam Homes Pvt. Ltd.**, a Chennai-based real estate developer. No build tools, no dependencies to install — just one HTML file that runs anywhere.

[![Netlify Status](https://api.netlify.com/api/v1/badges/f8380347-2477-4793-a8b7-d974381ffc41/deploy-status)](https://app.netlify.com/sites/sathyamhome/deploys)

### 🔗 [Live Demo](https://sathyamhome.netlify.app/) &nbsp;·&nbsp; [Source Code](https://github.com/kavinirfan/greenbudswebpage/tree/main)

---

## About

This project was designed around Sathyam Homes' brand identity — "Unlock the Door to Exceptional Living" — using a signature door-opening motif that recurs throughout the page as both a loading animation and a scroll-triggered section divider.

## Features

- **Signature door animation** — a custom inline SVG door mark used in the hero section and as a divider before major headings, with smooth CSS 3D transforms on scroll
- **Scroll-reveal effects** — sections fade and rise into view as the user scrolls
- **Brand color palette** — charcoal, ivory, rose, and terracotta tones drawn from the Sathyam Homes identity
- **Responsive navigation** — includes a services dropdown and a mobile burger menu
- **Key sections**:
  - Hero with animated door stage
  - Brand quote band
  - "Building Beyond Expectations" services section
  - Projects showcase
  - Trust strip
  - Stats counters
  - Contact form + FAQ
  - Newsletter signup
  - Footer
- **Custom typography** — Fraunces (serif, for headings) paired with Work Sans (sans-serif, for body text), loaded via Google Fonts
- **Zero dependencies** — no frameworks, build steps, or external image hosting; everything (including graphics) is inline SVG and CSS

## Tech Stack

| Layer | Technology |
|---|---|
| Markup | HTML5 |
| Styling | Vanilla CSS (custom properties, CSS Grid/Flexbox, 3D transforms) |
| Interactivity | Vanilla JavaScript (no libraries) |
| Fonts | Google Fonts (Fraunces, Work Sans) |
| Graphics | Inline SVG |

## Project Structure

```
sathyam-homes.html   # the entire site — HTML, CSS, and JS in one file
README.md            # this file
```

## Running Locally

No installation needed. Just open the file in a browser:

```bash
# clone the repo
git clone https://github.com/kavinirfan/greenbudswebpage.git
cd greenbudswebpage

# open directly
open sathyam-homes.html      # macOS
start sathyam-homes.html     # Windows
```

Or serve it locally for a closer-to-production feel:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000/sathyam-homes.html
```

## Deployment

This site is deployed on **Netlify**, connected directly to this GitHub repository. Every push to the `main` branch triggers an automatic redeploy — no build command needed since it's static HTML.

**Publish settings:**
- Build command: *(none)*
- Publish directory: `.`

## Notes

- Built as a single self-contained file by design, so it's easy to preview, share, or host anywhere without a build pipeline.
- The contact form is front-end only in this version; hook it up to a form backend (e.g. Netlify Forms) to make it functional.

---

Built with care, one section at a time.
