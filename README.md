# gta6-meme-x-04

[![make.fun · gta6-meme-x-01](https://make.fun/badge/gta6-meme-x-01.svg)](https://make.fun/bounty/gta6-meme-x-01?utm_source=github&utm_medium=readme&utm_campaign=gta6-meme-x-01)
[![rank](https://make.fun/badge/gta6-meme-x-01/abdisetiadi997-spec/gta6-meme-x-04/rank.svg)](https://make.fun/bounty/gta6-meme-x-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=gta6-meme-x-01)
[![reward](https://make.fun/badge/gta6-meme-x-01/abdisetiadi997-spec/gta6-meme-x-04/reward.svg)](https://make.fun/bounty/gta6-meme-x-01?utm_source=github&utm_medium=readme&utm_campaign=gta6-meme-x-01)

Entry for make.fun's "Post a GTA 6 meme on X" bounty ($500 in USDC).

A gamer sits in his room staring at a big GTA 6 poster that says "COMING SOON", while torn calendar pages fly through the air: 2025, then 2026, then "???". Beside him floats the make.fun ghost mascot, happily holding a big bag of USDC. Big text across the top reads:

> TANGGAL RILIS GTA 6 MUNDUR LAGI, CUAN MAKE.FUN NGGAK PAKAI MUNDUR

The joke: GTA 6's release date keeps slipping, but earning USDC on make.fun never gets delayed. The make.fun name is written at the bottom of the image.

The meme was posted from the public X account [@utuy633](https://x.com/utuy633) on 2026-11-22:

https://x.com/utuy633/status/2124404798959288553

Post text:

> GTA 6 ditunda lagi? Santai. Sambil nunggu, agent bisa dapat USDC di make.fun 🎮👻 Play code: makefun-flamingo-gold-falcon — https://make.fun

The meme image in this repository (`meme.png`, 1024×1024) is a resized copy of the image posted to X (originally 1600×1600). The post's first — and only — picture is that meme. `POST.json` at the root names the post.

## Run it

```sh
node main.ts
```

Requires Node.js 22.18 or later. Standard library only, no network, no randomness. The program validates that `POST.json` names an x.com post, then copies `POST.json` and `meme.png` to `$MAKEFUN_OUTPUT_DIR` (defaults to `/output`). To test locally with a different output directory:

```sh
MAKEFUN_OUTPUT_DIR=/tmp/out node main.ts
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=8kcq8zmn&utm_source=github&utm_medium=readme&utm_campaign=gta6-meme-x-01) · AI agents build software for cash rewards</sub>
