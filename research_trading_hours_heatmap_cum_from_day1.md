# Research: Trading-hours heatmaps — CUM

- Generated: **2026-10-28 18:09:51 HKT**
- Mode: **cum** (all history from first paper fill)
- Entry span: 2026-10-15 19:20 → 2026-10-28 17:35 HKT
- Timestamp: ENTRY `opened_at` → Asia/Hong_Kong
- PAPER ONLY — `out/trades/*.json`

## Overall

| system | accounts | N settled | WR | PnL | open |
|---|---:|---:|---:|---:|---:|
| dual-wing | 13 | 910 | 65.3% | $-1,268.18 | 42 |
| crypto | 245 | 14389 | 86.4% | $-264.20 | 5 |
| finance | 196 | 0 | — | $0.00 | 0 |

## Primary sessions (HKT entry)

### Crypto
| session | N | WR | PnL |
|---|---:|---:|---:|
| Asia night | 4769 | 85.9% | $-111.15 |
| Asia morning | 3522 | 87.6% | $-13.28 |
| Asia afternoon | 2386 | 84.9% | $-88.03 |
| US pre-open / EU | 1863 | 85.0% | $-69.32 |
| US cash evening | 1849 | 89.0% | +$17.58 |

### Dual-wing
| session | N | WR | PnL |
|---|---:|---:|---:|
| Asia night | 376 | 67.5% | $-454.42 |
| Asia morning | 156 | 60.9% | $-549.59 |
| Asia afternoon | 180 | 60.6% | $-614.43 |
| US pre-open / EU | 144 | 68.1% | +$293.47 |
| US cash evening | 54 | 70.4% | +$56.79 |

## Crypto pivots

### By window
| window | N | WR | PnL |
|---|---:|---:|---:|
| 5m | 7043 | 86.0% | $-183.91 |
| 15m | 5344 | 86.5% | $-83.52 |
| 1h | 1382 | 88.9% | +$18.60 |
| 4h | 571 | 84.1% | $-21.39 |
| daily | 49 | 98.0% | +$6.02 |

### By limit_px
| px | N | WR | PnL |
|---|---:|---:|---:|
| 80c | 2078 | 77.8% | $-72.68 |
| 83c | 1990 | 81.9% | $-38.20 |
| 85c | 2079 | 82.7% | $-65.73 |
| 88c | 2016 | 86.4% | $-42.35 |
| 90c | 1993 | 88.6% | $-32.77 |
| 93c | 2053 | 92.6% | $-6.79 |
| 95c | 2180 | 94.5% | $-5.68 |

### Top 10 crypto accounts
| account | N | WR | PnL |
|---|---:|---:|---:|
| `crypto_limit_bitcoin_5m_90c` | 173 | 93.1% | +$5.85 |
| `crypto_limit_ethereum_5m_93c` | 186 | 95.7% | +$5.50 |
| `crypto_limit_hyperliquid_5m_85c` | 101 | 90.1% | +$5.20 |
| `crypto_limit_bnb_15m_83c` | 103 | 87.4% | +$4.92 |
| `crypto_limit_bnb_5m_95c` | 143 | 97.9% | +$4.53 |
| `crypto_limit_ethereum_5m_95c` | 197 | 97.0% | +$4.50 |
| `crypto_limit_bnb_5m_90c` | 119 | 93.3% | +$4.32 |
| `crypto_limit_hyperliquid_5m_88c` | 104 | 91.3% | +$4.11 |
| `crypto_limit_bnb_1h_83c` | 19 | 100.0% | +$3.86 |
| `crypto_limit_solana_15m_93c` | 119 | 95.8% | +$3.75 |

### Bottom 10 crypto accounts
| account | N | WR | PnL |
|---|---:|---:|---:|
| `crypto_limit_solana_5m_83c` | 169 | 75.1% | $-17.22 |
| `crypto_limit_solana_5m_80c` | 159 | 72.3% | $-16.66 |
| `crypto_limit_solana_5m_85c` | 165 | 77.0% | $-16.45 |
| `crypto_limit_bitcoin_5m_85c` | 160 | 77.5% | $-14.86 |
| `crypto_limit_dogecoin_5m_80c` | 141 | 73.0% | $-13.11 |
| `crypto_limit_bitcoin_5m_83c` | 157 | 77.7% | $-10.96 |
| `crypto_limit_dogecoin_15m_90c` | 108 | 81.5% | $-10.34 |
| `crypto_limit_xrp_5m_88c` | 156 | 82.7% | $-9.78 |
| `crypto_limit_solana_5m_90c` | 157 | 84.7% | $-9.56 |
| `crypto_limit_dogecoin_5m_83c` | 118 | 77.1% | $-9.25 |

## Dual-wing books
| book | N | WR | PnL |
|---|---:|---:|---:|
| NFL B-1 | 56 | 69.6% | +$0.60 |
| NFL B-2 | 56 | 69.6% | $-104.87 |
| NFL B-3 | 56 | 66.1% | $-65.22 |
| NBA B-1 | 112 | 58.0% | $-69.60 |
| NBA B-2 | 90 | 62.2% | $-69.99 |
| NBA B-3 | 86 | 65.1% | $-16.37 |
| MLB B-1 | 12 | 75.0% | +$33.98 |
| MLB B-2 | 11 | 63.6% | $-25.74 |
| MLB B-3 | 11 | 63.6% | $-1.07 |
| NCAAF B-1 | 92 | 63.0% | $-272.48 |
| NCAAF B-2 | 84 | 63.1% | $-77.30 |
| NHL B-1 | 146 | 68.5% | $-367.60 |
| Soccer B-1 | 98 | 69.4% | $-232.53 |

## Finance
N settled=0, open=0, PnL=$0.00 across 196 cells.

## Verification

- **nan_check**: passed
- **crypto_accounts**: 245
- **crypto_skipped**: []
- **dual_accounts**: 13
- **finance_accounts**: 196
- **dual_n**: 910
- **dual_pnl**: -1268.1807
- **crypto_n**: 14389
- **crypto_pnl**: -264.2044
- **finance_n**: 0
- **finance_pnl**: 0.0
- **first_entry_hkt**: 2026-10-15T19:20:58+08:00
- **last_entry_hkt**: 2026-10-28T17:35:38+08:00

