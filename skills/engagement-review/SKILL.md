---
name: engagement-review
description: Use when the user wants to review SharedBrief readership statistics or prepare a sales follow-up based on a brief's engagement.
---

# Engagement review with SharedBrief

Identify the intended brief from the user's link, ID, or title. Use `list_documents` only if needed to resolve it; ask when multiple candidates remain. Read the document and use `get_document_stats` for current engagement. Do not fabricate tool results or substitute a different brief.

Report the returned time range, counts, latest activity, and aggregates only where present. SharedBrief's estimated views are approximate daily/browser views, not unique people. Visits can repeat. Active time and other activity are approximate. The stats tool does not return reader emails. Anonymous activity does not establish reader identity, buying readiness, or a purchase decision. Zero activity does not prove rejection or nondelivery. Flag missing data without filling it in.

Connect observations to the user's actual deal context, with interpretation labeled separately. Suggest a proportionate next step, such as answering an outstanding question or checking whether the document reached the right person. Draft a follow-up message if requested; this plugin cannot send email or messages. Do not infer recipient identity from an IP address, anonymous activity, or visit count.

This skill is read-only unless the user independently asks to change the brief. Never alter access, publish, delete, or rewrite a document merely to inspect engagement. If a requested change is authorized, read its latest revision and pass it to the appropriate update tool. Reread on revision conflict; preserve its stable URL, unrelated content/design, access, and publication state. Read [SharedBrief workflow](../../references/brief-workflow.md) before any document mutation.

Example: five estimated views and seven visits indicate activity, not five distinct buyers. Prepare a message for a known contact if the user supplies one; do not claim someone is ready to buy.
