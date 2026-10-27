# Design process — research, strategy, systems, ops, critique, handoff

63 playbooks. Read only the one that matches the task.

- **`a-b-test-design`** — Design an A/B experiment — hypothesis, variants, primary metric, and sample size. Use when a change can be measured quantitatively at scale. For observing behaviour qualitatively, use `test-scenario`.  
  `references/process/owl/a-b-test-design.md` · Owl-Listener/designer-skills
- **`accessibility-audit`** — Audit an existing interface against WCAG, producing findings with severity ratings and remediation steps. Use when you have a design or build to assess now. Not for planning future sessions with assistive-technology users — use `accessibili…  
  `references/process/owl/accessibility-audit.md` · Owl-Listener/designer-skills
- **`accessibility-test-plan`** — Plan accessibility testing — assistive technologies, participant criteria, WCAG coverage, and session protocol. Use when scheduling testing with real AT users. Not for evaluating a design yourself — use `accessibility-audit` (design-systems…  
  `references/process/owl/accessibility-test-plan.md` · Owl-Listener/designer-skills
- **`affinity-diagram`** — Cluster many qualitative data points into themes and insight statements. Use when synthesising across multiple sessions or sources. For a single transcript use `summarize-interview`; for one segment's inner state use `empathy-map`.  
  `references/process/owl/affinity-diagram.md` · Owl-Listener/designer-skills
- **`behavioural-analytics`** — Read funnels, retention curves, and event data as a designer — separating a design problem from a tracking artefact. Use when handed product data you did not design and asked why people drop off. For choosing what to measure, use `metrics-d…  
  `references/process/owl/behavioural-analytics.md` · Owl-Listener/designer-skills
- **`business-design`** — Read financials, map competitive landscapes, and argue design decisions in the language of value. Use when defending design to commercial stakeholders. For the live negotiation itself, use `design-negotiation` (designer-toolkit).  
  `references/process/owl/business-design.md` · Owl-Listener/designer-skills
- **`card-sort-analysis`** — Analyse open or closed card sort results into a proposed grouping and label set. Use after running a sort study. For turning that evidence into a full structure, use `information-architecture` (ux-strategy).  
  `references/process/owl/card-sort-analysis.md` · Owl-Listener/designer-skills
- **`case-study`** — Craft a portfolio case study with narrative arc, process evidence, and outcomes. Use when telling a project's story to an external audience. For an internal stakeholder deck, use `presentation-deck`.  
  `references/process/owl/case-study.md` · Owl-Listener/designer-skills
- **`click-test-plan`** — Design first-click and click tests for findability and navigation. Use when testing whether people can locate something. For full task-based observation, use `test-scenario`.  
  `references/process/owl/click-test-plan.md` · Owl-Listener/designer-skills
- **`competitive-analysis`** — Compare UX patterns, features, strengths, and gaps across rival products. Use when you need to know what others actually do. For deliberately adopting their conventions, use `jakobs-law` (interaction-design).  
  `references/process/owl/competitive-analysis.md` · Owl-Listener/designer-skills
- **`component-spec`** — Specify one component — props, states, variants, accessibility, and usage rules. Use when defining a library component. For the reusable doc scaffold use `documentation-template`; for a problem-solution pattern use `pattern-library`.  
  `references/process/owl/component-spec.md` · Owl-Listener/designer-skills
