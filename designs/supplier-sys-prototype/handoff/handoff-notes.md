# Handoff notes & interaction map

This document contains annotated notes for dev handoff and a high-level interaction map for the main flows.

## Key flows

- Company: Create RFQ → Publish → Receive Quotes → Compare → Accept → Generate PO → Track Order
- Supplier: Discover RFQs → Submit Quote (draft/submit) → Receive PO → Acknowledge → Ship → Upload invoice

## Annotation highlights

- Quote validity must be enforced (valid_until field). Expired quotes should be greyed out.
- Acceptance of a quote should open a confirmation modal allowing edits to quantities and shipping before PO generation.
- All actions must be logged in audit trail (user, timestamp, action).

## Assets included

- design tokens (design-tokens.json)
- component spec (components.md)
- icons (essential set)
- screen placeholders (SVG)

If you need the final ZIP release uploaded or a full set of PNG exports, tell me and I will add them as a release asset.
