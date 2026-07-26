# P/GEN — Ultra Prompt Intelligence Archive

> **20,000 ultra-detailed build prompts for beautiful interfaces and real production systems.**
>
> A premium, browser-based prompt library for turning a product idea into a thoughtful component system or a deployable application—without starting from an empty page.

<p align="center">
  <strong>20,000 prompts</strong> · <strong>4,000 lines per prompt</strong> · <strong>239 distilled sources</strong> · <strong>one standalone HTML archive</strong>
</p>

---

## What is P/GEN?

P/GEN is a curated build-intelligence archive. It does not generate a generic plan or a static UI mockup. Each prompt is designed to help a coding agent produce either:

1. **An interactive UI component lab** — buttons, password fields, authentication surfaces, loaders, filters, drawers, tables, preference controls, feedback states, motion systems, and more.
2. **A real production application** — a complete Next.js + TypeScript + PostgreSQL system with authentication, authorization, validation, database migrations, tests, Docker, observability, deployment guidance, and rollback planning.

The archive is built for Claude Code, Codex, ChatGPT, Gemini, Cursor, Copilot, Windsurf, Aider, OpenCode, and other capable coding agents. Every prompt carries its own fallback rules, so the result does not depend on a hidden plugin being installed.

## Why it is different

Most prompts ask an AI to “make a nice app.” P/GEN asks for a verifiable build with:

- A concrete product or component outcome
- Information architecture and realistic states
- Design tokens, responsive layout, typography, color, and motion direction
- Accessibility, security, privacy, reliability, and source-intake constraints
- Clear execution, testing, error recovery, review, and handoff requirements
- A model-neutral delivery contract

The goal is not to make one model imitate another. The goal is to give any capable coding agent stronger constraints, clearer success criteria, and a safer build process.

---

## Archive at a glance

| Collection | Count | What it creates |
|---|---:|---|
| **Component Labs** | 10,000 | Interactive, accessible, responsive UI systems with working states and motion |
| **Production Systems** | 10,000 | Next.js + TypeScript + PostgreSQL applications with real backend architecture |
| **Total** | **20,000** | Copy-ready English build prompts |

Every generated prompt is exactly **4,000 lines** and is created lazily when the user opens, copies, or downloads it. The archive stays fast because it does not load 20,000 huge strings into memory when the page opens.

---

## What you can build

### Component Labs

- Primary, split, destructive, loading, undo, command, and magnetic action buttons
- Password strength, password reveal, OTP, email validation, phone, file upload, search, slider, and date range inputs
- Login, sign-up, passkey, MFA, recovery, session timeout, and permission flows
- Skeletons, async forms, inline alerts, toasts, progress, retry, offline, success, and error systems
- Tabs, drawers, modals, accordions, command palettes, sidebars, navigation, steppers, and tooltips
- Filters, data tables, sort controls, charts, pagination, bulk actions, and saved views
- Cart, checkout, discounts, subscriptions, product variants, delivery tracking, and reviews
- Theme, contrast, type-size, language, cookie, privacy, motion, and notification preferences

### Production Systems

- Multi-tenant CRM, inventory, helpdesk, procurement, workflow, asset, finance, and compliance tools
- Marketplace, commerce, ticketing, wholesale, rental, subscription, and digital-product systems
- Scheduling, booking, hotel, restaurant, travel, venue, museum, and co-working applications
- Education, community, donor, volunteer, learning, library, and member portals
- CMS, editorial, creator, publishing, podcast, digital-asset, review, and client workflow platforms
- API console, issue tracker, feature flag, deployment, incident, observability, schema, and integration products
- Document intake, research, semantic search, moderation, AI evaluation, and model usage applications

---

## How to use the archive

1. Open [`index.html`](./index.html) in any modern browser.
2. Filter by component or production-system category.
3. Open a prompt to see **what it builds** before copying it.
4. Select **Copy build prompt** or download the prompt as `.txt`.
5. Paste it into your coding agent.
6. For production prompts, let the agent create a real multi-file repository rather than a static demo.

