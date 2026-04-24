NASDAQ Data Quality Report

1. Source of Data
Provider: Yahoo Finance API (via yfinance Python library)
Market: NASDAQ
Data type: Historical daily stock prices (OHLCV)
Collection date:** April 2026

| Ticker | Company | Period |
|--------|---------|--------|
| AAPL | Apple Inc. | 1 year |
| MSFT | Microsoft Corp. | 6 months |
| GOOGL | Alphabet Inc. | 3 months |
| TSLA | Tesla Inc. | 9 months |
| NVDA | NVIDIA Corp. | 2 months |

2. KPI Results

| Ticker | Rows | Completeness | Latency | Accuracy | Consistency |
|--------|------|-------------|---------|----------|-------------|
| AAPL | 251 | 100% | 1 day | 100% | 100% |
| MSFT | 124 | 100% | 1 day | 100% | 100% |
| GOOGL | 62 | 100% | 1 day | 100% | 100% |
| TSLA | 189 | 100% | 1 day | 100% | 100% |
| NVDA | 42 | 100% | 1 day | 100% | 100% |

 3. Conclusion
All 5 datasets scored 100% across all KPIs. The data from Yahoo Finance is complete with no missing values, up to date with only 1 day latency, contains no outliers, and has no duplicate or negative values.
