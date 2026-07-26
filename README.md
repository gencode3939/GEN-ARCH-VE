# P/GEN Component Motion Archive

A standalone **10,000-prompt component engineering library**. It is built for copy-ready prompts that ask a coding AI for a real interactive component lab, not a static UI snippet.

## Component coverage

The 100 component briefs cover:

- Buttons, CTA controls, undo actions, command triggers, destructive confirmations, and action menus
- Password strength/reveal, email, OTP, search, file upload, phone, range, date, address, and validation inputs
- Sign-in, sign-up, passkeys, multi-factor verification, recovery, security settings, and consent dialogs
- Loading buttons, skeletons, progress, async form states, toasts, alerts, empty/offline/error/retry/success feedback
- Navigation, tabs, command palettes, accordions, modals, drawers, steppers, sidebars, and help popovers
- Filters, sorting, date ranges, tables, charts, selection, saved views, pagination, and bulk actions
- Cart, variants, quantity, checkout, discount, subscriptions, wishlist, reviews, and delivery tracking
- Tasks, Kanban, autosave, calendar, collaboration, AI streaming, mentions, comments, and notifications
- Theme, motion, contrast, text size, language, cookie/privacy/notification preferences, shortcuts, and onboarding
- SVG success, validation error, transitions, reordering, custom cursor, 3D fallbacks, progress narratives, drag confirmation, and ambient controls

## Use it

1. Open [`index.html`](./index.html) in a modern browser.
2. Search/filter the 10 component families. The UI renders 24 cards at a time for quick browsing.
3. Copy or download any complete English component prompt.
4. Paste it into Claude Code or another coding AI. Every prompt requires one runnable `index.html` component lab.

## Skill protocol in every prompt

Every generated prompt combines one of 100 component briefs with ten visual design systems and ten motion systems: **100 × 10 × 10 = 10,000 unique prompts**.

The shared protocol incorporates the reviewed skill repositories:

- [UI/UX Pro Max](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill): design-system reasoning, responsive UX, accessibility, interaction, data, and performance rules.
- [Claude Design Skillstack](https://github.com/freshtechbro/claudedesignskills): modern web design, GSAP, Three.js, lightweight 3D, Canvas, and interaction implementation patterns.
- [LottieFiles Motion Design Skill](https://github.com/LottieFiles/motion-design-skill): emotional intent, motion personalities, setup→action→resolution, timing/easing, primary/secondary/ambient layers, choreography, and motion accessibility.
- [Addy Osmani Agent Skills](https://github.com/addyosmani/agent-skills): frontend UI engineering, silent spec/vertical-slice thinking, security boundaries, tests, browser verification, performance, code review, and production definition-of-done gates.
- [Anthropic Frontend Design](https://github.com/anthropics/claude-code/tree/main/plugins/frontend-design): subject-specific visual identity, intentional typography/layout/copy, one justified signature risk, deliberate motion, and self-critique against generic AI aesthetics.
- [shadcn/ui Skill](https://github.com/shadcn-ui/ui/tree/main/skills/shadcn): existing-component-first composition, semantic tokens, correct form/overlay/navigation/loading primitives, accessibility-required titles, and conditional React/Tailwind implementation conventions.
- [Awesome Design Skills](https://github.com/bergside/awesome-design-skills): a registry of 67 coherent design-system styles with tokens, component-state rules, accessibility constraints, anti-patterns, and QA gates.
- [Official GSAP Skills](https://github.com/greensock/gsap-skills): core API, timelines, labels, responsive matchMedia, ScrollTrigger, performance, plugins, utility methods, cleanup, and accessible fallbacks.
- [alirezarezvani Claude Skills](https://github.com/alirezarezvani/claude-skills): multi-tool skill portability plus senior frontend, WCAG audit, Playwright-style verification, UI-system, security, performance, and release-quality guidance.

Prompts enforce real component states, native semantic controls, keyboard/focus paths, 44px targets, error/loading/success states, form and password safety, security constraints, reduced-motion fallbacks, transform/opacity motion, official-GSAP-only-when-needed discipline, distinctive subject-grounded art direction, design-system component composition, and a final verification/review pass. They are explicitly **model-neutral**: Claude Code, ChatGPT/Codex, Gemini, Cursor, Copilot, Windsurf, Aider, OpenCode, and similar AI coding agents receive the same embedded requirements even when none of the external skill plugins are installed.

No API key, build process, external image, or remote AI call is needed to browse this single HTML archive.
