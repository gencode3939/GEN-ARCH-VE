# P/GEN — Ultra Prompt Intelligence Archive

> **20,000 ultra-detailed build prompts for beautiful interfaces and real production systems.**
>
> A premium, browser-based prompt library for turning a product idea into a thoughtful component system or a deployable application—without starting from an empty page.

<p align="center">
  <strong>20,000 prompts</strong> · <strong>10,000 lines per prompt</strong> · <strong>239 distilled sources</strong> · <strong>one standalone HTML archive</strong>
</p>

---

## What is P/GEN?

P/GEN is a curated build-intelligence archive. It does not generate a generic plan or a static UI mockup. Each prompt is designed to help a coding agent produce either:

1. **An interactive UI component lab** — buttons, password fields, authentication surfaces, loaders, filters, drawers, tables, preference controls, feedback states, motion systems, and more.
2. **A real production application** — a complete Next.js + TypeScript + PostgreSQL system with authentication, authorization, validation, database migrations, tests, Docker, observability, deployment guidance, and rollback planning.

The archive is built for Claude Code, Codex, ChatGPT, Gemini, Cursor, Copilot, Windsurf, Aider, OpenCode, and other capable coding agents. Every prompt carries its own fallback rules, so the result does not depend on a hidden plugin being installed. For new ideas, the built-in Gemini Prompt Forge can turn a user brief into a custom 10,000-line P/GEN build prompt.


## Türkçe dil desteği

P/GEN arayüzünde sağ üstteki **TR / EN** dil düğmesi ile İngilizce ve Türkçe arasında geçiş yapılabilir. Bu seçim yalnızca zararsız bir kullanıcı arayüzü tercihi olarak tarayıcıda saklanır; API key, brief veya prompt içeriği saklanmaz.

Gemini Prompt Forge içinde ayrıca **Prompt dili** seçeneği vardır:

- **English technical prompt** — uluslararası teknik isimlendirme ve İngilizce kullanıcı çıktısı
- **Türkçe yönlendirme + English technical rules** — Gemini spesifikasyonu ve kullanıcıya görünen ürün/metin yönlendirmeleri Türkçe hazırlanır; paket adları, API kimlikleri, kaynak adları ve uyumluluk kuralları gerektiğinde İngilizce kalır

Bu yaklaşım Türkçe ürün briefleri ile çalışmayı kolaylaştırırken teknik ekosistem referanslarının doğruluğunu korur.

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

Every generated prompt is exactly **10,000 lines** and is created lazily when the user opens, copies, or downloads it. The archive stays fast because it does not load 20,000 huge strings into memory when the page opens.

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


## Modular 10,000-line prompt system

The 10,000-line output is not stored as one opaque block. It is compiled lazily from a **modular Markdown system** in [`docs/prompt-system/`](./docs/prompt-system/).

| Module | Purpose |
|---|---|
| [01 — Product Discovery](./docs/prompt-system/01-product-discovery.md) | User outcomes, assumptions, non-goals, constraints, and acceptance criteria |
| [02 — UX and Information Flow](./docs/prompt-system/02-ux-information-flow.md) | Journeys, navigation, hierarchy, content, recovery, and completion |
| [03 — Tokens, Typography, Color](./docs/prompt-system/03-design-tokens-typography-color.md) | Visual tokens, fluid typography, color science, dark mode, contrast, spacing, and geometry |
| [04 — Component and Frontend System](./docs/prompt-system/04-component-frontend-system.md) | Semantic anatomy, variants, state contracts, responsive behavior, and frontend quality |
| [05 — Accessibility and Inclusion](./docs/prompt-system/05-accessibility-inclusion.md) | Keyboard, focus, screen readers, touch, zoom, language, and motion preferences |
| [06 — Motion and Visual Craft](./docs/prompt-system/06-motion-visual-craft.md) | Meaningful animation, feedback, reduced motion, and original interaction craft |
| [07 — Data and Backend Workflows](./docs/prompt-system/07-data-backend-workflows.md) | Schemas, APIs, queues, transactions, realtime behavior, and recovery |
| [08 — Security, Privacy, Auth](./docs/prompt-system/08-security-privacy-auth.md) | Validation, authorization, consent, secrets, audit, tenancy, and threat boundaries |
| [09 — Testing, Reliability, Release](./docs/prompt-system/09-testing-reliability-release.md) | Tests, diagnostics, SLOs, CI, rollout, backup, rollback, and operations |
| [10 — Agent Context and GitHub Delivery](./docs/prompt-system/10-agent-context-github.md) | Safe tool use, context, source intake, Git/PR hygiene, evidence, and approval |

