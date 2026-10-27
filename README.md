# From first use to a business

Static visual learning website for coaching software and SaaS.

## Run
Serve this folder with any static HTTP server, for example `python3 -m http.server 8080`, then open the served URL. Opening index.html directly as a file will not load the JSON data.

## Publish
GitHub Pages, main branch, root directory. No build step or paid service required. Do not upload private notes or research records.

## Edit
- cards.json: lifecycle cards
- rails.json: business-rails comparisons
- sales.json: sales/team cards
- sources.json: source ledger and evidence limits
- app.js: rendering, filtering and local-only working lab
- style.css: responsive presentation
- PRD.md: design and acceptance brief
- notes.md: full editorial notes

No analytics, backend, account system or data upload. Working-lab edits stay in localStorage on the viewing browser. JSON import/export moves user-authored plans. The public repo contains only generic learning content and illustrative assumptions.
