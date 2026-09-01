# Case study: Improving Collaboration Across Engineering, Product, and Design

[Back to case studies](../README.md) · [Back to portfolio](../../README.md)

> **Portfolio note:** This is a public-safe synthesis of a product-development process I co-designed and operationalized with Engineering, Product, and Design partners. It preserves the working model, my contribution, and a verified cycle-time result while excluding former-employer systems, internal links, individual contributors, and confidential implementation detail. It should not be read as sole authorship of a collaborative process.

## Executive summary

The delivery problem was not a lack of effort. Teams were losing time to evolving requirements, dates committed before the experience and technical approach were understood, hidden scope changes, unclear ownership, late quality work, and context scattered across tools. Product, Design, and Engineering could each be doing reasonable work while the initiative as a whole remained difficult to predict or learn from.

I helped develop and operationalize a six-stage product-development process from **Ideation** through **Learn**. A small cross-functional leadership group shared accountability for each initiative. At kickoff, that group defined the minimum useful **Artifacts, Ceremonies, and Expectations (ACE)** for the work. The stages made confidence visible: relative sizing early, a low-confidence range during Discovery, refined scope and estimates after experience and technical design, and committed dates only when fidelity supported them.

For initiatives that did not require new user research, the process reduced time from Ideation to the start of Development from eight weeks to four. It also kept the current problem, requirements, designs, technical decisions, scope changes, and measurement plan close to the work in Jira, GitHub, and Figma.

## The collaboration problem

The process was designed around recurring failure modes:

- A solution arrived before the customer or business problem was clear.
- Product, Design, and Engineering joined at different points and inherited decisions they had not helped shape.
- Early estimates hardened into commitments before dependencies, usability, or technical feasibility were known.
- Scope changed without an explicit trade-off, new forecast, or durable decision record.
- Quality, instrumentation, support readiness, and go-to-market work accumulated near launch.
- Teams shipped, moved on, and treated learning as a retrospective instead of a new investment decision.

The goal was not to add a universal checklist. It was to give teams a shared language for choosing the right work, making decisions at the right fidelity, and scaling the process to the size and reversibility of the bet.

## The operating model

### Shared ownership from day one

Each initiative had a small cross-functional leadership group:

- **Product** owned the problem, target behavior, business outcome, priorities, and success measures.
- **Design** owned the experience, research plan, usability, accessibility, and interaction quality.
- **Technical leadership** owned feasibility, architecture, system quality, and technical trade-offs.
- **Engineering management** owned delivery health, resourcing, execution, and sustainable pace.

The group owned alignment, trade-offs, and delivery together. Material scope, timing, and quality decisions required discussion and a visible decision record. When the group could not align, it escalated the competing options and consequences instead of escalating a political disagreement.

### An ACE agreement for each initiative

At the start of the work, the team chose the minimum useful:

- **Artifacts:** living sources of truth such as the problem brief, research synthesis, designs, technical plan, backlog, decision log, measurement plan, and dashboard.
- **Ceremonies:** only the working sessions needed to make decisions, review quality, or unblock delivery.
- **Expectations:** decision rights, response times, stakeholder cadence, quality bar, design fidelity, scope-change rules, and named coverage.

ACE made the collaboration contract explicit without pretending that a small reversible change and a large cross-system initiative need the same amount of process.

### Working norms behind the process

The mechanics worked only if the team also changed how it handled disagreement and accountability:

- Start together so no discipline inherits a direction it did not help shape.
- Share reasoning and unfinished work early enough for another expert to challenge it.
- Debate important trade-offs directly and with empathy; avoid artificial harmony and backchannel decisions.
- Once the group reaches a decision—or a named leader resolves an escalation—commit to the direction and surface new evidence instead of quietly reopening the debate.
- Judge the process by customer and business results, not by how many artifacts or meetings it produces.
- Treat defects and missed assumptions as learning inputs, not occasions to assign blame.

## How work moved through the six stages

Every stage followed the same basic pattern:

1. Confirm that the required inputs exist and are current.
2. Bring the right Product, Design, Engineering, and partner perspectives into the work.
3. Produce the decisions and documents the next stage needs.
4. Record the exit decision instead of letting work drift forward by default.

