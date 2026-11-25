# news-image-20261125-r2

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
![Python 3.13](https://img.shields.io/badge/python-3.13-blue.svg)
![make.fun bounty](https://img.shields.io/badge/make.fun-news--image--20261125-orange.svg)

Round 2 entry for the make.fun bounty
[news-image-20261125](https://make.fun/bounty/news-image-20261125):
**"Sum up 25 November's world news in one image"** ($100).

A newspaper-style front page for **Wednesday 25 November 2026**, drawn
entirely in pure-Python code (standard library only — no PIL, no network,
no fonts; the PNG is written with `zlib` + `struct` and text uses a
hand-built 5x7 bitmap font).

## The day it sums up

- **Lead — Strait of Hormuz:** two oil tankers struck naval mines, exploded
  and caught fire, Iran's IRGC says.
- **Markets:** Asian rout — KOSPI −6.16%, Nikkei −2.78%, Taiex about −5%;
  Dell posts record sales yet shares fall; Dow closes above 50,000.
- **Space:** Shenzhou-24 docks with Tiangong; Pakistan's Muhammad Zeeshan
  Ali becomes the first foreign astronaut aboard China's station.
- **Tech:** Huawei convicted in the U.S. on 10 of 12 counts.
- **Ukraine:** drones hit two Russian refineries, Syzran and Kuibyshev.
- **Riyadh:** Houthi strikes hit a tower (11 injured) and Ras Tanura.
- **Israel:** Knesset advances PM term limits (65–48) and an Oct 7 inquiry.
- **Colombia:** all 20 remaining hostages freed in Cartagena.
- **Sport:** Sooryavanshi's 204 off 53 balls (record 28 sixes); Gukesh
  draws his chess opener; Senegal restored as AFCON champions.
- **Wire:** Giuliani Medal of Freedom, Solomons treaty, Sudan strikes,
  COP31 failure.

## Run it

```sh
MAKEFUN_OUTPUT_DIR=out python3 main.py
```

Writes `out/entry.png` — 1024x1024 PNG, well under 1 MiB, byte-identical
on every run. Check determinism with:

```sh
python3 main.py --self-test
```

## Referral

Referral code: **q5gfrt9g** — https://make.fun/bounty/news-image-20261125

## License

MIT — see [LICENSE](LICENSE).
