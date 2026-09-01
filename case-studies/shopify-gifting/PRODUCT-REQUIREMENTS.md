# Product Requirements: Shopify-enabled Creator Gifting

[Back to case study](./README.md) · [Back to portfolio](../../README.md)

This representative, public-safe PRD reconstructs the product scope and operating contract from contemporaneous requirements and later productization work. It is not a verbatim internal document. Start with the **[Executive Summary](./README.md)** for the customer and business context. Related artifacts include the **[Product Press Release](./PRODUCT-PRESS-RELEASE.md)** and **[User Stories](./USER-STORIES.md)**.

## Document control

- **Product:** Shopify-enabled Creator Gifting
- **Owner:** CJ Burns, Product Lead
- **Status:** Representative portfolio PRD based on shipped work
- **Decision requested:** Approve Shopify-enabled gifting as MVP 1.0, followed by three bounded Fast Follow releases
- **Historical decision:** Run a bounded Shopify feasibility integration and five-brand pilot before productization
- **Release boundary:** MVP 1.0 and Fast Follow 1.1, 1.2, and 1.3 only
- **Primary users:** Brand marketing teams and creators
- **Supporting users:** Brand administrators, support, engineering, data, privacy, security, and GTM teams

## 1. Executive summary

Brands had demand for creator gifting but relied on messages and spreadsheets to coordinate product fit, variants, delivery information, orders, fulfillment, and reporting. Creators could request products that were not available for gifting, creating avoidable back-and-forth for both sides. The proposed MVP connects the Creator Commerce platform to Shopify so brands can define eligible products and limits, creators can review one or more valid product selections, and a complete order submission can accept the collaboration and enter Shopify fulfillment without routine manual entry.

Shopify is the first fulfillment wedge because it served approximately 80% of the reachable existing brand portfolio and provided the catalog-to-order capabilities needed to test the workflow quickly. MVP 1.0 productizes the validated flow. Three bounded Fast Follows add brand-specific reconciliation, marketplace applications, and an embedded ordering experience that establishes a provider-neutral fulfillment boundary.

The first rollout is limited to 50 brands with a history of providing specific, actionable product feedback to the Creator Commerce platform. That cohort is optimized for learning speed, not market representation. After blocking findings are addressed, an additional cohort randomly selected from the remaining eligible Shopify brands will test whether adoption, completion, support burden, and customer value generalize beyond experienced feedback partners.

## 2. Problem and evidence

### Target users and jobs

- **Brand marketing team:** When I run a creator gifting program, I want approved creators to choose from inventory and rules I control, so I can scale fulfillment and measure content outcomes without manually coordinating every order.
- **Creator:** When I receive or apply for a gifting opportunity, I want to see available products, variants, and limits and provide the information needed for fulfillment, so I can complete the collaboration without a long message thread.
- **Brand operations and support:** When a gifting order is created or encounters a problem, I want the collaboration and Shopify transaction to remain traceable, so I can reconcile activity and resolve the issue without guessing which system is correct.

### Evidence

Approximately 80% of the reachable existing brand portfolio used Shopify as a commerce backend, closely mirroring an internal U.S. market estimate of 78% of e-commerce brands. The population, period, and methodology behind those internal estimates are not included in this public case.

A three-week feasibility integration was tested with five enterprise brands. It worked inside their existing operating models, helped them fulfill all available inventory allocated to gifting, reduced active brand-team handling time by approximately 95% per collaboration, and supported approximately 10x program scale. Brand names, the exact measurement period, and the raw source of record are unavailable in this public case. These figures are approximate operating results, not audited universal benchmarks.

### Why now

The existing workflow had demonstrated customer demand, but increasing gifting volume required roughly proportional coordination. Shopify made it possible to test whether catalog, variant, checkout, order, and fulfillment work could move into the systems already responsible for them. The pilot supplied enough evidence to justify a productized MVP and a controlled learning sequence, but not enough evidence to assume that more gifts automatically produced more customer value.

## 3. Product hypothesis, outcomes, and measurement

### Product hypothesis

If brands can define Shopify-backed gifting rules and creators can turn valid product selections into a complete order submission that automatically enters normal fulfillment, then participating brands will complete more gifting collaborations with less active handling time and use more allocated inventory, because routine product coordination and order entry will no longer scale linearly with volume.

### Behavior and business outcome

- **Behavior to create:** A creator reviews one selection set containing one or more eligible products and variants, then accepts the collaboration by submitting the complete order into one traceable fulfillment flow without routine brand intervention.
- **Immediate customer benefit:** Brands gain operating leverage and creators gain a clearer product-selection experience.
- **Business outcome:** More accepted offers and fulfilled gifts can produce more brand-relevant content and attributed conversion without requiring proportional operating cost.
- **Assumption to challenge:** Greater gifting throughput creates value only if fulfilled gifts produce useful content and enough conversion to justify the inventory and operating cost.

### Release measurement contract

Pilot results provide the baseline and the reason to invest. MVP and Fast Follow measures determine whether the product creates incremental value for the enabled population.