The documents below are not all required for every initiative. The cross-functional group used its ACE agreement to choose the smallest set that matched the size, risk, and reversibility of the work.

The underlying work named the one-pager, PRD, research and testing synthesis, low- and high-fidelity designs, technical design, Jira/JPD, QA/UAT, operational-readiness review, dashboards, and learning summary. I have grouped those documents by the stage where they are created or consumed. The **as needed** lists show what a team could add when a particular risk or dependency required it.

### 1. Ideation — decide which problems deserve attention

**Inputs**

- A customer, business, operational, or technical signal worth investigating.
- Initial evidence from feedback, research, product data, incidents, strategy, or market context.
- Enough context to identify the affected user and the behavior or outcome that may need to change.

**Working model**

Product framed the problem and strategic relevance. Design and Engineering challenged assumptions, added user and system context, and helped expose obvious dependencies or constraints. The group did only enough early research and relative sizing to decide whether the problem merited Discovery.

**Outputs and exit decision**

- A problem-led one-pager or product idea, not a preselected feature specification.
- A lightweight PRD draft aligned by the cross-functional group.
- A relative size such as pebble, rock, or boulder.
- A clear decision to fund Discovery now, hold the idea, or stop.

**Documents**

- **Core:** product idea or one-pager; lightweight PRD draft.
- **As needed:** customer-feedback summary, product-data snapshot, incident summary, competitive context, early research notes.

### 2. Discovery — choose the simplest effective direction

**Inputs**

- The approved problem statement and lightweight PRD.
- Initial evidence, known assumptions, and relative size.
- The decision to spend time shaping an approach.

**Working model**

The group set its ACE agreement, identified stakeholders and dependent teams, and agreed on how decisions and updates would work. Product, Design, and Engineering explored more than one approach using low-fidelity flows, technical input, and partner expertise. Options were compared on whether they solved the problem and what complexity they introduced across the experience, technology, operations, organization, and business.

**Outputs and exit decision**

- A chosen direction and a written explanation of why it is the best current option.
- Explicit non-goals, assumptions, dependencies, and material trade-offs.
- Stakeholder and dependent-team alignment.
- A low-confidence effort range that preserves flexibility.
- A decision to advance to Design, continue Discovery, or stop.

**Documents**

- **Core:** ACE working agreement; updated PRD; low-fidelity flows or mocks; dependency list; decision record; initial Jira/JPD structure.
- **As needed:** stakeholder map, research plan and synthesis, competitive analysis, option comparison, technical spike, data assessment, Legal/Privacy/Security review notes.

### 3. Design — make the experience and technical plan build-ready

**Inputs**

- The selected direction, updated PRD, non-goals, and decision record.
- Low-fidelity flows, research findings, known dependencies, and ACE agreement.
- The low-confidence effort range from Discovery.

**Working model**

Design brought the experience to the fidelity needed for review and testing. Engineering completed the technical design and exposed architecture, infrastructure, platform, data, reliability, and migration implications. Product kept the work tied to the intended behavior and business outcome. Together, the group defined success measures, instrumentation, risks, final scope, and the quality bar.

**Outputs and exit decision**

- Approved experience designs and a clickable prototype where useful.
- A reviewed technical design and estimate.
- Finalized epics, acceptance criteria, and dependencies.
- A measurement plan covering events, dashboards, and outcome review.
- Locked scope and a medium-confidence forecast; later scope changes require a new trade-off and date.
- A decision that the initiative is build-ready or needs more Design work.

**Documents**

- **Core:** current PRD; high-fidelity designs; technical design; epics and acceptance criteria; measurement and instrumentation plan.
- **As needed:** usability-test plan and synthesis, data/event specification, privacy or threat review, accessibility review, design-system exception, migration plan, dependency agreement, launch experiment design.

### 4. Development — build, test, and prepare to operate the product

**Inputs**

- Locked scope, approved designs, technical design, and current decision record.
- Groomed epics and acceptance criteria.
- The measurement plan, quality bar, and known launch requirements.

**Working model**

The group began with a development kickoff covering scope, priorities, risks, and unresolved questions. Engineering built and tested each slice. Design stayed engaged through implementation and design QA. Product clarified business rules and evaluated whether the slices still served the intended outcome. Test planning began before final UAT, and instrumentation, support, and go-to-market preparation moved alongside the build rather than waiting for the end.

