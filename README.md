# P/GEN Skill Code Archive

A single-file library of **10,000 unique ultra-detailed English code-generation prompts**. The archive creates 100 product briefs × 10 art-direction systems × 10 motion/interaction architectures in the browser; every generated record has its own ID and complete copy-ready build prompt.

## Use it

1. Open [`index.html`](./index.html) in a modern browser.
2. Search, filter, sort, preview, copy, or download a prompt. Only 24 cards render at a time for responsive browsing.
3. Paste the copied prompt into Claude Code or another coding AI. Each prompt requires a complete runnable, single-file `index.html` response.

## Skill-informed protocol

The embedded implementation prompts were distilled after reviewing the supplied repositories:

- [UI/UX Pro Max](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill): product/design-system reasoning, accessibility, touch targets, responsive UI, form feedback, charts, performance and meaningful motion.
- [Claude Design Skillstack](https://github.com/freshtechbro/claudedesignskills): modern web design, GSAP ScrollTrigger, Three.js/WebGL, lightweight 3D, motion, Canvas, and progressive-enhancement patterns.

Each prompt asks Claude Code to invoke the relevant installed skills when present, and embeds fallback requirements so it works without plugin installation. It includes WCAG-oriented contrast/focus rules, 44px touch targets, keyboard paths, reduced-motion behavior, transform/opacity animation, performance budgets, real stateful interactions, and Canvas/WebGL/GSAP fallbacks when applicable.

## Composition

- 10 product families × 10 concrete product names = 100 product briefs
- 10 design systems
- 10 animation/interaction systems
- **100 × 10 × 10 = 10,000 unique full prompts**

No API key, build step, external image, package, or remote AI request is required to browse or copy this standalone archive.
