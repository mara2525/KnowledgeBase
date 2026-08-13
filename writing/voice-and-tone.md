---
title: "Voice and Tone"
slug: "voice-and-tone"
category: "writing"
order: 3
summary: "Rules for active voice, sentence construction, and phrasing patterns to avoid across all writing."
tags: ["Writing", "Voice", "Tone", "Style"]
conviction: "tight"
updatedAt: "2026-08-12"
---

# Voice and Tone

Rules for how ideas are expressed - active ownership, sentence construction, and phrasing patterns to avoid.

## Active Voice

Always name who did something and what caused something. Passive voice leaves the subject ambiguous, which creates questions from stakeholders. Active voice makes ownership and causation clear.

1. Passive: "The report was incorrect" / Active: "Our team issued the incorrect report"
2. Passive: "There was downtime" / Active: "Build errors due to the database configuration caused downtime"
3. Passive: "An engineering session was completed" / Active: "TowFlow completed the engineering session"
4. When writing about a problem, outcome, or action - ask: who did this, and what caused it? Put both in the statement.
5. This applies to all content: emails, reports, documents, status updates, chat responses, everything.
6. This is a hard rule with no exceptions.

## Overloaded Enumeration

Do not cram every related function, workflow, or example into a single sentence or paragraph. Avoid kitchen-sink writing that stacks items together without structure or priority.

1. Never string together long inline lists of nouns, features, or items separated by commas.
2. Avoid kitchen-sink writing that stacks items together without structure or priority.
3. Group ideas into clear categories and lead with the most important point.
4. Write in concise, strategic language.
5. If a long list is necessary, structure it intentionally as a numbered list - never append items inline.
6. When tempted to write "X, Y, Z, A, B, and C" in a sentence - stop. Pick the governing idea and write to it instead.

Bad: "The upgrade window is an opportunity to modernize trade capture, scheduling, nominations, valuation, settlement, invoicing, accounting handoffs, reporting, integrations, and support operations."

Good: Identify the governing idea and write to it. Move detail to a structured list only if the list adds clarity.

Caught in the KwikTrip proposal teardown (2026-08-12): "Deliver reusable code templates, architecture decisions, data contracts, evaluation patterns, operating procedures, and a prioritized AI use-case backlog." Six items stacked inline with no priority and no structure.

Also caught in the same teardown, inside a process-step table cell: "Load final MarketView pricing, inventory, supply, contract, lane, freight, carrier, store, and operational data; flag late or incomplete sources." Nine items enumerated in one cell. The pattern recurred in nearly every row of that table, not just this one.

A fourth instance, smaller but still worth catching: "Contract information must be pulled and interpreted repeatedly to determine which stores, terminals, lanes, and supply arrangements should be used." Four items where the specifics do not matter as much as the fact that many factors are in play. Mara's fix: "Contract information must be pulled and interpreted repeatedly across a multitude of factors." The rule applies even below the three-item threshold when the list is standing in for a general point rather than naming things the reader actually needs.

## Comma-Paired Slogan Phrasing

Never use comma-paired contrasting phrases in any content.

1. This is the pattern of pairing two nouns or concepts with a comma to create a slogan-style contrast, e.g.:
   a. "Outcomes, Not Outputs"
   b. "Strategy, Not Theater"
   c. "Signal, Not Noise"
   d. "Progress, Not Perfection"
   e. "Clarity, Not Complexity"
   f. "starting points, not constraints"
   g. "a recommendation, not a list of options"
   h. "informed input, not directives"
   i. "starting point, not a rulebook"
2. The pattern also appears mid-sentence, not just as standalone headers or slogans. Any "X, not Y" construction where both sides name a thing is a violation, regardless of capitalization or position in the sentence.
3. These phrases are opaque to first-time readers and signal AI-generated content.
4. Instead, write a plain sentence that explains the actual distinction or point being made.
   a. Bad: "Her implementation preferences are starting points, not constraints."
   b. Good: "Her implementation preferences are a reasonable starting point that can be updated when current practice diverges from them."
   c. Bad: "Lead with a recommendation, not a list of options."
   d. Good: "Lead with a recommendation. Mara prefers an informed point of view over a neutral menu of choices."
