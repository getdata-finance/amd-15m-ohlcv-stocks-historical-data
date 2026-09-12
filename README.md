# AMD 15m OHLCV US stocks Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-35_283_rows-blue)](https://getdata.finance/datasets/amd) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/amd)

### -> [**Download the full AMD dataset on getdata.finance**](https://getdata.finance/datasets/amd)

**AMD 15m OHLCV stocks historical data** — ultra high-quality 15m OHLCV for **Advanced Micro Devices**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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

- **Ultra high-quality 15m OHLCV** for **Advanced Micro Devices** (US stocks)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`15m`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/amd) · **35,283** `15m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `15m` sample updated in sync

> **Sample on GitHub** · `AMD_15m.csv` (3,302 rows, `2026-03-12` -> `2026-09-11`, 301.06 KB). **Full archive on [getdata.finance](https://getdata.finance/datasets/amd)** — **35,283** `15m` rows (full `1m`: 525,821), **11 timeframes**, `2021-04-13` -> `2026-09-11`.

## Download sample

**[AMD_15m.csv](https://github.com/getdata-finance/amd-15m-ohlcv-stocks-historical-data/blob/main/AMD_15m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/amd-15m-ohlcv-stocks-historical-data/main/AMD_15m.csv)) · [GitHub Releases](https://github.com/getdata-finance/amd-15m-ohlcv-stocks-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/amd-15m-ohlcv-stocks-historical-data/](https://getdata-finance.github.io/amd-15m-ohlcv-stocks-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/amd](https://getdata.finance/datasets/amd)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/amd))** |
|---|--:|---|
| Instrument | Advanced Micro Devices · US stocks | Advanced Micro Devices · US stocks |
| Timeframes | `15m` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 15m rows | 3,302 | **35,283** |
| Size | 301.06 KB | full ZIP on [getdata.finance](https://getdata.finance/datasets/amd) |
| Period | `2026-03-12` -> `2026-09-11` | `2021-04-13` -> `2026-09-11` |
| File | `AMD_15m.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/amd) |
| Coverage report | — | [AMD coverage](https://getdata.finance/coverage/amd) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`15m` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/amd)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `15m` sample · [getdata.finance](https://getdata.finance/datasets/amd) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `15m` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`AMD_15m.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-03-12T13:30:00+00:00 | 204.38 | 204.38 | 200.27 | 200.8 | 3257 |
| 2026-03-12T13:45:00+00:00 | 200.8 | 200.8 | 197.76 | 198.28 | 4239 |
| 2026-03-12T14:00:00+00:00 | 198.28 | 200 | 198.28 | 199.81 | 4589 |
| 2026-03-12T14:15:00+00:00 | 199.81 | 199.92 | 198 | 198.07 | 3681 |
| 2026-03-12T14:30:00+00:00 | 198.07 | 198.41 | 197.39 | 197.91 | 3541 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-11T18:45:00+00:00 | 517.65 | 518.22 | 516.75 | 517.32 | 877 |
| 2026-09-11T19:00:00+00:00 | 517.32 | 517.32 | 515.11 | 516.25 | 1006 |
| 2026-09-11T19:15:00+00:00 | 516.25 | 517.28 | 515.32 | 516.09 | 965 |
| 2026-09-11T19:30:00+00:00 | 516.09 | 516.34 | 514.97 | 515.29 | 1116 |
| 2026-09-11T19:45:00+00:00 | 515.29 | 516.19 | 514.02 | 515.87 | 2204 |

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
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='15min')
print(pf.stats())
```

## Download full data

The complete **AMD** archive on **[getdata.finance](https://getdata.finance/datasets/amd)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **35,283** rows at `15m`, plus all other timeframes in the same ZIP.

**[-> Get the full AMD dataset on getdata.finance](https://getdata.finance/datasets/amd)**

---
*GetData · AMD 15m OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/amd)*
