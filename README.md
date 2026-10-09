# Muneeb Shahzad: portfolio

Live portfolio with five interactive 3D research studies.

```
index.html                 main portfolio (photo and song are embedded)
lumora/index.html          Lumora: serum + hydrogel patch for acne scars (in vitro)
regeneration/index.html    Regeneration vs scarring
bioelectricity/index.html  Bioelectric wound simulation
aging/index.html           Mitonuclear imbalance and aging
plp1/index.html            PLP1 variants and the digital twin
assets/                    source copies of the photo and the song
```

## Put it online (GitHub Pages, free)

1. Create a **public** repository named `muneeb-dotcom.github.io`.
2. Upload everything in this folder (keep the folders as they are, include `.nojekyll`).
3. Repository **Settings > Pages > Build and deployment**: Source = *Deploy from a branch*, Branch = `main`, folder `/ (root)`.
4. After about a minute the site is live at `https://muneeb-dotcom.github.io`.

Any static host also works (Netlify Drop, Cloudflare Pages, Vercel): drag in this folder.

## Notes

- Open `index.html` in a browser to preview locally. Needs internet for fonts and three.js (loaded from cdnjs).
- The "Ask the Twin" chat box on the PLP1 page only appears inside Claude. Everywhere else it stays hidden and the rest of the page works.
- Sound is opt-in (browsers block autoplay). The song is embedded in `index.html`; to swap it, replace the base64 in the `SONG` variable.
- 3D pages are single self-contained HTML files plus three.js from a CDN.
