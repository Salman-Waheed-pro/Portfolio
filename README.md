# Portfolio

Personal site of Salman Waheed, software engineering student at TAMK (Tampere, Finland).

**Live:** https://salman-waheed-pro.github.io/Portfolio/

![Screenshot of the portfolio home page](assets/screenshot.jpg)

## What's here

- `index.html`: the whole site in one file, no framework or build step.
- `work/asten-coach-finder.html`: the interactive solution page from a workshop (journey, data model, a working filter-and-rank demo).
- `assets/mark.svg`: the logo, one flower whose stem is a growth curve.
- `assets/art/`: four public-domain paintings (Michelangelo, Hokusai, Friedrich, Van Gogh) from Wikimedia Commons.
- `assets/og.jpg`, `assets/screenshot.jpg`: social preview and README screenshot.
- `v1/` and `original/`: earlier versions of the site, kept as they were (served at `/Portfolio/v1/` and `/Portfolio/original/`, hidden from search engines).

The hero is the logo drawn in grains of sand: they settle into the flower, scatter under the pointer, and blow off to the right as you scroll. It respects `prefers-reduced-motion` (one still frame) and pauses off screen. In the work list, hovering a project raises a tilted browser screen: public projects click through, private ones scroll inside. Light and dark themes follow the system setting, with a manual toggle.

## Projects linked from the site

| Project | Code |
|---|---|
| Real Estate AI | [real-estate-ai](https://github.com/Salman-Waheed-pro/real-estate-ai) |
| Cloudberry Scout | [cloudberry-scout](https://github.com/Salman-Waheed-pro/cloudberry-scout) |
| SDLC governance (personal tool) | [govern-plugin](https://github.com/Salman-Waheed-pro/govern-plugin), [sdlc-governance-system](https://github.com/Salman-Waheed-pro/sdlc-governance-system) |
| Dewon Fried Chicken website | [Dewon-website](https://github.com/Salman-Waheed-pro/Dewon-website) |
| BeaconMed, Oppipolku, Artha | Private (client data); described on the site |

## Run locally

```bash
python -m http.server 8000
```

Then open http://localhost:8000.

## Deploy

GitHub Pages from the `main` branch root. Push to `main` and it updates.

## Contact

salman.waheed@tuni.fi
