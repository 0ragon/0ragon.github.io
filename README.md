# 0ragon.github.io

Public GitHub Pages site hosting interactive HTML reports from the (private) Megara knowledge vault.

**Live:** https://0ragon.github.io/

## Structure

```
index.html              # landing page / gallery — add one <a> block per report
<report-name>/
└── index.html           # a self-contained report → served at /<report-name>/
```

## Adding a report

1. Create a folder `<report-name>/` and drop the report in as `index.html`.
2. Add a card linking to `<report-name>/` in the root `index.html`.
3. Commit and push to `main` — GitHub Pages redeploys automatically.

Reports are self-contained static HTML (CDN-loaded Tailwind / Chart.js), so there is no build step.

> Source notes for these reports live in the private `megara` vault, not here.
