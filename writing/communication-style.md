---
title: "Communication Style"
slug: "communication-style"
category: "writing"
order: 1
summary: "Universal rules for how content is structured, formatted, and expressed across all written output."
tags: ["Writing", "Style", "Communication", "Formatting"]
conviction: "tight"
updatedAt: "2026-08-12"
---

# Communication Style

## Scope of These Rules

These preferences apply universally, without exception, across all of the following:

1. **Chat responses** - everything written directly to the user in conversation
2. **Generated content** - emails, documents, reports, proposals, and any other deliverable
3. **Generated code** - comments, strings, documentation, commit messages, and any human-readable text inside code
4. **All other output** - if Mara can read it, these rules apply to it

No rule in this file is limited to one type of output. If a rule exists here, it applies everywhere.

Formatting and mechanical rules that apply to all content.

## Conciseness

When "concise" is requested, that means under 200 words, preferably under 100 words.

1. This applies to all written communications: emails, LinkedIn messages, chat responses, summaries.
2. Get to the point quickly and eliminate unnecessary words.
3. If concise content is not specified, you can be more thorough.
4. Respect this strict word limit when concise content is requested.

## Keyword-Led List Items (Consulting Deliverables)

Every list item in formal deliverables, proposals, and reports must open with a bold keyword or short phrase, followed by a hyphen-dash, followed by the supporting detail. This does not apply to chat responses or emails.

1. The keyword names the idea; the detail explains or qualifies it.
2. Use a hyphen-dash ( - ) as the separator, never an em dash or colon.
3. Keep the keyword short (1-4 words); keep the supporting detail to one sentence.

Examples:

1. **Core system of record** - Keep Aligne as the authoritative source for transactions, operational workflows, and controlled commercial processing.
2. **V26 upgrade** - Deliver clear workflow ownership, cleaner integrations, stronger controls, and better testing discipline.
3. **Data lake path** - Architect the Aligne implementation to support future analytics, optimization, and AI without turning this engagement into a production data lake build.
4. **Functional scope** - Keep settlement, invoicing, reporting, and accounting handoff impacts inside the broader Aligne implementation.
5. **User burden** - Reduce it by applying VG knowledge, existing documentation, earlier discovery outputs, and targeted workshops.
6. **Roadmap** - Leave PSEG with an actionable plan for a future data lake, self-service analytics, optimization, and AI program.

Caught in the KwikTrip proposal teardown (2026-08-12), a violation rather than an example to follow: "Ranked sourcing and movement recommendations by the agreed business dimensions." A plain descriptive bullet with no keyword lead, repeated across the whole list. Rewrite as, for example, "**Ranked recommendations** - Sourcing and movement options ranked by the agreed business dimensions."

## Punctuation

### Em Dashes

Never use em dashes (—) in any content, ever.

1. This applies to all content: emails, documents, chat responses, release notes, reports, everything.
2. Alternatives to use instead:
   a. Rewrite the sentence to avoid the pause
   b. Use a comma
   c. Use a hyphen/dash (not em dash)
   d. Use a period and start a new sentence
3. This is a hard rule with no exceptions.

### Colons as Separators

A hyphen-dash is the default separator or introductory punctuation in copy, not a colon.

1. Use a hyphen/dash by default (e.g., "Next steps - FSS to document workflow" not "Next steps: FSS to document workflow")
2. A colon is acceptable where a list carries multiple separators and a hyphen-dash would read ambiguously.
3. Colons are also acceptable in list labels that are part of structured document formatting (e.g., "To:", "Subject:" in email headers)
4. This applies to emails, documents, chat responses, and all other content.

### Semicolons

Never chain multiple items or independent clauses together with semicolons in place of a real list. This is a strong AI-drafting tell, a sentence trying to hide a list inside prose.

1. If there are multiple distinct items, use a numbered list, not semicolon-joined clauses.
2. If there are exactly two independent clauses, use a period and start a new sentence, or a hyphen-dash if one clause is clearly the explanation of the other.
3. Caught in the KwikTrip proposal teardown (2026-08-12): "Source systems remain authoritative; the new applications consolidate data for decision support." Two independent clauses forced together. Rewrite as two sentences.
4. A more extreme version, same teardown, a table cell: "Versioned ARB, netback, freight, allocation, and optimization services; nightly work queue; scenario review; approval; export; alerts; run history; test evidence." Eight items chained with semicolons standing in for a numbered list. This is what a hidden list looks like, break it into one.

### Connector-Chained Run-Ons

Never fuse multiple distinct topics or facts into one sentence using prepositional or participial connectors like "with," "alongside," "while," or "as well as." This is the comma-and-preposition version of the semicolon problem above, a run-on hiding multiple ideas instead of a list.