Each specialist module contains exactly **1,000 guidance lines**. Together they form a 10,000-line documented system. Archive and Gemini Forge prompts include a module manifest and embed the equivalent rules, so an agent can work even when it cannot read repository files. When an agent can read the repository, it should load only the modules relevant to the task rather than stuffing all modules into a short context window.


## Model compatibility and quality adapter

P/GEN does not copy third-party private or leaked system prompts and does not claim to turn one AI model into another. Instead, every 10,000-line prompt now includes an original **Model-Compatibility Execution Adapter**.

It requires an AI agent to:

- Check its actual tools, context, permissions, filesystem, browser, network, JSON/schema, and test capabilities before acting
- Process the long modular system in stages rather than pretending unlimited context is available
- Use structured specifications and validate them before code generation
- Keep trusted instructions separate from untrusted briefs, memory, tool output, documents, web pages, attachments, and generated suggestions
- Work through clarify → assumptions → acceptance criteria → minimum slice → implementation → evidence → root-cause repair → review
- Report limitations and unsupported capabilities honestly
- Use strong component, button, input, overlay, loading, motion, and accessibility contracts

This makes output more predictable across different capable coding agents. It is a quality and safety protocol, not a claim of a specific proprietary model’s power.

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



## P/GEN Design Profile Library

P/GEN now includes a separate library of **10,000 original UI, typography, color, and interaction profiles**. This is not a claim that 10,000 additional GitHub repositories were individually researched. The profiles are generated from original combinations of the existing curated principles:

- 10 layout systems
- 10 typography systems
- 10 color systems
- 10 interaction systems

`10 × 10 × 10 × 10 = 10,000` unique profiles.

The complete catalog lives at [`docs/design-profiles/CATALOG.md`](./docs/design-profiles/CATALOG.md). Gemini Forge selects a relevant active profile set from this library. Users can bias selection toward **Premium product**, **Editorial clarity**, **Enterprise utility**, **Calm and accessible**, or **Bold creative** visual direction.

Every existing archive prompt also receives an active design-profile set during lazy compilation. Profile selection never overrides accessibility, contrast, responsive behavior, task clarity, or source-intake safety.

## Gemini Prompt Forge

P/GEN now includes a browser-based **Gemini Prompt Forge** inside `index.html`.

1. Select **Gemini Forge** in the archive header.
2. Enter a Gemini API key and a model available to that key.
3. Describe the application, users, constraints, integrations, data, and desired visual direction.
4. Gemini converts the brief into a compact structured build specification.
5. P/GEN compiles that specification locally into an exact **10,000-line** custom build prompt.

### What happens to the API key?

The key is held only in browser memory for the current page session. It is not stored in localStorage, sessionStorage, cookies, the HTML file, Git, GitHub, or P/GEN source data. The browser sends it directly to Google’s Gemini API under the user’s own account and API-key restrictions. Use a restricted browser/API key and clear the Forge session when finished.

### Gemini request architecture

The Forge uses the official Gemini **Interactions API** when available, then falls back to the compatible `generateContent` REST route if needed. Gemini is asked to return a small JSON specification—not a huge code dump. P/GEN then combines that specification with:

- The 239-source distilled principles already in the archive
- A local library of **10,000 original P/GEN Native Skills**
- A relevant set from the **10,000 original P/GEN Design Profiles**
- The relevant active-skill selection for the user brief
- The 10,000-line original safe execution protocol

This produces a detailed custom prompt without putting the user API key or a vendor-specific hidden system prompt into the archive.

### P/GEN Native Skill Library

The native library contains 10,000 structured skills across ten domains:

- Product discovery
- Information architecture
- Visual systems
- Typography
- Color science
- Component engineering
- Interaction design
- Accessibility
- Security and privacy
- Data and reliability

Each skill has an ID, domain, competency, specialty, and implementation directive. For each user brief, P/GEN retrieves a relevant cross-domain active set and puts it into the generated prompt. Existing archive prompts also use this native selection at lazy generation time.

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

## Important note about 10,000-line prompts

Each prompt is intentionally extensive. Use a long-context coding agent or follow the modular prompt system in staged sections when needed. The archive remains performant because prompts are generated only when requested—not while browsing. Long prompts improve coverage and consistency only when the agent still follows scoped acceptance criteria, evidence, and review; length alone is not a quality guarantee.

---

## License and attribution

P/GEN stores original distilled rules and source links. Referenced repositories, websites, models, tools, trademarks, and design systems remain the property of their respective owners. Check the source catalog and each upstream license before adopting a dependency or asset in a production project.
