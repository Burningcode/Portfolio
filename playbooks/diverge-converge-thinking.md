# Diverge → Converge: A Product Thinking Exercise

Teams often converge too early: the loudest idea becomes the plan, a stakeholder request becomes the problem, or three cosmetic variations are presented as strategic options. Divergent and convergent thinking create deliberate space to understand the problem, generate different mechanisms, and then commit using explicit evidence and trade-offs.

This exercise is an original facilitation playbook informed by the Design Council's public [Double Diamond](https://www.designcouncil.org.uk/resources/the-double-diamond/), which describes Discover, Define, Develop, and Deliver and is published under a CC BY 4.0 license.

## Use it when

- the team is anchored on one solution;
- a roadmap debate is producing advocacy instead of choices;
- discovery has produced many insights but no focus;
- an executive asks for options, but the alternatives are straw proposals; or
- the team needs a small set of experiments rather than a large idea inventory.

Do not use divergence to avoid a decision. The session ends with a choice, learning commitment, or explicit request for missing evidence.

## The two decision diamonds

```text
Evidence → diverge on problem → converge on priority challenge
        → diverge on responses → converge on bets and tests
```

The first diamond protects the team from solving the wrong problem. The second protects it from treating the first plausible response as inevitable.

## Roles

- **Decision owner:** states the decision and makes the final call.
- **Facilitator:** protects time, balanced participation, and process integrity.
- **Evidence steward:** distinguishes facts, inferences, and unknowns.
- **Cross-functional participants:** contribute different user, business, technical, operational, and risk perspectives.

The decision owner should avoid framing a preferred solution before divergence and should speak after independent options are visible.

## Prepare a one-page frame

```text
Decision:
User and context:
Desired outcome:
What we know, with sources:
What remains uncertain:
Constraints that are real:
Constraints that may be assumptions:
Decision owner and date:
```

Send the frame early enough for participants to inspect the evidence. Do not send a polished recommendation disguised as pre-read context.

## A 90-minute exercise

### 1. Align on the decision — 10 minutes

Confirm the decision, outcome, non-goals, and evidence labels. Ask what would make the session successful and what choice must exist at the end.

### 2. Diverge on the problem — 15 minutes

Use silent writing. Generate explanations through six lenses:

| Lens | Prompt |
| --- | --- |
| User | What progress, expectation, trust, or context may be breaking? |
| System | Where could a dependency, state transition, or feedback loop exert force? |
| Business | Which incentive, price, policy, or viability constraint matters? |
| Operations | Where do handoffs, queues, exceptions, or manual work change the experience? |
| Adversarial | How could misuse, gaming, harm, or silent failure appear? |
| Time | Is this a one-time event, trend, seasonality, learning effect, or delayed consequence? |

Write mechanisms, not vague themes. “Trust” is a topic; “users cannot distinguish verified providers before committing” is a mechanism.

### 3. Converge on the priority challenge — 15 minutes

Cluster overlapping mechanisms, then evaluate:

- purpose-linked impact;
- evidence strength;
- uncertainty;
- controllability; and
- cost of being wrong.

Choose one or two priority challenges. Preserve the rest in a parking lot with evidence needed—not a graveyard of discarded sticky notes.

### 4. Diverge on responses — 20 minutes

Generate responses from different mechanism classes:

- remove the need;
- change information or timing;
- change incentives or policy;
- reduce steps or decision load;
- add human service or recovery;
- automate bounded work;
- change the operating model; or
- deliberately do nothing and observe.

Use “How might we” only after the evidence-backed challenge is clear. Require at least three meaningfully different mechanisms before comparison.

### 5. Converge on bets — 20 minutes

For each candidate, complete an option card:

```text
Challenge addressed:
Causal mechanism:
Expected behavior change:
Immediate beneficiary:
New friction / who pays:
Second-order effect:
Riskiest assumption:
Reversibility:
Smallest credible test:
```

Evaluate through value, usability, feasibility, viability, safety, strategic fit, evidence, and reversibility. Scores can prompt discussion; they must not replace judgment. A weighted average can hide a fatal flaw.

### 6. Commit to learning — 10 minutes

The decision owner chooses:

- a bet to test;
- a challenge requiring more evidence;
- a reversible action to take now; or
- a reasoned stop/no-action decision.

Record owner, date, metric or evaluation signal, guardrails, and the result that would reverse the choice.

## Convergence scorecard

| Option | Evidence for mechanism | Outcome potential | New friction | Fatal assumption | Reversibility | Decision |
| --- | --- | --- | --- | --- | --- | --- |
| [Option] | [H/M/L + source] | [Expected change] | [Actor/cost] | [What must be true] | [H/M/L] | [Test/hold/stop] |

Do not sum the columns. Use them to expose where judgment differs.

## Fast version: 30 minutes

1. Five minutes: confirm decision and evidence.
2. Seven minutes: silent divergence on mechanisms.
3. Five minutes: select one challenge.
4. Seven minutes: generate distinct responses.
5. Six minutes: choose test, owner, and decision rule.

Use the fast version only for reversible choices with a bounded blast radius.

## Fictional example: low marketplace response

**Initial request:** “Add more reminders so service providers respond faster.”

**Problem divergence:** Providers may not see the request, may lack enough information to price it, may distrust lead quality, may already be at capacity, or may avoid declining because decline behavior affects ranking.

**Priority challenge:** Available providers cannot judge request fit and expected value quickly enough to respond with confidence.

**Response divergence:** Improve request completeness; expose fit indicators; offer structured decline reasons; route only to eligible providers; or change ranking consequences.

**Converged test:** For one service category, show a compact fit summary and structured decline path. Measure qualified response and decline rates, time to response, and customer wait-time guardrails. The test distinguishes information friction from notification frequency before adding more reminders.

## Remote and asynchronous use

- Collect independent written input before group discussion.
- Time-box comments and require evidence links.
- Ask each participant to steelman one option they did not propose.
- Publish the option cards and decision log after the session.
- Reopen only when new evidence crosses the stated decision rule.

## Agent-ready adaptation

An agent can prepare the evidence frame, generate alternative mechanisms, find option duplication, steelman and critique each bet, simulate edge cases, and check that decision criteria are applied consistently. The agent should not collapse to one recommendation before human divergence or infer organizational constraints that were not supplied. The accountable owner makes the trade-off.

## Common failure modes

- **Brainstorming without boundaries:** ideas are abundant but disconnected from an outcome.
- **Anchored divergence:** the sponsor names the answer before silent writing.
- **False options:** variants share the same causal mechanism.
- **Democratic strategy:** dot voting substitutes popularity for ownership and evidence.
- **Scorecard theater:** averages hide safety, feasibility, or viability failures.
- **Permanent divergence:** the team avoids commitment by requesting more possibilities.
- **Decision amnesia:** rejected ideas return because rationale and evidence were not preserved.

## Quality gate

- The exercise names one decision, owner, and date.
- Problem divergence happens before solution divergence.
- Claims are labeled as evidence, inference, or unknown.
- Options use genuinely different mechanisms.
- Each option names beneficiaries, friction, second-order effects, and a fatal assumption.
- Convergence uses explicit criteria without outsourcing judgment to a score.
- The session ends with a test, action, evidence request, or reasoned stop.

[Back to playbooks →](README.md)

