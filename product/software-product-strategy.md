# Software Product Strategy

Rules for evaluating software investments, scope decisions, and product direction. These are tightly held.

## Value Orientation

Software creates value for businesses in four ways. The first two are the strongest outcomes and the clearest path to product-market fit. The latter two are real but require different expectations.

**Primary outcomes (strongest ROI, clearest business case):**

1. Help clients make money - new revenue, new capabilities, or competitive advantage that directly drives growth
2. Help clients save money - cost reduction through automation, efficiency, or headcount leverage

**Secondary outcomes (real value, less direct correlation):**

3. Help businesses measurably improve processes through software - this often produces financial value indirectly (e.g., saving employee time), but the correlation to revenue or cost savings may not be immediate or obvious to the client; these require more education to sell and retain
4. Help businesses achieve regulatory or compliance requirements (insurance standards, legal obligations, OSHA, Sarbanes-Oxley, etc.) - these are profitable engagements but harder sells because clients often feel compelled rather than motivated; budget expectations are lower and enthusiasm is limited

When proposing or evaluating scope, always identify which of these four outcomes the work addresses and calibrate the business case accordingly.

## Economic Feasibility

Technical idealism must yield to economic reality.

1. A product that needs significant redesign but cannot generate enough revenue to justify the investment should not be rebuilt speculatively.
2. ARR, client count, and estimated rebuild cost must be evaluated together before recommending a major architectural change.
3. Knowing when to accept constraints is as important as knowing what to build.
4. Do not recommend a full rebuild when the business case does not support it, even if the technical case is clear.

## MVP Realism

An MVP is a validation tool, not a permanent product.

1. An MVP that ships to production and is never rebuilt is not an MVP. It is a permanent product with temporary quality.
2. The risks of treating an MVP as production-ready:
   a. Poor UX becomes the brand perception
   b. Technical debt accumulates and becomes expensive to unwind
   c. Bad naming conventions, data models, and UI patterns become entrenched
   d. Clients adapt workarounds rather than using the product as intended
3. When recommending an MVP approach, always include a rebuild path and the conditions that trigger it.
