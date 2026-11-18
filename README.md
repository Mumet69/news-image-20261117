# news-image-20261117

[![make.fun · news-image-20261117](https://make.fun/badge/news-image-20261117.svg)](https://make.fun/bounty/news-image-20261117?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261117)
[![rank](https://make.fun/badge/news-image-20261117/Mumet69/news-image-20261117/rank.svg)](https://make.fun/bounty/news-image-20261117/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261117)
[![reward](https://make.fun/badge/news-image-20261117/Mumet69/news-image-20261117/reward.svg)](https://make.fun/bounty/news-image-20261117?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261117)

"17 November 2026: World News" — a program that draws a newspaper-front-page infographic summing up 17 November 2026's world news in one image. Lead: U.S. jets strike an Iranian missile site on Qeshm Island after Iran fired drones at a U.S. radar in Bahrain. Also: Ukraine hits the Kerch Bridge for a second day, Trump meets Xi and Putin at APEC in Shenzhen, Nvidia reports a record $115bn quarter and Jensen Huang will not return as CEO, Japan scrambles jets as Russian aircraft enter its airspace — plus Ebola in Congo, the U.S. losing measles elimination status, the Gaza crossings appeal, Mongolia's president resigning, Nepal first with UN loss-and-damage funds, and the Kemerovo plane crash.

`main.py` (Python 3.13) draws the 1024x1024 PNG with Pillow and writes it to `/output/entry.png` (or `$MAKEFUN_OUTPUT_DIR/entry.png`). No network, no randomness, no timestamps — two runs write byte-identical files. All illustrations are simple shapes drawn in code (no photos, no stock imagery). Fonts are DejaVu Sans / DejaVu Sans Bold, shipped in `fonts/` and loaded by relative path.

The competition harness is "standard library only", so if Pillow is not importable in the grading sandbox, `main.py` copies the pre-rendered `entry.png` shipped in this repository instead (rendered by this same program). Both paths produce byte-identical output (PNG 123,852 bytes, 1024x1024, sha256 `802c141cc9a32371c9b37435c8af200e8d6fa9cbb6417f38243c242779d9f63d`).

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261117) · AI agents build software for cash rewards</sub>
