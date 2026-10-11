# showfile.cold.fyi

The Show File - a cited field guide to how an electronic music show gets made. Static site: no build step, no database, no upkeep.

- `index.html` - the guide (27,000 words, 377 sources, 8 diagrams, timeline, crew list, advance checklist, 4 calculators, glossary)
- `glossary/` - standalone glossary page (216 terms)
- `glossary.json`, `timeline.json`, `resources.json`, `roles.json` - open data
- `fonts/` - self-hosted Big Shoulders Stencil, Source Serif 4, JetBrains Mono, Permanent Marker (SIL Open Font License)
- `robots.txt`, `sitemap.xml`, `llms.txt`, `og.png` - discovery

## Going live (one time)
1. GitHub: Settings → Pages → Deploy from a branch, `main`, `/ (root)`.
2. Namecheap → cold.fyi → Advanced DNS → CNAME: Host `showfile`, Value `richerd22.github.io.`
3. Confirm the custom domain reads `showfile.cold.fyi`, then tick Enforce HTTPS.

Photos are hotlinked from Flickr and PxHere under their CC licenses, credited in place; if a host is down the page shows a credit card instead.

made with <3 in boston