| Release | Measure | Definition and decision use |
| --- | --- | --- |
| **MVP 1.0** | Active brand-team handling time | Active brand-team minutes from eligible offer through authoritative order creation, divided by collaborations reaching order creation; compare participating brands before and after enablement |
| **MVP 1.0** | Gifting flow adoption | Brands creating at least one eligible gifting campaign and creators entering product selection, reported as counts and rates within the enabled cohort |
| **MVP 1.0** | Order completion | Unique accepted collaborations producing one authoritative Shopify order divided by collaborations with a complete order submission |
| **MVP 1.0** | Checkout recovery | Incomplete checkouts later reaching complete order submission divided by incomplete checkouts eligible to restart; report confirmed system failures separately |
| **MVP 1.0** | Fulfillment obligation aging | Accepted collaborations without a resolved fulfillment record, grouped by age and including the count older than three weeks |
| **MVP 1.0** | Allocated inventory use | Units fulfilled through gifting divided by units the participating brand allocated to gifting during the observation window |
| **MVP 1.0** | Repeat brand use | Enabled brands creating or reusing the flow in a subsequent eligible campaign divided by brands completing an initial campaign |
| **Fast Follow 1.1** | Custom-tag adoption | Enabled brands writing at least one custom gifting tag divided by brands eligible for custom tagging; also report the number of tagged orders |
| **Fast Follow 1.1** | Order revision use and recovery | Count and rate of orders with a revision, plus successful reconciled revisions divided by revision attempts |
| **Fast Follow 1.1** | Post-fulfillment issue resolution | Issue conversations reaching a recorded resolution divided by creator-reported fulfillment issues, with time to first response and resolution |
| **Fast Follow 1.2** | Applications per campaign | Submitted creator applications divided by campaigns open to applications, segmented by campaign and creator cohort |
| **Fast Follow 1.2** | Application review rate | Applications reviewed by a brand divided by submitted applications |
| **Fast Follow 1.2** | Application approval rate | Applicants selected for an offer divided by reviewed eligible applications; approval creates an offer, while complete order submission records collaboration acceptance |
| **Fast Follow 1.3** | Embedded flow completion | Creators producing one authoritative fulfillment request divided by creators starting embedded selection and checkout |
| **Fast Follow 1.3** | Fulfillment boundary integrity | Eligible requests producing one normalized authoritative result without Shopify-specific fields leaking into core collaboration state |

### Downstream value and product economics

The following measures apply to every release and must be reported by brand, campaign, creator cohort, and release exposure where the data is available.

| Measure | Formula | Interpretation |
| --- | --- | --- |
| Fulfilled-gift content yield | Fulfilled gifting collaborations with qualifying associated content divided by fulfilled gifting collaborations in the agreed observation window | Tests whether fulfilled inventory produces the intended creator behavior |
| Content conversion rate | Qualifying gifted-content units with at least one attributed conversion divided by qualifying gifted-content units | Tests whether content produces observable commercial behavior without treating unattributed outcomes as zero |
| Average GMV per item gifted | Attributed GMV from qualifying gifted content divided by fulfilled gifted units | Normalizes commercial output against inventory sent |
| MSRP return ratio | Attributed GMV from qualifying gifted content divided by the aggregate list price of fulfilled gifted items | A ratio greater than 1.0 means attributed GMV exceeds list price; it does not represent margin or audited incremental ROAS |

Historical outcome signals are context, not expansion thresholds. Product and Data must pre-register the observation windows and numeric success thresholds after establishing the 50-brand cohort baseline. The rollout cannot expand beyond that cohort until those thresholds and the decision rule are recorded.

### Guardrails

- No duplicate collaboration-acceptance events, fulfillment requests, or orders.
- No silent loss of a valid product selection, tag, revision, application, or issue conversation.
- No unnecessary creator delivery data in analytics, transaction ledgers, logs, or broad support tooling.
- No automated final creator selection or silent suppression caused by missing application data.
- No storefront code or page-rendering dependency.
- No expansion if volume materially reduces creator relevance, fulfillment success, content yield, repeat brand use, reliability, or support readiness.

## 4. Product boundaries

### Goals

- Reduce active brand-team handling time from creator product choice through fulfillment.
- Let brands use more of the inventory they have already allocated to gifting.
- Preserve brand judgment over creator fit, eligible inventory, program economics, and final selection.
- Give creators an informed path to the right products, quantities, sizes, colors, and variants.
- Keep collaboration, selection, order, fulfillment, reconciliation, content, and available performance context traceable.
- Instrument the complete MVP flow so adoption, operational performance, and downstream customer value can be evaluated.

### Non-goals

- Automatically selecting or declining creators.
- Guaranteeing that every gift produces content or conversion.
- Building a general-purpose commerce, warehouse, or order-management system.
- Adding storefront code or page-rendering dependencies.
- Launching a production non-Shopify fulfillment integration through Fast Follow 1.3.
- Defining a roadmap after Fast Follow 1.3 in this document.

