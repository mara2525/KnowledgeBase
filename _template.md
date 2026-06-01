---
title: "Document Title"
slug: "document-slug"
category: "frameworks"
order: 1
summary: "One to two sentence summary used in navigation and AI context."
tags: ["Tag1", "Tag2"]
updatedAt: "YYYY-MM-DD"
---

# Document Title

One paragraph framing what this document is and when to use it.

## Overview

What this framework covers and the problem it addresses.

## How to Apply

1. First step
2. Second step
3. Third step

## Related Frameworks

1. [**Framework Name**](/category/slug) - One sentence on the relationship
2. [**Framework Name**](/category/slug) - One sentence on the relationship

---

# Frontmatter Field Reference

Required fields:

1. title - Display name of the document, used in navigation and headings
2. slug - Kebab-case identifier matching the filename, used in URLs and cross-references
3. category - Folder name the document lives in (frameworks, product, writing, engineering, ai)
4. order - Integer position within the category for sorting
5. summary - One to two sentences describing the document, shown in navigation and used by AI for context loading
6. tags - Array of descriptive keywords for filtering and discovery
7. updatedAt - ISO date (YYYY-MM-DD) of the last meaningful content change

Optional fields:

1. parent - Slug of the parent document when this doc is a child in a hierarchy (e.g., a detailed sub-topic under a broader overview)
2. hidden - Set to true when the document should not appear in top-level navigation (always paired with parent)
3. status - Lifecycle state of the content. Values: Live, Draft, Planned
4. conviction - How strongly these rules are held. Values: tight, moderate, loose
5. foundation - Slug of a conceptual predecessor this framework builds on (distinct from parent, which is a navigation relationship)
