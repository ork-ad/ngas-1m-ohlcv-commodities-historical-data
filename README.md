# NGAS 1m OHLCV Commodities Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-4_066_225_rows-blue)](https://ork.ad/) [![Updated](https://img.shields.io/badge/weekly_update-every_Sunday-green)]() [![Full data on ork.ad](https://img.shields.io/badge/download-ork.ad-orange)](https://ork.ad/)

### → [**Download the full NGAS dataset on ork.ad**](https://ork.ad/)

**NGAS 1m OHLCV Commodities historical data** — ultra high-quality one-minute OHLCV for **Natural Gas**. Extended-session energy and industrial metals — beyond US cash hours. Clean `time, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [GitHub Pages preview](#github-pages)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on ork.ad](#timeframes-on-orkad)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Code examples](#code-examples)
- [Download full data on ork.ad](#download-full-data)

## Why this dataset?

- **Ultra high-quality 1-minute OHLCV** for **Natural Gas** (Commodities)
- **Extended-session energy and industrial metals — beyond US cash hours**
- **Clean CSV schema** — `time, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`1m` only) · **13 timeframes** on [ork.ad](https://ork.ad/) · **4,066,225** `1m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [ork.ad](https://ork.ad/) every **Sunday**; GitHub `1m` sample updated in sync

> **Sample on GitHub** · `NGAS_1m.csv` (171,512 rows, `2026-01-04` → `2026-07-02`). **Full archive on [ork.ad](https://ork.ad/)** — **4,066,225** `1m` rows (~208.36 MB), **13 timeframes** (``1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W``), `2012-06-24` → `2026-06-26`.

## Download sample

**[NGAS_1m.csv](https://github.com/ork-ad/ngas-1m-ohlcv-commodities-historical-data/blob/main/NGAS_1m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/ork-ad/ngas-1m-ohlcv-commodities-historical-data/main/NGAS_1m.csv)) · [GitHub Releases](https://github.com/ork-ad/ngas-1m-ohlcv-commodities-historical-data/releases) when the release workflow is active.

## GitHub Pages

Interactive chart & stats: **[https://ork-ad.github.io/ngas-1m-ohlcv-commodities-historical-data/](https://ork-ad.github.io/ngas-1m-ohlcv-commodities-historical-data/)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([ork.ad](https://ork.ad/))** |
|---|--:|---|
| Instrument | Natural Gas · Commodities | Natural Gas · Commodities |
| Timeframes | `1m` only (sample) | **13** — `1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W` |
| 1m rows | 171,512 | **4,066,225** |
| Size | 9.07 MB | ~208.36 MB |
| Period | `2026-01-04` → `2026-07-02` | `2012-06-24` → `2026-06-26` |
| File | `NGAS_1m.csv` | ZIP on [ork.ad](https://ork.ad/) |
| Updates | Weekly (Sunday) — GitHub sample | Weekly (Sunday) — all timeframes |

## Timeframes on ork.ad

This GitHub repository ships a **1-minute (`1m`) evaluation sample** only. On **[ork.ad](https://ork.ad/)**, each full asset archive is delivered as a ZIP with **13 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **2H** · **4H** · **8H** · **12H** · **16H** · **1D** · **1W**

GitHub = `1m` sample · [ork.ad](https://ork.ad/) = all **13** timeframes above for the same instrument.

## Weekly updates

- **[ork.ad](https://ork.ad/)** — Full datasets on ork.ad are updated every Sunday.
- **GitHub (this repo)** — GitHub 1m samples are refreshed weekly (every Sunday), in sync with ork.ad.

When a new `1m` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`NGAS_1m.csv`**:

**First rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-01-04T23:01:00Z | 3.63394 | 3.63394 | 3.44693 | 3.44693 | 51 |
| 2026-01-04T23:02:00Z | 3.44693 | 3.46313 | 3.44693 | 3.45993 | 74 |
| 2026-01-04T23:03:00Z | 3.45993 | 3.4610 | 3.45443 | 3.4610 | 28 |
| 2026-01-04T23:04:00Z | 3.4610 | 3.46363 | 3.45243 | 3.45243 | 20 |
| 2026-01-04T23:05:00Z | 3.45243 | 3.4530 | 3.4450 | 3.4470 | 43 |

**Last rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| time | open | high | low | close | volume |
| 2026-07-02T22:30:00Z | 3.2026 | 3.2026 | 3.2021 | 3.2021 | 1.00 |
| 2026-07-02T22:31:00Z | 3.2021 | 3.2021 | 3.2015 | 3.2015 | 1.00 |
| 2026-07-02T22:32:00Z | 3.2015 | 3.2015 | 3.2014 | 3.2014 | 1.00 |
| 2026-07-02T22:33:00Z | 3.2014 | 3.2015 | 3.2014 | 3.2015 | 1.00 |

## Schema

```text
time,open,high,low,close,volume
```

## Code examples

### pandas

```python
import pandas as pd

df = pd.read_csv('NGAS_1m.csv', parse_dates=['time'])
df.set_index('time', inplace=True)
print(df.describe())
print(df.resample('1h').agg({'open': 'first', 'high': 'max',
                              'low': 'min', 'close': 'last', 'volume': 'sum'}).head())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('NGAS_1m.csv', parse_dates=['time'])
df.set_index('time', inplace=True)

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

df = pd.read_csv('NGAS_1m.csv', parse_dates=['time'])
close = df.set_index('time')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='1min')
print(pf.stats())
```

## Download full data

The complete **NGAS** archive on **[ork.ad](https://ork.ad/)** includes **13 OHLCV timeframes** (`1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W`) — **4,066,225** rows at `1m`, plus all higher timeframes in the same ZIP.

**[→ Get the full NGAS dataset on ork.ad](https://ork.ad/)**

---
*GetData · NGAS 1m OHLCV sample on GitHub · Full historical data on [ork.ad](https://ork.ad/) · 2026-07-03 UTC*