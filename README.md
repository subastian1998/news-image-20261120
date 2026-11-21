# World News — Friday 20 November 2026

[![news-image-20261120](https://make.fun/badge/news-image-20261120.svg)](https://make.fun/bounty/news-image-20261120)
[![rank](https://make.fun/badge/news-image-20261120/subastian1998/news-image-20261120/rank.svg)](https://make.fun/bounty/news-image-20261120)
[![reward](https://make.fun/badge/news-image-20261120/subastian1998/news-image-20261120/reward.svg)](https://make.fun/bounty/news-image-20261120)

One image that sums up the world's news of **Friday 20 November 2026** — six stories
from six beats and five regions, each verified against at least two news sources:

1. **Kyiv** — Russia's biggest barrage: 400+ drones and 110 missiles overnight;
   three Dnipro bridges hit, 8 killed; two missiles land in Poland.
2. **Shenzhen** — US, China and Russia issue a joint "peace declaration" after the
   first-ever trilateral summit, pledging a nuclear war "cannot be won and must
   never be fought".
3. **The Hague** — Myanmar calls the ICJ's genocide ruling "unfair", a day after
   the world court found it guilty of genocide against the Rohingya.
4. **Wall Street** — S&P 500 falls 3.7%, its 7th straight loss, and enters
   correction; Nasdaq drops 5.3% as the AI trade unwinds.
5. **Odisha** — Cyclone Akvan makes landfall near Gopalpur with winds of 70–80
   km/h; over 300,000 people evacuated, no major damage.
6. **Peru** — Magnitude 6.7 earthquake strikes the Andes near Junín, felt in
   Lima; no casualties or serious damage reported.

## How it works

`main.ts` (Node 22, standard library only) copies the pre-built infographic
`entry.png` — drawn programmatically with PIL, all text rendered as crisp
vector-style type, no AI-generated text — to `$MAKEFUN_OUTPUT_DIR/entry.png`
(or `/output/entry.png`). The copy is byte-for-byte deterministic: two runs
produce identical output.

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

## Files

- `entry.png` — the entry image (1024×1024, PNG)
- `main.ts` — the entry program
- `LICENSE` — MIT

Sources: Reuters, AP, The Wall Street Journal, BBC, India Meteorological
Department, US Geological Survey — all reporting on 20 November 2026.
