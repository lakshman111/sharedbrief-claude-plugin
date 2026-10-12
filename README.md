# SharedBrief

Turn selected work in Claude into clear buyer-facing briefs. This plugin combines the SharedBrief connector with three focused skills: buyer follow-up, proposals and business cases, and engagement review.

## Get started

Add the plugin, connect SharedBrief, and sign in to your SharedBrief account through OAuth. Then ask Claude: “Create a private buyer follow-up brief from the deal notes in this conversation.” Review the draft before asking to publish it. Account connection is required for SharedBrief tool calls; this package does not bypass authentication.

## Workflows

- **Buyer follow-up:** organize buyer needs, decisions, open questions, and next steps into a private draft.
- **Proposal and business case:** prepare scope, assumptions, success measures, and commercial terms using facts you supply.
- **Engagement review:** inspect a brief’s approximate readership statistics and prepare a follow-up draft. Anonymous activity does not identify buyers or establish purchase intent.

SharedBrief can publish a stable link, update its content, and withdraw publication. Access can be public, require verified sign-in, or be limited to selected verified email addresses. Publishing and access changes should follow your instructions. The plugin does not send emails or messages.

## Data and permissions

The plugin declares one remote MCP server: https://www.sharedbrief.com/mcp. It reads documents and access/engagement data from your SharedBrief account and sends only content and parameters explicitly selected for SharedBrief tool calls. It does not request or upload entire conversations automatically. Brief content may contain personal data you choose to include. Account information, document content, sharing settings, and approximate reading activity are handled by the SharedBrief service according to its [privacy policy](https://www.sharedbrief.com/privacy).

Drafts are private until published. Public links allow anyone with the link to read them. Do not include internal-only notes or unsupported claims in buyer-facing content. SharedBrief stores briefs until deleted; use the dashboard or request deletion of a specific brief. See the privacy policy for service-level retention details.

The package contains text instructions and a remote MCP configuration. It has no local executables, shell hooks, subagents, or additional outbound services. OAuth credentials are not bundled. The hosted service enforces account ownership and reader access. This plugin is intended for professional use, not directed at children.

## Support

[Help](https://www.sharedbrief.com/help) · [Privacy](https://www.sharedbrief.com/privacy) · [Terms](https://www.sharedbrief.com/terms)

Contact support@sharedbrief.com. Operated by SnuffleLabs LLC.
