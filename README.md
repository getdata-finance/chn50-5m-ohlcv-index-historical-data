# CHN50 5m OHLCV Stock index Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-534_171_rows-blue)](https://getdata.finance/datasets/chn50) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/chn50)

### -> [**Download the full CHN50 dataset on getdata.finance**](https://getdata.finance/datasets/chn50)

**CHN50 5m OHLCV stock index historical data** — ultra high-quality 5m OHLCV for **China 50**. Global cash and extended index sessions — Asia, Europe and US coverage, not US-hours only. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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

- **Ultra high-quality 5m OHLCV** for **China 50** (Stock index)
- **Global cash and extended index sessions — Asia, Europe and US coverage, not US-hours only**
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`5m`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/chn50) · **534,171** `1m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `5m` sample updated in sync

> **Sample on GitHub** · `CHN50_5m.csv` (30,028 rows, `2026-02-02` -> `2026-07-31`). **Full archive on [getdata.finance](https://getdata.finance/datasets/chn50)** — **534,171** `1m` rows (~39.65 MB), **11 timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W), `2017-07-17` -> `2026-07-31`.

## Download sample

**[CHN50_5m.csv](https://github.com/getdata-finance/chn50-5m-ohlcv-index-historical-data/blob/main/CHN50_5m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/chn50-5m-ohlcv-index-historical-data/main/CHN50_5m.csv)) · [GitHub Releases](https://github.com/getdata-finance/chn50-5m-ohlcv-index-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/chn50-5m-ohlcv-index-historical-data/](https://getdata-finance.github.io/chn50-5m-ohlcv-index-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/chn50](https://getdata.finance/datasets/chn50)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/chn50))** |
|---|--:|---|
| Instrument | China 50 · Stock index | China 50 · Stock index |
| Timeframes | `5m` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 1m rows | 30,028 | **534,171** |
| Size | 2.58 MB | ~39.65 MB |
| Period | `2026-02-02` -> `2026-07-31` | `2017-07-17` -> `2026-07-31` |
| File | `CHN50_5m.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/chn50) |
| Coverage report | — | [CHN50 coverage](https://getdata.finance/coverage/chn50) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`5m` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/chn50)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **4H** · **12H** · **1D** · **3D** · **1W**

GitHub = `5m` sample · [getdata.finance](https://getdata.finance/datasets/chn50) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `5m` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`CHN50_5m.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-02-02T01:00:00+00:00 | 15025.43 | 15026.73 | 15007.21 | 15013.72 | 271.3154780771 |
| 2026-02-02T01:05:00+00:00 | 15013.72 | 15016.73 | 14976.22 | 14976.72 | 312 |
| 2026-02-02T01:10:00+00:00 | 14976.72 | 14991.73 | 14976.71 | 14989.21 | 313 |
| 2026-02-02T01:15:00+00:00 | 14989.21 | 15012.21 | 14977.71 | 14984.21 | 1643 |
| 2026-02-02T01:20:00+00:00 | 14984.21 | 14985.73 | 14952.72 | 14964.73 | 1470 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-07-31T20:20:00+00:00 | 14813.05 | 14813.55 | 14811.05 | 14812.53 | 17 |
| 2026-07-31T20:25:00+00:00 | 14812.53 | 14813.05 | 14811.04 | 14812.04 | 23 |
| 2026-07-31T20:30:00+00:00 | 14812.04 | 14820.05 | 14811.03 | 14820.05 | 40 |
| 2026-07-31T20:35:00+00:00 | 14820.05 | 14821.05 | 14818.03 | 14821.03 | 47 |
| 2026-07-31T20:40:00+00:00 | 14821.03 | 14821.04 | 14816.54 | 14819.03 | 49 |

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

df = pd.read_csv('CHN50_5m.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
print(df.resample('1h').agg({'open': 'first', 'high': 'max',
                              'low': 'min', 'close': 'last', 'volume': 'sum'}).head())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('CHN50_5m.csv', parse_dates=['datetime'])
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

df = pd.read_csv('CHN50_5m.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='1min')
print(pf.stats())
```

## Download full data

The complete **CHN50** archive on **[getdata.finance](https://getdata.finance/datasets/chn50)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **534,171** rows at `1m`, plus all other timeframes in the same ZIP.

**[-> Get the full CHN50 dataset on getdata.finance](https://getdata.finance/datasets/chn50)**

---
*GetData · CHN50 5m OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/chn50) · 2026-08-04 UTC*
