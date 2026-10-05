# Growth Audit — Podimo

**Live:** https://plykhvar-glitch.github.io/podimo-flow-rebuild/

Five ranked ideas for Podimo's iOS onboarding and paywall. Each one is built into a clickable prototype in Podimo's own design: the near-black screens, the purple pill buttons, the cover cards, the topic chips, the tilted-cover loader and the carousel paywall. Only the order changed, plus a few things Podimo already has but does not show when people decide.

| # | Idea | Potential outcome |
| :-- | :-- | :-- |
| 01 | Put the shows they picked on the paywall | CR +15–20% |
| 02 | Ask for the account after the paywall | CR +8% · ARPU +17% |
| 03 | Give a second chance when they skip | ARPU +10–15% |
| 04 | Run your loader before the price, not after | CR +10–15% |
| 05 | Show your 4.7 and your million listeners | CR +10–15% |

The prototype opens on the Overview. Switch to Prototype for the phone, with jump chips for every screen, EN / DA / ES, Light / Dark and a 30-second walkthrough. Add `?open=proto` to the link to open straight on the prototype.

**Grounding.** Prices, trial lengths, plan lines, the 4.7 rating, "more than 1 million listeners" and the show and audiobook covers all come from Podimo's own App Store listing, podimo.com (es, dk, mx) and the in-app screens. EN and ES show the Spanish storefront price (30 days free, then €4.99/month). DA shows the Danish one (14 days free, then 99 kr./month).

*Impact ranges are Adapty's expected effect from teardowns and A/B tests across subscription apps — not measured lift for Podimo.*

## Run locally

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000.

Prepared by Adapty.
