# nimbus-store

Nimbus is a tiny storefront — browse products, add to a cart, check out.

**Stack:** Plain HTML / CSS / JS (no build step)

It is realistic but intentionally small, and ships with **no product analytics, experimentation, or session-replay wired in** — the user-action handlers just log to the console today.

## User actions worth tracking

open cart · add to cart · checkout

## Running it

```bash
# static site — no build
python3 -m http.server 8000   # then open http://localhost:8000
```
