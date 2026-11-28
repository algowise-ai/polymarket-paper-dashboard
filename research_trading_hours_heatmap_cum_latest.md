# Research: Trading-hours heatmaps — CUM

- Generated: **2026-10-30 18:03:33 HKT**
- Mode: **cum** (all history from first paper fill)
- Entry span: 2026-10-15 19:20 → 2026-10-30 17:06 HKT
- Timestamp: ENTRY `opened_at` → Asia/Hong_Kong
- PAPER ONLY — `out/trades/*.json`

## Overall

| system | accounts | N settled | WR | PnL | open |
|---|---:|---:|---:|---:|---:|
| dual-wing | 13 | 1044 | 65.8% | $-1,176.44 | 96 |
| crypto | 245 | 19122 | 86.1% | $-424.61 | 0 |
| finance | 196 | 0 | — | $0.00 | 0 |

## Primary sessions (HKT entry)

### Crypto
| session | N | WR | PnL |
|---|---:|---:|---:|
| Asia night | 6884 | 85.0% | $-236.84 |
| Asia morning | 4174 | 87.8% | $-10.57 |
| Asia afternoon | 2734 | 84.9% | $-100.04 |
| US pre-open / EU | 2921 | 85.2% | $-102.53 |
| US cash evening | 2409 | 89.0% | +$25.37 |

### Dual-wing
| session | N | WR | PnL |
|---|---:|---:|---:|
| Asia night | 404 | 67.6% | $-549.25 |
| Asia morning | 170 | 62.4% | $-465.33 |
| Asia afternoon | 210 | 61.4% | $-512.15 |
| US pre-open / EU | 154 | 68.2% | +$317.13 |
| US cash evening | 106 | 69.8% | +$33.15 |

## Crypto pivots

### By window
| window | N | WR | PnL |
|---|---:|---:|---:|
| 5m | 9233 | 85.8% | $-265.31 |
| 15m | 7190 | 85.9% | $-162.71 |
| 1h | 1815 | 87.8% | $-0.04 |
| 4h | 833 | 87.3% | $-2.80 |
| daily | 51 | 98.0% | +$6.25 |

### By limit_px
| px | N | WR | PnL |
|---|---:|---:|---:|
| 80c | 2732 | 77.8% | $-95.19 |
| 83c | 2667 | 81.4% | $-66.14 |
| 85c | 2717 | 82.6% | $-87.51 |
| 88c | 2644 | 85.9% | $-68.97 |
| 90c | 2719 | 88.2% | $-58.98 |
| 93c | 2749 | 92.1% | $-25.35 |
| 95c | 2894 | 94.1% | $-22.47 |

### Top 10 crypto accounts
| account | N | WR | PnL |
|---|---:|---:|---:|
| `crypto_limit_bnb_5m_95c` | 177 | 97.7% | +$5.27 |
| `crypto_limit_ethereum_5m_95c` | 249 | 96.8% | +$5.16 |
| `crypto_limit_hyperliquid_5m_88c` | 135 | 91.1% | +$4.73 |
| `crypto_limit_ethereum_1h_80c` | 75 | 85.3% | +$4.55 |
| `crypto_limit_bnb_1h_83c` | 22 | 100.0% | +$4.45 |
| `crypto_limit_ethereum_5m_93c` | 238 | 94.5% | +$3.95 |
| `crypto_limit_bnb_5m_90c` | 153 | 92.2% | +$3.56 |
| `crypto_limit_ethereum_15m_88c` | 152 | 90.1% | +$3.31 |
| `crypto_limit_solana_15m_88c` | 129 | 89.9% | +$2.63 |
| `crypto_limit_bitcoin_5m_90c` | 234 | 91.0% | +$2.48 |

### Bottom 10 crypto accounts
| account | N | WR | PnL |
|---|---:|---:|---:|
| `crypto_limit_solana_5m_85c` | 211 | 77.2% | $-20.27 |
| `crypto_limit_bitcoin_5m_85c` | 215 | 78.6% | $-17.04 |
| `crypto_limit_solana_5m_83c` | 219 | 77.6% | $-15.74 |
| `crypto_limit_bitcoin_5m_83c` | 216 | 77.8% | $-14.96 |
| `crypto_limit_ethereum_5m_80c` | 207 | 75.4% | $-13.61 |
| `crypto_limit_dogecoin_5m_80c` | 181 | 74.6% | $-13.40 |
| `crypto_limit_solana_5m_80c` | 204 | 75.5% | $-13.12 |
| `crypto_limit_xrp_15m_90c` | 162 | 83.3% | $-12.03 |
| `crypto_limit_ethereum_5m_88c` | 226 | 83.6% | $-11.88 |
| `crypto_limit_ethereum_5m_83c` | 210 | 79.0% | $-11.47 |

## Dual-wing books
| book | N | WR | PnL |
|---|---:|---:|---:|
| NFL B-1 | 58 | 69.0% | $-29.08 |
| NFL B-2 | 58 | 70.7% | $-73.92 |
| NFL B-3 | 58 | 65.5% | $-94.90 |
| NBA B-1 | 138 | 58.7% | $-176.24 |
| NBA B-2 | 118 | 64.4% | +$6.39 |
| NBA B-3 | 108 | 66.7% | +$87.07 |
| MLB B-1 | 14 | 78.6% | +$64.48 |
| MLB B-2 | 13 | 69.2% | +$20.00 |
| MLB B-3 | 13 | 61.5% | $-21.03 |
| NCAAF B-1 | 100 | 63.0% | $-321.70 |
| NCAAF B-2 | 90 | 62.2% | $-147.76 |
| NHL B-1 | 164 | 68.3% | $-381.14 |
| Soccer B-1 | 112 | 71.4% | $-108.62 |

## Finance
N settled=0, open=0, PnL=$0.00 across 196 cells.

## Verification

- **nan_check**: passed
- **crypto_accounts**: 245
- **crypto_skipped**: []
- **dual_accounts**: 13
- **finance_accounts**: 196
- **dual_n**: 1044
- **dual_pnl**: -1176.4444
- **crypto_n**: 19122
- **crypto_pnl**: -424.6055
- **finance_n**: 0
- **finance_pnl**: 0.0
- **first_entry_hkt**: 2026-10-15T19:20:58+08:00
- **last_entry_hkt**: 2026-10-30T17:06:07+08:00

