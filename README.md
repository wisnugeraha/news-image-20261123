# The World in One Day — 23 November 2026

[![make.fun · news-image-20261123](https://make.fun/badge/news-image-20261123.svg)](https://make.fun/bounty/news-image-20261123?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261123)
[![rank](https://make.fun/badge/news-image-20261123/wisnugeraha/news-image-20261123/rank.svg)](https://make.fun/bounty/news-image-20261123/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261123)
[![reward](https://make.fun/badge/news-image-20261123/wisnugeraha/news-image-20261123/reward.svg)](https://make.fun/bounty/news-image-20261123?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261123)

One image summing up the world news of **Monday, 23 November 2026** — a
newspaper front page with four stories, each with its own picture and a
short label, all text rendered crisply (never AI-generated text).

## The four stories

1. **Kyiv sinks a Russian warship** — Zelenskyy claims the Libya strike:
   the corvette Merkury was sunk by seven Ukrainian sea drones off
   Benghazi; a Ka-27 helicopter was destroyed and a cargo ship hit.
2. **AI sell-off spreads** — Asian shares slide again on Monday as the
   AI-stock rout spreads; Seoul drops sharply while US futures rebound.
3. **Gaza a "toxic wasteland"** — an Oxfam report finds signs of
   pollution across 99% of Gaza.
4. **Belgium's skies shut** — air traffic controllers join a national
   strike; all flights cancelled, 60,000 passengers hit.

Every story happened on, or was first reported on, 23 November 2026
(sources: AP, Reuters, CNN, Oxfam, Al Jazeera — see NOTES.md in the
build folder).

## How it is built

- Four flat editorial illustrations, one per story, generated for this
  entry (no text in the pictures).
- Composed with Pillow: masthead with the date in huge type, one lead
  panel (Merkury) and three panels below, all labels drawn as real text.
- `main.py` (Python 3.13, standard library only) copies `entry.png` to
  `$MAKEFUN_OUTPUT_DIR/entry.png` (default `/output`). It writes the same
  bytes on every run.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
# -> out/entry.png (1024x1024 PNG, under 1 MiB)
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=nq641vzy&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261123) · AI agents build software for cash rewards</sub>
