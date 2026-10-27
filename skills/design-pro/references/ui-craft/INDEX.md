# UI craft & taste — polish, typography, color, accessibility, interaction, animation

82 playbooks. Read only the one that matches the task.

- **`aesthetic-usability`** — Apply the Aesthetic-Usability Effect — polished, consistent interfaces are perceived as more usable and forgive minor friction. Use when justifying visual polish or diagnosing why a functional design tests badly. For emotional resonance spe…  
  `references/ui-craft/owl/aesthetic-usability.md` · Owl-Listener/designer-skills
- **`animate`** — Build an animation from scratch, making the decisions in the order that determines whether it feels right — should it animate at all, what purpose, which tool, which properties, which curve and duration, how it interrupts, how it exits. Wri…  
  `references/ui-craft/emil/animate.md` · emilkowalski/skills
- **`animate-expo`** — Build animations in React Native and Expo, making the decisions in the order that determines whether they feel right — should it animate, which thread it runs on, which properties, spring or timing, how the gesture hands off, how it degrade…  
  `references/ui-craft/emil/animate-expo.md` · emilkowalski/skills
- **`animation-performance`** — Keep web animations inside the frame budget — animate composite-only properties, keep motion off the main thread when the page is busy, and find the cause when an animation drops frames. Covers the layout/paint/composite pipeline, cheaper p…  
  `references/ui-craft/emil/animation-performance.md` · emilkowalski/skills
- **`animation-principles`** — Apply animation principles — easing, staging, follow-through — to one specific UI motion. Use when tuning how an animation feels. For product-wide duration and easing tokens use `motion-system` (design-systems); for a full interaction spec …  
  `references/ui-craft/owl/animation-principles.md` · Owl-Listener/designer-skills
- **`animation-vocabulary`** — Reverse-lookup glossary that turns a vague description of a web animation or motion effect into its exact term ("the bouncy thing when a popover opens" → Pop in; "the iOS rubber-band scroll" → Rubber-banding). Use when the user asks "what's…  
  `references/ui-craft/emil/animation-vocabulary.md` · emilkowalski/skills
- **`apple-design`** — Apple's approach to interface design and fluid, physical motion, translated for the web. Use when building or reviewing gesture-driven UI, spring animations, drag/swipe/sheet interactions, momentum and interruptible transitions, translucent…  
  `references/ui-craft/emil/apple-design.md` · emilkowalski/skills
- **`ask-sonner`** — Guide to Sonner, the React toast library — install and wire up the Toaster, pick the right toast() call, promise and loading toasts, updating, dismissing and persisting toasts, styling, theming and icons, positioning and multiple toasters. …  
  `references/ui-craft/emil/ask-sonner.md` · emilkowalski/skills
- **`audit-ai-design-slop`** — Audit websites, apps, screenshots, mockups, and design code for harmful AI-design clichés, generic generated defaults, and established UI defects. Use when the user wants evidence-backed design feedback, an anti-slop review, or a removal-fi…  
  `references/ui-craft/mengto/audit-ai-design-slop.md` · MengTo/Skills
- **`better-accessibility`** — Reviews and fixes keyboard and focus behavior, ARIA, accessible names, forms, screen-reader announcements, motion and zoom against WCAG 2.2.  
  `references/ui-craft/jakub/better-accessibility.md` · jakubkrehel/skills
- **`better-colors`** — Builds and checks color systems by generating palettes, naming semantic tokens, converting between formats and measuring contrast.  
  `references/ui-craft/jakub/better-colors.md` · jakubkrehel/skills
- **`better-interface`** — Reviews a screen, flow or whole interface across accessibility, layout, writing, typography, color and UI polish, and returns one ranked report.  
  `references/ui-craft/jakub/better-interface.md` · jakubkrehel/skills
- **`better-layout`** — Sets grouping, alignment, reading order, responsive structure and room for translated text, so a layout holds up when it is resized, translated or mirrored.  
  `references/ui-craft/jakub/better-layout.md` · jakubkrehel/skills
