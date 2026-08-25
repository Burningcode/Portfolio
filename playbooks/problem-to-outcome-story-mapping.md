# Problem-to-Outcome Story Mapping

A story map should do more than arrange backlog cards. It should connect a real user's current experience to a testable future outcome and then slice the smallest coherent experiences that can deliver value or reduce uncertainty.

This public-safe playbook combines an evidence-backed journey with outcome intent and end-to-end story mapping. It is informed by IBM's public [Enterprise Design Thinking framework](https://www.ibm.com/training/enterprise-design-thinking/framework) and Jeff Patton's public [User Story Mapping guidance](https://jpattonassociates.com/story-mapping/). It is not an official IBM or Jeff Patton template.

## Use it when

- a backlog has many stories but no visible user journey;
- teams are slicing by component rather than customer value;
- a solution has been chosen before the current problem is understood;
- multiple functions disagree about what “MVP” means; or
- the team needs an end-to-end learning release rather than a feature inventory.

## The working contract

```text
Decision this map must change:
Primary user and context:
Trigger that begins the journey:
Desired progress:
Owner and decision date:
Evidence available and missing:
```

Follow one primary user. Put buyers, administrators, operators, partners, and systems in dependency lanes rather than letting them replace the user's story.

## Step 1: Ground the user problem

Define:

- the specific user and situation;
- the trigger;
- the progress they are trying to make;
- the observed failure, delay, or workaround;
- frequency or severity where known; and
- the product decision this evidence should change.

Label journey claims as **observed**, **reported**, **inferred**, or **unknown**. Do not invent emotions, needs, or persona details to make the canvas feel complete.

## Step 2: Map the as-is journey

Use the user's natural phases, from trigger through attempted outcome.

| Phase | User job | Observable behavior | Expectation | Friction/workaround | Dependency | Evidence |
| --- | --- | --- | --- | --- | --- | --- |
| [Phase] | [Progress sought] | [Action/channel] | [Mental model] | [Failure/delay] | [Person/system] | [Source + confidence] |

Mark moments that disproportionately determine completion, trust, abandonment, or downstream work. A long journey does not require equal detail everywhere.

## Step 3: Define outcome intent

IBM describes a Hill through **Who, What, and Wow**: a user, an implementation-independent outcome, and differentiated proof. Use the spirit of that framing:

```text
[Who in context] can [accomplish what outcome]
with [measurable or observable differentiator].
```

Add a success contract:

```text
Primary metric or rubric:
Population and eligibility:
Time window:
Authoritative source:
Threshold hypothesis:
Guardrails:
```

Separate foundational work from the outcome. “Create an identity service” may be necessary, but it is not a user's destination.

## Step 4: Find priority opportunities

For the critical journey moments, distinguish symptoms from mechanisms.

| Moment | Unmet need or mechanism | User impact | Evidence | Opportunity | Riskiest assumption |
| --- | --- | --- | --- | --- | --- |
| [Phase] | [Why progress breaks] | [Outcome effect] | [Source] | [Change to enable] | [What must be true] |

Generate more than one response before choosing. Test value, usability, feasibility, viability, safety, accessibility, and operational support where relevant.

## Step 5: Design the to-be journey

Keep the future journey aligned to the same phases so the change is visible.

| Phase | Future behavior | Value realized | Enabling capability | New/remaining friction | Proof |
| --- | --- | --- | --- | --- | --- |
| [Phase] | [Observable change] | [Progress] | [Product/service/process] | [Cost/risk] | [Evidence to collect] |

Do not turn the to-be journey into a screen tour. Include human service, policy, communications, and recovery paths when they shape the outcome.

## Step 6: Build the story map

1. Put journey phases across the top as the **backbone**.
2. Under each phase, place the user's major tasks left to right.
3. Break tasks downward into smaller outcome-oriented stories.
4. Add exceptions, recovery, accessibility, trust, and operational dependencies.
5. Tell the full journey aloud. Gaps that remain invisible in a backlog often become obvious in the story.

Use a story form only when it improves the conversation:

```text
As a [user in context], I can [observable capability]
so that [progress or outcome].

Evidence/assumption:
Acceptance proof:
Failure or recovery case:
Explicit non-goal:
```

Technical tasks belong beneath the user outcome they enable or in a clearly named foundation lane.

## Step 7: Slice end-to-end releases

Slice horizontally across the backbone. Each release should create a coherent journey, not complete one system layer.

| Slice | Purpose | What crosses the journey | Evidence expected | Decision unlocked |
| --- | --- | --- | --- | --- |
| 1. Learn | Test the riskiest mechanism | Smallest credible end-to-end path | Behavior or evaluation signal | Continue, change, or stop |
| 2. Useful | Deliver a complete outcome for a narrow population | Essential journey plus recovery | Outcome and guardrail movement | Expand or refine |
| 3. Scale | Improve reach, automation, resilience, or economics | Broader variants and operations | Segment and system performance | Scale or optimize |

Useful slicing strategies include narrowing the population, scenario, channel, frequency, automation level, or edge-case coverage while preserving an end-to-end outcome.

Avoid these component slices:

- “database first, then APIs, then UI”;
- “all administrator stories before all user stories”;
- “happy path with no safe recovery”; and
- “instrumentation later.”

## A two-hour workshop

| Time | Activity | Output |
| --- | --- | --- |
| 0–15 min | Confirm decision, user, trigger, and evidence | Working contract |
| 15–40 min | Tell and map the as-is story | Journey backbone |
| 40–55 min | Write outcome intent and success contract | Solution-independent destination |
| 55–75 min | Identify mechanisms and opportunities | Priority moments |
| 75–100 min | Design to-be journey and stories | Story map |
| 100–115 min | Cut end-to-end slices | Learn/useful/scale releases |
| 115–120 min | Assign validation and playback | Owners and dates |

Use a playback, not a presentation: tell the end-to-end user story, invite representative users and operators to challenge it, and record which decision the evidence changes.

## Fictional example: scheduled home services

**Primary user:** A renter who needs a time-sensitive repair while working away from home.

**As-is:** The renter reports the problem, waits without knowing urgency or ownership, exchanges availability messages, and cannot tell whether entry is confirmed.

**Outcome intent:** A renter with a time-sensitive repair can understand its status and coordinate safe access without repeated follow-up, with appointment ownership and next action always visible.

**Slice 1—learn:** One repair category, manual dispatcher, a single status timeline, explicit access confirmation, and verified completion. This tests whether visibility and ownership reduce repeated contacts.

**Slice 2—useful:** More categories, rescheduling, missed-appointment recovery, and operator alerts.

**Slice 3—scale:** Automated matching, predictive windows, partner integrations, and segment-specific service levels.

The first slice is operationally manual but experientially complete. It tests the outcome before the team automates the system.

## Agent-ready adaptation

An agent can synthesize authorized research, label evidence, draft journey phases, find missing recovery cases, generate story alternatives, and test whether slices cross the backbone. It must not invent user evidence or autonomously publish a roadmap. Representative users, builders, operators, and the accountable decision owner validate the map.

## Quality gate

- One primary user and real context anchor the journey.
- Current behavior is evidence-backed, not a list of generic pain points.
- The outcome is solution-independent.
- New friction and secondary actors are visible.
- Every story connects to a journey phase and outcome.
- Release slices are end to end.
- Slice 1 can deliver value or test the riskiest assumption.
- Success, guardrails, validation owners, and the next decision are explicit.

[Back to playbooks →](README.md)

