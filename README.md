# SOURA — Drinking Water Delivery (Redesign)

A premium, framework-free redesign of the **Acuas · Drinking Water Website Template** (source zip: `source/Acuas.zip`).

> Reimagined as **SOURA**, a fictional northern-highlands spring-water brand. English / LTR only.

## What changed
The original was a Bootstrap-based HTMLCodex template with a generic carousel hero and placeholder copy. This rebuild:

- **Drops all frameworks** — pure semantic HTML, hand-written CSS (token-driven design system), and vanilla JS. No Bootstrap, no Tailwind, no build step.
- **New brand identity** — "SOURA", a calm, natural, trustworthy water brand with its own name, voice and visual language.
- **New Design DNA** — aqua-teal + warm-sand palette, Fraunces (display) × Hanken Grotesk (body), fluid organic layouts, generous whitespace.
- **Real, specific copy** — no Lorem Ipsum, no "Elevate/Seamless" clichés, believable names, prices and stats.
- **Motion with purpose** — scroll reveals, count-up stats, floating hero badges, drifting droplets, all respecting `prefers-reduced-motion`.
- **Accessibility** — semantic landmarks, visible focus, keyboard nav, ARIA on the mobile toggle, reduced-motion support.

## Design DNA (summary)
- **Philosophy:** water as a quiet daily ritual of purity and care.
- **Personality:** Premium · Natural · Calm · Trustworthy.
- **Palette:** aqua teal `#0E8C82` (primary), sand gold `#D8A24A` (accent), mist `#F4F8F7` (bg), teal-ink `#0C1B1A` (text).
- **Type:** Fraunces display + Hanken Grotesk body; tabular figures for stats.
- **WOW moment:** split hero with a fluid SVG "blob", floating glass-bottle badges and gently rising water droplets.

## Pages
| File | Purpose |
|------|---------|
| `index.html` | Home — hero, trust marquee, services, story, bottles, stats, testimonials, CTA |
| `about.html` | Brand story, the source, the bottle loop, values, team, FAQ |
| `service.html` | Services, how a drop works, plans, delivery areas |
| `product.html` | Bottle & jug catalogue with prices |
| `blog.html` | Journal — purity reports and spring notes |
| `contact.html` | Request form (validated, no `alert()`), contact info, area check |

## Structure
```
drinking-water-delivery-html-template/
├─ index.html  about.html  service.html  product.html  blog.html  contact.html
├─ assets/
│  ├─ css/base.css      # design tokens + components + motion + responsive
│  └─ js/main.js        # nav state, mobile menu, reveals, counters, form
└─ README.md
```

## Run it
Open `index.html` in a browser — no server or install required. Imagery uses seeded `picsum.photos` placeholders; swap `src` values for real photography when available.

## Notes
- Original assets were used for reference only and are **not** copied into this folder.
- The GitHub-Pages automation step described in the project workflow is handled separately (not generated here).
