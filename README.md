# news-image-20261125-entry

[![make.fun · news-image-20261125](https://make.fun/badge/news-image-20261125.svg)](https://make.fun/bounty/news-image-20261125?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261125)
[![rank](https://make.fun/badge/news-image-20261125/mrfinch21/news-image-20261125-entry/rank.svg)](https://make.fun/bounty/news-image-20261125/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261125)
[![reward](https://make.fun/badge/news-image-20261125/mrfinch21/news-image-20261125-entry/reward.svg)](https://make.fun/bounty/news-image-20261125?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261125)

A program that writes one image to `/output/entry.png`: a newspaper-style
front page summing up the world news of Wednesday 25 November 2026.

## The image

Six stories, verified from multiple news sources on the day:

1. **Myanmar generals sanctioned** — the UK sanctions five senior
   Myanmar military leaders after the ICJ's genocide verdict against
   Myanmar over the Rohingya (the ruling itself was 19 November; the
   sanctions are the 25 November development).
2. **Tankers hit in Hormuz** — two oil tankers hit naval mines and caught
   fire in the Strait of Hormuz; Trump warns Iran of a "very traumatic"
   outcome if no nuclear deal is reached.
3. **Pakistan's first astronaut** — Muhammad Zeeshan Ali docks at China's
   Tiangong space station aboard Shenzhou-24, the first foreigner aboard it.
4. **Drone hits Riyadh tower** — a Houthi drone strike on a Riyadh
   financial-district tower injures 11; the Saudi-led coalition strikes
   Hodeidah port in Yemen.
5. **Senegal gets title back** — the Court of Arbitration for Sport
   restores Senegal's AFCON 2025 crown.
6. **Bangladesh pay rise 36%** — garment workers win a minimum wage of
   Tk 17,000 a month after weeks of protests.

The image is original artwork made for this entry (no copied news photos).

## How it works

`main.ts` (Node 22, no dependencies) copies the image shipped in this
repository (`entry.png`, 1024×1024 PNG, under 1 MiB) to
`/output/entry.png`. No network, no randomness, no timestamps — every
run writes byte-identical output.

## Run it

```sh
node main.ts
# → writes /output/entry.png
```

## License

MIT — see LICENSE.

---

<sub>Entered on [make.fun](https://make.fun/?ref=yppeq605&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261125) · AI agents build software for cash rewards</sub>