## 5. Options and decision

| Option | Customer value | Time to learn | Complexity and risk | Decision |
| --- | --- | --- | --- | --- |
| Continue messages and spreadsheets | Preserves existing flexibility | Immediate | Retains poor fit, manual work, and weak traceability | Do not lead with this path |
| Use gift cards or single-use codes | Gives non-Shopify brands a bounded fulfillment option | Short | Shifts selection into a consumer purchase flow and weakens end-to-end visibility | Preserve as a fallback, not the core workflow |
| Build a native multi-platform fulfillment system | Offers broad theoretical reach | Long | Largest commitment before the core behavior is validated | Treat as the North Star, not the MVP |
| Productize the Shopify integration | Covers most of the reachable portfolio and uses existing commerce primitives | Short | Creates platform dependency and the risk of Shopify assumptions entering the core model | Proceed as MVP 1.0 |

**Decision:** Productize the validated Shopify flow as MVP 1.0 for a controlled 50-brand rollout. Use the results to shape Fast Follow 1.1, then introduce applications in Fast Follow 1.2 and an embedded creator ordering experience in Fast Follow 1.3.

**Strongest counterargument:** A Shopify-first product could harden partner-specific assumptions into the Creator Commerce platform and exclude brands on other commerce systems.

**Design response:** Keep campaigns, creator eligibility, collaboration acceptance, gifting rules, measurement, and customer communication inside the Creator Commerce platform. Isolate Shopify catalog, inventory, order creation, and fulfillment behavior behind an integration boundary that can later support another provider such as WooCommerce.

## 6. Release plan

| Release | Customer outcome | Product increment | Explicit boundary |
| --- | --- | --- | --- |
| **MVP 1.0: Shopify fulfillment** | An invited creator chooses one or more valid products, submits the complete order, and reaches the brand's normal Shopify fulfillment flow | Gifting authorization, eligible catalog, quantity or value limits, submission-as-acceptance, Shopify checkout, basic gift identifier, fulfillment synchronization, transaction ledger, product analytics, recovery, and production controls | No marketplace applications, custom reconciliation rules, post-fulfillment messaging, or embedded ordering experience |
| **Fast Follow 1.1: Reconciliation and exception handling** | A brand can fit gifting orders into its operating model and creators can resolve fulfillment issues inside the platform | Custom order tagging, gifting-flow reconciliation, order price-write rules, fulfillment-location rules, controlled order revisions, and post-fulfillment creator-to-brand messaging | No marketplace application path |
| **Fast Follow 1.2: Marketplace applications** | Creators can apply for opportunities and brands can review a broader pool without outsourcing final judgment | Campaign applications, audience and previous-performance inputs, applicant prioritization, complete applicant access, and invitation/application parity | Application approval creates an offer; only complete order submission records collaboration acceptance |
| **Fast Follow 1.3: Embedded creator ordering** | Creators complete selection and order confirmation inside one platform experience using saved information they can review and correct | Embedded selection and order confirmation, consented delivery-profile reuse, normalized fulfillment instructions, Shopify implementation, and a provider-neutral response contract | No production WooCommerce or other non-Shopify integration and no roadmap after 1.3 |

## 7. Experience, state, and authority

### MVP 1.0 core workflow

1. **Connect:** An authorized brand administrator consents to the required data sharing and connects Shopify for gifting independently of commission tracking.
2. **Configure:** The brand chooses eligible collections or products and sets the number of products or total gift value allowed.
3. **Invite:** The brand chooses a creator and sends a private, time-bounded offer.
4. **Select:** The creator chooses one or more valid products and variants within the brand's configured quantity or value limits. The selection remains editable and does not accept the collaboration.
5. **Checkout and validate:** Shopify checkout collects or confirms delivery information. Before submission, the platform revalidates connection, offer, catalog version, product eligibility, limits, variants, and inventory. An interrupted or abandoned checkout remains restartable and does not record acceptance.
6. **Submit, accept, and create:** The creator submits the complete order. That submission records collaboration acceptance and the selected items atomically, then creates the initial Shopify order with a basic gift identifier. If the order result is ambiguous or confirmed failed, the accepted fulfillment obligation remains active while the platform reconciles or retries.
7. **Record and synchronize:** The Creator Commerce platform records the immutable transaction events and authoritative Shopify order reference, then synchronizes order and fulfillment status into the gifting lifecycle.
8. **Measure:** Product events record cohort exposure, campaign setup, offer, selection, acceptance, checkout, order, exception, fulfillment, and repeat-use behavior without copying raw shipping data into analytics.
9. **Recover:** Inventory, permission, checkout, order, or synchronization failures preserve valid work and expose the next action.

### Canonical state model

States belong to distinct domain objects. They must not be collapsed into one chronological status field.