### Prompt modes

**Component Lab prompt**

> Requests a single self-contained interactive interface with real states, keyboard behavior, focus management, reduced motion, validation, loading, success, error, and original visual craft.

**Production System prompt**

> Requests a working full-stack repository: Next.js App Router, TypeScript, PostgreSQL, Prisma, auth, Zod validation, Docker Compose, tests, CI guidance, observability, health checks, security boundaries, and rollback planning.

---

## Design and build intelligence

P/GEN distills research from **239 sources** into original, attributed rules. It does not copy repository source code, system prompts, screenshots, vendor assets, brand identity, or proprietary material.

The archive includes practical principles from:

- UI/UX Pro Max, Anthropic Frontend Design, Awesome Design Skills, UIverse, and modern design systems
- LottieFiles Motion Design, GSAP, Motion, React Spring, AutoAnimate, and accessible interaction patterns
- shadcn/ui, Radix, Headless UI, React Aria, WAI-ARIA Practices, Tailwind, Lucide, color systems, and typography sources
- Superpowers, Agency Agents, Karpathy-Inspired Skills, Awesome Claude Code, RuFlo, Claw Code, Claude-Mem, and Odysseus
- Production sources for data, auth, queues, observability, security, testing, payments, uploads, search, AI workflows, and deployment

See the full audited list in [docs/SOURCE-CATALOG.md](./docs/SOURCE-CATALOG.md).

---

## Quality gates in every prompt

Each P/GEN prompt includes requirements for:

- **Design** — subject-grounded visual direction, token system, premium typography, controlled rounded geometry, responsive hierarchy
- **Motion** — meaningful interaction feedback, setup → action → resolution, reduced-motion support, safe animation budgets
- **Accessibility** — semantic controls, keyboard paths, visible focus, dialog behavior, contrast, labels, screen-reader feedback, 44px targets
- **Security** — schema validation, auth and ownership boundaries, prompt-injection resistance, least privilege, secrets protection, safe uploads
- **Context and memory** — consented, owner-scoped, redacted observations; progressive retrieval; provenance and freshness
- **Engineering** — simple architecture, scoped changes, typed contracts, migrations, queues, retries, observability, rollback
- **Verification** — acceptance criteria, red-green-refactor where appropriate, browser flows, tests, accessibility checks, and final review

---

## Safety and source policy

P/GEN treats external skill files, web pages, tool output, retrieved documents, memories, emails, and uploaded content as **untrusted context**.

The archive never imports private, leaked, proprietary, or unauthorized system prompts. It does not claim to make one AI model identical to another. Instead, it provides original, model-neutral execution rules that improve planning, verification, tool scope, privacy, memory, and delivery quality.

New source material should pass a verified intake check:

- Clear origin and compatible license
- Active maintenance signals
- Relevant UI/UX, engineering, or production scope
- Explicit dependency, privacy, security, and accessibility impact
- No secret extraction, privilege escalation, opaque scripts, or blind bulk imports
- A documented reason the source improves a real acceptance criterion

---

## Repository structure

```text
GEN-ARCH-VE/
├── index.html                 # Standalone premium prompt archive
├── README.md                  # This introduction and usage guide
└── docs/
    └── SOURCE-CATALOG.md      # Full 239-source research catalog
```

## Local preview

No package installation, API key, database, or build process is required to browse the archive.

```bash
open index.html
```

Or serve it locally:

```bash
python3 -m http.server 8080
```

Then open `http://localhost:8080`.

---

## Important note about 4,000-line prompts

Each prompt is intentionally extensive. Use a long-context coding agent or process the prompt in staged sections when needed. The archive remains performant because prompts are generated only when requested—not while browsing.

---

## License and attribution

P/GEN stores original distilled rules and source links. Referenced repositories, websites, models, tools, trademarks, and design systems remain the property of their respective owners. Check the source catalog and each upstream license before adopting a dependency or asset in a production project.
