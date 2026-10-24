# Research: Trading-hours heatmaps — CUM

- Generated: **2026-10-24 00:03:14 HKT**
- Mode: **cum** (all history from first paper fill)
- Entry span: 2026-10-15 19:20 → 2026-10-23 23:27 HKT
- Timestamp: ENTRY `opened_at` → Asia/Hong_Kong
- PAPER ONLY — `out/trades/*.json`

## Overall

| system | accounts | N settled | WR | PnL | open |
|---|---:|---:|---:|---:|---:|
| dual-wing | 13 | 374 | 66.0% | $-841.07 | 254 |
| crypto | 245 | 9877 | 86.9% | $-119.99 | 0 |
| finance | 196 | 0 | — | $0.00 | 0 |

## Primary sessions (HKT entry)

### Crypto
| session | N | WR | PnL |
|---|---:|---:|---:|
| Asia night | 2953 | 87.0% | $-31.62 |
| Asia morning | 2311 | 89.0% | +$26.09 |
| Asia afternoon | 1915 | 85.0% | $-65.10 |
| US pre-open / EU | 1352 | 86.2% | $-28.37 |
| US cash evening | 1346 | 86.9% | $-20.99 |

### Dual-wing
| session | N | WR | PnL |
|---|---:|---:|---:|
| Asia night | 188 | 68.6% | $-259.59 |
| Asia morning | 62 | 62.9% | $-182.97 |
| Asia afternoon | 54 | 63.0% | $-168.27 |
| US pre-open / EU | 50 | 68.0% | $-18.42 |
| US cash evening | 20 | 55.0% | $-211.82 |

## Crypto pivots

### By window
| window | N | WR | PnL |
|---|---:|---:|---:|
| 5m | 5049 | 86.5% | $-99.32 |
| 15m | 3637 | 87.2% | $-20.76 |
| 1h | 860 | 89.2% | +$12.73 |
| 4h | 282 | 81.6% | $-18.66 |
| daily | 49 | 98.0% | +$6.02 |

### By limit_px
| px | N | WR | PnL |
|---|---:|---:|---:|
| 80c | 1429 | 78.6% | $-34.59 |
| 83c | 1359 | 81.4% | $-34.32 |
| 85c | 1419 | 83.7% | $-28.57 |
| 88c | 1421 | 87.0% | $-19.54 |
| 90c | 1363 | 89.3% | $-11.82 |
| 93c | 1412 | 93.6% | +$9.61 |
| 95c | 1474 | 94.7% | $-0.76 |

### Top 10 crypto accounts
| account | N | WR | PnL |
|---|---:|---:|---:|
| `crypto_limit_ethereum_5m_93c` | 128 | 96.9% | +$5.51 |
| `crypto_limit_bitcoin_5m_90c` | 121 | 93.4% | +$4.57 |
| `crypto_limit_ethereum_15m_90c` | 79 | 94.9% | +$4.19 |
| `crypto_limit_bnb_5m_95c` | 116 | 98.3% | +$4.08 |
| `crypto_limit_ethereum_15m_88c` | 73 | 93.2% | +$4.02 |
| `crypto_limit_bnb_15m_83c` | 73 | 87.7% | +$3.82 |
| `crypto_limit_solana_15m_93c` | 74 | 97.3% | +$3.53 |
| `crypto_limit_ethereum_15m_93c` | 71 | 97.2% | +$3.50 |
| `crypto_limit_bnb_15m_85c` | 74 | 89.2% | +$3.46 |
| `crypto_limit_hyperliquid_5m_85c` | 76 | 89.5% | +$3.39 |

### Bottom 10 crypto accounts
| account | N | WR | PnL |
|---|---:|---:|---:|
| `crypto_limit_solana_5m_83c` | 114 | 74.6% | $-12.43 |
| `crypto_limit_solana_5m_80c` | 111 | 73.0% | $-10.57 |
| `crypto_limit_dogecoin_5m_80c` | 106 | 73.6% | $-9.10 |
| `crypto_limit_dogecoin_5m_95c` | 127 | 88.2% | $-8.94 |
| `crypto_limit_bitcoin_5m_83c` | 103 | 76.7% | $-8.48 |
| `crypto_limit_xrp_5m_88c` | 116 | 81.9% | $-8.42 |
| `crypto_limit_dogecoin_15m_90c` | 75 | 80.0% | $-8.38 |
| `crypto_limit_bitcoin_5m_85c` | 104 | 78.8% | $-8.01 |
| `crypto_limit_solana_5m_85c` | 112 | 79.5% | $-7.78 |
| `crypto_limit_dogecoin_5m_83c` | 84 | 77.4% | $-6.32 |

## Dual-wing books
| book | N | WR | PnL |
|---|---:|---:|---:|
| NFL B-1 | 30 | 73.3% | +$70.92 |
| NFL B-2 | 30 | 70.0% | $-51.83 |
| NFL B-3 | 30 | 66.7% | $-73.60 |
| NBA B-1 | 40 | 55.0% | $-178.38 |
| NBA B-2 | 30 | 60.0% | $-55.87 |
| NBA B-3 | 28 | 64.3% | $-55.93 |
| MLB B-1 | 4 | 75.0% | $-2.12 |
| MLB B-2 | 4 | 50.0% | $-49.27 |
| MLB B-3 | 4 | 50.0% | $-42.59 |
| NCAAF B-1 | 28 | 64.3% | $-105.83 |
| NCAAF B-2 | 16 | 56.2% | $-126.05 |
| NHL B-1 | 88 | 72.7% | +$47.61 |
| Soccer B-1 | 42 | 66.7% | $-218.12 |

## Finance
N settled=0, open=0, PnL=$0.00 across 196 cells.

## Verification

- **nan_check**: passed
- **crypto_accounts**: 245
- **crypto_skipped**: []
- **dual_accounts**: 13
- **finance_accounts**: 196
- **dual_n**: 374
- **dual_pnl**: -841.0711
- **crypto_n**: 9877
- **crypto_pnl**: -119.9935
- **finance_n**: 0
- **finance_pnl**: 0.0
- **first_entry_hkt**: 2026-10-15T19:20:58+08:00
- **last_entry_hkt**: 2026-10-23T23:27:45+08:00