**Outputs and exit decision**

- A release candidate that passes the agreed functional, integration, responsive, and design checks.
- Working instrumentation and launch dashboards.
- Completed or scheduled UAT with material issues resolved or explicitly accepted.
- A draft go-to-market and support plan.
- A cross-functional go/no-go recommendation for Launch.

**Documents**

- **Core:** groomed backlog; linked designs and technical plan; test plan and test cases; design-QA record; decision and scope-change log; dashboard specification; draft go-to-market plan.
- **As needed:** UAT plan, data-QA checklist, dependency delivery plan, support runbook, release checklist, training or enablement materials.

### 5. Launch — release safely and make the product operable

**Inputs**

- The release candidate and quality evidence.
- The cross-functional go/no-go recommendation.
- UAT results, operational-readiness work, dashboards, alerts, support ownership, and customer communication plan.

**Working model**

Product, Design, Engineering, Support, and go-to-market partners reviewed readiness together. The team verified the customer experience, operational ownership, monitoring, communications, and recovery path. The release decision was made from evidence, not from the calendar alone.

**Outputs and exit decision**

- A recorded go/no-go decision and, when approved, a live product.
- A completed operational-readiness review.
- Working dashboards, monitoring, and alerts.
- Customer communication, support coverage, and availability rules in place.
- A clear owner for early results, incidents, and escalation.

**Documents**

- **Core:** go/no-go record; operational-readiness review; UAT sign-off; monitoring and dashboard links; customer communication and support plan.
- **As needed:** phased-rollout plan, rollback plan, incident-response guide, escalation matrix, launch checklist, internal enablement materials.

### 6. Learn — decide what happens next

**Inputs**

- The original problem, hypothesis, success measures, and decision thresholds.
- Product behavior and business results from the agreed measurement window.
- Customer feedback, support themes, incidents, operating cost, and quality findings.

**Working model**

Product, Design, Engineering, Data, and relevant partners compared results with the original goals. They looked at both aggregate and segmented behavior, combined quantitative results with qualitative evidence, and separated a product problem from an operating, adoption, or measurement problem.

**Outputs and exit decision**

- A clear result against the original hypothesis and measures.
- A documented summary of what worked, what did not, and what remains uncertain.
- A recommendation to iterate, invest further, scale, pause, de-scope, or stop.
- New work created for the next decision instead of being hidden inside the retrospective.

**Documents**

- **Core:** outcome readout; learning summary; recommendation or decision memo; updated product idea, roadmap, or backlog.
- **As needed:** research synthesis, segmented funnel analysis, experiment readout, incident review, cost analysis, follow-up PRD, revised measurement plan.

## The rules that changed behavior

### Confidence had to rise before precision

Early sizing was useful for comparing opportunities, not promising dates. Discovery preserved flexibility through a low-confidence range. Dates became commitments only after the experience and technical design exposed meaningful dependencies. A material scope change after that point required a new trade-off and forecast.

### Quality was cross-functional work

Acceptance criteria were not a substitute for collaboration. Product clarified the intended behavior and business rules. Design reviewed the implemented experience. Engineering built and exercised the test strategy. The group shared UAT, instrumentation, readiness, and the release recommendation.

### Decisions lived with the work

The current problem, requirements, designs, technical boundaries, accepted trade-offs, non-goals, test expectations, and decision history had to be easy for the team to find. The goal was to prevent each new conversation or handoff from rebuilding the project from memory.

### Learning ended with a choice

The Learn stage was not complete when a dashboard or retrospective existed. It ended when the team recommended a next action against the original outcome: continue, change, scale, pause, or stop.

## Outcome and limits

For initiatives not requiring new user research, time from Ideation to Development start fell from eight weeks to four. That measure is a stage-cycle result, not total delivery time, feature throughput, or proof that every initiative moved twice as fast.

The process localized product, design, technical, and decision context for the team. It did not eliminate every organizational bottleneck. Executive alignment and access to decision-makers remained a meaningful headwind when a bet required approval outside the cross-functional group.

## What this demonstrates