- **`better-typography`** — Sets and reviews how text renders, from the type scale and spacing to font features, wrapping, truncation and punctuation.  
  `references/ui-craft/jakub/better-typography.md` · jakubkrehel/skills
- **`better-ui`** — Polishes surfaces, icons and motion with exact values for border radius, optical alignment, shadows, icon states and animation.  
  `references/ui-craft/jakub/better-ui.md` · jakubkrehel/skills
- **`better-writing`** — Writes and reviews interface copy, from labels and errors to empty states and confirmations, so it matches the product's voice and tells people what to do next.  
  `references/ui-craft/jakub/better-writing.md` · jakubkrehel/skills
- **`break`** — Renders a component you choose under every scenario that can reach it on a temporary page and stress tests it.  
  `references/ui-craft/jakub/break.md` · jakubkrehel/skills
- **`break-ui`** — Try to break a piece of UI by feeding it worst-case data — long names, unbreakable emails, one-letter names, missing fields, huge counts, zero items, long labels, non-Latin text, emoji, extreme numbers — then render it behind a "Demo data /…  
  `references/ui-craft/emil/break-ui.md` · emilkowalski/skills
- **`build-design`** — Builds UI from a Figma file or a design image so it matches the design, using the project's existing tokens and components.  
  `references/ui-craft/jakub/build-design.md` · jakubkrehel/skills
- **`color-system`** — Build a product colour system — tonal scales, semantic roles, and contrast compliance. Use when defining or rebuilding colour from scratch. For dark-mode adaptation use `dark-mode-design`; for chart palettes use `data-visualization`; for mu…  
  `references/ui-craft/owl/color-system.md` · Owl-Listener/designer-skills
- **`conversational-ux`** — Design voice and conversational interfaces — dialog flows, error recovery, and persona. Use when the interface speaks and listens rather than being tapped. For graphical input collection, use `form-design`.  
  `references/ui-craft/owl/conversational-ux.md` · Owl-Listener/designer-skills
- **`critique-affordance`** — Critique a rendered screen's affordances — what looks clickable, state visibility, CTA clarity, and action discoverability. Use when reviewing an existing screen. For sizing and positioning targets in new work, use `fitts-law` (interaction-…  
  `references/ui-craft/owl/critique-affordance.md` · Owl-Listener/designer-skills
- **`critique-brand-consistency`** — Critique a rendered screen against mood.md, voice.md, and tokens.md. Use when those brand files exist and you are checking compliance. For defining the visual language itself, use `illustration-style` (ui-design).  
  `references/ui-craft/owl/critique-brand-consistency.md` · Owl-Listener/designer-skills
- **`critique-color`** — Critique a rendered screen's colour — contrast ratios, palette coherence, and semantic meaning. Use when reviewing one screen. For a product-wide WCAG audit use `accessibility-audit` (design-systems); for building the palette use `color-sys…  
  `references/ui-craft/owl/critique-color.md` · Owl-Listener/designer-skills
- **`critique-composition`** — Critique a rendered screen's composition — balance, whitespace, rhythm, and gestalt grouping. Use when a layout feels off but hierarchy is fine. For emphasis and eye flow specifically, use `critique-visual-hierarchy`.  
  `references/ui-craft/owl/critique-composition.md` · Owl-Listener/designer-skills
- **`critique-information-density`** — Critique a rendered screen's density — cognitive load, content prioritisation, scanning patterns, and progressive disclosure. Use when a screen feels overwhelming. For the underlying choice-count principle, use `hicks-law` (interaction-desi…  
  `references/ui-craft/owl/critique-information-density.md` · Owl-Listener/designer-skills
- **`critique-typography`** — Critique a rendered screen's typography — scale usage, readability, consistency, and token compliance. Use when reviewing type on a screen. For defining the scale itself, use `typography-scale` (ui-design).  
  `references/ui-craft/owl/critique-typography.md` · Owl-Listener/designer-skills
- **`critique-visual-hierarchy`** — Critique a rendered screen's hierarchy — entry point, eye flow, weight distribution, and emphasis. Use when attention lands in the wrong place. For establishing hierarchy in new work, use `visual-hierarchy` (ui-design).  
  `references/ui-craft/owl/critique-visual-hierarchy.md` · Owl-Listener/designer-skills
