# DEAL

*He wrote the book. This is the deal.*

A seven-part sourced series examining the convergence of exposure, leverage, and power shaping American foreign policy in real time.

423 sourced links. 90+ outlets. Seven installments.

## Reading the series

Open `index.html` in a browser, or visit the hosted version at `https://yourusername.github.io/deal/`

Navigate between installments using the Contents menu or the previous/next links at the bottom of each page.

## Structure

```
index.html          — Main reader (renders all markdown)
visual.html         — Visual overview (standalone interactive page)
md/
  deal-series-overview.md
  the-closing.md
  the-underwriters.md
  the-co-signers.md
  the-counterparties.md
  the-hedge.md
  the-collateral.md
  the-handshake.md
```

## Hosting

This site is designed for GitHub Pages. Enable Pages in your repo settings (Settings → Pages → Deploy from branch → main → root) and the site will be live at `https://yourusername.github.io/deal/`.

The site has two external dependencies loaded via CDN:
- Google Fonts (Source Serif 4, Libre Franklin)
- marked.js (markdown parser)

No build step required.
