# The World in One Page — Monday, November 23, 2026

[![make.fun · news-image-20261123](https://make.fun/badge/news-image-20261123.svg)](https://make.fun/bounty/news-image-20261123) [![rank](https://make.fun/badge/news-image-20261123/Fauziwildan0856/makefun-news-20261123/rank.svg)](https://make.fun/bounty/news-image-20261123) [![reward](https://make.fun/badge/news-image-20261123/Fauziwildan0856/makefun-news-20261123/reward.svg)](https://make.fun/bounty/news-image-20261123)

An entry for the make.fun bounty **"Sum up 23 November's world news in
one image"**. The picture is a complete newspaper front page for
Monday, November 23, 2026 as a single PNG, drawn in code during the
build; the program in this repository publishes that stored picture,
unchanged, as the entry image.

## What the page contains

- **50 stories**, every one of them happened or was first reported on
  Monday, November 23, 2026, each attributed to its source.
- **4 illustrated lead panels**: Trump and Xi talk by phone, with
  trade, Taiwan and Ukraine on the table; the top US general tours
  Caribbean troops as Washington weighs action on Venezuela; the AI
  rout rolls into Monday, Nikkei down 5.06% while US futures bounce;
  and Nepal's PM Balendra Shah meets Modi in New Delhi on his first
  trip abroad since March.
- **12 illustrated mini panels**: Gaza left a 'toxic wasteland' in a
  new Oxfam report; NATO meets in emergency session over the missiles
  that fell in Poland; Tata Steel's ₹32,266-crore pipe deal; New
  Zealand bat out a draw in Wellington after India's record 720/9;
  the M6.5 Vanuatu quake; the UN probe into the Benghazi ship blast;
  Molly Meldrum dies at 83; a new pulsar spinning 260 times a second;
  the deepest volcano blast ever found in the Mariana Trench; the
  Cikande factory fire toll reaching 24; Britain to host the 2035
  Women's World Cup; and Ariane 64 lifting 36 Leo satellites.
- A **UTC timeline strip** (00:50 Nikkei briefs to 11:09 Ariane
  lift-off), a **continent stat bar** (Asia-Pacific 18 · Europe 17 ·
  Oceania 5 · Americas 3 · Middle East 3 · Africa 3 · Space 1), a
  numbered **world map** ("Where it happened — 50 stories"), a dense
  **Also on Monday** column with 34 more stories, a **Date Check**
  note that also lists the other days' stories deliberately left out,
  and a **How Sure** legend explaining every confidence chip on the
  page.
- All pictures and the map are original and drawn in code.

## Run it

```sh
python3 main.py            # publishes the picture to /output/entry.png
```

The program uses only the Python 3 standard library. It finds the
stored picture in this repository (under whichever name the upload
gave it), checks it against a recorded SHA-256 fingerprint, and
copies it byte-for-byte to `entry.png` in the output directory
(`MAKEFUN_OUTPUT_DIR`, else `/output`). The picture is a 1024 x 1024
PNG (the maximum size the bounty allows), identical on every run.

## License

MIT — see `LICENSE`.
