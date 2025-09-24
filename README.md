# U.S. Equity Index — Intraday Breakout/Reversion (Public Artifacts)

## Equity Curve

![Portfolio Equity Curve](assets/images/equity_curve_portfolio_20250816_171726.png)

**Public artifacts only** (images & CSV summaries). No source code; NDA required for code review.

## At-a-Glance Performance

- **Sharpe Ratio**: ~1.56
- **Mean Daily Return**: ~0.0293% (0.000293)
- **Daily Volatility**: ~0.2992% (0.002992)
- **Total Return**: 17.13%
- **CAGR**: 10.29%
- **Maximum Drawdown**: -3.80%
- **Win Rate**: 53.92%
- **Profit Factor**: 1.27
- **Number of Trades**: 1,110
- **Trading Period**: Jan 2024 - Aug 2025 (549 days)
- **Start Equity**: $9,957.86
- **End Equity**: $11,664.11


## Performance Tables

### Strategy Performance
| Strategy | Trades | Total P&L |
|----------|--------|-----------|
| Strategy1      | 836    | $562.78   |
| Strategy2     | 274    | $2,064.28 |

### Symbol Performance
| Symbol | Trades | Total P&L |
|--------|--------|-----------|
| XLK     | 265    | $762.64   |
| XLF     | 157    | $500.77   |
| IWM     | 258    | $490.77   |
| QQQ     | 251    | $453.39   |
| SPY     | 179    | $419.50   |

### Hourly Performance
| Hour (NY) | Trades | Total P&L |
|-----------|--------|-----------|
| 10        | 771    | $95.95    |
| 11        | 193    | $1,363.57 |
| 12        | 114    | $854.25   |
| 13        | 26     | $147.73   |
| 14        | 5      | $126.31   |
| 15        | 1      | $39.26    |

## Trade Samples

| Date | Symbol | Side | Qty | Entry Time | Exit Time | P&L | R-Multiple |
|------|--------|------|-----|------------|-----------|-----|------------|
| 2024-01-02 | IWM | long | 16 | 15:00 | 15:45 | -$14.78 | -0.59 |
| 2024-01-02 | SPY | short | 82 | 16:32 | 16:45 | -$29.45 | -1.18 |
| 2024-01-03 | IWM | short | 28 | 15:00 | 15:02 | -$25.82 | -1.03 |
| 2024-01-03 | XLK | long | 181 | 16:27 | 16:33 | $36.81 | 1.47 |
| 2024-01-04 | XLK | short | 34 | 15:00 | 15:09 | -$25.64 | -1.03 |
| ... | ... | ... | ... | ... | ... | ... | ... |
| 2025-08-11 | IWM | long | 45 | 15:49 | 16:56 | $16.35 | 0.65 |
| 2025-08-12 | QQQ | short | 23 | 14:08 | 16:00 | -$3.45 | -0.14 |
| 2025-08-13 | SPY | long | 67 | 16:00 | 16:14 | -$17.15 | -0.69 |
| 2025-08-14 | XLK | short | 89 | 16:14 | 18:18 | $6.90 | 0.28 |
| 2025-08-14 | XLF | long | 156 | 18:18 | 18:18 | $0.00 | 0.00 |

*Full trade ledger available in CSV under assets/metrics/.*

## Files

### Key Artifacts
- `assets/images/equity_curve_portfolio_20250816_171726.png` - Portfolio equity curve visualization
- `assets/metrics/equity_compounded_20250816_171726.csv` - Time series of portfolio equity values
- `assets/metrics/trades_20250816_171726.csv` - Complete trade ledger (1,110 trades)
- `assets/metrics/summary_20250816_171726.txt` - Basic performance metrics
- `assets/metrics/summary_compounded_20250816_171726.txt` - Compounded performance metrics

### Performance Reports
- `assets/metrics/report_by_strategy_20250816_171726.csv` - Strategy-level performance breakdown
- `assets/metrics/report_by_symbol_20250816_171726.csv` - Symbol-level performance breakdown
- `assets/metrics/report_by_hour_20250816_171726.csv` - Hourly trading performance analysis

## Folder Preview

```
.
├─ assets/
│  ├─ images/
│  │  └─ equity_curve_portfolio_20250816_171726.png
│  └─ metrics/
│     ├─ equity_compounded_20250816_171726.csv
│     ├─ trades_20250816_171726.csv
│     ├─ summary_20250816_171726.txt
│     ├─ summary_compounded_20250816_171726.txt
│     ├─ report_by_strategy_20250816_171726.csv
│     ├─ report_by_symbol_20250816_171726.csv
│     └─ report_by_hour_20250816_171726.csv
├─ .gitattributes
├─ .gitignore
└─ README.md
```

## Contact

**Yuke Zhang** · New York, NY · yukez@seas.upenn.edu · For code review, NDA is required.

---

*This repository contains public artifacts only. Source code and implementation details are proprietary and require NDA for access.*
