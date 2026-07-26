# P/GEN UIverse Component Motion Archive

A standalone **20,000-prompt engineering library**: 10,000 component labs plus 10,000 production system build prompts. It is built for copy-ready prompts that ask a coding AI for a real interactive component lab, not a static UI snippet.

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

The library has two distinct prompt archives: **100 component briefs × 10 visual systems × 10 motion systems = 10,000 component prompts**, plus **100 production system opportunities × 10 architecture profiles × 10 capability packs = 10,000 production system prompts**.

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
- [UIverse](https://uiverse.io/): community-made, open-source component inspiration across buttons, cards, loaders, toggles, forms, inputs, tooltips, hover effects, animated backgrounds, and feedback patterns. Prompts use it for category-level inspiration only and require original implementations rather than copied submissions.

Prompts enforce real component states, native semantic controls, keyboard/focus paths, 44px targets, error/loading/success states, form and password safety, security constraints, reduced-motion fallbacks, transform/opacity motion, official-GSAP-only-when-needed discipline, distinctive subject-grounded art direction, design-system component composition, original UIverse-inspired micro-craft, and a final verification/review pass. Each asks for a polished primary component plus purposeful default/expressive states without copying any individual UIverse submission. They are explicitly **model-neutral**: Claude Code, ChatGPT/Codex, Gemini, Cursor, Copilot, Windsurf, Aider, OpenCode, and similar AI coding agents receive the same embedded requirements even when none of the external skill plugins are installed.

## Long-form prompt architecture

Every one of the **20,000 prompts** expands lazily when copied, opened, or downloaded. The archive keeps browsing light by storing prompt metadata first, then builds the complete long-form prompt on demand. Each complete prompt contains:

- A distilled and attributed **234-source synthesis**: all previously supplied repositories, Odysseus AI Workspace, Agency Agents, Karpathy-Inspired Skills, an AI Tool Prompt Safety reference, the earlier 20-repository catalog, 100 production-system repositories, and 100 additional design/typography/motion/web sources
- Repository-specific `SOURCE`, `APPLY`, `GUARD`, `VERIFY`, `DOMAIN`, `INTEGRATE`, and design-source directives
- Ten quality matrices with explicit checks for intent, tokens, anatomy, accessibility, input/password safety, motion, loading, performance, test/review, and output
- The selected component brief or production-system opportunity, architecture profile, capability pack, style system, motion profile, UIverse craft cue, and model-neutral delivery contract

The complete prompts are deliberately detailed: all component and production-system prompts are currently **exactly 4,000 lines**. They do not copy repository code or documentation verbatim. The archive remains fast to browse because prompts are generated lazily; copying a 4,000-line brief is intended for long-context coding agents or a workflow that can process the brief in staged sections.

## Twenty newly researched repositories

The following new repositories were researched and turned into explicit prompt rules. They are **not** all installed together; every prompt tells an AI to select compatible primitives/dependencies for a real target stack and to provide dependency-free semantic fallbacks for its requested single-file lab.

| # | Repository | Integrated prompt direction |
|---:|---|---|
| 1 | [WAI-ARIA Practices](https://github.com/w3c/wai-aria-practices) | Authoritative keyboard, role, focus, dialog, menu, tab, slider, listbox, and disclosure behavior. |
| 2 | [Radix Primitives](https://github.com/radix-ui/primitives) | Composable parts, state contracts, data attributes, and accessible overlay behavior. |
| 3 | [Headless UI](https://github.com/tailwindlabs/headlessui) | Semantic, unstyled interaction patterns and state-driven presentation. |
| 4 | [Adobe React Spectrum](https://github.com/adobe/react-spectrum) | Accessibility, focus, touch, localization, validation, and adaptive interactions. |
| 5 | [Ariakit](https://github.com/ariakit/ariakit) | Composite widgets and explicit accessible state stores. |
| 6 | [Base UI](https://github.com/mui/base-ui) | Accessible unstyled primitives with complete CSS ownership. |
| 7 | [Melt UI](https://github.com/melt-ui/melt-ui) | Separate behavior builders from presentation and expose styling state. |
| 8 | [Motion](https://github.com/motiondivision/motion) | Interruptible layout-aware continuity where motion is genuinely useful. |
| 9 | [React Spring](https://github.com/pmndrs/react-spring) | Physics for direct manipulation and interruption, not delayed navigation. |
| 10 | [AutoAnimate](https://github.com/formkit/auto-animate) | Small meaningful automatic layout transitions with reduced-motion safety. |
| 11 | [Animate.css](https://github.com/animate-css/animate.css) | Sparse, semantic entrance/exit use—not stacked decorative attention effects. |
| 12 | [tsParticles](https://github.com/tsparticles/tsparticles) | Bounded, pausable, optional particle atmosphere with static fallback. |
| 13 | [Color.js](https://github.com/color-js/color.js) | Perceptual color spaces, gamut-aware palette choices, and contrast-aware operations. |
| 14 | [Culori](https://github.com/Evercoder/culori) | OKLCH scales, interpolation, dark mode, and clear state colors. |
| 15 | [Colorable](https://github.com/jxnblk/colorable) | Explicit contrast validation for text and UI pairs. |
| 16 | [contrast-ratio](https://github.com/LeaVerou/contrast-ratio) | Measured contrast rather than visual guessing. |
| 17 | [Lucide](https://github.com/lucide-icons/lucide) | Consistent accessible SVG icon language. |
| 18 | [Tailwind CSS](https://github.com/tailwindlabs/tailwindcss) | Deliberate tokens/utilities/responsive variants rather than one-off values. |
| 19 | [Class Variance Authority](https://github.com/joe-bell/cva) | Finite explicit component variant contracts. |
| 20 | [Vaul](https://github.com/emilkowalski/vaul) | Touch-friendly drawers/sheets and predictable gesture fallback. |

## AI system-prompt safety boundary

The repository `x1xhlol/system-prompts-and-models-of-ai-tools` was reviewed as a **security reference**, not a prompt source. Its structure includes many files labelled as system prompts/internal tools for third-party AI products, some of which may be private, proprietary, leaked, or unauthorized. The archive does **not** copy, reproduce, infer, or redistribute those prompts. Instead, every generated prompt now includes an original 4,000-line safe agent-execution protocol covering provider capability adapters, scoped tools, trusted/untrusted context separation, prompt-injection resistance, secret handling, consented memory, human confirmation, audit logging, source intake, testing, and verification.

## Agency Agents and Karpathy execution integration

[Agency Agents](https://github.com/msitarzewski/agency-agents) was distilled into a lean specialist-lens workflow: UX research, UX architecture, UI design, brand guardianship, inclusive visuals, visual storytelling, frontend delivery, and UI finish-gate review. Production prompts conditionally add identity/access, privacy, security, payments, realtime, SRE, product, and code-review gates only where scope makes them necessary. The system explicitly rejects persona role-play, copied agent prompts, and autonomous multi-agent ceremony without a concrete user benefit.

[Karpathy-Inspired Skills](https://github.com/multica-ai/andrej-karpathy-skills) contributes four execution rules: surface assumptions/tradeoffs, simplicity before abstraction, surgical scope, and goal-driven verification loops. All prompts now require internal success criteria, minimal safe implementation, evidence-backed tests/checks, and a final simplification pass.

### Rounded visual system

Every prompt now requires a controlled rounded geometry scale: 8–10px compact controls, 10–12px inputs/buttons, 14–16px cards, 18–20px drawers/modals, and pill forms only for compact semantic controls. Nested surfaces reduce radius. Motion, shadows, focus, press, loading, success, and error states must follow the same geometry tokens; rounding cannot replace accessibility, contrast, or information hierarchy.

## Odysseus AI workspace integration

[Odysseus](https://github.com/odysseus-dev/odysseus) was reviewed as a self-hosted AI workspace pattern. The prompt master now includes a conditional agentic-AI foundation: multi-provider capability adapters, server-enforced scoped tools/tokens, untrusted-context and prompt-injection boundaries, owner-scoped consented memory, cited research, transparent model comparison, durable background tasks, human confirmation for effectful actions, Docker/network hardening, audited logs, backups, and recovery. These requirements apply only when the target application genuinely includes an AI/agentic workflow; ordinary systems are not forced to add an AI agent.

## Verified large-catalog source policy

A blanket import of 10,000 arbitrary GitHub `SKILL.md`/`DESIGN.md` files would be unsafe and unreviewable: source files can contain conflicting instructions, unknown licenses, malicious setup commands, stale dependencies, or prompt-injection content. The prompts now include a verified-source intake gate that requires source provenance, license, activity, scope, dependency/security/accessibility impact, and an original-principles-only transformation before a new source can influence a production build. This keeps the 231 curated sources auditable while allowing future verified batches to be added safely.

## One hundred additional design, typography, motion, and web sources

These 100 sources include design-system repositories, component/motion libraries, typography/color tooling, and curated web inspiration. They are applied to every one of the 20,000 prompts as an original-principles-only knowledge layer: the prompts explicitly prohibit copying layouts, screenshots, videos, font files, brand assets, CSS, or source code.

| # | Source | Category | Prompt integration |
|---:|---|---|---|
| 1 | [Material Web](https://github.com/material-components/material-web) | Design systems and component languages | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 2 | [Material Color Utilities](https://github.com/material-foundation/material-color-utilities) | Design systems and component languages | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 3 | [Fluent UI](https://github.com/microsoft/fluentui) | Design systems and component languages | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 4 | [Fluent System Icons](https://github.com/microsoft/fluentui-system-icons) | Design systems and component languages | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 5 | [IBM Carbon](https://github.com/carbon-design-system/carbon) | Design systems and component languages | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 6 | [Adobe Spectrum CSS](https://github.com/adobe/spectrum-css) | Design systems and component languages | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 7 | [Shopify Polaris](https://github.com/Shopify/polaris) | Design systems and component languages | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 8 | [GitHub Primer](https://github.com/primer) | Design systems and component languages | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 9 | [Atlassian Design System](https://github.com/atlassian/design-system) | Design systems and component languages | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 10 | [GitLab UI](https://github.com/gitlab-org/gitlab-ui) | Design systems and component languages | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 11 | [Salesforce Lightning](https://github.com/salesforce-ux/design-system) | Design systems and component languages | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 12 | [Elastic EUI](https://github.com/elastic/eui) | Design systems and component languages | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 13 | [Evergreen](https://github.com/segmentio/evergreen) | Design systems and component languages | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 14 | [Chakra UI](https://github.com/chakra-ui/chakra-ui) | Design systems and component languages | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 15 | [Mantine](https://github.com/mantinedev/mantine) | Design systems and component languages | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 16 | [Grommet](https://github.com/grommet/grommet) | Design systems and component languages | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 17 | [Ant Design](https://github.com/ant-design/ant-design) | Design systems and component languages | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 18 | [Material UI](https://github.com/mui/material-ui) | Design systems and component languages | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 19 | [PrimeReact](https://github.com/primefaces/primereact) | Design systems and component languages | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 20 | [Base Web](https://github.com/uber/baseweb) | Design systems and component languages | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 21 | [Cloudscape](https://github.com/cloudscape-design/components) | Design systems and component languages | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 22 | [PatternFly](https://github.com/patternfly/patternfly-react) | Design systems and component languages | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 23 | [Braid](https://github.com/seek-oss/braid-design-system) | Design systems and component languages | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 24 | [Pinterest Gestalt](https://github.com/pinterest/gestalt) | Design systems and component languages | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 25 | [Twilio Paste](https://github.com/twilio-labs/paste) | Design systems and component languages | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 26 | [Zendesk Garden](https://github.com/zendeskgarden/react-components) | Design systems and component languages | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 27 | [Orbit](https://github.com/kiwicom/orbit) | Design systems and component languages | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 28 | [Anthropic Frontend Aesthetics Cookbook](https://github.com/anthropics/claude-cookbooks/blob/main/coding/prompting_for_frontend_aesthetics.ipynb) | Design systems and component languages | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 29 | [Awesome Claude Design](https://github.com/rohitg00/awesome-claude-design) | Design systems and component languages | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 30 | [Tremor](https://github.com/tremorlabs/tremor) | Design systems and component languages | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 31 | [Popmotion](https://github.com/Popmotion/popmotion) | Motion, visual interaction, and spatial craft | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 32 | [Lottie Web](https://github.com/airbnb/lottie-web) | Motion, visual interaction, and spatial craft | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 33 | [dotLottie Web](https://github.com/LottieFiles/dotlottie-web) | Motion, visual interaction, and spatial craft | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 34 | [React Native Reanimated](https://github.com/software-mansion/react-native-reanimated) | Motion, visual interaction, and spatial craft | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 35 | [use-gesture](https://github.com/pmndrs/use-gesture) | Motion, visual interaction, and spatial craft | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 36 | [Parallax.js](https://github.com/wagerfield/parallax) | Motion, visual interaction, and spatial craft | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 37 | [Lenis](https://github.com/darkroomengineering/lenis) | Motion, visual interaction, and spatial craft | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 38 | [Tween.js](https://github.com/tweenjs/tween.js) | Motion, visual interaction, and spatial craft | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 39 | [Bezier Easing](https://github.com/gre/bezier-easing) | Motion, visual interaction, and spatial craft | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 40 | [Anime.js](https://github.com/juliangarnier/anime) | Motion, visual interaction, and spatial craft | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 41 | [Rough.js](https://github.com/rough-stuff/rough) | Motion, visual interaction, and spatial craft | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 42 | [Floating UI](https://github.com/floating-ui/floating-ui) | Motion, visual interaction, and spatial craft | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 43 | [React Transition Group](https://github.com/reactjs/react-transition-group) | Motion, visual interaction, and spatial craft | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 44 | [React Modal](https://github.com/reactjs/react-modal) | Motion, visual interaction, and spatial craft | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 45 | [Magic UI](https://github.com/magicuidesign/magicui) | Motion, visual interaction, and spatial craft | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 46 | [Motion Primitives](https://github.com/ibelick/motion-primitives) | Motion, visual interaction, and spatial craft | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 47 | [DaisyUI](https://github.com/saadeghi/daisyui) | Motion, visual interaction, and spatial craft | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 48 | [React 95](https://github.com/React95/React95) | Motion, visual interaction, and spatial craft | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 49 | [Blueprint](https://github.com/palantir/blueprint) | Motion, visual interaction, and spatial craft | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 50 | [React Suite](https://github.com/rsuite/rsuite) | Motion, visual interaction, and spatial craft | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 51 | [Style Dictionary](https://github.com/amzn/style-dictionary) | Design tooling, token governance, typography, and color | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 52 | [Design Tokens Community Group](https://github.com/design-tokens/community-group) | Design tooling, token governance, typography, and color | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 53 | [Tokens Studio](https://github.com/tokens-studio/figma-plugin) | Design tooling, token governance, typography, and color | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 54 | [Storybook](https://github.com/storybookjs/storybook) | Design tooling, token governance, typography, and color | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 55 | [Chromatic](https://github.com/chromaui/chromatic) | Design tooling, token governance, typography, and color | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 56 | [Figma Plugin Samples](https://github.com/figma/plugin-samples) | Design tooling, token governance, typography, and color | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 57 | [Figma REST API Spec](https://github.com/figma/rest-api-spec) | Design tooling, token governance, typography, and color | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 58 | [Google Fonts](https://github.com/google/fonts) | Design tooling, token governance, typography, and color | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 59 | [Fontsource](https://github.com/fontsource/fontsource) | Design tooling, token governance, typography, and color | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 60 | [Inter](https://github.com/rsms/inter) | Design tooling, token governance, typography, and color | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 61 | [IBM Plex](https://github.com/IBM/plex) | Design tooling, token governance, typography, and color | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 62 | [Source Sans](https://github.com/adobe-fonts/source-sans) | Design tooling, token governance, typography, and color | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 63 | [Monaspace](https://github.com/githubnext/monaspace) | Design tooling, token governance, typography, and color | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 64 | [Cascadia Code](https://github.com/microsoft/cascadia-code) | Design tooling, token governance, typography, and color | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 65 | [JetBrains Mono](https://github.com/JetBrains/JetBrainsMono) | Design tooling, token governance, typography, and color | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 66 | [Recursive](https://github.com/arrowtype/recursive) | Design tooling, token governance, typography, and color | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 67 | [Radix Colors](https://github.com/radix-ui/colors) | Design tooling, token governance, typography, and color | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 68 | [Open Color](https://github.com/yeun/open-color) | Design tooling, token governance, typography, and color | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 69 | [Color Names](https://github.com/meodai/color-names) | Design tooling, token governance, typography, and color | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 70 | [Pick a Good Color](https://github.com/colorjs/pick-a-good-color) | Design tooling, token governance, typography, and color | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 71 | [Material Design 3](https://m3.material.io) | Authoritative design, typography, color, and inspiration websites | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 72 | [Apple Human Interface Guidelines](https://developer.apple.com/design/human-interface-guidelines/) | Authoritative design, typography, color, and inspiration websites | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 73 | [Fluent 2](https://fluent2.microsoft.design) | Authoritative design, typography, color, and inspiration websites | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 74 | [Carbon Design System](https://carbondesignsystem.com) | Authoritative design, typography, color, and inspiration websites | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 75 | [Adobe Spectrum](https://spectrum.adobe.com) | Authoritative design, typography, color, and inspiration websites | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 76 | [Shopify Polaris](https://polaris.shopify.com) | Authoritative design, typography, color, and inspiration websites | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 77 | [GitHub Primer](https://primer.style) | Authoritative design, typography, color, and inspiration websites | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 78 | [Atlassian Design](https://atlassian.design) | Authoritative design, typography, color, and inspiration websites | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 79 | [US Web Design System](https://designsystem.digital.gov) | Authoritative design, typography, color, and inspiration websites | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 80 | [GOV.UK Design System](https://design-system.service.gov.uk) | Authoritative design, typography, color, and inspiration websites | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 81 | [Design Systems Gallery](https://www.designsystems.com) | Authoritative design, typography, color, and inspiration websites | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 82 | [Design Systems One](https://www.designsystems.one) | Authoritative design, typography, color, and inspiration websites | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 83 | [Type Scale](https://typescale.com) | Authoritative design, typography, color, and inspiration websites | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 84 | [Modular Scale](https://www.modularscale.com) | Authoritative design, typography, color, and inspiration websites | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 85 | [Google Fonts Knowledge](https://fonts.google.com/knowledge) | Authoritative design, typography, color, and inspiration websites | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 86 | [Variable Fonts](https://variablefonts.io) | Authoritative design, typography, color, and inspiration websites | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 87 | [Typewolf](https://www.typewolf.com) | Authoritative design, typography, color, and inspiration websites | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 88 | [Coolors](https://coolors.co) | Authoritative design, typography, color, and inspiration websites | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 89 | [Adobe Color](https://color.adobe.com) | Authoritative design, typography, color, and inspiration websites | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 90 | [OKLCH Color Picker](https://oklch.com) | Authoritative design, typography, color, and inspiration websites | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 91 | [Color Hunt](https://colorhunt.co) | Authoritative design, typography, color, and inspiration websites | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 92 | [Realtime Colors](https://www.realtimecolors.com) | Authoritative design, typography, color, and inspiration websites | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 93 | [Awwwards](https://www.awwwards.com) | Authoritative design, typography, color, and inspiration websites | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 94 | [Codrops](https://tympanus.net/codrops/) | Authoritative design, typography, color, and inspiration websites | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 95 | [Mobbin](https://mobbin.com) | Authoritative design, typography, color, and inspiration websites | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 96 | [Page Flows](https://pageflows.com) | Authoritative design, typography, color, and inspiration websites | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 97 | [Refero](https://refero.design) | Authoritative design, typography, color, and inspiration websites | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 98 | [SaaSFrame](https://www.saasframe.io) | Authoritative design, typography, color, and inspiration websites | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 99 | [Land-book](https://land-book.com) | Authoritative design, typography, color, and inspiration websites | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |
| 100 | [Lapa Ninja](https://www.lapa.ninja) | Authoritative design, typography, color, and inspiration websites | Use as a principle reference for distinctive, accessible, token-driven design; never copy the source visual output. |

## One hundred newly researched production repositories

These repositories were individually verified as active Git repositories and distilled into the lazy master protocol. They are a **knowledge/selection catalog**, not a mandate to install every package. Production prompts select compatible libraries for a Next.js + TypeScript + PostgreSQL system and include fallback/operational requirements.

| # | Repository | Research integration |
|---:|---|---|
| 1 | [w3c/wai-aria-practices](https://github.com/w3c/wai-aria-practices) | Use authored WAI-ARIA keyboard, focus, role, and composite-widget patterns as the semantic baseline. |
| 2 | [radix-ui/primitives](https://github.com/radix-ui/primitives) | Use composable primitive anatomy, data-state styling, and accessible overlay behavior. |
| 3 | [tailwindlabs/headlessui](https://github.com/tailwindlabs/headlessui) | Separate semantic behavior from visual styling and keep interaction state explicit. |
| 4 | [adobe/react-spectrum](https://github.com/adobe/react-spectrum) | Design for robust focus, touch, validation, localization, and assistive-technology behavior. |
| 5 | [ariakit/ariakit](https://github.com/ariakit/ariakit) | Model composite widgets with explicit store relationships and observable active-item state. |
| 6 | [mui/base-ui](https://github.com/mui/base-ui) | Retain styling ownership while preserving accessible primitives and predictable APIs. |
| 7 | [melt-ui/melt-ui](https://github.com/melt-ui/melt-ui) | Separate interaction builders from presentation and expose state attributes for styling. |
| 8 | [lucide-icons/lucide](https://github.com/lucide-icons/lucide) | Use a consistent accessible SVG icon language with meaningful names and fallbacks. |
| 9 | [pacocoursey/cmdk](https://github.com/pacocoursey/cmdk) | Build command interfaces around keyboard-first filtering, groups, empty state, and focus restoration. |
| 10 | [emilkowalski/vaul](https://github.com/emilkowalski/vaul) | Use touch-friendly sheets/drawers with non-drag alternatives and reliable focus management. |
| 11 | [motiondivision/motion](https://github.com/motiondivision/motion) | Use layout-aware, interruptible transitions only where continuity improves orientation. |
| 12 | [pmndrs/react-spring](https://github.com/pmndrs/react-spring) | Use physics only for direct manipulation and interruption, never delayed navigation. |
| 13 | [formkit/auto-animate](https://github.com/formkit/auto-animate) | Limit automatic layout transition to meaningful small DOM mutations with reduced-motion fallback. |
| 14 | [animate-css/animate.css](https://github.com/animate-css/animate.css) | Use semantic entrances/exits sparsely and never stack decorative attention animations. |
| 15 | [tsparticles/tsparticles](https://github.com/tsparticles/tsparticles) | Treat particles as optional bounded ambient atmosphere with pause and static fallback. |
| 16 | [clauderic/dnd-kit](https://github.com/clauderic/dnd-kit) | Use accessible drag-and-drop with keyboard alternatives, announcements, collision clarity, and undo. |
| 17 | [react-dropzone/react-dropzone](https://github.com/react-dropzone/react-dropzone) | Make file input keyboard accessible, validate type/size, expose progress, remove, and retry states. |
| 18 | [gpbl/react-day-picker](https://github.com/gpbl/react-day-picker) | Use calendar semantics, keyboard date navigation, locale-safe formatting, and range constraints. |
| 19 | [petyosi/react-virtuoso](https://github.com/petyosi/react-virtuoso) | Virtualize large lists while preserving loading, keyboard, item measurement, and empty-state behavior. |
| 20 | [react-grid-layout/react-grid-layout](https://github.com/react-grid-layout/react-grid-layout) | Use resizable/reorderable grid layouts only with persistence, keyboard alternatives, and bounded breakpoints. |
| 21 | [color-js/color.js](https://github.com/color-js/color.js) | Use perceptual, gamut-aware color operations instead of naive RGB shifts. |
| 22 | [Evercoder/culori](https://github.com/Evercoder/culori) | Use OKLCH, interpolation, contrast, and separate dark-mode scale thinking. |
| 23 | [jxnblk/colorable](https://github.com/jxnblk/colorable) | Validate foreground/background combinations before treating a palette as ready. |
| 24 | [LeaVerou/contrast-ratio](https://github.com/LeaVerou/contrast-ratio) | Calculate contrast rather than guessing from screenshots or color names. |
| 25 | [tailwindlabs/tailwindcss](https://github.com/tailwindlabs/tailwindcss) | Use a deliberate token and responsive utility scale instead of arbitrary values. |
| 26 | [joe-bell/cva](https://github.com/joe-bell/cva) | Define finite component variant contracts rather than scattered conditional style branches. |
| 27 | [tailwindlabs/heroicons](https://github.com/tailwindlabs/heroicons) | Use simple consistent SVG silhouettes aligned to component anatomy and visible labels. |
| 28 | [tailwindlabs/prettier-plugin-tailwindcss](https://github.com/tailwindlabs/prettier-plugin-tailwindcss) | Keep utility ordering and visual intent maintainable rather than accumulating conflicting classes. |
| 29 | [catppuccin/catppuccin](https://github.com/catppuccin/catppuccin) | Treat light/dark palettes as coherent named systems with readable accents and surfaces. |
| 30 | [dracula/dracula-theme](https://github.com/dracula/dracula-theme) | Use a deliberate dark theme with semantic state colors and contrast-tested syntax/data tones. |
| 31 | [TanStack/query](https://github.com/TanStack/query) | Model remote data with cache keys, loading/error/empty states, invalidation, optimistic updates, and rollback. |
| 32 | [TanStack/table](https://github.com/TanStack/table) | Use explicit data-table state, sorting, filtering, pagination, column visibility, and accessible alternatives. |
| 33 | [TanStack/form](https://github.com/TanStack/form) | Model forms with field-level state, validation, submission lifecycle, and type-safe constraints. |
| 34 | [trpc/trpc](https://github.com/trpc/trpc) | Use typed client/server contracts, validated inputs, explicit error shapes, and no duplicated schemas. |
| 35 | [honojs/hono](https://github.com/honojs/hono) | Use small composable HTTP handlers, boundary validation, middleware, and portable runtime behavior. |
| 36 | [fastify/fastify](https://github.com/fastify/fastify) | Use schema-first routes, structured validation, plugin boundaries, and predictable performance behavior. |
| 37 | [expressjs/express](https://github.com/expressjs/express) | Use clear middleware ordering, secure error handling, route validation, and explicit status contracts. |
| 38 | [nestjs/nest](https://github.com/nestjs/nest) | Use modules, dependency boundaries, DTO validation, guards, and testable service/controller separation. |
| 39 | [OAI/OpenAPI-Specification](https://github.com/OAI/OpenAPI-Specification) | Document stable API contracts, errors, auth, pagination, versioning, and backward compatibility. |
| 40 | [scalar/scalar](https://github.com/scalar/scalar) | Provide human-readable API documentation, examples, authentication guidance, and a safe interactive explorer. |
| 41 | [prisma/prisma](https://github.com/prisma/prisma) | Use schema/migration discipline, relation integrity, seed data, transactions, and least-privilege database access. |
| 42 | [drizzle-team/drizzle-orm](https://github.com/drizzle-team/drizzle-orm) | Use typed schema definitions, explicit SQL boundaries, migrations, indexes, and transactional writes. |
| 43 | [supabase/supabase](https://github.com/supabase/supabase) | Use row-level security, auth boundaries, storage policies, realtime rules, and environment separation. |
| 44 | [better-auth/better-auth](https://github.com/better-auth/better-auth) | Use secure session/auth flows, provider boundaries, credential safety, and account recovery paths. |
| 45 | [nextauthjs/next-auth](https://github.com/nextauthjs/next-auth) | Use provider/session callbacks, protected routes, CSRF-safe flows, and role checks close to data access. |
| 46 | [clerk/javascript](https://github.com/clerk/javascript) | Use managed identity boundaries, organization roles, session awareness, and secure middleware integration. |
| 47 | [lucia-auth/lucia](https://github.com/lucia-auth/lucia) | Use explicit session lifecycle, secure cookies, CSRF protection, and controlled user/session persistence. |
| 48 | [kysely-org/kysely](https://github.com/kysely-org/kysely) | Use typed SQL, query boundaries, transactions, migrations, and query-plan-aware indexes. |
| 49 | [typeorm/typeorm](https://github.com/typeorm/typeorm) | Use entity relations, migrations, transaction scope, validation, and N+1 avoidance deliberately. |
| 50 | [redis/ioredis](https://github.com/redis/ioredis) | Use cache keys, TTL, invalidation, rate limits, queues, and connection handling without storing secrets in code. |
| 51 | [taskforcesh/bullmq](https://github.com/taskforcesh/bullmq) | Use durable queues, idempotent workers, retries/backoff, dead-letter handling, and status observability. |
| 52 | [temporalio/sdk-typescript](https://github.com/temporalio/sdk-typescript) | Model long-running workflows with durable state, retries, compensation, timeouts, and versioned activities. |
| 53 | [inngest/inngest](https://github.com/inngest/inngest) | Use event-driven functions, idempotency keys, step boundaries, retries, scheduling, and observability. |
| 54 | [triggerdotdev/trigger.dev](https://github.com/triggerdotdev/trigger.dev) | Use durable background jobs, schedules, retries, progress, and safe environment configuration. |
| 55 | [socketio/socket.io](https://github.com/socketio/socket.io) | Use authenticated rooms, reconnection, event schemas, presence, rate limits, and fallback polling behavior. |
| 56 | [websockets/ws](https://github.com/websockets/ws) | Use explicit WebSocket lifecycle, authentication, heartbeat, backpressure, reconnect, and message validation. |
| 57 | [graphql/graphql-js](https://github.com/graphql/graphql-js) | Use explicit schemas, input validation, resolver authorization, depth/complexity controls, and error hygiene. |
| 58 | [apollographql/apollo-client](https://github.com/apollographql/apollo-client) | Use normalized cache policy, loading/error states, mutations, invalidation, and optimistic rollback. |
| 59 | [hasura/graphql-engine](https://github.com/hasura/graphql-engine) | Use role-aware permissions, metadata migration, generated APIs, event triggers, and auditability. |
| 60 | [nats-io/nats.js](https://github.com/nats-io/nats.js) | Use subject naming, request/reply timeouts, durable consumers, backpressure, and message contracts. |
| 61 | [microsoft/playwright](https://github.com/microsoft/playwright) | Test user-visible flows through roles, web-first assertions, responsive projects, and no arbitrary waits. |
| 62 | [vitest-dev/vitest](https://github.com/vitest-dev/vitest) | Use fast isolated unit tests, deterministic fixtures, clear assertions, coverage, and watchable local feedback. |
| 63 | [testing-library/react-testing-library](https://github.com/testing-library/react-testing-library) | Test behavior through accessible roles and labels, not implementation internals. |
| 64 | [cypress-io/cypress](https://github.com/cypress-io/cypress) | Use stable end-to-end flows, retryable assertions, network control, and real browser feedback. |
| 65 | [dequelabs/axe-core](https://github.com/dequelabs/axe-core) | Automate accessibility checks but supplement them with keyboard, focus, and screen-reader logic tests. |
| 66 | [pa11y/pa11y](https://github.com/pa11y/pa11y) | Run repeatable page-level accessibility checks and treat violations as release blockers. |
| 67 | [eslint/eslint](https://github.com/eslint/eslint) | Enforce code correctness, security-aware linting, and a rule set that catches real defects. |
| 68 | [prettier/prettier](https://github.com/prettier/prettier) | Keep formatting deterministic so reviews focus on behavior, not whitespace. |
| 69 | [typescript-eslint/typescript-eslint](https://github.com/typescript-eslint/typescript-eslint) | Use TypeScript-aware linting, avoid unsafe any, and preserve strict boundary types. |
| 70 | [semgrep/semgrep](https://github.com/semgrep/semgrep) | Use static security patterns for injection, auth, secrets, dangerous sinks, and unsafe dependencies. |
| 71 | [open-telemetry/opentelemetry-js](https://github.com/open-telemetry/opentelemetry-js) | Instrument meaningful traces, metrics, context propagation, and error boundaries for critical workflows. |
| 72 | [getsentry/sentry-javascript](https://github.com/getsentry/sentry-javascript) | Capture actionable client/server errors with safe context and user-facing recovery, not silent failures. |
| 73 | [pinojs/pino](https://github.com/pinojs/pino) | Use structured logs, stable event names, redaction, correlation IDs, and no sensitive payloads. |
| 74 | [siimon/prom-client](https://github.com/siimon/prom-client) | Expose meaningful service metrics, labels, histograms, counters, and alertable error/latency signals. |
| 75 | [GoogleChrome/web-vitals](https://github.com/GoogleChrome/web-vitals) | Measure LCP, INP, CLS, and interaction attribution instead of making unverified performance claims. |
| 76 | [OWASP/ASVS](https://github.com/OWASP/ASVS) | Apply authentication, authorization, validation, session, cryptography, logging, and deployment verification controls. |
| 77 | [OWASP/CheatSheetSeries](https://github.com/OWASP/CheatSheetSeries) | Use practical secure defaults for password storage, CSRF, input validation, file upload, headers, and logging. |
| 78 | [snyk/snyk](https://github.com/snyk/snyk) | Audit dependencies, identify vulnerable packages, pin/upgrade safely, and document supply-chain risk. |
| 79 | [dependabot/dependabot-core](https://github.com/dependabot/dependabot-core) | Keep dependency updates reviewable, grouped, tested, and compatible with security policy. |
| 80 | [aquasecurity/trivy](https://github.com/aquasecurity/trivy) | Scan filesystem, containers, dependencies, IaC, and secrets before release; remediate rather than suppress findings. |
| 81 | [stripe/stripe-node](https://github.com/stripe/stripe-node) | Use server-side payment intents, webhook signature verification, idempotency, receipts, and no client-side secrets. |
| 82 | [resend/resend-node](https://github.com/resend/resend-node) | Use authenticated transactional email, templates, safe recipient handling, retries, and delivery visibility. |
| 83 | [nodemailer/nodemailer](https://github.com/nodemailer/nodemailer) | Use transport configuration through environment variables, validation, rate limits, and failure handling. |
| 84 | [pingdotgg/uploadthing](https://github.com/pingdotgg/uploadthing) | Use authenticated uploads, server-side file policy, type/size limits, cleanup, and secure URLs. |
| 85 | [transloadit/uppy](https://github.com/transloadit/uppy) | Use resumable uploads, progress, validation, recovery, and accessible drop/picker interfaces. |
| 86 | [meilisearch/meilisearch](https://github.com/meilisearch/meilisearch) | Use indexed search, typo tolerance, filter safety, permissions, and explicit no-result states. |
| 87 | [algolia/algoliasearch-client-javascript](https://github.com/algolia/algoliasearch-client-javascript) | Use search indexing, debounced query, facets, analytics privacy, and graceful offline/no-result behavior. |
| 88 | [typesense/typesense](https://github.com/typesense/typesense) | Use schema-first search, scoped keys, filters, ranking, facets, and predictable search latency. |
| 89 | [posthog/posthog-js](https://github.com/posthog/posthog-js) | Use privacy-aware analytics, feature flags, event naming, consent, and no sensitive event data. |
| 90 | [serwist/serwist](https://github.com/serwist/serwist) | Use PWA caching, offline strategy, update lifecycle, service-worker safety, and network fallback. |
| 91 | [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | Use explicit cache strategies, precache/runtime separation, offline behavior, and safe updates. |
| 92 | [vercel/ai](https://github.com/vercel/ai) | Use streaming UI with cancellation, model/provider boundaries, validation, error states, and human review where needed. |
| 93 | [langchain-ai/langchainjs](https://github.com/langchain-ai/langchainjs) | Use explicit retrieval/tool boundaries, prompt/data validation, tracing, and safe fallback behavior. |
| 94 | [mastra-ai/mastra](https://github.com/mastra-ai/mastra) | Use agent/workflow boundaries, typed tools, evaluations, observability, and guardrails for AI actions. |
| 95 | [microsoft/semantic-kernel](https://github.com/microsoft/semantic-kernel) | Use plugin boundaries, planners, memory/retrieval controls, evaluation, and secure orchestration. |
| 96 | [xyflow/xyflow](https://github.com/xyflow/xyflow) | Use graph/node state, keyboard controls, bounds, persistence, accessibility, and performance for large canvases. |
| 97 | [recharts/recharts](https://github.com/recharts/recharts) | Use labelled data visualizations, responsive containers, tooltips, legends, tables, and reduced-motion readability. |
| 98 | [plouc/nivo](https://github.com/plouc/nivo) | Use accessible chart configuration, bounded data density, color-safe palettes, and fallback tables. |
| 99 | [emilkowalski/sonner](https://github.com/emilkowalski/sonner) | Use non-blocking toast stacks with action/undo, accessible announcements, dismissal, and timing discipline. |
| 100 | [colinhacks/zod](https://github.com/colinhacks/zod) | Validate every external boundary with schemas, actionable errors, inferred types, and server/client consistency. |

## Production system prompt contract

The extra 10,000 prompts no longer request a single-file demo. They request working **Next.js App Router + TypeScript + PostgreSQL + Prisma** systems, with real server-side persistence, secure auth/roles, Zod validation, migrations, seed data, Docker Compose, tests, Playwright critical flow coverage, accessibility, observability, Docker/deploy setup, environment validation, health checks, CI guidance, rollback strategy, and explicit external-provider boundaries. A text-only AI is told to emit a complete file tree and essential file contents; an agent with filesystem access is told to create/run the application.

No API key, build process, external image, or remote AI call is needed to browse this single HTML archive.