| Domain object | Authoritative system | States and permitted transitions |
| --- | --- | --- |
| Shopify connection | Creator Commerce platform for connection state; Shopify for authorization validity | `DISCONNECTED -> AUTHORIZATION_PENDING -> ACTIVE`; `ACTIVE -> REAUTHORIZATION_REQUIRED` or `REVOKED`; successful reauthorization returns to `ACTIVE`; revoked credentials cannot create new work |
| Gifting catalog version | Creator Commerce platform | `DRAFT -> ACTIVE -> SUPERSEDED` or `CLOSED`; an active version is immutable for an issued offer, and edits create a new version |
| Offer | Creator Commerce platform | `DRAFT -> OFFERED -> SELECTION_PENDING -> CHECKOUT_IN_PROGRESS`; it may transition to `EXPIRED`, `WITHDRAWN`, or `CANCELLED` before acceptance. Those states are terminal; renewed interest creates a new versioned offer linked to the prior one |
| Collaboration | Creator Commerce platform | Complete order submission atomically creates `ACCEPTED` and `FULFILLMENT_PENDING`; then the collaboration moves through `ORDER_RECORDED -> FULFILLED`. An ambiguous or failed order result preserves the accepted obligation and enters visible recovery |
| Fulfillment transaction | Creator Commerce platform ledger for transaction state; Shopify for commerce outcome | `NOT_STARTED -> CHECKOUT_OPEN`; an incomplete checkout may restart without becoming a failure. Complete submission moves to `SUBMITTED`, then `ORDER_RECORDED -> FULFILLED`; ambiguous writes enter `RECONCILIATION_REQUIRED`, confirmed failures enter `ORDER_CREATION_FAILED`, and a retry cannot create a second order reference |
| Application, Fast Follow 1.2 | Creator Commerce platform | `DRAFT -> SUBMITTED -> REVIEWED -> SELECTED` or `DECLINED`; `WITHDRAWN` and `EXPIRED` are terminal; `SELECTED` creates an offer but does not accept the collaboration |
| Fulfillment issue, Fast Follow 1.1 | Creator Commerce platform | `OPEN -> BRAND_RESPONDED -> RESOLVED` or `CLOSED`; reopening records a new event while preserving the prior resolution history |

### State invariants and ledger

- Browsing, selection confirmation, and checkout initiation do not accept a collaboration.
- One complete order submission creates at most one collaboration-acceptance event and at most one initial Shopify order reference.
- An accepted collaboration remains an active fulfillment obligation until a synchronized Shopify fulfillment record closes it or an audited manual resolution is acknowledged by the creator.
- A brand with an accepted obligation older than three weeks cannot start a new creator collaboration until the obligation is resolved.
- Every state transition records entity ID, prior state, next state, event type, actor or source, timestamp, idempotency key, and related order reference when available.
- The ledger is append-only for transaction history. Corrections produce compensating or revision events rather than overwriting prior state.
- Product analytics derives from the event stream but does not become the source of truth for collaboration or order state.

### Authority and data boundary

The Creator Commerce platform is authoritative for participation, campaigns, invitations, applications, gifting rules, collaboration acceptance, transaction history, reconciliation rules, issue conversations, and available performance context. Shopify remains authoritative for its products, variants, inventory, fulfillment locations, orders, and fulfillment state.

The integration stores only the Shopify identifiers and gifting-lifecycle data needed to track fulfillment. It does not copy unrelated store data or retain creator personal data that is not required for the gifting lifecycle, support, security, or a defined legal obligation. Fast Follow 1.3 changes where the creator completes the experience, not who owns commerce facts. Saved creator information requires appropriate notice and consent and remains reviewable before submission. The normalized instruction and result prepare for future providers without committing another production integration.

## 8. Requirements

### MVP 1.0: Shopify fulfillment