- **`concept-selection`** — Choose between competing concepts against criteria fixed in advance, and record what each rejected concept was testing. Use when several directions are alive and one has to win. For picking which problem to work on, use `opportunity-framewo…  
  `references/process/owl/concept-selection.md` · Owl-Listener/designer-skills
- **`content-strategy`** — Define what content a product needs, how it is structured, and who owns it. Use when content itself is the problem. For the words in the interface use `ux-writing` (designer-toolkit); for structural hierarchy use `information-architecture`.  
  `references/process/owl/content-strategy.md` · Owl-Listener/designer-skills
- **`design-brief`** — Write a project brief — problem space, constraints, audience, and success criteria. Use at kickoff for one specific project. For long-horizon aspiration use `north-star-vision`; for reusable decision rules use `design-principles`.  
  `references/process/owl/design-brief.md` · Owl-Listener/designer-skills
- **`design-critique`** — Facilitate a structured team critique — framing, feedback rules, and actionable outcomes. Use when running a session with people in the room. For a solo expert review, use `heuristic-evaluation` (prototyping-testing).  
  `references/process/owl/design-critique.md` · Owl-Listener/designer-skills
- **`design-debt-audit`** — Inventory and prioritise accumulated design inconsistencies across a product. Use when drift has built up over time. For token coverage specifically use `design-token-audit` (designer-toolkit); for WCAG gaps use `accessibility-audit` (desig…  
  `references/process/owl/design-debt-audit.md` · Owl-Listener/designer-skills
- **`design-impact-reporting`** — Communicate design's contribution to business and user outcomes in stakeholder language. Use when reporting results upward. For choosing the metrics in the first place, use `metrics-definition` (ux-strategy).  
  `references/process/owl/design-impact-reporting.md` · Owl-Listener/designer-skills
- **`design-negotiation`** — Advocate for design quality, scope, and timeline with partners and leadership using evidence and shared goals. Use in the conversation itself. For the commercial vocabulary behind it, use `business-design` (ux-strategy).  
  `references/process/owl/design-negotiation.md` · Owl-Listener/designer-skills
- **`design-principles`** — Define actionable principles that resolve trade-offs when the team disagrees. Use when the same decisions keep getting relitigated. For a single project's framing, use `design-brief`.  
  `references/process/owl/design-principles.md` · Owl-Listener/designer-skills
- **`design-qa-checklist`** — Build a QA checklist for verifying that a build matches the design. Use at implementation review. For the spec engineers build from, use `handoff-spec`.  
  `references/process/owl/design-qa-checklist.md` · Owl-Listener/designer-skills
- **`design-rationale`** — Write rationale connecting decisions to user needs, business goals, and principles. Use when a decision needs defending in writing. For a live conversation, use `design-negotiation`.  
  `references/process/owl/design-rationale.md` · Owl-Listener/designer-skills
- **`design-review-process`** — Establish review gates — criteria, checkpoints, and approval flow. Use when work ships without consistent review. For running one individual session, use `design-critique`.  
  `references/process/owl/design-review-process.md` · Owl-Listener/designer-skills
- **`design-sprint-plan`** — Plan and facilitate a design sprint from challenge framing through prototype testing. Use when compressing discovery into days. For ongoing team cadence, use `team-workflow`.  
  `references/process/owl/design-sprint-plan.md` · Owl-Listener/designer-skills
- **`design-system-adoption`** — Create adoption strategy and enablement materials to drive design system usage. Use when the system exists but teams ignore it. For contribution and versioning rules, use `design-system-governance` (design-systems).  
  `references/process/owl/design-system-adoption.md` · Owl-Listener/designer-skills
- **`design-system-governance`** — Define how the system evolves — contribution model, versioning, deprecation, and change management. Use when multiple teams contribute. For driving uptake use `design-system-adoption` (designer-toolkit); for design file history use `version…  
  `references/process/owl/design-system-governance.md` · Owl-Listener/designer-skills
- **`design-token`** — Define and organise tokens for colour, spacing, type, and elevation with naming and usage rules. Use when establishing the token layer. For auditing existing usage use `design-token-audit` (designer-toolkit); for multi-brand mapping use `th…  
  `references/process/owl/design-token.md` · Owl-Listener/designer-skills
- **`design-token-audit`** — Audit token usage across a product for coverage, drift, and hard-coded values. Use when tokens exist and you suspect they are being bypassed. For defining tokens in the first place, use `design-token` (design-systems).  
  `references/process/owl/design-token-audit.md` · Owl-Listener/designer-skills
- **`diary-study-plan`** — Design a diary study — prompts, cadence, duration, participant criteria, and analysis frame. Use when behaviour unfolds over days or weeks. For a single-session study, use `usability-test-plan`.  
  `references/process/owl/diary-study-plan.md` · Owl-Listener/designer-skills
- **`documentation-template`** — Generate a reusable documentation scaffold for components, patterns, or guidelines. Use when standardising how the system is documented. For the content of one component's spec, use `component-spec`.  
  `references/process/owl/documentation-template.md` · Owl-Listener/designer-skills
- **`empathy-map`** — Build a Says, Thinks, Does, Feels map for one user or segment. Use when sharing user understanding quickly. For a composite archetype with goals and behaviours use `user-persona`; for cross-session themes use `affinity-diagram`.  
  `references/process/owl/empathy-map.md` · Owl-Listener/designer-skills
- **`experience-map`** — Map the full ecosystem of touchpoints, channels, and relationships across a service. Use when the experience spans more than one product. For one persona's linear journey use `journey-map` (design-research); for backstage operations use `se…  
  `references/process/owl/experience-map.md` · Owl-Listener/designer-skills
