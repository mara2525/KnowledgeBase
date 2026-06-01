---
title: "Coding Guidelines"
slug: "coding-guidelines"
category: "engineering"
order: 1
summary: "Rules for writing, reviewing, and planning software applied to code, PRs, system design, and implementation advice."
tags: ["Engineering", "Code", "Guidelines", "Development"]
conviction: "moderate"
updatedAt: "2026-06-01"
---

# Coding Guidelines

Rules for writing, reviewing, and planning software. Apply these whenever writing code, evaluating a pull request, designing a system, or advising on implementation.

## Don't Introduce Abstractions Speculatively

Abstractions should be extracted from real, existing duplication or complexity, not anticipated from imagined future requirements.

1. Write the concrete implementation first. Extract a pattern or abstraction only once it has appeared at least twice in real code.
2. A function, class, or layer added "in case we need it later" is dead weight until proven otherwise. It increases surface area, adds indirection, and makes the code harder to change when the actual requirement arrives.
3. The right abstraction for a use case you haven't seen yet is almost never the abstraction you would design in advance.
4. If code is similar but not identical, copy it. Duplication is cheaper than the wrong abstraction.
5. When reviewing or planning, flag any abstraction that has only one caller or only one implementation - it likely does not need to exist yet.

**Signal that this rule is being violated**: a helper, base class, interface, or utility is being added to "support future use cases," "make it easier to extend later," or "give us flexibility down the road."
