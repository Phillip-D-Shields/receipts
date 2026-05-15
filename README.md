# She'll Be Right (Rich)

A single-page, data-driven infographic about wealth inequality in Aotearoa New Zealand. Built from official sources: Stats NZ, IRD, NBR Rich List.

## Stack

- One self-contained `index.html`
- Chart.js (loaded from jsDelivr) for the quintile and rich-list charts
- Google Fonts for typography
- No build step

## Local preview

Just open `index.html` in a browser. Or, if you want a proper localhost:

```
python3 -m http.server 8000
```

then visit `http://localhost:8000`.

## Deployment

Auto-deployed via Cloudflare Pages on push to `main`.

## Sources

All numbers cited in the page link to their public source in the "Receipts" footer. If a stat changes, update it in `index.html` and push.