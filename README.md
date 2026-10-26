# Portfolio

Personal site of Salman Waheed, software engineering student at TAMK (Tampere, Finland).

**Live:** https://salman-waheed-pro.github.io/Portfolio/

![Screenshot of the portfolio home page](assets/screenshot.jpg)

## What's here

- `index.html`: the current site, one file, no framework or build step.
- `assets/work/`: screenshots of the projects, shown inside each project's screen.
- `assets/vendor/`: d3-geo, topojson-client and world map data for the small globe (licences in `NOTICE.md`).
- `work/asten-coach-finder.html`: the interactive solution page from a workshop.
- `v1/`, `v2/`, `original/`: earlier versions, kept as they were and hidden from search engines.

The top of the page is a storm of sand lines. Calm builds while you hold still and drains when you move fast or scroll; as it builds, the sand gathers into a desert rose, a flower that only forms out of heat, wind and sand. It respects `prefers-reduced-motion` (one still frame) and pauses off screen. In the work list, opening a project raises a browser screen: public projects click through from the picture, private ones scroll for the details. Light and dark themes follow the system, with a toggle.

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