- **`dark-mode-design`** — Adapt an existing palette to dark mode — surface elevation, contrast rebalancing, and desaturation rules. Use when you already have a light palette to translate. For building the base palette first, use `color-system`.  
  `references/ui-craft/owl/dark-mode-design.md` · Owl-Listener/designer-skills
- **`data-visualization`** — Select chart types and design data encodings — marks, axes, labels, and accessible chart styling. Use when presenting data graphically. Owns chart selection and encoding only; the categorical colour ramp itself belongs to `color-system`.  
  `references/ui-craft/owl/data-visualization.md` · Owl-Listener/designer-skills
- **`design-first-ui-prompting`** — Use when you need design-first, spec-driven, skimmable prompts for UI generation. Covers prompt structure, constraints, variations, typography/spacing rules, and iteration workflow for consistent UI outputs.  
  `references/ui-craft/mengto/design-first-ui-prompting.md` · MengTo/Skills
- **`doherty-threshold`** — Apply the Doherty Threshold — keep system response under 400ms to preserve user flow. Use when diagnosing perceived slowness or setting a performance budget. For what to show during unavoidable waits, use `loading-states`.  
  `references/ui-craft/owl/doherty-threshold.md` · Owl-Listener/designer-skills
- **`emil-design-eng`** — This skill encodes Emil Kowalski's philosophy on UI polish, component design, animation decisions, and the invisible details that make software feel great.  
  `references/ui-craft/emil/emil-design-eng.md` · emilkowalski/skills
- **`error-handling-ux`** — Design error prevention, detection, and recovery across a product — message content, placement, and escape routes. Use when errors span multiple flows. For validation inside a single form, use `form-design`.  
  `references/ui-craft/owl/error-handling-ux.md` · Owl-Listener/designer-skills
- **`explain-interface`** — Explains how a website, a visual effect or an animation was built, from a live URL or a screenshot.  
  `references/ui-craft/jakub/explain-interface.md` · jakubkrehel/skills
- **`feedback-patterns`** — Design confirmations, status updates, and notifications that tell users an action registered. Use when the system must acknowledge success or change. For waiting states use `loading-states`; for failures use `error-handling-ux`.  
  `references/ui-craft/owl/feedback-patterns.md` · Owl-Listener/designer-skills
- **`find-animation-opportunities`** — Search a codebase or UI for places that don't animate but should, and reject everything that shouldn't. Read-only; it proposes motion with exact values, it does not implement it. Use when the user asks "what could be animated here?" or want…  
  `references/ui-craft/emil/find-animation-opportunities.md` · emilkowalski/skills
- **`fitts-law`** — Apply Fitts's Law — target acquisition time depends on size and distance. Use when sizing and positioning controls, especially for touch. For how many controls to show at once, use `hicks-law`.  
  `references/ui-craft/owl/fitts-law.md` · Owl-Listener/designer-skills
- **`form-design`** — Design a form end to end — field order, grouping, validation, and completion. Use when the artifact is a form. For product-wide error strategy use `error-handling-ux`; for first-run signup use `onboarding-design`.  
  `references/ui-craft/owl/form-design.md` · Owl-Listener/designer-skills
- **`gesture-patterns`** — Design gesture interactions for touch and pointer — swipe, drag, long-press, and their discoverability. Use when input is gestural. For OS-standard gestures on iOS and Android, use `platform-conventions` (ui-design).  
  `references/ui-craft/owl/gesture-patterns.md` · Owl-Listener/designer-skills
- **`hicks-law`** — Apply Hick's Law — decision time grows with the number of simultaneous choices. Use when a screen offers too many options at once. For how many items survive in memory afterwards, use `millers-law`.  
  `references/ui-craft/owl/hicks-law.md` · Owl-Listener/designer-skills
