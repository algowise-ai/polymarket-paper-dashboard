# Crypto multi-dim compare — CUM

- Generated: **2026-10-24 00:03:21 HKT**
- Mode: **cum** (cumulative from first paper fill)
- Entry span: 2026-10-19 20:59 → 2026-10-21 23:37 HKT
- Figure: `research_crypto_multidim_compare_cum.png`
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
- Entries kept: **9,877**
- Settled fills: **9,877** (for context only; not plotted as a metric)
- Realized PnL (sum of cells): **$-119.98**

### Top 12 cells (window × coin × px × HKT-hour)
| PnL | window | coin | px | HKT hour |
|---:|---|---|---|---:|
| $+1.97 | 15m | XRP | 80c | 07 |
| $+1.79 | 5m | XRP | 80c | 10 |
| $+1.73 | 15m | HYPE | 80c | 06 |
| $+1.71 | 5m | DOGE | 80c | 09 |
| $+1.57 | 5m | DOGE | 80c | 07 |
| $+1.55 | 5m | ETH | 85c | 07 |
| $+1.52 | 5m | BNB | 80c | 10 |
| $+1.49 | 5m | XRP | 80c | 22 |
| $+1.49 | 5m | BTC | 80c | 23 |
| $+1.46 | 15m | ETH | 80c | 15 |
| $+1.46 | 5m | SOL | 80c | 10 |
| $+1.45 | 5m | BTC | 80c | 22 |

### Bottom 8 cells
| PnL | window | coin | px | HKT hour |
|---:|---|---|---|---:|
| $-3.04 | 15m | ETH | 80c | 23 |
| $-3.33 | 5m | BTC | 85c | 06 |
| $-3.35 | 5m | SOL | 80c | 15 |
| $-3.42 | 15m | XRP | 83c | 13 |
| $-3.57 | 15m | XRP | 85c | 13 |
| $-3.60 | 15m | XRP | 88c | 13 |
| $-3.68 | 15m | XRP | 90c | 13 |
| $-3.85 | 5m | BTC | 85c | 14 |