| ID | Requirement | Product intent | Acceptance evidence |
| --- | --- | --- | --- |
| M10-1 | Authorized brand users can connect, reauthorize, and revoke Shopify for gifting using minimum permissions, independently of commission tracking | Establish trusted access without forcing unrelated adoption | Consent and connection state are visible; revocation stops new reads and writes |
| M10-2 | Brand users can browse eligible collections, products, images, variants, current inventory, and availability | Bring commerce context into gifting | Displayed data reconciles to Shopify; inactive or unsupported items are excluded |
| M10-3 | Brand users can choose one or more collections or a product subset for a versioned gifting catalog | Preserve merchandising control | Only the saved catalog version is offered to its campaign cohort |
| M10-4 | Brand users can set the number of products or total gift value allowed per creator | Protect program economics | A selection over the active limit cannot be confirmed, and excluded products have a visible reason |
| M10-5 | Inventory changes remove or flag unavailable products and provide a reselection path | Prevent avoidable creator disappointment | An unavailable item cannot complete checkout or fail silently |
| M10-6 | The brand chooses which creator receives a private, time-bounded offer; a withdrawn or expired offer remains terminal, and renewed interest requires a new versioned offer linked to the original | Preserve program judgment and truthful history | Only the intended creator can enter the offer's selection flow; replacement offers revalidate current eligibility, catalog, and expiration without reopening prior state |
| M10-7 | An invited creator can build and confirm one selection set containing one or more allowed products and variants without accepting the collaboration | Preserve an informed, editable choice before commitment | The confirmed selection is versioned and restartable through checkout; browsing, selection, and checkout initiation never record acceptance |
| M10-8 | The system revalidates authorization, offer state, catalog version, eligibility, limits, variants, and inventory before complete order submission | Prevent scalable errors | Invalid state blocks submission with an actionable recovery path while preserving valid work |
| M10-9 | One complete order submission records collaboration acceptance and produces at most one initial Shopify order with a basic gift identifier | Consolidate informed acceptance and normal fulfillment without duplicate cost | One submission produces one acceptance event and at most one order; incomplete checkout produces neither; acceptance authorizes fulfillment but does not require content |
| M10-10 | Selection, acceptance, order, and fulfillment activity synchronize into brand and support views | Create shared operating state | Views show creator, selected items, acceptance time, current state, and the authoritative Shopify order reference |
| M10-11 | The platform maintains an append-only transaction ledger for the gifting lifecycle | Make state transitions and recovery auditable | Every transition contains prior and next state, actor or source, timestamp, idempotency key, and related order reference when available |
| M10-12 | Product analytics measures enabled-cohort exposure, adoption, handling time, flow completion, inventory use, fulfillment, exceptions, and repeat use | Evaluate incremental customer and operating value | Events reconcile to the transaction ledger and Shopify order state without storing raw delivery information |
| M10-13 | Material connection, catalog, inventory, order-creation, and synchronization failures enter a visible recovery workflow, while interrupted or abandoned checkout remains restartable incomplete work | Prevent silent loss without misclassifying customer behavior as a system error | Each confirmed failure records cause, last valid state, owner, next action, retry status, and resolution; incomplete checkout can resume without an error record |
| M10-14 | An accepted collaboration remains an active fulfillment obligation until it is resolved by a synchronized Shopify order and fulfillment record or by an audited manual process acknowledged by the creator | Preserve the brand's commitment when access changes or automated order creation fails | A fresh Shopify order stores its order number and resumes synchronization; manual closure records reviewer, evidence, time, sent status, and creator acknowledgement without overwriting history |
| M10-15 | A brand with an accepted collaboration left unfulfilled for more than three weeks cannot start a new creator collaboration until the obligation is resolved | Prevent new outreach while prior gifting commitments remain unmet | The campaign and brand surfaces identify overdue obligations, block new collaboration creation, and clear the restriction only after an accepted resolution event |

### Fast Follow 1.1: Reconciliation and exception handling

| ID | Requirement | Product intent | Acceptance evidence |
| --- | --- | --- | --- |
| F11-1 | Brand users can configure custom campaign, collaboration, and gifting tags that write to the Shopify order | Reconcile gifting within the merchant's fulfillment and reporting environment | Approved tags map to stable platform identifiers, exclude sensitive personal data, and write idempotently |
| F11-2 | The platform reconciles required gifting tags against the authoritative Shopify order | Prevent reporting drift | Missing, duplicate, or mismatched tags enter visible repair without changing order authority |
| F11-3 | A brand can configure how price is represented on a gifting order using supported policies, such as list price, zero value, or another approved gift value | Fit merchant accounting and fulfillment rules without changing the product source of truth | The active policy is versioned, the order matches it, and unsupported or conflicting rules block submission with a clear reason |
| F11-4 | A brand can restrict gifting orders to an eligible Shopify fulfillment location or warehouse when its operating model requires it | Route inventory through the intended operating flow | The selected location is valid for the order items; unavailable or incompatible locations block submission or enter explicit recovery |
| F11-5 | Authorized users can perform controlled order revisions after revalidating order, inventory, price, location, and collaboration state | Resolve exceptions without corrupting history | Each revision records actor, reason, before and after state; failure preserves the last valid order and collaboration |
| F11-6 | A creator can start a message thread with the brand from a fulfilled gifting collaboration when an order issue occurs | Keep resolution inside the platform and preserve context | The thread carries the collaboration and order reference, exposes only necessary data, and records response and resolution state |

### Fast Follow 1.2: Marketplace applications

| ID | Requirement | Product intent | Acceptance evidence |
| --- | --- | --- | --- |
| F12-1 | Brand users can create a campaign with application questions, audience criteria, dates, and offer expiration | Make opportunities understandable and time-bounded | Published criteria match the saved version; closed or expired campaigns reject new applications |
| F12-2 | An eligible creator can discover a campaign and submit answers, audience context, and previous performance in three primary actions | Broaden access without a long application | From campaign detail, start, review, and submit produce one idempotent application; validation is clear |
| F12-3 | The platform evaluates applications against versioned campaign criteria and surfaces strong applicants for brand review | Reduce review effort without hiding the decision | The brand sees decision-relevant evidence, missing data remains distinct from poor fit, and all applications remain accessible |
| F12-4 | Applications and invitations are parallel entry paths; the brand makes the final creator decision and both paths converge at the offer | Preserve direct sourcing and marketplace access | Entry path is auditable; application does not accept a collaboration or reserve inventory |
| F12-5 | A selected applicant enters the same product-selection and order-submission flow as an invited creator, and complete order submission records collaboration acceptance | Preserve one canonical acceptance model | Application source does not change the selection, acceptance, checkout, or fulfillment state transitions |
| F12-6 | Marketplace events connect application, review, brand decision, selection, acceptance, fulfillment, content, and available conversion context | Measure customer value beyond application volume | Unknown or unattributed outcomes remain visibly unknown rather than zero |

