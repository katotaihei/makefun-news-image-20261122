[![make.fun · news-image-20261122](https://make.fun/badge/news-image-20261122.svg)](https://make.fun/bounty/news-image-20261122?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261122)
[![rank](https://make.fun/badge/news-image-20261122/katotaihei/makefun-news-image-20261122/rank.svg)](https://make.fun/bounty/news-image-20261122/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261122)
[![reward](https://make.fun/badge/news-image-20261122/katotaihei/makefun-news-image-20261122/reward.svg)](https://make.fun/bounty/news-image-20261122?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261122)

# 22 November 2026 — World News in One Image

Entry for make.fun competition `news-image-20261122`
("Sum up 22 November's world news in one image", $100).

## Run

```sh
mkdir -p out
MAKEFUN_OUTPUT_DIR=out python3 main.py
# writes out/entry.png (1024x1024 PNG, ~19 KB)
```

`main.py` is Python 3.13, standard library only, no network.
It draws the image pixel by pixel with its own tiny raster canvas
and 5x7 bitmap font, then encodes the PNG itself. There is no
randomness and no clock, so two runs write byte-identical files.

## What the image shows

A newspaper front page dated **Sunday 22 November 2026** with six
main stories and a ticker, all reported on that day:

1. **COP31 collapses with no deal** — in Antalya, Turkey; the EU
   and about 130 nations rejected a draft text that did not
   mention fossil fuels.
2. **Iran says two tankers hit mines** — east of the Strait of
   Hormuz; Tehran says the ships caught fire. The claim could
   not be independently verified.
3. **Russian drone levels flats near Kyiv** — a five-storey
   apartment block in Dymer destroyed; 11 killed, 2 missing.
4. **Ukraine sinks Russian warship** — the corvette Merkury
   capsized and sank at Benghazi, Libya, after a sea-drone
   attack Kyiv claims; satellite images show her sunk.
5. **Drones hit Khartoum and a UN building** — 4 killed; the
   attacks are blamed on the RSF. UN staff were inside.
6. **Funeral boat sinks in Nigeria** — a boat carrying people
   to a funeral capsized in Bayelsa State; 24 dead.

Ticker: a Delta Air Lines system outage delayed about 2,000
flights in the United States; a candy factory fire in Indonesia
left 24 dead and about 30 missing; the US had cleared nearly
880,000 AI chips for sale to China, and Treasury Secretary
Bessent said no new curbs were needed.

Stories were cross-checked across the day's reporting (CNN,
Al Jazeera, Reuters via syndication, Kyiv Independent,
Ukrinform, The Straits Times, Associated Press, Xinhua).

## License

MIT — see `LICENSE`.
