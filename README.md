# Atelier Maram — Portfolio Site

A single-page portfolio for an architectural and digital art studio. Editorial gallery aesthetic with a Middle Eastern visual identity: navy `#1B2A4A`, ember `#D94F2B`, and an off-white `#F5F0EB` base, paired with a serif display face, a condensed sans, and bilingual English/Arabic typography.

## Run locally

It's a static site — open `index.html` in a browser, or serve it:

```bash
python -m http.server 8000
# then visit http://localhost:8000
```

## Structure

- `index.html` — markup, styles, and behavior in one file
- Fonts via Google Fonts (Cormorant Garamond, Barlow Condensed, Amiri)
- Imagery from Unsplash; one demo video from Mixkit

## Sections

1. Sticky header with wordmark + category filter
2. Hero (navy, diamond pattern at 8% opacity)
3. Selected Work — masonry-style CSS grid, hover overlays, JS-driven category filter
4. About — portrait, bilingual bio, clients, press, talks, exhibitions
5. Footer — studio address, contact, socials
