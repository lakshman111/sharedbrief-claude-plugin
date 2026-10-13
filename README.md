# SharedBrief

Create readable, shareable business documents from selected content in Claude, Cursor, or Grok Build. SharedBrief combines one authenticated remote connector with 66 original skills: 63 document workflows, two writing/design skills, and an engagement-review skill.

## Start with one useful document

Add the plugin and connect SharedBrief through OAuth using your SharedBrief account. Try “Create a private sales follow-up brief from these notes,” “Draft an investor memo from these facts,” or “Prepare a consulting audit report from these findings.” Review the draft, then request publication for the intended audience. Installing the package does not bypass account connection or publish content automatically.

## Included workflows

- **Sales:** Account research brief, Case study, Champion enablement page, Deal room, Follow-up page, Mutual action plan, Personalized outbound page, Pricing calculator, Pricing page, ROI business case, Sales funnel page, Sales proposal.
- **Founder:** Customer pitch, Fundraising deck, Hiring page, Investor memo, Launch page, Product brief, Product demo page, Strategy workbook.
- **Consultant:** Account growth plan, Audit report, Client proposal, Client report, Strategy brief, Workshop recap.
- **Agency:** Campaign recap, Client pitch, Creative brief, Performance report, Proposal, Strategy deck.
- **Recruiting:** Candidate profile, Hiring packet, Interview plan, Role brief, Search update, Talent pitch.
- **Real Estate:** Buyer guide, Market report, Neighborhood page, Open house page, Property listing, Seller pitch.
- **Creator:** Course page, Flipbook page, Instagram Freebie Builder, Launch page, Lead magnet, Media kit, Portfolio page, Sponsor pitch.
- **Other:** Brief, Business proposal, Event field guide, Event invitation, Event landing page, Landing page, One-pager, Report, Service page, Shareable doc, Team playbook.
- **General:** document design and plain-language editing.
- **Engagement:** inspect approximate readership and prepare a suggested follow-up draft.

Skills with similar names have audience-specific descriptions. Choose the one that matches the user's requested context rather than running multiple equivalent workflows. These instructions were independently authored for SharedBrief; this is not Send's package and does not imply affiliation with Send.

## Supported output and limits

SharedBrief creates private structured documents and, where available, designed static HTML. You can publish a stable link, update it, restrict access, inspect approximate engagement, or withdraw publication. Public links are readable by anyone with the link; verified and specific-email modes require verified sign-in.

Calculator skills produce static scenarios and arithmetic, not live calculators. Flipbooks become numbered reading sections. Deck skills produce document outlines, not PowerPoint or slide files. Event, hiring, course, and service pages can link existing destinations but do not implement RSVP, applications, checkout, scheduling, or enrollment. Product demos link existing recordings or demos. Instagram resources do not automate comments or messages. Lead-magnet skills do not automatically configure capture gates. The plugin has no email/DM sending capability and contains no executable hooks or scripts.

Internal account research and sensitive hiring/client material remain private unless the user authorizes appropriate sharing. Unknown pricing, dates, metrics, approvals, and returns remain explicit. Anonymous views do not identify readers or establish purchase intent. Engagement statistics are approximate daily/browser observations, not unique people.

## Data and permissions

The only declared remote MCP endpoint is https://www.sharedbrief.com/mcp. The plugin reads account-owned documents, access settings, and approximate engagement data and sends selected content/parameters only when the user requests a SharedBrief action. It does not automatically request or collect whole conversations, memory, private chat history, or unrelated uploaded files. Supplied briefs and sharing lists can contain personal data. Hosted processing and providers are described in the [privacy policy](https://www.sharedbrief.com/privacy).

Briefs are retained until deleted. Account and readership retention details appear in the privacy policy. Public readers may copy accessible material. Unpublishing withdraws hosted access; deleting a brief removes it and associated view records. Requests involving analytics data can be sent to support@sharedbrief.com. The plugin is for professional use and is not directed at children.

The package contains readable instructions, a local shared reference, an icon, and a remote MCP configuration. There are no local executables, shell hooks, subagents, hidden network destinations, or bundled OAuth credentials. The hosted service enforces ownership and reader access. Plugin source is proprietary; see LICENSE.

## Support

[Help](https://www.sharedbrief.com/help) · [Privacy](https://www.sharedbrief.com/privacy) · [Terms](https://www.sharedbrief.com/terms)

Contact support@sharedbrief.com. Operated by SnuffleLabs LLC.

## Marketplace compatibility

This source contains Claude and Cursor manifests. Grok Build accepts the Claude manifest. Cursor uses `mcp.json`; Claude and Grok Build use `.mcp.json`. Both configurations declare the same authenticated endpoint. Marketplace submission does not mean approval or native execution verification. The repository name is retained for stable existing Claude review references.
