---
name: buyer-follow-up
description: Use when the user wants a SharedBrief buyer follow-up, sales meeting recap, or deal next-steps brief from selected conversation context or notes.
---

# Buyer follow-up with SharedBrief

Create a concise buyer-facing recap using the deal context the user selects. Include their objectives, agreed decisions, outstanding questions, and next steps with owners and dates where supplied. Distinguish suggestions from agreed commitments. Omit internal sales strategy and other material not intended for the buyer. Ask only for missing information needed to make the brief useful.

Use the connected SharedBrief tools and their current input schemas. `create_document` creates a private draft and requires an idempotency key; reuse that key only for retries of the same creation. A returned owner/preview URL is not proof of publication. If the connector is unavailable, explain how to connect it and offer a local draft; do not claim a saved brief.

Present the saved draft for review. Publish only when the user's instructions authorize it. Before publishing, inspect the current access settings using `get_document_sharing`; public access means anyone with the link can read it. Honor the intended audience using supported access tools or the dashboard. Access changes on published briefs take effect immediately. Do not claim invitations or emails were sent: sharing tools do not send them.

For revisions, read the latest document and use its current revision with `update_document`. Preserve the existing URL and unrelated content/design. Treat a revision conflict as a reason to reread rather than overwrite. Return the URL actually supplied by the successful tool result.

Example: “Draft only: Acme wants a pilot; security review is outstanding; pricing is unapproved.” Produce a private recap with those open items, not a priced offer or approved pilot commitment.