1. A sentence carries one idea. If a connector word is introducing a second, unrelated fact or topic, that fact belongs in its own sentence.
2. This is especially common in status and weekly summaries, where every open workstream gets crammed into one opening sentence.
3. Caught in the SCC CEO Weekly Report (2026-08-15): "This week's work centered on the CFE International engagement, with kickoff held August 17 and discovery meetings scoped across finance, risk, operations, and commercial stakeholders, alongside finalizing the Kwik Trip AI Foundation and Commercial Optimization proposal." Two unrelated engagements (CFE International and Kwik Trip) fused via "alongside," and the CFE International clause alone already stacks two facts (kickoff date, discovery scope) via "with... and." Rewrite as three sentences: "This week's work centered on the CFE International engagement. Kickoff was held August 17, with discovery meetings scoped across finance, risk, operations, and commercial stakeholders. The team also finalized the Kwik Trip AI Foundation and Commercial Optimization proposal."

## Numbers

### Time Units, Whole Numbers Only

Never state a duration in fractional units a reader cannot picture, such as "2.3 months" or "0.3 weeks." Humans do not have an intuitive sense of a third of a month.

1. Round up to the next whole unit, not to the nearest one. "2.3 months" becomes "3 months," not "2 months." Rounding a favorable duration (payback, time to value) down overpromises speed. Rounding up is the conservative, defensible direction.
2. If the precision genuinely matters, switch to a smaller whole unit instead of using a fraction of a larger one, "10 weeks" rather than "2.3 months."
3. This applies everywhere a duration appears, not only value or ROI sections: timelines, payback periods, project lengths, anywhere a time span is stated.
4. Caught in the KwikTrip proposal teardown (2026-08-12): "Illustrative payback: 2.3 months." Rewrite as "Time to payback: 3 months."

### Redundant Total Restatement

Once a headline figure is established in a table, a callout, or a stat, later sentences reference it descriptively, "this estimate," "the total," rather than repeating the specific number.

1. A figure that reappears verbatim in a heading, an assumption, and a callout has not been emphasized, it has been duplicated. The reader remembers a number better when it appears once, in the place built to hold it, than when it is scattered through the document.
2. This applies to any document with a headline number stated more than once: proposals, reports, emails, status updates.
3. Caught in the KwikTrip proposal teardown (2026-08-12): $585,600 appeared in the section heading, the pricing table's total row, a workstream allocation table's total row, a Key Assumptions bullet, and an "authorize now" callout, five separate places for one number.

### Count Drift (Stated Number Doesn't Match the List)

Never state a specific count and then append additional instances of that same category afterward with "plus," "as well as," or "along with." The reader is told a number, then shown more than that number, a miscount in plain sight.

1. Tally the complete list first, then state the count. Do not write the number before the full set of items is assembled.
2. If an item was drafted or remembered after the count was already written, go back and revise the number, do not bolt the item on with a connector word.
3. This is especially likely when items in the same category come from more than one source (e.g., some folded into other sections, some listed standalone), since it is easy to count only the source in front of you and miss the rest.
4. Caught in the SCC CEO Weekly Report (2026-08-15): "Two networking meetings, Quinn and Harrison from The Farmer's Dog and independent consultant Matt Bernier, plus a networking call with Andrew Brummer on AI." Three meetings are described, the stated count says two. Rewrite as "Three networking meetings: Quinn and Harrison (The Farmer's Dog), independent consultant Matt Bernier, and Andrew Brummer (AI discussion)."

## Links and URLs

Always render URLs as markdown hyperlinks, never as bare plaintext URLs.

1. Use `[descriptive text](url)` syntax so links are clickable.
2. The link text should describe the destination, not repeat the raw URL.
3. This applies to all chat responses, documents, and written content.

## Paragraph Alignment

Always use left-aligned paragraphs unless explicitly stated otherwise.

1. Never use justified alignment for paragraphs.
2. This applies to all documents: Word docs, cover letters, emails, presentations.
3. Only use center or right alignment when explicitly requested.

## File Paths

State the full absolute Windows file path immediately after creating or editing any file.

1. Use the complete path, not a relative path or filename alone.
2. State it right after the action, not only when asked.

## Company Names

The first mention of any company name in a document gets its website in parentheses.

1. Applies only to the first mention within a given document; later mentions do not repeat it.
2. Use the company's primary website, e.g., "The Vessel Group (thevesselgroup.com)."

## Consistent Nomenclature

Use one label for one concept throughout a document.

1. Once a term is chosen for a concept, do not swap in a synonym or a shortened variant later in the same document.
2. Caught in review: "Count" in one section and "Body count" in the next for the same idea.
3. Applies to all documents, reports, proposals, and decks.

## Detail in the Wrong Place

Too much detail in an opening or a summary is a signal that the writer has not decided what matters.

1. Specifics such as phase names, hour estimates, and system names belong in the body, not the opening or summary.
2. An opening or summary should orient the reader, not front-load the details that belong later.
