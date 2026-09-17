# Brand Marketian — Portfolio

Standalone single-page portfolio site, deployed separately from the main
brandmarketian.com site.

- Live at: https://portfolio.brandmarketian.com
- Static HTML/CSS/JS, no build step — `site/index.html` is the whole page.
- Deployed via Cloudflare Workers Static Assets.

## Structure

- `site/` — the deployed page and its assets (`creators/`, `logos/`, `dashboards/`)
- `wrangler.jsonc` — Cloudflare Worker config, including the
  `portfolio.brandmarketian.com` custom domain route

## Deploy

```
npx wrangler deploy
```
