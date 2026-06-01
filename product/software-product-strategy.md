---
title: "Software Product Strategy"
slug: "software-product-strategy"
category: "product"
order: 1
summary: "Framework for evaluating software investments, scoping product decisions, and understanding how technology serves business. Derived from the Purpose of Business framework."
tags: ["Product", "Strategy", "Investment", "Frameworks"]
conviction: "tight"
foundation: "purpose-of-business"
updatedAt: "2026-05-31"
---

# Software Product Strategy

Rules for evaluating software investments, scope decisions, and product direction.

## How Technology Serves Business

*Derived from [The Purpose of Business](../frameworks/purpose-of-business.md)*

Technology delivers value to a business in four ways. The first three represent motivated buying decisions where the client actively wants the outcome. The fourth is a forced obligation.

| Outcome | What It Means |
|---|---|
| **Increase Revenue** | Make the business more money |
| **Decrease Spending** | Save the business money |
| **Improve Processes** | Make something easier or better |

*Clients are willing buyers for these three outcomes. They see the value and want to invest.*

---

| Outcome | What It Means |
|---|---|
| **Compliance Requirements** | Business must do this |

*Clients are reluctant buyers for compliance work. They are compelled to spend, not motivated to.*

---

### Increase Revenue

The strongest outcome. New revenue streams, competitive advantage, or capability unlocks that directly drive business growth. Clients are motivated, budgets are available, and the business case is easy to articulate. This is the clearest path to product-market fit.

### Decrease Spending

A strong outcome. Cost reduction through automation, efficiency gains, or headcount leverage. Clients actively want this and the ROI is usually measurable and direct.

### Improve Processes

A real outcome, but a harder sell. The financial value is often indirect - saving employee time, reducing errors, improving consistency. The correlation to revenue or cost savings may not be immediate or obvious to the client. These engagements require more education to sell and more effort to demonstrate ongoing value.

### Compliance Requirements

The most difficult engagement type. The client is not choosing to invest; they are required to by legal, regulatory, or insurance obligations (e.g., OSHA, Sarbanes-Oxley, insurance standards). Budget expectations are lower, enthusiasm is limited, and the engagement often feels adversarial rather than collaborative. These can be profitable for the consultant but require different expectations going in.

When proposing or evaluating scope, identify which of these four outcomes the work addresses and calibrate the business case, pricing, and stakeholder approach accordingly.

---

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
