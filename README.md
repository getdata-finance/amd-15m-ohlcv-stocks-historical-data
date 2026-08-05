# AMD 15m OHLCV US stocks Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-34_529_rows-blue)](https://getdata.finance/datasets/amd) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/amd)

### -> [**Download the full AMD dataset on getdata.finance**](https://getdata.finance/datasets/amd)

**AMD 15m OHLCV us stocks historical data** — ultra high-quality 15m OHLCV for **AMD**. US equity cash and extended sessions — institutional-style OHLCV candles for US stocks. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [GitHub Pages preview](#github-pages)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on GetData](#timeframes-on-getdata)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Code examples](#code-examples)
- [Download full data on getdata.finance](#download-full-data-on-getdata)

## Why this dataset?

- **Ultra high-quality 15m OHLCV** for **AMD** (US stocks)
- **US equity cash and extended sessions — institutional-style OHLCV candles for US stocks**
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`15m`) · **9 timeframes** on [getdata.finance](https://getdata.finance/datasets/amd) · **34,529** `1m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `15m` sample updated in sync

> **Sample on GitHub** · `AMD_15m.csv` (3,250 rows, `2026-02-02` -> `2026-07-31`). **Full archive on [getdata.finance](https://getdata.finance/datasets/amd)** — **34,529** `1m` rows (~3.05 MB), **9 timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 12H · 3D · 1W), `2021-04-13` -> `2026-07-31`.

## Download sample

**[AMD_15m.csv](https://github.com/getdata-finance/amd-15m-ohlcv-stocks-historical-data/blob/main/AMD_15m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/amd-15m-ohlcv-stocks-historical-data/main/AMD_15m.csv)) · [GitHub Releases](https://github.com/getdata-finance/amd-15m-ohlcv-stocks-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/amd-15m-ohlcv-stocks-historical-data/](https://getdata-finance.github.io/amd-15m-ohlcv-stocks-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/amd](https://getdata.finance/datasets/amd)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/amd))** |
|---|--:|---|
| Instrument | AMD · US stocks | AMD · US stocks |
| Timeframes | `15m` (sample) | **9** — 1m · 3m · 5m · 15m · 30m · 1H · 12H · 3D · 1W |
| 1m rows | 3,250 | **34,529** |
| Size | 0.32 MB | ~3.05 MB |
| Period | `2026-02-02` -> `2026-07-31` | `2021-04-13` -> `2026-07-31` |
| File | `AMD_15m.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/amd) |
| Coverage report | — | [AMD coverage](https://getdata.finance/coverage/amd) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`15m` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/amd)**, each full asset archive is delivered as a ZIP with **9 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **12H** · **3D** · **1W**

GitHub = `15m` sample · [getdata.finance](https://getdata.finance/datasets/amd) = all **9** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `15m` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`AMD_15m.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-02-02T14:30:00+00:00 | 233.31 | 241.23 | 230.88 | 240.8 | 4984 |
| 2026-02-02T14:45:00+00:00 | 240.8 | 242.01 | 239.52 | 240.83 | 4133 |
| 2026-02-02T15:00:00+00:00 | 240.83 | 245.46 | 240.6 | 245.46 | 3943 |
| 2026-02-02T15:15:00+00:00 | 245.46 | 246.18 | 244.29 | 244.55 | 3162 |
| 2026-02-02T15:30:00+00:00 | 244.55 | 245.43 | 243.85 | 244.47 | 2913 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-07-31T18:45:00+00:00 | 488.3 | 488.95 | 486.46 | 487.39 | 1390 |
| 2026-07-31T19:00:00+00:00 | 487.39 | 487.92 | 485.41 | 485.87 | 1980 |
| 2026-07-31T19:15:00+00:00 | 485.87 | 486.8 | 485 | 486.7 | 2087 |
| 2026-07-31T19:30:00+00:00 | 486.7 | 487.01 | 482.66 | 484.08 | 2340 |
| 2026-07-31T19:45:00+00:00 | 484.08 | 486.59 | 475.73 | 476.49 | 3317 |

## Schema

| Column | Description |
| --- | --- |
| `datetime` | Bar open timestamp (UTC, ISO-8601). |
| `open` | Opening price of the candlestick bar. |
| `high` | Highest price during the bar. |
| `low` | Lowest price during the bar. |
| `close` | Closing price of the candlestick bar. |
| `volume` | Tick volume (number of price updates) during the bar. |

```text
datetime,open,high,low,close,volume
```

## Code examples

### pandas

```python
import pandas as pd

df = pd.read_csv('AMD_15m.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
print(df.resample('1h').agg({'open': 'first', 'high': 'max',
                              'low': 'min', 'close': 'last', 'volume': 'sum'}).head())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('AMD_15m.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)

class PandasData(bt.feeds.PandasData):
    params = (('datetime', None), ('open', 'open'), ('high', 'high'),
              ('low', 'low'), ('close', 'close'), ('volume', 'volume'))

cerebro = bt.Cerebro()
cerebro.adddata(PandasData(dataname=df))
# cerebro.addstrategy(YourStrategy)
# cerebro.run()
```

### vectorbt

```python
import pandas as pd
import vectorbt as vbt

df = pd.read_csv('AMD_15m.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='1min')
print(pf.stats())
```

## Download full data

The complete **AMD** archive on **[getdata.finance](https://getdata.finance/datasets/amd)** includes **9 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 12H · 3D · 1W) — **34,529** rows at `1m`, plus all other timeframes in the same ZIP.

**[-> Get the full AMD dataset on getdata.finance](https://getdata.finance/datasets/amd)**

---
*GetData · AMD 15m OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/amd) · 2026-08-05 UTC*