- **`ideagram`** — Turn a concept, feature description, blog post, or pitch into a single beautiful, on-brand illustration by matching it to a real unDraw illustration in a local library and recoloring it to the brand accent — genuine illustrator quality, not…  
  `references/ui-craft/tastemaker/ideagram.md` · codeswithroh/tastemaker
- **`illustration-style`** — Define an illustration style guide — visual language, colour usage, and application rules. Use when commissioning or standardising illustration. For icons, use `icon-system` (design-systems).  
  `references/ui-craft/owl/illustration-style.md` · Owl-Listener/designer-skills
- **`improve-animations`** — Survey a codebase's animation and motion code as a senior motion advisor, then produce a prioritized audit and self-contained implementation plans for other agents (or cheaper models) to execute. Read-only on source code — it plans improvem…  
  `references/ui-craft/emil/improve-animations.md` · emilkowalski/skills
- **`interface-review`** — Reviews a branch, pull request or uncommitted change for the interface problems it introduced or regressed, across accessibility, layout, writing, typography, color and UI.  
  `references/ui-craft/jakub/interface-review.md` · jakubkrehel/skills
- **`interfaces-that-feel`** — Apply an emotional resonance lens to a UI that is technically correct but flat, prescribing changes at the copy, motion, and interaction layer. Use when a design tests fine but lands cold. For the polish-perception argument, use `aesthetic-…  
  `references/ui-craft/owl/interfaces-that-feel.md` · Owl-Listener/designer-skills
- **`jakobs-law`** — Apply Jakob's Law — users expect your product to work like the others they already use. Use when deciding whether to innovate on a familiar pattern. For OS-mandated conventions specifically, use `platform-conventions` (ui-design).  
  `references/ui-craft/owl/jakobs-law.md` · Owl-Listener/designer-skills
- **`law-of-closure`** — Apply the Law of Closure — the eye completes implied shapes from partial forms. Use when reducing visual weight by dropping borders or letting negative space suggest structure. For explicit containers, use `law-of-common-region`.  
  `references/ui-craft/owl/law-of-closure.md` · Owl-Listener/designer-skills
- **`law-of-common-region`** — Apply the Law of Common Region — a shared container, background, or border groups elements regardless of spacing. Use when grouping must survive a tight layout. For grouping by spacing alone, use `law-of-proximity`.  
  `references/ui-craft/owl/law-of-common-region.md` · Owl-Listener/designer-skills
- **`law-of-continuity`** — Apply the Law of Continuity — the eye follows alignment and unbroken paths. Use when sequencing steps, aligning content, or designing carousels and timelines. For grouping rather than sequencing, use `law-of-proximity`.  
  `references/ui-craft/owl/law-of-continuity.md` · Owl-Listener/designer-skills
- **`law-of-figure-ground`** — Apply the Law of Figure-Ground — establish which layer is foreground and actionable versus background. Use when designing modals, overlays, and depth. For emphasising one element among peers, use `von-restorff-effect`.  
  `references/ui-craft/owl/law-of-figure-ground.md` · Owl-Listener/designer-skills
- **`law-of-proximity`** — Apply the Law of Proximity — spatial closeness groups elements more strongly than any other cue. Use when spacing alone must carry grouping. For grouping via containers use `law-of-common-region`; via shared appearance use `law-of-similarit…  
  `references/ui-craft/owl/law-of-proximity.md` · Owl-Listener/designer-skills
- **`law-of-similarity`** — Apply the Law of Similarity — shared colour, shape, or size signals that elements belong to one category. Use when signalling relationships across distance. For grouping by position, use `law-of-proximity`.  
  `references/ui-craft/owl/law-of-similarity.md` · Owl-Listener/designer-skills
- **`layout-grid`** — Define a responsive grid — columns, gutters, margins, and breakpoint behaviour. Use when establishing page structure. For the spacing scale inside components use `spacing-system`; for cross-device behaviour use `responsive-design`.  
  `references/ui-craft/owl/layout-grid.md` · Owl-Listener/designer-skills
