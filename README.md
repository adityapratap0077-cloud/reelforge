<div align="center">

# REELFORGE
### Cinematic AI promo reels for local businesses — $40, delivered in 48 hours

![ReelForge](https://img.shields.io/badge/REELFORGE-2026-%23F2F0EB?style=for-the-badge&labelColor=%23060608)
![Status](https://img.shields.io/badge/STATUS-LIVE-%237A1212?style=for-the-badge&labelColor=%23060608)
![License](https://img.shields.io/badge/License-MIT-%23060608?style=for-the-badge)

**No shoots. No crews. Just send your details — we forge the rest.**

[Live Site](https://reelforge-opal.vercel.app) • [GitHub](https://github.com/adityapratap0077-cloud)

</div>

---

ReelForge is a landing page + service site for a productized video offer: **cinematic AI-generated promo reels for local businesses** — cafés, gyms, boutiques, salons, restaurants. The page sells the offer end to end: AI video hero, sample reels, how it works, pricing, FAQ, and an Instagram-DM order flow.

## What you get

- **Single Reel — $40.** One scroll-stopping vertical reel for your business.
- **3-Reel Pack — $99** (was $120). Three reels, delivered one every 48 hours.
- **48-hour delivery** from brief approval. Two revision rounds included so it lands exactly right.
- **Zero camera work on your side** — send a few photos, a logo or a menu; the AI pipeline handles the cinematography, motion, and edit. Ready for Reels, Shorts, and TikTok.

Pricing is live in the page copy — `$40` flat, `$99` pack with the `$120` anchor struck through.

## The page

- **Hero** — full-bleed AI-generated video background, `$40 / 48 hours` positioning, one CTA
- **For strip** — who it's for: cafés, gyms, boutiques, salons, restaurants
- **Samples** — three AI-generated sample reels on hover-play cards (café, gym, boutique — `samples/`)
- **How it works** — from DM to done in 48 hours, three steps
- **Pricing** — Single vs. 3-Pack cards, both wired to the Instagram DM order link
- **FAQ** — accordion: no shoots needed, revision policy, delivery timing, 24-hour rush option on the pack
- **Order flow** — every CTA opens an Instagram DM to [@dyafterdark_](https://ig.me/m/dyafterdark_)
- **Chat bubble** — floating BanaoBot chat bubble for instant questions, embedded from the live BanaoBot app

## Media

All sample videos and imagery are AI-generated — no camera shoots involved.

```
samples/
├── reelforge-cafe.mp4      (hero background + sample card)
├── reelforge-gym.mp4       (sample card)
├── reelforge-boutique.mp4  (sample card)
assets/
├── logo.webp
└── og.webp                 (poster frame / OG image)
```

---

## Design System

Dark, ember-hot, video-first.

### Color Palette

| Color | Hex | Usage |
| :--- | :--- | :--- |
| Coal | `#0B0B0F` | Background |
| Smoke | `#14141B` | Sections, cards |
| Ember | `#FF6B1A` | Accent — CTAs, checks, status pulse |
| White | `#FFFFFF` | Headlines |
| Zinc-400 | `#A1A1AA` | Body text |

### Typography

- **Display:** Space Grotesk — tight-tracking headlines
- **Body:** Inter — readable, quiet

Rounded-full pill CTAs, ember glow shadows, reveal-on-scroll, hover-zoom sample cards.

---

## Tech Stack

`HTML / Tailwind CSS (CDN) / Vanilla JS`

One static `index.html` — no build step, no framework, no dependencies to install. Tailwind via CDN with a small config block (`ember`, `coal`, `smoke` colors; Space Grotesk + Inter). FAQ accordion and scroll reveals are a few lines of vanilla JS.

## Deploy

Push to `main` — Vercel auto-deploys the static site.

```bash
git clone https://github.com/adityapratap0077-cloud/reelforge.git
cd reelforge
# that's it — open index.html or deploy as-is
```

---

## Author

**Aditya Pratap** — Creative Technologist
Gorakhpur, India — github.com/adityapratap0077-cloud

## License

MIT © Aditya Pratap
