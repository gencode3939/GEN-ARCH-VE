# P/GEN Modular Prompt System

> Ten specialist Markdown modules used by the P/GEN 10,000-line prompt compiler.

## How coding agents should read this folder

1. Read `01-product-discovery.md` before defining scope.
2. Load the domain modules relevant to the task; do not blindly load every file into a short-context model.
3. Use the P/GEN master prompt as the binding contract. These modules add domain-specific checks but do not override safety, privacy, authorization, or user approval rules.
4. For production systems, read modules 01, 02, 03, 04, 05, 07, 08, 09, and 10. Add module 06 when motion/visual behavior is material.
5. For component labs, read modules 01–06 and 10; add 07–09 if the component has backend or production release implications.

## Modules

- [`01-product-discovery.md`](./01-product-discovery.md) — Product Discovery and Scope: Clarify user outcome, constraints, non-goals, assumptions, acceptance criteria, and measurable product value.
- [`02-ux-information-flow.md`](./02-ux-information-flow.md) — UX, Information Architecture, and Content Flow: Design task journeys, navigation, hierarchy, recovery, content clarity, and task completion.
- [`03-design-tokens-typography-color.md`](./03-design-tokens-typography-color.md) — Design Tokens, Typography, and Color: Create tokenized, accessible, original visual systems with fluid type, controlled geometry, and contrast-tested color.
- [`04-component-frontend-system.md`](./04-component-frontend-system.md) — Component and Frontend System: Define semantic anatomy, finite variants, state contracts, responsive behavior, and maintainable implementation.
- [`05-accessibility-inclusion.md`](./05-accessibility-inclusion.md) — Accessibility and Inclusion: Apply keyboard, focus, screen-reader, touch, zoom, localization, motion, and inclusive content requirements.
- [`06-motion-visual-craft.md`](./06-motion-visual-craft.md) — Motion and Visual Craft: Use meaningful motion, premium visual craft, original interaction feedback, and static reduced-motion fallbacks.
- [`07-data-backend-workflows.md`](./07-data-backend-workflows.md) — Data, Backend, and Workflow Systems: Define schemas, APIs, queues, transactions, idempotency, realtime flows, observability, and recovery.
- [`08-security-privacy-auth.md`](./08-security-privacy-auth.md) — Security, Privacy, and Authorization: Apply validation, auth, tenancy, least privilege, consent, secrets handling, audit trails, and threat-aware boundaries.
- [`09-testing-reliability-release.md`](./09-testing-reliability-release.md) — Testing, Reliability, and Release: Define unit/browser/accessibility tests, diagnostics, SLOs, CI, staged rollout, backup, rollback, and operational readiness.
- [`10-agent-context-github.md`](./10-agent-context-github.md) — Agent Execution, Context, and GitHub Delivery: Use safe orchestration, progressive context, evidence, bounded tools, source intake, Git/PR hygiene, and human approval.

Each module contains exactly 1,000 concise implementation guidance lines. The browser archive carries an equivalent module manifest and uses the same module domains while compiling each 10,000-line prompt.
