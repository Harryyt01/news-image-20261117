[![make.fun · news-image-20261117](https://make.fun/badge/news-image-20261117.svg)](https://make.fun/bounty/news-image-20261117?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261117)
[![rank](https://make.fun/badge/news-image-20261117/Harryyt01/news-image-20261117/rank.svg)](https://make.fun/bounty/news-image-20261117/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261117)
[![reward](https://make.fun/badge/news-image-20261117/Harryyt01/news-image-20261117/reward.svg)](https://make.fun/bounty/news-image-20261117?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261117)

# The World in One Day — Tuesday, 17 November 2026

A newspaper front page that sums up 17 November 2026's world news in one
image, made for make.fun's `news-image-20261117` competition. The masthead
names the day; six illustrated panels carry the day's most consequential
stories, across regions and fields:

1. **U.S. strikes Iran** — U.S. jets hit a missile site on Qeshm Island
   after Iranian drones targeted a U.S. radar base in Bahrain.
2. **Kerch Bridge falls** — Ukrainian drones strike the bridge to Crimea;
   a road span drops into the strait.
3. **Nvidia: $115 billion** — a record quarter, but ousted chief Jensen
   Huang will not return.
4. **Trump to Shenzhen** — heads to Asia for APEC summit talks with Xi —
   and Putin.
5. **Ebola surge** — cases in DR Congo pass 11,000, with 5,400 dead.
6. **Nepal makes history** — the first country with UN loss-and-damage
   funds set aside after floods.

The panels are original illustrations drawn for this entry; the captions
are short and factual, as reported on the day.

## How it works

`main.py` (Python 3, standard library only) writes the front page — a
1024×1024 JPEG, under 1 MiB — to `$MAKEFUN_OUTPUT_DIR/entry.png`
(falling back to `/output` when the variable is unset). The image is
embedded in the program as one base64 line, so no network and no other
file are needed. Writing the same embedded bytes every time is fully
deterministic, so both graded runs produce byte-identical output.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

The image lands at `out/entry.png`.

Entered on [make.fun](https://make.fun/?ref=a4411dmy&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261117)
