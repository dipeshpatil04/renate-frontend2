# Renate AI — Frontend Task

Static frontend build of the Renate AI landing page, based on the provided Figma design.

## Structure
```
index.html   — page markup (navbar, hero, feature sections, footer)
style.css    — all styling
script.js    — tab-switcher logic for the "Everything A Recruiter Needs" section
assets/      — images used on the page
```

## Run it
No build step needed. Either:
- Open `index.html` directly in a browser, or
- Run a local server from this folder, e.g. `npx serve` or VS Code's "Live Server" extension, then visit the shown localhost URL.

## Notes
- Built for desktop widths (1200px+). Not optimized for mobile.
- The tab switcher (Job Upload / AI Screening / Ranking / Insights / Pipeline / Analytics) is functional — clicking a tab swaps the panel below.
- No backend — all data shown is static/mock content matching the design.
