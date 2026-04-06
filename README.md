# High Bar Ranch — Fence Wire Price Tracker

A single-file HTML tool for comparing high-tensile woven wire fencing prices across two local Commerce City CO suppliers, with a roll/post calculator and material estimator.

## Features

- **Price table** — All confirmed high-carbon / high-tensile woven wire products from SWI Fence & Supply and Stockyard Ranch Supply, with direct product links
- **Price check** — Verifies supplier sites are reachable on open and records timestamp; prices persist via localStorage between sessions
- **Roll calculator** — Enter total linear feet OR pen dimensions; calculates rolls needed, overage, and total cost for any product in the table
- **T-post estimator** — Optimizes spacing between 8–11 ft based on fence line length for cleanest fit
- **Wooden post & brace calculator** — Estimates corner posts, H-brace assemblies, gate posts, and brace rails based on corners, inline braces, gates, and fence height

## Usage

No server required. Open `index.html` directly in any browser.

For GitHub Pages hosting:

1. Push to a GitHub repository
1. Enable GitHub Pages (Settings → Pages → Deploy from `main` branch)
1. Access at `https://yourusername.github.io/repo-name/`

Prices persist in `localStorage` — last verified timestamp is shown in the header and footer.

## Products Included

All products are confirmed **high-carbon / high-tensile** wire, **Class 3 or Zinc-Aluminum coated**. Standard Class 1 / low-carbon field fence is excluded.

|Supplier              |Products                                                                                                           |
|----------------------|-------------------------------------------------------------------------------------------------------------------|
|SWI Fence & Supply    |XtraLife 836, 1348 (3”/12” stay, 200’/330’/660’ roll), 1775 · Tornado 1147 Torus, 1348 Titan · Bekaert Horseman 2×4|
|Stockyard Ranch Supply|HT Field Fence 14ga (39”, 47”) · 72” MaxLoc · 78” HT Game Fence · 96” Max-Lock Game Fence                          |

## Notes

- **Both suppliers are local pickup** — no shipping costs apply
- SWI Fence prices are JavaScript-rendered; cart verification is required before ordering
- Stockyard prices are static page listings; call (303) 287-8081 to confirm
- Price check attempts a `no-cors` HEAD request to confirm sites are reachable; it does not scrape or auto-update prices. Manual verification before ordering is always required.

## Planned

- [ ] Visual pen diagram tool (separate repo/file)
- [ ] Gate sizing options in calculator
- [ ] Price history log

## Location

Stockyard Ranch Supply — 6990 US Hwy 85, Commerce City CO 80022 · M–F 8am–4:45pm

-----

*High Bar Ranch LLC · Larimer County, CO*