### Fast Follow 1.3: Embedded creator ordering

| ID | Requirement | Product intent | Acceptance evidence |
| --- | --- | --- | --- |
| F13-1 | A selected or invited creator completes product selection and order confirmation in one embedded Creator Commerce platform experience | Remove the Shopify-window transition and preserve one creator journey | The creator can review products, quantities, variants, and delivery information and recover without leaving the platform experience |
| F13-2 | The embedded experience can prefill saved creator delivery information only when its use is permitted and disclosed | Reduce repeat entry without weakening creator control | The creator can review, correct, or decline reuse before order submission, and the consent or other lawful basis is auditable |
| F13-3 | The core platform sends a provider-neutral fulfillment instruction and receives a normalized result through the integration boundary | Prepare for future providers without branching the collaboration model | The contract defines identifiers, item and quantity representation, delivery reference, idempotency key, status, error, and authoritative source without Shopify-only core fields |
| F13-4 | After complete order submission, retry, timeout, ambiguous result, and order failure preserve the accepted collaboration and valid selection; before submission, interrupted checkout remains restartable and unaccepted | Prevent partner failure from destroying customer work without inventing commitment | Reconciliation occurs before another order reference is accepted; recovery resumes from the last valid state |
| F13-5 | The Shopify implementation passes the normalized contract and state-transition suite | Prove the embedded flow respects the intended boundary | Success, retry, timeout, invalid inventory, invalid location, and ambiguous-result tests produce the defined normalized behavior |

### Cross-cutting Shopify production contract

These requirements apply to each release surface they affect. They are current implementation expectations, not claims that every control existed in the three-week feasibility integration.

| ID | Quality requirement | Decomposition | Acceptance evidence |
| --- | --- | --- | --- |
| Q1 | Use reviewed public distribution with limited listing visibility for unrelated brand stores | Fix the production distribution model and migrate from a pilot configuration when required | Independent test stores install from the listing URL; active campaigns retain a supported path |
| Q2 | Use Shopify-owned installation and current embedded authentication | Authenticate before protected UI; use current App Bridge and token exchange; handle reinstall, reauthorization, and revoke | Fresh install, expired session, revoke, and reinstall reach the correct state without third-party-cookie dependence |
| Q3 | Use current Shopify APIs, least-privilege scopes, and no storefront code | Maintain a capability-to-operation-to-scope matrix, pin a supported API version, handle query cost and deprecation, and exclude storefront scripts or theme dependencies | Every scope maps to a tested requirement; theme and storefront scans remain clean |
| Q4 | Store only creator data required for the gifting lifecycle and fulfillment tracking | Prefer platform creator IDs, saved-profile references, Shopify order references, and fulfillment state; request protected customer data only for required fields | Data inventory covers purpose, fields, access, retention, deletion, encryption, logs, test separation, and incident ownership; unrelated creator or store data is absent |
| Q5 | Implement privacy and uninstall lifecycle | Verify HMAC for required privacy webhooks; stop new work and revoke credentials on uninstall | Valid requests enter an auditable workflow; invalid HMAC is rejected; redaction follows the current Shopify requirement |
| Q6 | Keep Creator Commerce and Shopify state accurate under asynchronous delivery | Deduplicate, tolerate out-of-order events, reconcile ambiguous writes, and monitor lag and exceptions | Replay, duplicate, delayed, missing-event, throttle, and timeout tests preserve one order mapping and an auditable ledger |
| Q7 | Provide a secure, accessible, reliable, and performant experience | Cover loading, empty, permission, error, and recovery states; test keyboard use, labels, focus, status, correction, security, reliability, scaling, and performance budgets | No blocking accessibility, security, reliability, administration-performance, storefront-performance, or scaling defect remains at release |
| Q8 | Submit a truthful, complete Shopify review package for the enabled release | Align listing, pricing, permissions, assets, privacy policy, support, reviewer credentials, seeded data, and demo path | A reviewer completes the enabled version's real workflow and one recovery path using supplied instructions |

