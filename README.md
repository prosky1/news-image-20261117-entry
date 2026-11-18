# The Day in World News — Tuesday 17 November 2026

[![make.fun · news-image-20261117](https://make.fun/badge/news-image-20261117.svg)](https://make.fun/bounty/news-image-20261117)
[![rank](https://make.fun/badge/news-image-20261117/prosky1/news-image-20261117-entry/rank.svg)](https://make.fun/bounty/news-image-20261117/leaderboard)
[![reward](https://make.fun/badge/news-image-20261117/prosky1/news-image-20261117-entry/reward.svg)](https://make.fun/bounty/news-image-20261117)

Entry for the make.fun competition **news-image-20261117**: one image summing
up the world news of Tuesday 17 November 2026 — 43 stories from 6 continents
on a single page.

The front page leads with a span of the Crimea bridge falling into the Kerch
Strait after a second day of Ukrainian strikes, the widening US–Iran war in
the Gulf (US jets strike an IRGC missile site on Qeshm Island; Iranian drones
target a radar in Bahrain; an ADNOC vessel hit in the Strait of Hormuz, 11
crew hurt), and the Quad leaders reuniting in Manila for the first time since
2024. Ten more stories follow — Nvidia's $115.8bn quarter, Ebola cases
doubling in three months in DR Congo, the US, Mexico and Bolivia losing
measles-free status, a Russian An-12 crash killing all 19 aboard, COP31
ministers taking charge in Antalya, Mongolia's president saying he will
resign, Serbia's Student List sworn in, Bangladesh garment workers met with
tear gas, the Mondlane trial opening in Maputo, and the Board of Peace
warning the Gaza truce may collapse — plus a by-the-numbers strip, a dotted
world map with numbered pins and a pin legend, a DATE CHECK note, and 30
more briefs. Every story happened, or was first reported, on 17 November
2026; every figure was verified against live sources.

All illustrations are original drawings made in code: atmospheric dusk and
night feature scenes with location caption bars, dense icon-led story cards,
a dark by-the-numbers band, a calendar date block and region-colour rule in
the masthead, and per-story source tags.

## Run

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

`main.ts` (Node 22, standard library only) gates `entry.png` (PNG magic bytes,
1024×1024, under 1 MiB) and copies it to the output directory, verifying the
copy byte for byte. The image is a 1024×1024 PNG, 232,378 bytes — within the
1 MiB and 1024×1024 limits.
