# Kiln

> **Preview: the full template is being built by the Pinies.** This repository is a small working EmDash site: its home page is the accepted design, and the rest is EmDash's own `starter-cloudflare` template. The Pinies' real build lands here later.

A warm EmDash shop for a potter's small firings, its pieces an EmDash collection and its checkout Stripe's hosted page.

## Start it

- **In Piny:** pick it in the Templates tab.
- **Outside Piny:** `npm create astro -- --template github:pinylabs/kiln`, then `pnpm install` and `pnpm dev`, and open `/_emdash/admin` to set up the site.

It needs Node 22 or later and pnpm. On Cloudflare it uses a D1 database (`DB`) and an R2 bucket (`MEDIA`), as EmDash's Cloudflare templates do.

## Its look

The pages are styled with Tailwind CSS 4. Every colour, face, size, radius and measure is a token in `src/styles/theme.css`, so the look changes there; `src/styles/global.css` holds the motion, the hero's arch and the styles for what EmDash renders itself. Light and dark follow the visitor's system, and all motion stops under `prefers-reduced-motion`.

## Photos and video

They are linked from their sources and never copied into this repository:

- Home: the hero, first of three: [Annie Spratt](https://unsplash.com/@anniespratt) on Unsplash, [Unsplash License](https://unsplash.com/license), linked from [its page](https://unsplash.com/photos/white-ceramic-mug-on-wooden-table-top-n42ogaQn32o), not copied.
- Home: the hero, second; a product: [Tom Crew](https://unsplash.com/@tomcrewceramics) on Unsplash, [Unsplash License](https://unsplash.com/license), linked from [its page](https://unsplash.com/photos/two-white-ceramic-bowls-bgIO-u4GEfI), not copied.
- Home: the hero, third; a product: [Tom Crew](https://unsplash.com/@tomcrewceramics) on Unsplash, [Unsplash License](https://unsplash.com/license), linked from [its page](https://unsplash.com/photos/four-round-white-ceramic-bowls-on-white-surface-YA2E3d7a9Wo), not copied.
- Home: a product: [Liu T. Corriveau](https://unsplash.com/@liutcorriveau) on Unsplash, [Unsplash License](https://unsplash.com/license), linked from [its page](https://unsplash.com/photos/a-simple-white-bowl-on-a-white-background-ka8gj7iAMMk), not copied.
- Home: a product; the product page: [Katja Vogt](https://unsplash.com/@folkmade) on Unsplash, [Unsplash License](https://unsplash.com/license), linked from [its page](https://unsplash.com/photos/two-white-ceramic-mug-CipURjPCXOo), not copied.
- Home: the studio band: [Earl Wilcox](https://unsplash.com/@earl_plannerzone) on Unsplash, [Unsplash License](https://unsplash.com/license), linked from [its page](https://unsplash.com/photos/person-in-blue-denim-jeans-making-clay-pot-7ZK_CuHroq4), not copied.
- The product page: made by hand: [Anne Nygård](https://unsplash.com/@polarmermaid) on Unsplash, [Unsplash License](https://unsplash.com/license), linked from [its page](https://unsplash.com/photos/hands-shaping-ceramic-bowl-rim-G4IB-r6nsJI), not copied.
- Home: a product: [Odiseo Castrejon](https://unsplash.com/@edgarraw) on Unsplash, [Unsplash License](https://unsplash.com/license), linked from [its page](https://unsplash.com/photos/person-holding-ceramic-mug-RuKqwXCwEos), not copied.

## Licence

MIT. Built on EmDash's `starter-cloudflare` template, MIT, Copyright 2026 Cloudflare Inc.; its notice is kept in [LICENSE](LICENSE). Made by the Pinies in [Piny](https://piny.studio/home/). The Piny Studio mark in `public/brand` is Piny's and is not covered by this template's MIT licence.
