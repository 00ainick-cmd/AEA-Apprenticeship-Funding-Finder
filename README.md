# AEA Apprenticeship Funding Finder

Interactive web tool for AEA member shops to find apprenticeship funding opportunities by state.

## What It Does

- Select your state → see all federal and state funding you qualify for
- Filter by category (tax credits, wage support, training, veteran programs)
- Click any program for plain-English details, eligibility, and how to apply
- See stacking examples showing total first-year value ($30K-$60K+ for veteran hires)
- Toggle veteran-specific programs on/off

## How It Works

Pure static site. No backend. All data lives in `data/grants.json`.

- `index.html` — single page app
- `css/style.css` — responsive design
- `js/app.js` — state selection, filtering, modals
- `data/grants.json` — structured grant database (10 federal programs, 15+ states)

## Deployment

Same pattern as AEA career map:
1. Push to GitHub
2. Aaron tests on AEA staging
3. Deploy to AEA website

Can also run standalone via GitHub Pages or any static host.

## Data Sources

Every program links to its .gov source URL. See `data/grants.json` → `verificationNeeded` for items flagged for pre-convention verification.

## Local Development

Just open `index.html` in a browser. No build step.

```bash
# Or use a local server for proper fetch() behavior
python3 -m http.server 8080
```

## Built For

AEA Convention 2026 (March 23-26, Dallas) — announced alongside the AEA/Fastport Registered Apprenticeship program launch and DOL signing ceremony.
