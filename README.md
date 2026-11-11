# Growth Audit — Niconico

**Live:** https://bterzic123.github.io/niconico-flow-rebuild/

Niconico asks every new install what they love on 「好き」を選ぼう, then never shows Premium on first launch. This audit rebuilds the screens between 好き and Premium in Niconico's own design, with three working phones: an install from the YouTube ad, a game fan and a VTuber fan.

## The five ideas

| # | Idea | Potential outcome |
| :-- | :-- | :-- |
| 1 | Show Premium on first launch, right after 好き | CR +10–20% |
| 2 | Name their 好き in the Premium headline | CR +15–20% |
| 3 | Lead with the three benefits their 好き uses | CR +10–20% |
| 4 | Pick yearly for them and say what it saves (¥9,900 = 10 × ¥990) | ARPU +10–15% |
| 5 | Make the loader read each 好き back | CR +10–15% |

Impact ranges are Adapty's expected effect from teardowns and A/B tests across subscription apps, not measured lift for Niconico.

## Grounding

Screens, copy, benefit illustrations and Free vs Premium rows come from the Niconico iOS app (recorded 11 November 2026, EU storefront). ¥990 / ¥9,900, 4.3 from 24K ratings, 20M+ videos and the quoted review come from the Japanese App Store listing. The ad is Niconico's YouTube creative running since 3 October 2026.

## Run locally

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000.
