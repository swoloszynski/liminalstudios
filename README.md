# liminalstudios

Static site for Liminal Studios, a practice under the [samdw.org](https://samdw.org) umbrella.

Live: https://liminalstudios.org

## Hosting

Hosted on GitHub Pages, deployed from the root of `main`. Every push to `main` rebuilds the site. The custom domain is set in `CNAME`.

## Files

- `index.html` — homepage
- `404.html` — not-found page
- `styles.css` — all styles; shares samdw.org's chassis (colors, borders, offset shadows, system fonts) with yellow as primary
- `public/logos/` — client logos, trimmed to their content

Design source: [Figma](https://www.figma.com/design/12vuRnodtvAnCHhc7hZlqf/Liminal-Studios-Website), page "Website design - current".

To preview locally:

```bash
python3 -m http.server 8765
```