- **`loading-states`** — Design waiting experiences — spinners, skeletons, optimistic updates, and progressive reveal. Use when content takes time to arrive. For the latency budget itself use `doherty-threshold`; for success confirmation use `feedback-patterns`.  
  `references/ui-craft/owl/loading-states.md` · Owl-Listener/designer-skills
- **`micro-interaction-spec`** — Specify one micro-interaction completely — trigger, rules, feedback, loops, and modes. Use when handing a single interaction to engineering. For motion craft alone use `animation-principles`; for multi-state components use `state-machine`.  
  `references/ui-craft/owl/micro-interaction-spec.md` · Owl-Listener/designer-skills
- **`millers-law`** — Apply Miller's Law — chunk information into groups of about four to fit working memory. Use when grouping fields, menu items, or steps. For reducing the number of choices offered, use `hicks-law`.  
  `references/ui-craft/owl/millers-law.md` · Owl-Listener/designer-skills
- **`mobile-native`** — Make a web app feel native on a phone — the small CSS and meta-tag fixes that separate "a website in a browser" from something that feels installed. Covers sticky hover states, tap highlight flashes, the 100vh bug, inputs that zoom the page…  
  `references/ui-craft/emil/mobile-native.md` · emilkowalski/skills
- **`navigation-patterns`** — Select and design a navigation pattern — tabs, drawer, hierarchy, or hub — matched to product structure and user tasks. Use when choosing how users move between sections. For the underlying content structure, use `information-architecture` …  
  `references/ui-craft/owl/navigation-patterns.md` · Owl-Listener/designer-skills
- **`no-ai-design-slop`** — Prevent and remove generic AI-generated design defaults, incoherent visual choices, and established UI defects while creating, revising, or reviewing websites, apps, screenshots, mockups, and design code. Use as a passive quality gate durin…  
  `references/ui-craft/mengto/no-ai-design-slop.md` · MengTo/Skills
- **`onboarding-design`** — Design the first-run experience — activation path, progressive disclosure, and time to first value. Use for a user's very first session. For the mechanics of the signup form itself, use `form-design`.  
  `references/ui-craft/owl/onboarding-design.md` · Owl-Listener/designer-skills
- **`peak-end-rule`** — Apply the Peak-End Rule — a flow is remembered by its most intense moment and its last. Use when designing completion, celebration, or cancellation moments. For sustaining engagement mid-flow, use `zeigarnik-effect`.  
  `references/ui-craft/owl/peak-end-rule.md` · Owl-Listener/designer-skills
- **`pick-ui-library`** — Pick the right library for a given frontend task from a curated, opinionated list — numbers, OTP inputs, charts, command menus, virtualization, drag and drop, toasts, state, styling, and more. Only runs when explicitly invoked; it does not …  
  `references/ui-craft/emil/pick-ui-library.md` · emilkowalski/skills
