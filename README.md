# Jim's Auto Repair — Concept Demo Site

A mobile-first concept website for Jim's Auto Repair (Riverside, CA), built as the
demo piece of an AI-automated website service for local auto-repair shops: shops
without a real web presence get a full site generated from their public business
profile — services, reviews, hours, contact, and quote CTAs.

This repo holds the exported, self-contained demo: one `index.html` (no build
step, no dependencies — open it in any browser). It was the sales asset used to
pitch the shop, alongside a personalized outreach letter.

## What's in the demo

- **Services** — brakes, oil & routine maintenance, tires, diagnostics & repair,
  each with a "get exact quote" call to action
- **Social proof** — embedded Google rating block (4.8★ / 436 reviews)
- **Local SEO basics** — address, phone, hours, and map-ready location info for
  9764 Magnolia Ave, Riverside, CA
- **Mobile-first layout** — built for customers searching on their phones

## Viewing it

Open `index.html` directly, or serve the folder:

```bash
cd jims-auto-repair-demo
python3 -m http.server 8000
# then open http://localhost:8000
```

## Notes

- Concept demo, not the shop's live site — business details reflect the shop's
  public listings as of September 2026.
- Part of a larger project: a reusable pipeline (prospecting via the Google
  Places API → AI-generated site per shop → automated cold-email outreach).
  Template and tooling live in separate repos.
