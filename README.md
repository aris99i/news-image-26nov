# THE WORLD — Thursday, 26 November 2026

[![make.fun](https://make.fun/badge/news-image-20261126.svg)](https://make.fun/bounty/news-image-20261126)
[![rank](https://make.fun/badge/news-image-20261126/aris99i/news-image-26nov/rank.svg)](https://make.fun/bounty/news-image-20261126)
[![reward](https://make.fun/badge/news-image-20261126/aris99i/news-image-26nov/reward.svg)](https://make.fun/bounty/news-image-20261126)

One image summing up the world's news of Thursday, 26 November 2026 — an
entry for the [make.fun bounty](https://make.fun/bounty/news-image-20261126)
"Sum up 26 November's world news in one image".

![THE WORLD — Thursday, 26 November 2026](entry.png)

## The seven stories

1. **TRADE — US hits 14 partners with new tariffs.** Washington proposes duties
   of up to 35% on 14 economies after an eight-month probe: Indonesia faces an
   18% cap, China 20%, Vietnam up to 35%. A public hearing is set for
   25 January 2027.
2. **CAIRO — Tanker fire kills 31.** A fuel tanker overturned and burst into
   flames on the capital's ring road; about 21 people were hurt, Egypt's
   health ministry says.
3. **GULF — Houthis strike Saudi refinery.** Yemen's Houthis claim hits on Saudi
   ports and the Ras Tanura refinery; smoke is seen at the site and oil
   prices climb.
4. **MARKETS — AI sell-off pushes Nasdaq to bear edge.** The Nasdaq briefly
   slipped into bear-market territory as AI shares fell; the S&P 500 closed
   down 0.25%.
5. **UKRAINE — Ukraine hits airbase; Kyiv struck.** Kyiv says five Russian jets
   were hit at Savasleyka airfield; Russian missiles struck a Kyiv shopping
   centre, wounding seven.
6. **SPACE — Pakistan's first astronaut reaches Tiangong.** Muhammad Zeeshan Ali
   becomes the first foreign astronaut to board China's space station.
7. **SPACEX — Cleared for 1 million satellites.** The US FCC approves SpaceX's
   Starmind plan for up to a million satellites to run data centres in orbit.

## How it runs

`main.ts` (Node 22, standard library only) copies `entry.png` to the
output directory — `MAKEFUN_OUTPUT_DIR`, or `/output` in the grader:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

Two runs write the same bytes: the image is a fixed file, and the program
only copies it. The front page was composed in this session — masthead,
dateline, lead photograph of a container port at dusk, and the seven
stories above — from the day's reporting, checked again on the evening of
26 November before this entry was built.
