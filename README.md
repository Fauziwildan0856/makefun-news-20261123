# The World in One Page — Monday, November 23, 2026

[![make.fun · news-image-20261123](https://make.fun/badge/news-image-20261123.svg)](https://make.fun/bounty/news-image-20261123) [![rank](https://make.fun/badge/news-image-20261123/Fauziwildan0856/makefun-news-20261123/rank.svg)](https://make.fun/bounty/news-image-20261123) [![reward](https://make.fun/badge/news-image-20261123/Fauziwildan0856/makefun-news-20261123/reward.svg)](https://make.fun/bounty/news-image-20261123)

This repository is an entry for the make.fun bounty **"Sum up 23
November's world news in one image"**. The entry is one picture: a
newspaper front page for Monday, November 23, 2026, drawn in code
as a single 1024x1024 PNG. The program here publishes that stored
picture, unchanged, as the entry image.

## The page

- **50 stories**, each one happened or was first reported on
  Monday, November 23, 2026 — nothing from another day.
- **4 illustrated lead panels**: the Trump–Xi phone call; the top
  US general's tour of Caribbean troops; the AI rout that sent the
  Nikkei down 5.06%; Nepal's PM meeting Modi in New Delhi.
- **12 illustrated mini panels**: the Oxfam report calling Gaza a
  'toxic wasteland'; NATO's emergency session over the missiles in
  Poland; Tata Steel's ₹32,266-crore pipe deal; New Zealand batting
  out a draw in Wellington; the M6.5 Vanuatu quake; the UN probe
  into the Benghazi ship blast; Molly Meldrum's death at 83; a
  pulsar spinning 260 times a second; the deepest volcano blast
  ever found, in the Mariana Trench; the Cikande fire toll at 24;
  Britain hosting the 2035 Women's World Cup; Ariane 64 lifting 36
  Leo satellites.
- A **UTC timeline** under the masthead (00:50 Nikkei briefs to
  11:09 Ariane lift-off), a **continent stat bar**, a numbered
  **world map** ("Where it happened — 50 stories"), **34 more
  stories** in the "Also on Monday" column, a **Date Check** listing
  the other days' stories left out on purpose, and a **How Sure**
  legend for the confidence chip on every pictured panel.
- Every illustration and the map are original, drawn in code.

## Running it

```sh
python3 main.py
```

That publishes the picture to `entry.png` in the output directory
(`MAKEFUN_OUTPUT_DIR`, else `/output`). It needs nothing beyond the
Python 3 standard library: it finds the stored picture in this
repository (under whichever name the upload gave it), checks it
against a recorded SHA-256 fingerprint and a PNG size check, then
copies it byte-for-byte. The picture comes out identical on every
run.

## Licence

Released under the MIT licence; the full text is in `LICENSE`.
