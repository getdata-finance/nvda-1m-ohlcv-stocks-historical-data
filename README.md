# NVDA 1m OHLCV US stocks Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-599_253_rows-blue)](https://getdata.finance/datasets/nvda) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/nvda)

### -> [**Download the full NVDA dataset on getdata.finance**](https://getdata.finance/datasets/nvda)

**NVDA 1m OHLCV stocks historical data** — ultra high-quality 1m OHLCV for **NVIDIA**. Clean `time, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on GetData](#timeframes-on-getdata)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Download full data on getdata.finance](#download-full-data-on-getdata)

## Why this dataset?

- **Ultra high-quality 1m OHLCV** for **NVIDIA** (US stocks)
- **Clean CSV schema** — `time, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`1m`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/nvda) · **599,253** `1m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `1m` sample updated in sync

> **Sample on GitHub** · `NVDA_1m.csv` (55,440 rows, `2026-02-06` -> `2026-09-01`). **Full archive on [getdata.finance](https://getdata.finance/datasets/nvda)** — **599,253** `1m` rows, **11 timeframes**, `2020-07-14` -> `2026-09-01`.

## Download sample

**[NVDA_1m.csv](https://github.com/getdata-finance/nvda-1m-ohlcv-stocks-historical-data/blob/main/NVDA_1m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/nvda-1m-ohlcv-stocks-historical-data/main/NVDA_1m.csv))

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/nvda))** |
|---|--:|---|
| Instrument | NVIDIA · US stocks | NVIDIA · US stocks |
| Timeframes | `1m` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 1m rows | 55,440 | **599,253** |
| Period | `2026-02-06` -> `2026-09-01` | `2020-07-14` -> `2026-09-01` |
| File | `NVDA_1m.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/nvda) |
| Coverage report | — | [NVDA coverage](https://getdata.finance/coverage/nvda) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`1m` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/nvda)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes**:

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **4H** · **12H** · **1D** · **3D** · **1W**

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples refreshed weekly, in sync with getdata.finance.

## Data preview

First and latest rows from the GitHub sample **`NVDA_1m.csv`**:

**First rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-02-06T20:00:00+00:00 | 182.68 | 182.68 | 182.37 | 182.56 | 331 |
| 2026-02-06T20:01:00+00:00 | 182.56 | 182.77 | 182.52 | 182.77 | 184 |
| 2026-02-06T20:02:00+00:00 | 182.77 | 182.77 | 182.69 | 182.72 | 164 |
| 2026-02-06T20:03:00+00:00 | 182.72 | 182.8 | 182.7 | 182.77 | 108 |
| 2026-02-06T20:04:00+00:00 | 182.77 | 182.85 | 182.72 | 182.85 | 105 |

**Last rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-01T19:55:00+00:00 | 213.35 | 213.71 | 213.35 | 213.51 | 374 |
| 2026-09-01T19:56:00+00:00 | 213.51 | 213.53 | 213.34 | 213.45 | 340 |
| 2026-09-01T19:57:00+00:00 | 213.45 | 213.68 | 213.39 | 213.66 | 335 |
| 2026-09-01T19:58:00+00:00 | 213.66 | 213.94 | 213.6 | 213.89 | 342 |
| 2026-09-01T19:59:00+00:00 | 213.89 | 214.02 | 213.77 | 213.99 | 522 |

## Schema

| Column | Description |
| --- | --- |
| `time` | Bar open timestamp (UTC, ISO-8601). |
| `open` | Opening price of the candlestick bar. |
| `high` | Highest price during the bar. |
| `low` | Lowest price during the bar. |
| `close` | Closing price of the candlestick bar. |
| `volume` | Tick volume (number of price updates) during the bar. |

```text
time,open,high,low,close,volume
```

## Download full data

Full NVDA archive — 11 timeframes, gap-free, updated weekly:

**[-> Get the full NVDA dataset on getdata.finance](https://getdata.finance/datasets/nvda)**
