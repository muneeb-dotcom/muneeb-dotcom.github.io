# Muneeb Shahzad | Interactive 3D Portfolio

**Live site: [muneeb-dotcom.github.io](https://muneeb-dotcom.github.io)**

Explore the 3D worlds of my research projects: scroll through each one, drag the models, hover over any part and read what I found, including what I didn't. Turn the sound on for the full experience. Sound is opt-in, because browsers block autoplay.

🌐 **Portfolio:** [muneeb-dotcom.github.io](https://muneeb-dotcom.github.io) · explore my research as interactive 3D worlds (turn the sound on for the full experience)

## The 3D worlds

| World | What it covers | Code |
|---|---|---|
| Lumora | A serum and hydrogel patch for acne scars, tested in vitro | `lumora/` |
| Regeneration vs scarring | Mouse digit tips and skin wounds: shared genes and a larger network that flagged Gja1 | [regen-convergence-v2](https://github.com/muneeb-dotcom/regen-convergence-v2) |
| Bioelectricity | Simulating cell voltage after a wound | [bioelectric-sim](https://github.com/muneeb-dotcom/bioelectric-sim) |
| Aging | Mitonuclear imbalance and regeneration | [mito-aging-project](https://github.com/muneeb-dotcom/mito-aging-project) |
| PLP1 and the Twin | 371 PLP1 variants sorted by mechanism, plus a digital twin | [plp1-pmd-mechanism-mapping](https://github.com/muneeb-dotcom/plp1-pmd-mechanism-mapping), [plp1-pmd-digital-twin](https://github.com/muneeb-dotcom/plp1-pmd-digital-twin) |

A sixth project, in silico drug design for pulmonary fibrosis, links out to [its GitHub repo](https://github.com/muneeb-dotcom/Bioinformatics-Drug-Discovery-IPF).

## Repository layout

```text
index.html                 main portfolio (photo and song are embedded)
lumora/index.html          Lumora: serum + hydrogel patch for acne scars (in vitro)
regeneration/index.html    Regeneration vs scarring
bioelectricity/index.html  Bioelectric wound simulation
aging/index.html           Mitonuclear imbalance and aging
plp1/index.html            PLP1 variants and the digital twin
assets/                    source copies of the photo and the song
```

## Run locally

Open `index.html` in a browser. It needs an internet connection for fonts and three.js, which load from cdnjs.

## Notes

- Each 3D page is a single self-contained HTML file plus three.js from a CDN.
- The song is embedded in `index.html`. To swap it, replace the base64 string in the `SONG` variable.
- The "Ask the Twin" chat box on the PLP1 page only appears inside Claude. Everywhere else it stays hidden and the rest of the page works.

## Hosting

Served with GitHub Pages from the `main` branch, root folder (`.nojekyll` is included so files are served as-is).
