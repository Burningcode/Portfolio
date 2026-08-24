# A concise, agent-ready product development playbook

This public-safe playbook is an abbreviated synthesis of a six-stage operating model I co-designed. It preserves the reusable product principles while excluding former-employer systems, people, internal governance, links, data, and implementation detail.

## The outcome

Create a repeatable path from an important problem to a measurable result. The process should improve decision quality and context quality while remaining proportionate to the size and risk of the bet.

## Shared ownership

Each initiative has a small cross-functional leadership group:

- **Product:** owns the problem, target behavior, business outcome, and priorities.
- **Design:** owns the experience, research plan, usability, and interaction quality.
- **Technical lead:** owns feasibility, architecture, system quality, and technical trade-offs.
- **Engineering lead:** owns delivery health, resourcing, execution, and sustainable pace.

The group makes trade-offs together. Material decisions, changed assumptions, and scope changes are recorded where builders and agents can find them.

## ACE working agreement

At the start of the work, define the minimum useful **Artifacts, Ceremonies, and Expectations**:

- **Artifacts:** the living sources of truth, such as the product brief, decision log, designs, technical plan, backlog, evaluation plan, and dashboard.
- **Ceremonies:** only the working sessions needed to make decisions, review quality, or unblock the team.
- **Expectations:** decision rights, response times, stakeholder cadence, quality bar, scope-change rules, and human approval points.

ACE is a contract for how the team will work, not a fixed checklist imposed on every project.

## Six stages

| Stage | Key question | Minimum evidence and outputs | Exit gate | Useful agent role |
| --- | --- | --- | --- | --- |
| **1. Ideation** | Is this problem important enough to investigate now? | Problem statement, target user and behavior, strategic fit, initial evidence, alternatives, rough size. | A named decision-maker funds discovery or explicitly stops the bet. | Synthesize source material, map assumptions, identify missing evidence, draft the brief. |
| **2. Discovery** | What is the simplest effective approach? | User and business insight, option set, value/usability/feasibility/viability risks, dependencies, low-confidence estimate, explicit non-goals. | The team selects a direction and can explain why its complexity is justified. | Research, cluster feedback, compare options, model scenarios, surface contradictions. |
| **3. Design** | Is the chosen approach build-ready and measurable? | Validated flow, high-fidelity experience where needed, technical design, threat/privacy review, instrumentation and evaluation plan, refined scope and estimate. | Scope is explicit; UX and technical reviews pass; dates reflect current fidelity. | Draft stories and acceptance criteria, check traceability, generate test cases, critique silent failures. |
| **4. Development** | Are we building the intended outcome with observable quality? | Groomed work, linked decisions and designs, tests, instrumentation, evaluation fixtures, launch and support preparation. | The experience passes agreed functional, design, security, data, and evaluation checks. | Implement bounded work, open pull requests, run tests, document decisions, flag context drift. |
| **5. Launch** | Can we release safely and operate the result? | Go/no-go evidence, rollout and rollback plan, monitoring, customer/support readiness, ownership and escalation paths. | The accountable humans approve release; product and operational health are observable. | Run readiness checks, analyze preflight results, monitor signals, summarize anomalies. |
| **6. Learn** | Did behavior and business outcomes change enough to continue? | Results versus hypothesis and threshold, qualitative feedback, segment analysis, incidents, cost and quality findings, next-bet recommendation. | Decide to iterate, invest, scale, pause, or stop; create new work rather than hiding it in the retrospective. | Reconcile data sources, synthesize feedback, test hypotheses, draft the decision memo. |

## Confidence should rise by stage

- **Ideation:** relative size and directional value only.
- **Discovery:** low-confidence effort range; flexibility is still an asset.
- **Design:** refined estimate after experience and technical decisions expose dependencies.
- **Development:** dates reflect explicit scope. Material scope change requires a new trade-off and forecast.

Premature precision is not rigor. It disguises uncertainty and creates incentives to skip learning.

## The agent-ready context contract

An initiative is ready for coding or workflow agents when the repository or task context makes these items easy to find:

1. Problem, target user, and behavior to create.
2. Source-grounded requirements and explicit non-goals.
3. Decision log with current assumptions and rejected alternatives.
4. Relevant architecture, data contracts, designs, and interface boundaries.
5. Small, testable work with acceptance criteria and examples.
6. Tool and data permissions, plus actions that always require human approval.
7. Test, evaluation, observability, rollout, and rollback expectations.
8. A named human accountable for the product decision and release.

Agents should not infer missing authority, product strategy, or irreversible permissions from an implementation task.

## AI product quality contract

For an AI experience, define three levels before launch:

- **Quality floor:** the minimum acceptable behavior; below this, do not ship or automatically fall back.
- **Target:** the performance needed for the product to create sustained value.
- **Delight:** the behavior that feels meaningfully better than the prior workflow.

Also document:

- Silent failure modes and how they become observable.
- Authoritative product state versus model-generated interpretation.
- Human review, escalation, override, and recovery paths.
- Evaluation set, primary metric, segment checks, and success threshold.
- Cost, latency, and quality trade-offs at the workflow level.
- Security, privacy, data retention, and tool-permission boundaries.

## Product judgment checkpoint

Before a material commitment, answer:

1. What behavior are we trying to create?
2. Who benefits immediately?
3. Who experiences new friction?
4. What second-order effects should we expect?
5. What feedback loop changes?
6. What assumption deserves explicit pushback?

If the team cannot answer these clearly, more backlog detail will not make the product ready.

## Proportional process

Small, reversible changes may combine stages and use a short brief. Large, cross-system, regulated, or hard-to-reverse bets need deeper discovery, explicit risk ownership, stronger evaluation, staged rollout, and more deliberate approvals. The stages stay stable; the amount of ceremony changes.

