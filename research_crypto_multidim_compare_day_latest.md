# Crypto multi-dim compare — DAY

- Generated: **2026-10-28 18:09:59 HKT**
- Mode: **day** (HKT calendar day 20261028)
- Entry span: 2026-10-28 00:05 → 2026-10-28 17:35 HKT
- Figure: `research_crypto_multidim_compare_day_20261028.png`
- PAPER ONLY — `out/trades/crypto_limit_*.json`
- Metric: **PnL$ only** (no fill-count panels or N labels)

## How to read

| Dimension | Where on the figure |
|---|---|
| **CRYPTO** | Outer **columns** (BTC / ETH / SOL / …) |
| **TIME WINDOW** | Outer **rows** (5m / 15m / 1h / 4h / daily) |
| **TRADING TIMEZONE** | Inner **X** = HKT entry hour **0–23** |
| **80–95¢** | Inner **Y** = limit_px (**95c→80c** top→bottom; labeled on left column) |
| **PnL $** | Cell color + label; blank = no settled fills. RdYlGn: darker green = higher +PnL$ (scale encodes magnitude). P03 picks prefer LIGHT green — do not treat dark green as better. |

## Totals

- Accounts scanned: **245**
- Entries kept: **515**
- Settled fills: **510** (for context only; not plotted as a metric)
- Realized PnL (sum of cells): **$-7.44**

### Top 12 cells (window × coin × px × HKT-hour)
| PnL | window | coin | px | HKT hour |
|---:|---|---|---|---:|
| $+0.52 | 5m | BTC | 80c | 06 |
| $+0.49 | 5m | HYPE | 80c | 03 |
| $+0.47 | 15m | HYPE | 80c | 00 |
| $+0.46 | 15m | BTC | 80c | 06 |
| $+0.44 | 5m | ETH | 90c | 03 |
| $+0.41 | 5m | ETH | 83c | 01 |
| $+0.39 | 15m | DOGE | 83c | 00 |
| $+0.39 | 15m | XRP | 83c | 05 |
| $+0.35 | 15m | HYPE | 85c | 05 |
| $+0.35 | 5m | BTC | 85c | 00 |
| $+0.35 | 5m | SOL | 85c | 05 |
| $+0.34 | 5m | DOGE | 90c | 06 |

### Bottom 8 cells
| PnL | window | coin | px | HKT hour |
|---:|---|---|---|---:|
| $-1.01 | 4h | ETH | 80c | 05 |
| $-1.02 | 15m | SOL | 80c | 02 |
| $-1.02 | 1h | BTC | 80c | 01 |
| $-1.02 | 1h | ETH | 80c | 00 |
| $-1.02 | 5m | SOL | 80c | 05 |
| $-1.82 | 5m | ETH | 83c | 05 |
| $-1.95 | 15m | BTC | 93c | 00 |
| $-2.03 | 15m | XRP | 80c | 00 |

