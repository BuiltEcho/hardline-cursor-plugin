# Hardline for Cursor and Grok Bot

Connect your Hardline account to access project context, call summaries, captures, tasks, contacts, and messaging through the Hardline remote MCP server.

## Connection

Server: `https://api.hardlineapp.com/mcp`. Authentication uses the Hardline OAuth browser flow. Sign in with your production Hardline account and review the permissions requested by the client. Availability depends on account permissions and enabled features.

After installation, connect the Hardline MCP server in Cursor and complete OAuth. Team administrators control plugin availability. Grok Bot inherits the team connector policy.

Example prompts:

- Find my recent call summaries in Hardline.
- Find project documentation related to today's site meeting.
- Show my open follow-up tasks.

## Permissions and actions

Depending on the approved scopes, tools can read context and media, query or learn Miriel context, manage projects/tasks/contacts, and send or retry SMS/MMS. Review each write action in the host approval UI. Message acceptance means queued; check the message or timeline before treating it as sent or delivered. Reconnect when adding scopes.

## Support and privacy

- Website: https://www.hardlineapp.com
- Account: https://app.hardlineapp.com
- Privacy: https://www.hardlineapp.com/privacy
- Support: support@hardlineapp.com
- Security reports: security@hardlineapp.com

## Status and licensing

Connection behavior depends on the deployed Hardline service. This package has not yet completed Cursor runtime or marketplace review.

The connection configuration and documentation are licensed under MIT; see LICENSE. The Hardline logo in assets/hardline-logo.png and Hardline trademarks are excluded from the MIT grant. All rights in the logo and trademarks are reserved. No license to the Hardline service or product implementation is granted by this repository. A Hardline account is required; service plan and feature availability apply.
