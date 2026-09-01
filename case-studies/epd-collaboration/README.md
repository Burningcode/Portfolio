# Case study: Improving Collaboration Across Engineering, Product, and Design

[Back to case studies](../README.md) · [Back to portfolio](../../README.md)

> **Portfolio note:** This is a public-safe synthesis of a product-development system I co-designed and operationalized with Engineering, Product, and Design partners. It preserves the operating model, my contribution, and a verified cycle-time result while excluding former-employer systems, internal links, individual contributors, and confidential implementation detail. It should not be read as sole authorship of a collaborative system.

## Executive summary

The delivery problem was not a lack of effort. Teams were losing time to evolving requirements, dates committed before the experience and technical approach were understood, hidden scope changes, unclear ownership, late quality work, and context scattered across tools. Product, Design, and Engineering could each be doing reasonable work while the initiative as a whole remained difficult to predict or learn from.

I helped develop and operationalize a six-stage product-development system from **Ideation** through **Learn**. A small cross-functional leadership group shared accountability for each initiative. At kickoff, that group defined the minimum useful **Artifacts, Ceremonies, and Expectations (ACE)** for the work. The stages made confidence visible: relative sizing early, a low-confidence range during Discovery, refined scope and estimates after experience and technical design, and committed dates only when fidelity supported them.

For initiatives that did not require new user research, the system reduced time from Ideation to the start of Development from eight weeks to four. It also localized product, design, technical, and decision context across Jira, GitHub, Figma, Cursor, and coding agents so smaller tasks could move from clear requirements into tickets and pull requests without asking an agent to infer product strategy or authority.

## The collaboration problem

The system was designed around recurring failure modes:

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

## What the six stages looked like

| Stage | How Product, Design, and Engineering worked together | Decision or exit gate |
| --- | --- | --- |
| **1. Ideation** | Define the problem, target user and behavior, strategic fit, initial evidence, and relative size. Keep the brief centered on the problem rather than a preferred feature. | Decide whether the problem is worth funding for Discovery now. |
| **2. Discovery** | Confirm the ACE agreement and stakeholder cadence; involve dependent teams; explore genuinely different approaches with low-fidelity flows, technical input, and a low-confidence estimate. | Select the simplest effective direction and explain why any added complexity is justified. |
| **3. Design** | Bring the experience and technical approach to build-ready fidelity. Validate the flow where needed; identify architecture, platform, data, privacy, and reliability implications; define instrumentation and success measures. | Approve the experience and technical plan, lock explicit scope, and make a medium-confidence forecast. |
| **4. Development** | Kick off from shared scope and risks; keep stories linked to decisions and designs; test function, integration, responsiveness, and design quality; implement instrumentation; prepare support and go-to-market work in parallel. | Pass the agreed quality checks and assemble evidence for a go/no-go recommendation. |
| **5. Launch** | Complete operational readiness, UAT, monitoring, rollout and rollback planning, customer communication, and support ownership. Verify that the product and its health are observable. | The accountable humans make and record the go/no-go decision. |
| **6. Learn** | Compare behavior and business outcomes with the hypothesis and thresholds; combine data with user feedback; examine incidents and operating cost; make segment differences visible. | Decide to iterate, invest further, scale, pause, or stop—and create new work for that decision. |

## The rules that changed behavior

### Confidence had to rise before precision

Early sizing was useful for comparing opportunities, not promising dates. Discovery preserved flexibility through a low-confidence range. Dates became commitments only after the experience and technical design exposed meaningful dependencies. A material scope change after that point required a new trade-off and forecast.

### Quality was cross-functional work

Acceptance criteria were not a substitute for collaboration. Product clarified the intended behavior and business rules. Design reviewed the implemented experience. Engineering built and exercised the test strategy. The group shared UAT, instrumentation, readiness, and the release recommendation.

### Decisions lived with the work

The current problem, requirements, designs, technical boundaries, accepted trade-offs, non-goals, test expectations, and decision history had to be easy for builders to find. This improved human handoffs and created a bounded context contract for coding agents: an agent could implement clear work, but it could not invent missing product strategy, authority, or irreversible permissions.

### Learning ended with a choice

The Learn stage was not complete when a dashboard or retrospective existed. It ended when the team recommended a next action against the original outcome: continue, change, scale, pause, or stop.

## Outcome and limits

For initiatives not requiring new user research, time from Ideation to Development start fell from eight weeks to four. That measure is a stage-cycle result, not total delivery time, feature throughput, or proof that every initiative moved twice as fast.

The system localized product, design, technical, and decision context for teams and coding agents. It did not eliminate every organizational bottleneck. Executive alignment and access to decision-makers remained a meaningful headwind when a bet required approval outside the cross-functional group.

## What this demonstrates

- Cross-functional operating-system design grounded in actual delivery failure modes.
- Shared accountability without blurring functional expertise or decision rights.
- Honest confidence management instead of premature delivery precision.
- Quality, measurement, launch readiness, and learning treated as product work.
- Agent-ready context with explicit human authority and approval boundaries.

For the reusable version of the method, see the [agent-ready product development playbook](../../playbooks/agent-ready-product-development.md).
