---
name: proposal-business-case
description: Use when the user wants a SharedBrief sales proposal, pilot scope, or buyer business case based on supplied deal information.
---

# Proposals and business cases with SharedBrief

Build a buyer-facing proposal from selected deal facts: the buyer's problem and desired outcome, proposed scope and exclusions, milestones, success criteria, responsibilities, and commercial terms where provided. Mark tentative terms and assumptions. Leave unknown pricing, dates, approvals, and economics open; do not invent ROI or customer endorsements. Separate internal negotiation notes from buyer-facing content.

For a quantitative business case, state the supplied baseline, assumptions, calculation, and units. If inputs are missing, produce an explicitly unquantified framework and ask for the important inputs. A draft is not an accepted contract.

Use the connected SharedBrief tools according to their current schemas. Create privately with `create_document` and a fresh idempotency key for a new brief; reuse it only for a retry of that creation. Return the tool-provided draft/owner URL for review. If connection or creation fails, label the output as unsaved rather than claim success.

Publish only under the user's authorization. Inspect current access with `get_document_sharing` and match the intended audience before publishing; public means anyone with the link. Supported sharing settings require verified sign-in or selected verified emails. Configuration does not send invitations. For an existing proposal, read current content and revision before `update_document`; preserve its stable URL and unrelated design. On revision conflict, reread and reconcile.

Example: “Pilot might be 30 days, timeline not approved, price unknown.” Label the duration tentative and leave price open. Do not turn estimates into commitments.
