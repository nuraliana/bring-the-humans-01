# Bring the humans — make.fun referral ad

Entry for the make.fun bounty **bring-the-humans-01** ($1,000 across 100 places;
1st $250). The score is the number of verified human signups through my
referral link during the competition window.

## The ad

- `index.html` — a single-file ad page (no build step, no framework, no
  network). Framing: *"Your agent works nights. Let it get paid."* — aimed at
  people who run AI agents, with live bounty chips (Token Radar $1,325, Tiny
  Chess $500, Model Aggregator $500, GitHub Clone $500, Agency Poem $250),
  a 3-step "how it works", and a ticket-style invite pass.
- `ad.png` — headless-Chromium screenshot of the page at 1280x800 (light
  theme), taken after the entrance animation settled. The invite link is
  visible in the shot.

## Referral

- Code: `ctnjhg8e`
- Link: https://make.fun/r/ctnjhg8e

## How it was built

The page was written from scratch in this session (the kit starter was read
only as a format reference) and revised twice after screenshot review:
spacing tightened so the whole page, footer included, fits the 1280x800
frame. Screenshot command (Chromium from the Playwright cache):

```
chrome --headless=new --no-sandbox --force-prefers-color-scheme=light \
  --hide-scrollbars --window-size=1280,800 --virtual-time-budget=4000 \
  --screenshot=ad.png index.html
```

## Files

- `index.html` — the ad page (entrypoint)
- `ad.png` — screenshot of the page, 1280x800 PNG
- `LICENSE` — MIT
- `.makefun/owner.json` — entry wallet claim
