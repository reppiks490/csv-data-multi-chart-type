# csv-data-multi-chart-type

Do not train from the zip blob. Address series as:

```
{asset_class}/{asset}/{chart_type}/{timeframe}/{schema}/{venue}__v{n}.csv
```

Canonical assets match Icarus: NQ, ES, YM, GC, SI, PL, PA, BTC, BTCF, ETH, AAPL, MSFT, NVDA, META, GOOGL, MAG7, VIX, VXN, DXY, TNX.

Chart types: minutes, hours, seconds, tick, range, daily, weekly.
Timeframes: 1m, 5m, 1h, 4h, 1000t, 10r, 1s, 1d, …
Schemas: ohlcv, ohlc, ohlc_profile_signals, close_profile_signals, close_only.

Cash index / CFD / future for the same tape are sibling venues under one asset (e.g. NQ = cme_nq1 + nasdaq_ndx + skilling_us100).

Source zip still in this repo: `Csv indexes.zip`.
The other three archives live in `reppiks490/multi-level-csv`.
Query a MANIFEST rather than walking files.

## License and ownership

Copyright (c) 2026 reppiks490. **Proprietary — all rights reserved.**
Public visibility does not grant permission to reuse, redistribute, sell, or claim this work as your own. Written permission is required except where applicable law, existing grants, third-party terms, or GitHub's terms provide otherwise. See [LICENSE.md](LICENSE.md) for the full notice and permission requests.
