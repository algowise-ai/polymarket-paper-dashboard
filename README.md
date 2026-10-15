# Polymarket Paper Dashboard (static)

**Paper-only** equity monitor. No API keys, wallets, or live trading.

## Files

| File | Role |
|------|------|
| `index.html` | Dashboard (self-contained data + Chart.js) |
| `dashboard_data.json` | Same snapshot (optional; HTML already embeds data) |
| `vendor/chart.umd.min.js` | Offline Chart.js |

## Local preview

Open `index.html` in a browser (keep `vendor/` beside it).

## Hosting

Intended for **GitHub Pages** on a **public** repo (free). Rebuild on the Mac Mini, then sync this folder.

Do not commit `config/secrets/`, databases, or `.env` files.
