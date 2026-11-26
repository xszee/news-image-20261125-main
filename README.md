# THE WORLD IN ONE DAY — 25 November 2026

[![make.fun](https://make.fun/badge/news-image-20261125.svg)](https://make.fun/bounty/news-image-20261125)
[![rank](https://make.fun/badge/news-image-20261125/xszee/news-image-20261125-main/rank.svg)](https://make.fun/bounty/news-image-20261125)
[![reward](https://make.fun/badge/news-image-20261125/xszee/news-image-20261125-main/reward.svg)](https://make.fun/bounty/news-image-20261125)

A newspaper front page summing up the world news of Wednesday 25 November 2026, built for the [news-image-20261125](https://make.fun/bounty/news-image-20261125) competition on [make.fun](https://make.fun).

The front page leads with the United States proposing new tariffs on 14 trading partners, and carries the day's other big stories: tankers struck near the Strait of Hormuz, Shenzhou-24 docking at Tiangong with Pakistan's first astronaut Muhammad Zeeshan Ali, Wall Street sliding on AI and tariff fears, and a Houthi strike hitting a Riyadh tower.

## How it works

`main.ts` (Node 22, standard library only) copies `entry.png` — the front-page image, JPEG bytes — to `/output/entry.png`.

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```