5. The pattern is especially tempting when articulating calibration rules, preferences, or distinctions between two approaches. That is exactly when to stop and rewrite as a plain sentence.
6. This applies to all content: chat responses, documentation, emails, UI copy, headers, release notes, everything.
7. Caught in the KwikTrip proposal draft (2026-08-12), and worth noting because Claude wrote it while actively enforcing this exact rule elsewhere in the same document: "Contract terms get re-derived, not looked up" and "Commercial capacity goes to assembly, not analysis." Both went into a first-draft rewrite meant to fix other violations. The lesson isn't just for the source document, generated content needs the same check applied to it before it's presented, not just the material being edited.
8. The pattern isn't limited to the literal "X, not Y" contrast. Short parallel phrases joined by a comma for rhythm, with no "not" at all, read the same way to a reader: sloganeering rather than a plain statement. Also caught in the KwikTrip draft, in section subtitles specifically, which are short by design and where this temptation is strongest: "Three problems, one root cause: manual assembly of data that already exists" and "One shared foundation, built once, carries both projects and future AI work." Neither uses "not," both still read as a slogan. Rewritten plainly: "All three problems trace to manual assembly of data that already exists" and "A single shared foundation supports both projects and future AI work."

## Opaque Shorthand

Never invent a compact phrase that makes the reader work out what it means.

1. Examples caught in review: "show the shape," "the concrete fact the word was standing in for," "brand as a layer." Also caught in the KwikTrip proposal teardown (2026-08-12): "a production contract-intelligence capability," where "production" sits in an unclear spot and the reader cannot tell what it is being contrasted against; and a callout summarizing how two projects relate that took two reads to follow, "Project 1 may consume approved structured terms from Project 2 as constraints or context. Project 2 remains a separate, independently useful contract capability and will not be limited to the nightly workflow."
2. Write the plain instruction instead. "Show the shape of the scope" becomes "Include a visual showing which workstreams run in parallel."
3. If a reader has to read a sentence twice to understand it, rewrite it.

## Claiming Completeness

Never label a list "full" or "complete" when it can't actually be verified as exhaustive.

1. A pre-discovery assumptions list, a first-draft requirements set, anything gathered before the work that would confirm it, is not "full" or "complete." It's what's known so far.
2. Caught in the KwikTrip proposal draft (2026-08-12): "Full Assumptions, Constraints, and Dependencies" as an appendix title, and "the complete constraints, dependencies, and assumptions list" describing the same content. Neither claim was true, discovery hadn't happened yet.
3. Drop the word rather than qualify it. "Assumptions, Constraints, and Dependencies" states what the section is without a claim it can't back up.

## Leading Statements That Do Not Deliver

Never announce that something exists and then fail to state it plainly.

1. Bad: "The failure has a name and a fixed remedy."
2. Good: "The failure is undifferentiated scope."
3. The announcement costs a sentence and delays the point.

## Metaphor in Place of Plain Description

Do not describe a business concept through a metaphor borrowed from another field when a plain word exists.

1. "Symptoms rather than causes" borrows from medicine and states nothing specific.
2. Name the actual thing instead of reaching for a metaphor from an unrelated domain.

## Stacked Compound Sentences

A paragraph carrying more than two "and" or "while" connectors gets broken up.

1. Each sentence carries one idea.
2. Split overloaded sentences at the connector rather than adding more clauses.

Caught in the KwikTrip proposal teardown (2026-08-12):

Bad: "At handoff, Kwik Trip should be able to operate both projects and begin a new read-oriented AI use case using approved patterns without rebuilding model access, security, data governance, monitoring, or deployment from the ground up." One sentence stating three separate points and enumerating five technical categories.

Good: "At handoff, Kwik Trip's team fully operates both projects without support from The Vessel Group." State the one point the sentence is actually trying to make.
