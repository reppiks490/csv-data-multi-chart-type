# Maintainer workspace

> [!CAUTION]
> **PROPRIETARY — ALL RIGHTS RESERVED**
>
> **No public license or personal-use license is granted.** Except where [LICENSE.md](LICENSE.md) preserves applicable law, GitHub platform rights, third-party terms, or prior valid permissions, written authorization is required to use, run, copy, modify, redistribute, or sell covered material. Do not remove ownership notices or claim this work as your own.
>
> Unauthorized infringement may lead to takedown requests and legal proceedings for available remedies. Public visibility is not permission to reuse.

This workspace is maintained for its owner and authorized collaborators. Permission requests and the full terms are in [LICENSE.md](LICENSE.md).

<details>
<summary>Maintainer documentation</summary>

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

</details>
