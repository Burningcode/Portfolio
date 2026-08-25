# PROBE Product Analysis

PROBE is a structured way to turn an ambiguous product situation into a decision and a learning loop:

```text
Purpose → Reality → Obstacles → Bets → Experiments → updated Reality
```

Use it when a team is circling a problem, debating solutions without shared evidence, or carrying an initiative whose purpose is no longer connected to its work.

This is an original, public-safe operationalization inspired by licensed PROBE materials created by Ethan Tan / Exponentially.io and copyrighted by Pureplay Studios Ltd. It does not reproduce the course worksheets, private examples, or source canvas.

## When to use it

- **Quick PROBE:** a small, reversible choice that needs a 20-minute reset.
- **Initiative PROBE:** a product opportunity, recovery plan, or discovery sequence.
- **Strategic PROBE:** a portfolio decision with multiple actors, constraints, or feedback loops.

Do not use the strategic version to make a small decision look important. Use the smallest depth that can change the decision.

## The decision contract

Before gathering the team, write:

```text
Decision this analysis must change:
Decision owner:
Decision date:
Evidence window:
What happens if we do nothing:
```

If there is no owner or decision date, the exercise is likely analysis theater.

## Prepare the evidence pack

Bring the smallest credible set of sources:

- direct research or observed user behavior;
- product and business outcomes with definitions and dates;
- operational and support signals;
- architecture, policy, capacity, and incentive constraints;
- prior decisions and rejected alternatives; and
- contradictory evidence or known gaps.

Label every statement as **fact**, **evaluation**, **inference**, or **unknown**. Evidence quality matters more than the number of artifacts.

## Run the sequence

### P — Purpose

Define the destination before debating the route.

Ask:

- What should become meaningfully better for a specific user or affected party?
- What observable behavior needs to change?
- Why does that outcome matter now?
- By when must useful progress be visible?
- What metric would indicate progress, and what harm must not increase?

Write the purpose as an outcome, not a feature:

```text
[User in context] can [make progress / change behavior]
so that [user and business outcome],
measured by [metric contract] without [guardrail violation].
```

### R — Reality

Describe current conditions without making the purpose sound inevitable.

Separate two views:

| External reality | Internal reality |
| --- | --- |
| User behavior, journey, alternatives, market, partners, regulation | Capabilities, architecture, incentives, decision rights, data quality, capacity |

For each claim, record its source, date, population, and confidence. Actively seek the strongest evidence that would challenge the preferred story.

### O — Obstacles

Find the mechanisms preventing Reality from becoming Purpose.

Use this form:

```text
[Actor or system] cannot or does not [needed behavior]
because [mechanism], which prevents [purpose-linked outcome].
Evidence: [source]. Confidence: [high / medium / low].
```

Separate symptoms from causes. “Conversion is low” is an outcome. “Eligible sellers cannot predict which attributes are mandatory before publication” is a mechanism the team can investigate.

Prioritize only a few obstacles using four questions:

1. If removed, how much progress would it unlock?
2. How strong is the evidence for the mechanism?
3. Can the team influence it?
4. What is the cost of being wrong?

### B — Bets

Generate multiple responses for each priority obstacle. Include product, communication, policy, process, data, and operating-model changes where relevant.

Each bet needs:

- the obstacle it addresses;
- the causal mechanism;
- the expected behavior change;
- new friction or second-order effects;
- the riskiest assumption;
- reversibility; and
- a reason it may fail.

Do not compare bets until the team has produced genuinely different mechanisms. Three interface variations are usually one bet.

### E — Experiments and execution

Turn the assumption with the largest blast radius into the smallest credible learning step.

```text
We believe [bet] will change [behavior] for [population]
because [mechanism]. We will test this through [method].
We will continue if [threshold], modify if [range],
and stop if [invalidating result or guardrail breach].
```

Define the unit of analysis, authoritative source, duration, threshold, owner, cost boundary, and stopping condition before observing the result.

## A 90-minute working session

| Time | Activity | Output |
| --- | --- | --- |
| 0–10 min | Confirm decision, owner, and evidence rules | Decision contract |
| 10–25 min | Write Purpose individually, then reconcile | Outcome and guardrails |
| 25–45 min | Map external/internal Reality | Evidence and unknowns |
| 45–60 min | Generate and prioritize mechanisms | Two or three obstacles |
| 60–75 min | Diverge on responses | Distinct bets |
| 75–90 min | Choose assumption test and decision rule | First experiment |

Use silent writing before discussion to reduce anchoring. The decision owner speaks after the evidence and alternatives have been heard.

## PROBE Decision Canvas

| Decision | Owner | Timeframe | Confidence |
| --- | --- | --- | --- |
| [Decision to change] | [Role] | [Window] | [H/M/L + why] |

| Purpose | Reality | Priority obstacle |
| --- | --- | --- |
| [Outcome, behavior, success, guardrail] | [Strongest external/internal evidence and unknown] | [Mechanism preventing progress] |

| Bet | Riskiest assumption | First experiment |
| --- | --- | --- |
| [Response and causal mechanism] | [What must be true] | [Method, population, metric, threshold, owner] |

**Decision rule:** [continue / modify / stop conditions]

**Learning loop:** [how the result updates Reality and the next decision]

## Fictional example: first-listing completion

**Situation:** Orbit Market wants more new sellers to publish an accurate first listing.

- **Purpose:** Eligible new sellers publish one accurate listing during their first setup session without increasing incorrect catalog data or support contacts.
- **Reality:** Completion falls most sharply after category selection. Attribute requirements vary by category. Support cases describe uncertainty, but mobile behavior has not been reconciled with transactional outcomes.
- **Obstacle:** Sellers cannot predict which attributes will be mandatory before attempting publication.
- **Bets:** Progressive requirements guidance; category-specific examples; or a smaller starter listing with deferred enrichment.
- **Riskiest assumption:** Uncertainty about requirements—not inventory readiness, trust, or a technical defect—is the dominant mechanism.
- **Experiment:** Prototype progressive guidance for one high-volume category. Compare verified first-listing completion and time to publish while monitoring incorrect-data and support-contact guardrails.

Notice that the experiment tests the mechanism before funding a platform-wide redesign.

## Learning log

| Date | Result and evidence quality | Reality updated | Obstacle change | Bet decision | Next owner/date |
| --- | --- | --- | --- | --- | --- |
| [Date] | [Observed result] | [What is now more or less likely] | [Up/down/same] | [Continue/modify/stop] | [Owner/date] |

PROBE is a loop. If the result is not used to update Reality, the team has run an activity, not a learning system.

## Agent-ready adaptation

An agent can gather authorized evidence, label claims, cluster obstacle statements, generate counter-hypotheses, draft the canvas, and check traceability. It must not invent sources, choose product strategy, set production experiments, or infer permission to alter roadmaps. The accountable human owns the purpose, trade-offs, test approval, and decision.

## Quality gate

- One decision, owner, and date are named.
- Purpose describes a behavior and outcome, not a feature.
- External and internal Reality are separated.
- Claims carry evidence labels and confidence.
- Each obstacle names a mechanism and purpose-linked impact.
- Each bet connects to an obstacle and a risky assumption.
- The first experiment has a metric contract, threshold, guardrails, and decision rule.
- The result has an explicit path back into Reality.

[Back to playbooks →](README.md)

