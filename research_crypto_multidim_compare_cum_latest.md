# Crypto multi-dim compare — CUM

- Generated: **2026-10-28 18:10:01 HKT**
- Mode: **cum** (cumulative from first paper fill)
- Entry span: 2026-10-19 20:59 → 2026-10-28 17:35 HKT
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
- Entries kept: **14,394**
- Settled fills: **14,389** (for context only; not plotted as a metric)
- Realized PnL (sum of cells): **$-264.19**

### Top 12 cells (window × coin × px × HKT-hour)
| PnL | window | coin | px | HKT hour |
|---:|---|---|---|---:|
| $+2.28 | 5m | ETH | 85c | 07 |
| $+2.22 | 15m | BTC | 80c | 04 |
| $+2.19 | 15m | BNB | 83c | 07 |
| $+2.10 | 5m | ETH | 83c | 07 |
| $+2.00 | 5m | BTC | 83c | 11 |
| $+1.96 | 5m | BNB | 80c | 10 |
| $+1.96 | 5m | XRP | 83c | 04 |
| $+1.89 | 5m | ETH | 85c | 10 |
| $+1.81 | 5m | XRP | 83c | 05 |
| $+1.74 | 5m | XRP | 80c | 22 |
| $+1.74 | 15m | BTC | 83c | 10 |
| $+1.73 | 15m | HYPE | 80c | 06 |

### Bottom 8 cells
| PnL | window | coin | px | HKT hour |
|---:|---|---|---|---:|
| $-3.57 | 5m | DOGE | 85c | 11 |
| $-3.58 | 15m | XRP | 90c | 13 |
| $-3.65 | 5m | BTC | 85c | 06 |
| $-3.66 | 5m | BTC | 85c | 14 |
| $-3.79 | 15m | BNB | 80c | 01 |
| $-3.82 | 5m | DOGE | 80c | 19 |
| $-3.84 | 5m | SOL | 80c | 19 |
| $-5.30 | 5m | DOGE | 80c | 06 |

