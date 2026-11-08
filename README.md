# DeliGran Store Plan

A one-page, step-by-step guide to getting DeliGran granola into stores. No login, no signup, no build step: everything lives in `index.html`.

## What's on the page

- **Progress at a glance**: a ring showing tasks done, plus the four things stores need (inspected kitchen, registered business with insurance, bilingual label, simple wholesale offer).
- **Nine step boxes.** Tap one and it opens as slides with Back and Next. Each task slide has a **Mark as done** button.
  1. Health unit inspection
  2. Business registration and insurance
  3. Nutrition Facts table
  4. Barcode
  5. Label content in English and French
  6. Label design and printing
  7. Batch log
  8. Pricing for stores (live price calculator)
  9. Sales kit and first stores (pitch in Spanish and English)
- **Copy buttons** for the phone script, the bilingual ingredient and allergen text, the ChatGPT front-label prompt, and the store pitches.
- **Timeline**, **Where we stand** (costs and status) and **Later**.

Progress is saved in the browser on each device (localStorage). The **Reset progress** button at the bottom clears it.

Each step has its own link, for example `…/#step-3` opens the Nutrition Facts step directly.

## Publish on GitHub Pages

1. Merge this branch into `main`.
2. In the repository, go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, pick `main` and `/ (root)`, then **Save**.
4. After a minute the page is live at `https://innovatiff.github.io/deligranplan/`.

To preview locally, open `index.html` in any browser.