- A process built around problems teams were actually experiencing.
- Shared accountability without blurring functional expertise or decision rights.
- Estimates that became more specific only as the work became clearer.
- Quality, measurement, launch readiness, and learning treated as product work.
- A repeatable handoff from evidence to decisions, delivery, launch, and learning.

## Language appendix

The source SDLC process used the terms below as working language. These definitions are paraphrased for public use and show how the vocabulary supported clearer ownership, decisions, and handoffs.

### Team operating language

| Term | Working definition | Why it mattered |
| --- | --- | --- |
| **ACE** | **Artifacts, Ceremonies, and Expectations:** the three parts of the team's collaboration model. | It made the mechanics of collaboration explicit instead of relying on individual habits. |
| **Artifact** | A living document or record that captures the current problem, decisions, changes, or progress. | It preserved context and gave the team a shared source of truth. |
| **Ceremony** | A recurring or purpose-built working session used to align, decide, review, or execute. | Each meeting had a job and produced a decision, action, or updated artifact. |
| **Expectation** | An agreed working norm covering roles, quality, communication, timelines, or accountability. | It exposed assumptions early and gave the team a standard for resolving friction. |
| **QUAD** | The Product Manager, Product Designer, Tech Lead, and Engineering Manager jointly leading an initiative. | It placed product, experience, technical direction, and delivery health in one accountable group. |

### Discovery and definition language

| Term | Working definition | Why it mattered |
| --- | --- | --- |
| **One-pager / project brief / Jira Idea** | A concise statement of the problem, target user, opportunity, expected outcome, risks, assumptions, and open questions. | It gave the team enough context to decide whether deeper discovery was warranted without pretending the solution was settled. |
| **PRD** | A Product Requirements Document describing the purpose, goals, success measures, intended behavior, users and use cases, constraints, dependencies, and scope. | It converted an agreed direction into a testable product contract while leaving implementation decisions with the right owners. |
| **User flow** | A map of the steps, screens, and decisions a person moves through to complete a task. | It helped the team find missing states, friction, and dependencies before build. |
| **User research** | Qualitative or quantitative evidence about users' needs, behaviors, motivations, and pain points. | It tested whether the team understood the problem and informed which opportunity to pursue. |
| **User testing** | Observation of people using a concept, design, or product to evaluate comprehension, usability, and fit. | It tested whether the proposed experience worked, not merely whether stakeholders liked it. |
| **Low fidelity** | Rough flows or wireframes focused on structure, hierarchy, and behavior rather than visual polish. | It made early options inexpensive to compare and change. |
| **High fidelity** | A detailed representation of the intended interface, content, and interactions. | It supported precise review, realistic testing, and build-ready communication. |
| **T-shirt estimate** | A relative effort or complexity range such as small, medium, or large rather than an exact date or hour count. | It supported early comparison without turning limited information into false precision. |

### Portfolio and release language

| Term | Working definition | Why it mattered |
| --- | --- | --- |
| **JPD** | Jira Product Discovery, used to manage product ideas, evidence, priority, and lifecycle state before and alongside delivery work. | It kept opportunity and decision context connected to execution. |
| **SDLC stage** | The current lifecycle position of an initiative: Ideation, Discovery, Design, Development, Launch, or Learn. | It answered, “Where is this work in the process?” |
| **Now / Next / Later** | A portfolio signal showing present commitment, likely future intent, or an option that remains open. | It answered, “How strongly are we betting on this, and roughly when?” without confusing priority with lifecycle progress. |
| **Pebble / Rock / Boulder** | Relative initiative sizes: a small and reversible change, a meaningful feature or system investment, or a large effort spanning much of a quarter or multiple teams. | It created a common way to discuss scope, dependencies, and planning expectations. |
| **UAT** | User Acceptance Testing: validation that the completed experience satisfies the agreed product behavior and business needs. | It supplied evidence for release readiness beyond implementation completion. |
| **ORR** | Operational Readiness Review: confirmation that monitoring, support, communications, ownership, and recovery plans are ready for release. | It made operability part of the product launch decision. |
| **Go / No-Go** | An explicit cross-functional decision to release or hold based on quality, user acceptance, operational readiness, and unresolved risk. | It prevented the calendar alone from determining whether a product shipped. |

For the shorter reusable version, see the [product development playbook](../../playbooks/agent-ready-product-development.md).
