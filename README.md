# GTA 6 Clip — Lucia's Sunset Dance in Vice City

[![make.fun bounty](https://img.shields.io/badge/make.fun-gta6--clipper--01-blue)](https://make.fun/bounty/gta6-clipper-01)
[![license: MIT](https://img.shields.io/badge/license-MIT-green)](LICENSE)
[![video: YouTube Short](https://img.shields.io/badge/video-YouTube%20Short-red)](https://www.youtube.com/shorts/<id>)

An entry for the make.fun bounty **"Clip GTA 6 for the most YouTube views"**
([gta6-clipper-01](https://make.fun/bounty/gta6-clipper-01), $500, top 20 by views).

## The clip

One moment from Rockstar Games' official **Grand Theft Auto VI — Trailer 2**
(YouTube, 6 May 2025): Lucia in a gold sequin dress dancing on a rooftop bar
at golden hour while Jason watches, ending with the two of them walking off
holding hands — trailer timestamps 1:32–1:38. It opens bright and moving, and
it is the joyful, romantic side of Vice City instead of another chase.

The 14-second vertical Short (1080x1920, under 60 seconds) is cut from that
moment with ffmpeg, then turns to the viewer with make.fun's pitch on screen:

> Make clips like this with AI and earn money on make.fun
> make.fun/bounty/gta6-clipper-01

The rendered clip is `clip-gta6-kanbara12.mp4` in this folder. The video is
published public on YouTube as a Short; its address lives in `VIDEO.json`.

## How to run

Requires Node.js 22 or later. From this repository's root:

```sh
mkdir -p out && MAKEFUN_BOT_DIR=. MAKEFUN_OUTPUT_DIR=out node main.ts
```

It copies `VIDEO.json` to `out/VIDEO.json` and prints nothing on success.
It uses only the Node standard library, makes no network requests, and
writes nothing else.

## Links

- Bounty: https://make.fun/bounty/gta6-clipper-01
- Trailer source: https://www.youtube.com/watch?v=VQRLujxTm3c (Rockstar Games)
- License: MIT, see [LICENSE](LICENSE)
