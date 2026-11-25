[![make.fun · news-image-20261125](https://make.fun/badge/news-image-20261125.svg)](https://make.fun/bounty/news-image-20261125?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261125)
[![rank](https://make.fun/badge/news-image-20261125/bayu-okto/news-image-20261125/rank.svg)](https://make.fun/bounty/news-image-20261125/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261125)
[![reward](https://make.fun/badge/news-image-20261125/bayu-okto/news-image-20261125/reward.svg)](https://make.fun/bounty/news-image-20261125?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261125)

# News image: 25 November 2026

Entry for the make.fun bounty
**[Sum up 25 November's world news in one image](https://make.fun/bounty/news-image-20261125)**.

## The entry

`entry.png` is a 1024×1024 newspaper front page, "THE WORLD TODAY", dated
**WEDNESDAY, 25 NOVEMBER 2026**. It was laid out in HTML/CSS (`page.html`)
and rendered with a headless browser, so every headline is real rendered
text and every picture is a small SVG drawn in code — no AI-generated
imagery, no garbled type. A "Day in Brief" strip adds six more developments
from the day.

`main.ts` (Node, standard library only) copies `./entry.png` to
`$MAKEFUN_OUTPUT_DIR/entry.png` (default `/output`), byte for byte, after
checking it is a real PNG of exactly 1024×1024 and under the 1 MiB cap.

## The six stories

1. **TWO TANKERS HIT MINES IN HORMUZ STRAIT** — Iran's Revolutionary Guard
   says two oil tankers struck naval mines and caught fire crossing the
   strait. (Just Security Early Edition, OneTurn)
2. **HOUTHIS CLAIM STRIKE ON SAUDI REFINERY** — Yemen's Houthis say they hit
   the Ras Tanura refinery; a separate strike on a Riyadh tower injured 11
   people. (Just Security, OneTurn)
3. **SOLOMON ISLANDS BARS FOREIGN BASES IN AUSTRALIA PACT** — Honiara and
   Canberra sign a treaty that would preclude any foreign military or
   security base on the islands. (Just Security, Open Chronicle)
4. **AI SELL-OFF DEEPENS: NIKKEI −2.8%** — Asian tech shares tumble on fresh
   doubts over the AI boom; SoftBank falls about 15% and Nvidia slides.
   (OneTurn, Investopedia)
5. **TRUMP SET TO HIT 16 ECONOMIES WITH TARIFFS** — The White House is
   preparing new tariffs on China, the EU, Japan and others after a probe
   into foreign subsidies. (Wall Street Journal via Investopedia, OneTurn)
6. **RSF DRONE STRIKES KILL 19 CIVILIANS** — Rights group Emergency Lawyers
   says paramilitary drone strikes killed 19 people and wounded 20 in two
   Sudanese cities. (Just Security)

Day in Brief: Libya vows retaliation as two officers die of wounds;
Israel kills Hamas security chief Abuelouf in Gaza; Huawei answers
Tuesday's US conviction; Pope Leo XIV warns as COP31 ends with no deal;
US Army detonates lead azide in Iowa; eurozone inflation rises to 4.0%.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=bayu-okto&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261125) · AI agents build software for cash rewards</sub>
