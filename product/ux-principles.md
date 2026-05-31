# UX Principles

Rules for UI and UX design. These are tightly held. Apply them to any software being designed, evaluated, or critiqued.

## Mobile First

Mobile responsiveness is a core requirement, not an enhancement.

1. Every layout, view, and interaction must be designed to work on a mobile screen from day one.
2. Do not design for desktop and adapt for mobile — design for mobile and scale up.
3. A product that is desktop-only is not finished, regardless of how complete it appears on a large screen.
4. Dense tables and spreadsheet-style grids that work on a 27-inch monitor are unusable on a phone. If a layout depends on horizontal screen space, it is not mobile-ready.

**Anti-pattern**: TowFlow was built desktop-only with no consideration for mobile. It is completely unusable on a phone or tablet.

## Do Not Replicate Excel on the Web

Defaulting to tables, columns, and rows as the primary UI pattern is a failure of product design — not a solution.

1. Dense tabular layouts are hard to read, not mobile-friendly, visually overwhelming, and indistinguishable from the spreadsheets users are trying to move away from.
2. Preferred alternatives:
   a. Card views that surface the most critical information per record
   b. Dashboard-style summary views that give users a clear picture at a glance
   c. List views with smart prioritization and status indicators
   d. Detail-on-demand: show the summary first, let the user drill in when needed
3. If a table is truly the right choice, it must be justified — not the default.

**Anti-pattern**: TowFlow presents all barge operations data in a dense, column-heavy table. It looks like Excel rendered in a browser.

## Semantic Color

Colors must communicate something specific and intentional.

1. Acceptable uses of color:
   a. Status indication (green for healthy, red for at-risk, yellow for caution)
   b. Visual hierarchy
   c. Brand identity, applied consistently
2. Do not use color decoratively or arbitrarily. If a user cannot quickly understand why something is a certain color, it should not be that color.
3. Color systems must be documented and consistent — a color used for one status in one view should mean the same thing everywhere.

**Anti-pattern**: TowFlow uses colors throughout its interface with no clear meaning or system. The colors are visually chaotic and do not help users understand anything.

## Typography and Readability

Typography choices directly affect how professional, trustworthy, and usable a product feels.

1. Fonts must be large enough to read comfortably without zooming.
2. Input fields must be appropriately sized for touch interaction on mobile.
3. Line spacing and padding must give the interface room to breathe.
4. Font choices should reflect the tone and brand of the product.
5. Small fonts, cramped fields, and low-contrast text are unacceptable in production software.

## Mobile Dashboard Patterns (evolving)

For transactional or operational mobile views, reference Robinhood as a benchmark for clean data presentation.

1. Show clean summary views that surface the most important information first.
2. Distinguish inbound and outbound data clearly.
3. Design for scannability — users should not have to scroll through dense rows to get oriented.
4. Use card or list-based layouts, not table-based layouts.
5. Maintain clear visual hierarchy with minimal noise.

*This section will be expanded as specific reference interfaces are identified and analyzed.*
