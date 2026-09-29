# vibe/forge

Forge your viber in 3D: **https://vibe-forge-3d.vercel.app**

Token: [$FORGE on vibe/vibe testnet](https://testnet.vibevibe.fun/token/0xDB5276bB71BF71219F265A71104fea9BF7fd2423) · by [@Devran1an](https://x.com/Devran1an)

A fan-made character studio for the [vibe/vibe](https://testnet.vibevibe.fun) community, inspired by the vibe vibers collection.

- Mix traits: body (incl. a translucent Glass body), eyes, headwear, gear, background
- Animations: idle, wave, dance, quant mode (floating candle-chart screens)
- Level 1 to 20: the aura, orbiting coins and sparkles grow; gold at 15, crown at 20
- Export a 1080px PFP (PNG) or a 360° spinning GIF
- Share links: every viber is encoded as 10 bytes of DNA in the URL hash, so a link rebuilds the exact same viber with no backend

## DNA

`0x` + 10 bytes: `body, accent, eyes, eyeColor, hat, hatColor, gear, bg, title, level`.
The planned Forge Pass contract on Robinhood Chain Testnet stores only these bytes; the page renders the 3D viber from them.

## Run locally

It's a single static file. Serve the folder with anything, e.g.

```bash
python -m http.server 5188
```

Built with [three.js](https://threejs.org) and [gifenc](https://github.com/mattdesl/gifenc), loaded from jsDelivr.

Not affiliated with or endorsed by the vibe/vibe team. Testnet only.