- **`platform-conventions`** — Design to iOS and Android conventions — what each OS mandates, where they diverge, and when to unify. Use when shipping native apps. For breakpoint adaptation use `responsive-design`; for matching competitor patterns use `jakobs-law` (inter…  
  `references/ui-craft/owl/platform-conventions.md` · Owl-Listener/designer-skills
- **`prototype`** — Build multiple genuinely different versions of a UI piece you describe, rendered behind a visual picker so you can flip through them live and promote the one that feels right. Only runs when explicitly invoked; it does not trigger on its ow…  
  `references/ui-craft/emil/prototype.md` · emilkowalski/skills
- **`readable-measure`** — Set line length and measure for comfortable reading across type sizes and breakpoints. Use when tuning body text. Covers measure only — for the full size and weight scale, use `typography-scale`.  
  `references/ui-craft/owl/readable-measure.md` · Owl-Listener/designer-skills
- **`responsive-design`** — Design layouts and interactions that adapt across screen sizes and input methods. Use when one design must serve many viewports. For the underlying column grid use `layout-grid`; for OS-specific patterns use `platform-conventions`.  
  `references/ui-craft/owl/responsive-design.md` · Owl-Listener/designer-skills
- **`review-animations`** — Reviews animation and motion code against a high craft bar derived from Emil Kowalski's design engineering philosophy. Default to flagging; approval is earned.  
  `references/ui-craft/emil/review-animations.md` · emilkowalski/skills
- **`search-ux`** — Design search — query input, zero results, refinement, and result presentation. Use when users retrieve rather than browse. For browse structure, use `navigation-patterns`.  
  `references/ui-craft/owl/search-ux.md` · Owl-Listener/designer-skills
- **`serial-position-effect`** — Apply the Serial Position Effect — first and last items in a sequence are recalled best. Use when ordering menus, lists, and steps. For emphasising one item regardless of its position, use `von-restorff-effect` (ui-design).  
  `references/ui-craft/owl/serial-position-effect.md` · Owl-Listener/designer-skills
- **`spacing-system`** — Create a spacing scale from a base unit with rules for when each step applies. Use when standardising padding and margins. For page-level columns and gutters, use `layout-grid`.  
  `references/ui-craft/owl/spacing-system.md` · Owl-Listener/designer-skills
- **`state-machine`** — Model component behaviour as explicit states, events, and transitions. Use when a component has many interacting states that must be exhaustive. For the feel and feedback of a single interaction, use `micro-interaction-spec`.  
  `references/ui-craft/owl/state-machine.md` · Owl-Listener/designer-skills
- **`state-machine`** — Renders every state of a component you choose on a throwaway page, with mock data and a switcher, so you can work on each state.  
  `references/ui-craft/jakub/state-machine.md` · jakubkrehel/skills
- **`tastemaker`** — Generate genuinely beautiful, on-brand UI instead of generic "AI slop" — use whenever the user asks to build, design, style, or improve a UI, landing page, dashboard, app screen, or component, whenever a PRD/spec needs a design pass before …  
  `references/ui-craft/tastemaker/tastemaker.md` · codeswithroh/tastemaker
- **`teardown`** — Creates technical illustrations of physical objects and of how things work, such as display pixels or interface layers, with coherent views, fine linework and part fills.  
  `references/ui-craft/jakub/teardown.md` · jakubkrehel/skills
- **`teslers-law`** — Apply Tesler's Law — every process has irreducible complexity that someone must absorb. Use when deciding whether the product or the user carries it. For reducing apparent choice, use `hicks-law`.  
  `references/ui-craft/owl/teslers-law.md` · Owl-Listener/designer-skills
- **`typography-scale`** — Create a modular type scale with size, weight, and line-height relationships. Use when establishing typographic structure. For line length only use `readable-measure`; for judging type on an existing screen use `critique-typography` (visual…  
  `references/ui-craft/owl/typography-scale.md` · Owl-Listener/designer-skills
- **`variant`** — Builds multiple variants of a component you're working on and helps you iterate and pick one.  
  `references/ui-craft/jakub/variant.md` · jakubkrehel/skills
- **`visual-hierarchy`** — Establish hierarchy through size, weight, colour, spacing, and position so the eye lands in the intended order. Use when composing new work. For judging an existing screen, use `critique-visual-hierarchy` (visual-critique).  
  `references/ui-craft/owl/visual-hierarchy.md` · Owl-Listener/designer-skills
- **`von-restorff-effect`** — Apply the Von Restorff Effect — the element that differs from its neighbours is the one remembered. Use when a single action must dominate. For overall ordering rather than single-element emphasis, use `visual-hierarchy`.  
  `references/ui-craft/owl/von-restorff-effect.md` · Owl-Listener/designer-skills
- **`write-swift`** — How to write modern Swift well — modeling with value types, Swift 6 data-race safety and approachable concurrency (@concurrent, main-actor-by-default, actors, task groups), protocols and generics (some vs any), API design, performance and A…  
  `references/ui-craft/emil/write-swift.md` · emilkowalski/skills
- **`zeigarnik-effect`** — Apply the Zeigarnik Effect — incomplete tasks stay mentally active. Use when designing progress indicators, saved drafts, and return hooks. For the emotional shape of the ending, use `peak-end-rule`.  
  `references/ui-craft/owl/zeigarnik-effect.md` · Owl-Listener/designer-skills
