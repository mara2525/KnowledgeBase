---
title: "Document Design"
slug: "document-design"
category: "design"
order: 1
summary: "Principles for using visual elements to keep long-form documents readable and hold the reader's attention."
tags: ["Design", "Documents", "Formatting", "Visual Design"]
conviction: "tight"
updatedAt: "2026-08-12"
---

# Document Design

Rules for using visual elements in long-form documents. These apply to proposals, reports, decks, and internal documents.

## The Monotony Problem

Visual relief is a functional tool rather than decoration. It resets the reader's attention and signals that something matters.

1. **Every major section carries a visual moment.** A chart, a callout, a formatted box, or a divider with a color accent all qualify.
2. **The purpose is to hold the reader's attention.** A page of unbroken text on white loses the reader regardless of how good the writing is.
3. **Applies to any long-form document.** Proposals, reports, decks, and internal documents all follow it.

## Totals Rows

Any table with a totals row contrasts that row from the body rows above it, bolded text, a shaded background, or both.

1. A totals row that looks like every other row makes the reader hunt for the number that matters most.
2. Applies to any table with a summary or total line, not only pricing tables: budgets, timelines, scorecards, any tabular data with a bottom-line figure.
3. Caught in the KwikTrip proposal teardown (2026-08-12): neither the pricing table nor the workstream allocation table distinguished its total row from the rows above it.

## Column Width Follows Content

Table columns are sized to what they hold, not split evenly by default.

1. A column carrying a short label next to one carrying multiple sentences or a nested list needs visibly more width, an even split makes the dense column look cramped and the short column look empty.
2. Set widths explicitly (a `colgroup` in HTML, column width settings in Word) rather than letting the renderer split space equally.
3. Caught in the KwikTrip proposal draft (2026-08-12): a three-column deliverables table with a one-word workstream name, a multi-item deliverables list, and a full sentence of acceptance criteria, all rendered at equal width until corrected.

## Accent Color Is Never Text

A brand's accent color marks a bar, a divider, or a background fill. It is not used as text color.

1. On a white or black background, most accent colors, especially a mid-tone gold or yellow, don't carry enough contrast to read comfortably as text.
2. Section labels, headings, and callout labels are set in the brand's dark color. The accent color does its job as a line, a border, or a background fill behind dark text.
3. Caught in the KwikTrip proposal draft (2026-08-12): section number labels and a cover label were set in the brand's gold accent color and were hard to read. Both moved to the brand's dark navy.

## Heading and Subtitle Hierarchy

When a section heading carries a one-line descriptive subtitle underneath it, the subtitle is visibly subordinate, never equal or larger.

1. The heading is the primary visual anchor: largest, boldest, brand dark color.
2. The subtitle is smaller, a muted grey, and boxed as a callout rather than left as plain text competing with the heading above it.
3. A subtitle set at the same size as its heading, or larger, reads as two headings fighting for the same job.
4. Caught in the KwikTrip proposal draft (2026-08-12), and worth noting because it went the wrong direction twice: the descriptive subtitle was first built larger and more prominent than the section-number heading above it, the opposite of the intended hierarchy.

## Value Framing for Highlighted Metrics

A callout built around one number states the reader's benefit against a baseline, not the raw internal or technical figure being measured.

1. "30 minutes" (a processing turnaround time) means little on its own. "Ready roughly 3.5 hours earlier than today" states the actual value, even though 30 minutes is technically the more precise number.
2. Before finalizing any single-stat callout, ask what the reader compares the number to, then state that comparison instead of, or alongside, the raw figure.
3. Caught in the KwikTrip proposal draft (2026-08-12): a "30 minutes" callout for the nightly recommendation's processing time didn't communicate anything until reframed as time reclaimed versus the current 10 PM finish.
