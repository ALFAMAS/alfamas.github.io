# alfamas.dev

Personal site of **MAS Yasin Arafat**, a travel technology engineer in Sydney,
Australia. NDC/GDS integrations, payment systems, and full-stack TypeScript.

Live at **[alfamas.dev](https://alfamas.dev)**, hosted on GitHub Pages.

## Design

- A single static `index.html` with no build step, no frameworks, no external
  requests (fonts, styling, icons, and the favicon are all inline or system-provided)
- Dark by default with a light-mode toggle (persisted in `localStorage`)
- Sci-fi HUD styling: grid backdrop, glow accents, corner-bracket portrait
  frame, and scroll-reveal animations, all in plain CSS and ~40 lines of JS
- Accessible: semantic landmarks, skip link, visible focus states,
  `prefers-reduced-motion` respected
- Contact form via [Formspree](https://formspree.io) with a honeypot field

## Development

Open `index.html` in a browser, or serve it locally:

```bash
python3 -m http.server 8000
```

## License

[MIT](LICENSE)