- **`handoff-spec`** — Write the implementation handoff — measurements, behaviours, assets, states, and edge cases. Use when engineering picks up the work. For verifying the result afterwards use `design-qa-checklist`; for reusable library components use `compone…  
  `references/process/owl/handoff-spec.md` · Owl-Listener/designer-skills
- **`heuristic-evaluation`** — Run an expert review against Nielsen's heuristics and domain criteria, with severity ratings. Use when you need findings without recruiting participants. For a facilitated team feedback session, use `design-critique` (design-ops).  
  `references/process/owl/heuristic-evaluation.md` · Owl-Listener/designer-skills
- **`icon-system`** — Specify an icon system — grid, sizing, stroke weight, naming, categories, and implementation. Use when standardising iconography. For broader illustration, use `illustration-style` (ui-design).  
  `references/process/owl/icon-system.md` · Owl-Listener/designer-skills
- **`information-architecture`** — Design content structure, hierarchy, labelling, and the navigation model. Use when organising what exists. For the UI that exposes it use `navigation-patterns` (interaction-design); for user-generated grouping evidence use `card-sort-analys…  
  `references/process/owl/information-architecture.md` · Owl-Listener/designer-skills
- **`interview-script`** — Write a structured interview guide — warm-up, core exploration, and wrap-up. Use before running interviews. For analysing what comes back, use `summarize-interview`.  
  `references/process/owl/interview-script.md` · Owl-Listener/designer-skills
- **`jobs-to-be-done`** — Map functional, emotional, and social jobs with outcome expectations. Use when reframing decisions around motivation rather than features. For who the user is, use `user-persona`.  
  `references/process/owl/jobs-to-be-done.md` · Owl-Listener/designer-skills
- **`journey-map`** — Map one persona's end-to-end experience with stages, touchpoints, emotions, and pain points. Use when improving an existing experience. For the multi-channel ecosystem use `experience-map` (ux-strategy); for screen-level paths use `user-flo…  
  `references/process/owl/journey-map.md` · Owl-Listener/designer-skills
- **`localization-design`** — Design for multiple languages, writing directions, and cultural contexts — text expansion, RTL mirroring, and locale formats. Use when shipping beyond one locale. For the words themselves, use `ux-writing` (designer-toolkit).  
  `references/process/owl/localization-design.md` · Owl-Listener/designer-skills
- **`metrics-definition`** — Define UX metrics and KPIs that connect design decisions to measurable outcomes. Use when choosing what to measure. For presenting the results afterwards, use `design-impact-reporting` (design-ops).  
  `references/process/owl/metrics-definition.md` · Owl-Listener/designer-skills