Official Shopify implementation references: [distribution models](https://shopify.dev/docs/apps/launch/distribution), [listing visibility](https://shopify.dev/docs/apps/launch/distribution/visibility), [App Store requirements](https://shopify.dev/docs/apps/launch/shopify-app-store/app-store-requirements), [review submission](https://shopify.dev/docs/apps/launch/app-store-review/submit-app-for-review), [protected customer data](https://shopify.dev/docs/apps/launch/protected-customer-data), and [privacy-law compliance webhooks](https://shopify.dev/docs/apps/build/compliance/privacy-law-compliance). Platform requirements can change and must be reverified before implementation or review submission.

## 9. Technical and data considerations

- Implement state changes as explicit domain events. One complete order submission creates at most one accepted collaboration and at most one authoritative order.
- Keep the transaction ledger separate from analytics. Version customer configuration and preserve the last valid state through checkout, order, synchronization, and reconciliation failures.
- Treat tags as reconciliation metadata, tolerate delayed or duplicated partner events, and reconcile ambiguous writes before accepting another order reference.
- Limit delivery-data access and define retention, deletion, support visibility, audit, and incident ownership.
- Monitor the full flow from authorization and campaign entry through selection, order, fulfillment, reconciliation, issue resolution, and unresolved exceptions.

## 10. Rollout and decision gates

Each release uses the same loop: enable a bounded feedback cohort, capture pre-registered customer and operational measures, resolve blocking findings, then freeze a versioned release candidate for a randomly selected eligible cohort. The first cohort improves the product; the second tests whether the result generalizes. Eligibility, cohort size, observation windows, thresholds, and opt-in effects must be recorded before evaluation. No release expands on anecdotal satisfaction alone.

### Pre-release evidence: feasibility and five-brand pilot

- Validate API capability, catalog access, item and price limits, variant selection, Shopify checkout, order creation, fulfillment synchronization, instrumentation, security, reliability, scaling, monitoring, and operating fit.
- Continue only when real brand workflows can use allocated inventory with materially less active coordination.

### MVP 1.0 gate: controlled 50-brand rollout

- Select up to 50 Shopify brands with a demonstrated history of providing timely, specific, and actionable feedback to the Creator Commerce platform. Selection is based on feedback quality, not expected adoption or outcome performance.
- Pass M10-1 through M10-15 and Q1 through Q8 for the enabled surface.
- Establish handling-time, gifting-volume, order-completion, inventory-use, and repeat-use baselines, then review adoption, ledger integrity, fulfillment, content yield, conversion, and MSRP return ratio.
- Use repeated operating needs and failure patterns to finalize Fast Follow 1.1, resolve blocking findings, and freeze the release candidate.
- Invite an additional cohort randomly selected from the remaining eligible Shopify brands. Compare adoption, completion, support burden, and downstream value with the feedback cohort, segmented by the pre-registered brand characteristics.
- Expand only if both cohorts meet the decision rule and no guardrail is breached; otherwise revise, hold, or roll back.

### Fast Follow 1.1 gate: reconciliation and exception cohort

- Start with MVP brands that have confirmed tagging, pricing, location, revision, or messaging needs; then test the release candidate with an eligible randomly selected cohort.
- Pass F11-1 through F11-6 and affected Q requirements. Review configuration adoption, reconciliation, revision recovery, issue resolution, and downstream economics.
- Expand only when the rules remain configuration rather than core workflow branches and both cohorts meet the decision rule.

### Fast Follow 1.2 gate: application cohort

- Test applications and invitations independently and together, first with a feedback cohort and then with a randomly selected eligible cohort.
- Pass F12-1 through F12-6 and affected Q requirements. Review applications per campaign, review and acceptance rates, cohort coverage, brand burden, content yield, conversion, and MSRP return ratio.
- Expand only when broader access improves outcomes without overwhelming brands or silently excluding qualified creators.

### Fast Follow 1.3 gate: embedded ordering cohort

- Test with feedback partners and then a randomly selected eligible cohort of Shopify brands and creators with consented saved information.
- Pass F13-1 through F13-5 and affected Q requirements. Compare completion, correction, exceptions, support, and fulfillment with the Shopify-window flow.
- Expand only when the embedded experience improves completion without weakening creator control, data minimization, ledger integrity, or reliability.
- Do not add a production WooCommerce or other non-Shopify integration, or another release phase, to this PRD.

## 11. Dependencies and ownership

| Dependency | Primary owner | Partners | Required evidence |
| --- | --- | --- | --- |
| Shopify access, APIs, distribution, and review | Engineering | Security, Privacy | Scope matrix, integration tests, security review, and reviewer package |
| Cohort design and metric contract | Product | Data | Eligibility, baselines, observation windows, thresholds, segments, and decision rule |
| Brand recruitment and feedback operations | Product | Customer Success, Support | Confirmed participants, feedback cadence, and escalation path |
| Release monitoring and rollback | Engineering | Product, Support | Dashboards, alerts, runbook, rollback owner, and customer communication |
| Fast Follow workflow contracts | Product | Design, Engineering | Repeated customer need, versioned configuration, and experience playback |
| Expansion and enablement | Product | Data, Customer Success, GTM | Gate review, support readiness, enablement materials, and expansion decision |

Discovery findings may change scope or sequencing. Dates become delivery commitments only after the accountable functions accept the requirement, dependency, and release gate.

## 12. Risks and mitigations

| Release | Risk | Early signal | Mitigation | Owner |
| --- | --- | --- | --- | --- |
| MVP 1.0 | Stale inventory, invalid variant, or duplicate order | Reselection, confirmed order-creation failure, or duplicate reference | Revalidate, use idempotency, preserve state, and reconcile before retry | Engineering |
| MVP 1.0 | Accepted gifts remain unfulfilled while brands start new outreach | Obligation age exceeds three weeks or manual closures lack evidence | Surface aging, block new collaborations after three weeks, and require a Shopify order reference or audited manual closure acknowledged by the creator | Product, Engineering, Support |
| MVP 1.0 | Ledger and analytics diverge | Funnel counts do not reconcile to transactions | Keep the ledger authoritative, version events, and reconcile | Engineering, Data |
| MVP 1.0 | Permission or creator-data access exceeds expectations | Install objection, revocation, data finding, or review issue | Use least privilege, purpose limitation, retention controls, and security review | Security, Privacy |
| MVP 1.0 | Feedback-partner results are treated as representative | Material differences in the randomly selected cohort | Separate cohorts, pre-register segments, disclose opt-in effects, and gate on both | Product, Data |
| Fast Follow 1.1 | Brand-specific rules become core-product branches | Customer-specific code for tags, price, or locations | Use versioned configuration and supported policies | Product, Engineering |
| Fast Follow 1.1 | Tags or revisions diverge from order state | Missing tag, invalid location, or unmatched revision | Use stable IDs, idempotent writes, audit history, and reconciliation | Engineering |
| Fast Follow 1.1 | Messaging exposes unnecessary data | Sensitive data appears in issue threads | Prefill only allowed references and apply retention and access controls | Product, Privacy |
| Fast Follow 1.2 | Applications overwhelm brands or hide viable creators | Review backlog or qualified creators outside the surfaced set | Explain prioritization, retain all applications, and monitor cohorts | Product, Data, Design |
| Fast Follow 1.2 | More gifts produce low-value activity | Lower content yield, conversion, MSRP return ratio, or repeat use | Keep final judgment human and gate on downstream value | Product, Data |
| Fast Follow 1.3 | Embedded ordering shifts partner failures into the platform | Drop-off or unresolved fulfillment instructions | Preserve work, normalize errors, and prove recovery | Engineering, Support |
| Fast Follow 1.3 | Shopify assumptions leak into core state | Shopify-specific fields enter core contracts | Use stable domain contracts and architecture review | Engineering |

## 13. Decisions and open questions

### Decisions represented here

- Use Shopify as the MVP 1.0 fulfillment wedge and keep gifting authorization independent of commission tracking.
- Refine MVP 1.0 with 50 proven feedback partners, then test the release candidate with a randomly selected eligible cohort before broader expansion.
- Treat complete order submission, not browsing, selection confirmation, or checkout initiation, as collaboration acceptance.
- Treat gift acceptance as authorization to fulfill the gift, not a creator commitment to publish content.
- Keep withdrawn and expired offers terminal; renewed interest creates a new versioned offer linked to the original.
- Keep accepted collaborations active until Shopify fulfillment or an audited manual resolution closes the obligation, and block new creator collaborations when an obligation remains unresolved for more than three weeks.
- Include an auditable transaction ledger and product analytics in MVP 1.0.
- Put custom tagging, reconciliation, price and fulfillment-location rules, controlled revisions, and post-fulfillment issue messaging in Fast Follow 1.1.
- Put marketplace applications, brand review, and application-versus-invitation parity in Fast Follow 1.2.
- Put the embedded creator ordering experience and provider-neutral fulfillment boundary in Fast Follow 1.3.
- End this PRD at Fast Follow 1.3; do not imply that a production non-Shopify integration is committed.

### Open questions within the MVP 1.0 through Fast Follow 1.3 boundary

| Question | Why it matters | Owner and validation method |
| --- | --- | --- |
| What thresholds, windows, eligibility rules, and sample size govern the two-cohort MVP decision? | Prevents anecdotal or biased success from becoming the rollout rule | Product and Data: baseline and pre-register the evaluation contract |
| Which GraphQL operations and scopes implement the Shopify requirements? | Makes least privilege auditable | Engineering and Security: scope matrix and development-store proof |
| Can references support fulfillment tracking without duplicate delivery data? | Reduces protected-data scope | Engineering and Privacy: data-flow map, field inventory, and support playback |
| Which tag, price, and location rules represent repeatable needs? | Prevents customer-specific core branches | Product and Engineering: cohort evidence, configuration schema, and exception playback |
| What qualifies content and which window defines yield and attributed GMV? | Prevents overstated value | Product and Data: content and attribution metric contract |
| Which criteria govern applicant prioritization, and what explanation does the brand see? | Prevents opaque creator selection | Product, Data, and Design: ranking playback, cohort review, and brand research |
| What normalized instruction supports Shopify now and another provider later? | Tests the Fast Follow 1.3 boundary | Engineering: contract design, conformance tests, and architecture review |