- **`motion-system`** — Define motion tokens — durations, easing vocabulary, and reduced-motion handling — for consistency product-wide. Use when standardising motion across a system. For crafting one specific animation, use `animation-principles` (interaction-des…  
  `references/process/owl/motion-system.md` · Owl-Listener/designer-skills
- **`naming-convention`** — Establish naming rules for components, tokens, and layers with patterns and worked examples. Use when names are inconsistent or being set. For what the tokens actually contain, use `design-token`.  
  `references/process/owl/naming-convention.md` · Owl-Listener/designer-skills
- **`north-star-vision`** — Articulate a long-horizon product vision that aligns teams and anchors strategy. Use when direction is contested or absent. For near-term project scope, use `design-brief`.  
  `references/process/owl/north-star-vision.md` · Owl-Listener/designer-skills
- **`opportunity-framework`** — Identify, score, and prioritise design opportunities against impact and effort. Use when there are more ideas than capacity. For framing the one you choose, use `design-brief`.  
  `references/process/owl/opportunity-framework.md` · Owl-Listener/designer-skills
- **`parallel-concepts`** — Build several genuinely different solutions to the same problem at once, spread across what the user does rather than how it looks. Use when one direction is on the table and the team is about to refine it by default. For choosing between t…  
  `references/process/owl/parallel-concepts.md` · Owl-Listener/designer-skills
- **`pattern-library`** — Structure a pattern entry — problem context, solution, usage examples, and related patterns. Use when documenting a recurring solution rather than a component. For a single component's API, use `component-spec`.  
  `references/process/owl/pattern-library.md` · Owl-Listener/designer-skills
- **`presentation-deck`** — Structure a design presentation for a specific audience and decision. Use when presenting internally. For a portfolio narrative use `case-study`; for the written argument use `design-rationale`.  
  `references/process/owl/presentation-deck.md` · Owl-Listener/designer-skills
- **`prototype-strategy`** — Choose prototype fidelity and method to match the design question and the decision at stake. Use before building a prototype. For what to test once it exists, use `test-scenario`.  
  `references/process/owl/prototype-strategy.md` · Owl-Listener/designer-skills
- **`qual-quant-triangulation`** — Reconcile what the numbers say with what users say, and design the study that settles it rather than restates it. Use when behavioural data and research findings point different ways. For reading the data on its own, use `behavioural-analyt…  
  `references/process/owl/qual-quant-triangulation.md` · Owl-Listener/designer-skills
- **`research-repository`** — Build a repository that makes findings findable, reusable, and cumulative across teams. Use when the same research keeps getting redone. For synthesising one study, use `affinity-diagram`.  
  `references/process/owl/research-repository.md` · Owl-Listener/designer-skills
- **`service-blueprint`** — Map service delivery across frontstage actions, backstage processes, and supporting systems. Use when staff and operations are part of the experience. For the customer-visible layer only, use `experience-map`.  
  `references/process/owl/service-blueprint.md` · Owl-Listener/designer-skills
- **`stakeholder-alignment`** — Build alignment artifacts — responsibility matrices, decision rights, and communication plans. Use when unclear ownership stalls decisions. For persuading in the moment, use `design-negotiation` (designer-toolkit).  
  `references/process/owl/stakeholder-alignment.md` · Owl-Listener/designer-skills
- **`summarize-interview`** — Turn one interview transcript into themes, supporting quotes, and action items. Use immediately after a session. For synthesising many sessions at once, use `affinity-diagram`.  
  `references/process/owl/summarize-interview.md` · Owl-Listener/designer-skills
- **`survey-design`** — Design unbiased survey instruments — question wording, scales, and sampling — to measure attitudes at scale. Use when you need quantitative breadth. For behavioural experiments, use `a-b-test-design` (prototyping-testing).  
  `references/process/owl/survey-design.md` · Owl-Listener/designer-skills
- **`team-workflow`** — Design the team's operating rhythm — task management, collaboration rituals, and tooling. Use when the day-to-day cadence needs structure. For a time-boxed sprint, use `design-sprint-plan`.  
  `references/process/owl/team-workflow.md` · Owl-Listener/designer-skills
- **`test-scenario`** — Write realistic usability task scenarios with success criteria and facilitation notes. Use when you have a study and need the tasks. For the surrounding study design, use `usability-test-plan` (design-research).  
  `references/process/owl/test-scenario.md` · Owl-Listener/designer-skills
- **`theming-system`** — Design theming architecture — brand variants, dark mode, and high-contrast — mapped through token layers. Use when one system must serve multiple themes. For a single palette use `color-system` (ui-design); for dark mode craft use `dark-mod…  
  `references/process/owl/theming-system.md` · Owl-Listener/designer-skills
- **`usability-test-plan`** — Design a usability study — research questions, methodology, participant criteria, metrics, and facilitation guide. Use when planning the study as a whole. For writing the task scenarios inside it, use `test-scenario` (prototyping-testing).  
  `references/process/owl/usability-test-plan.md` · Owl-Listener/designer-skills
- **`user-flow-diagram`** — Diagram screen-level paths, decision points, and branch logic. Use when specifying how a feature is traversed. For the emotional end-to-end arc, use `journey-map` (design-research).  
  `references/process/owl/user-flow-diagram.md` · Owl-Listener/designer-skills
- **`user-persona`** — Build research-grounded personas with goals, frustrations, and behavioural patterns. Use when decisions need a consistent user reference. For one session's emotional snapshot use `empathy-map`; for motivation framing use `jobs-to-be-done`.  
  `references/process/owl/user-persona.md` · Owl-Listener/designer-skills
- **`ux-writing`** — Write interface copy — microcopy, error messages, empty states, and CTAs. Use when the words are the deliverable. For content structure and ownership, use `content-strategy` (ux-strategy).  
  `references/process/owl/ux-writing.md` · Owl-Listener/designer-skills
- **`version-control-strategy`** — Define version control for design files, components, and libraries — branching, naming, and release. Use when file history is chaotic. For design system contribution rules, use `design-system-governance` (design-systems).  
  `references/process/owl/version-control-strategy.md` · Owl-Listener/designer-skills
- **`wireframe-spec`** — Specify wireframe layout — content priority, component placement, and annotation. Use when defining structure before visual design. For grid mechanics, use `layout-grid` (ui-design).  
  `references/process/owl/wireframe-spec.md` · Owl-Listener/designer-skills
