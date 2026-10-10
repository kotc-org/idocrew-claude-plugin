# I Do Crew for Claude

Review your connected I Do Crew wedding preferences, vendor recommendations, matches, approved conversations, and notifications. This plugin contains one focused review skill and the existing remote MCP connector. It does not include customer records, credentials, or a local executable.

## Connect

The MCP endpoint is `https://idocrew-connectors-85059751688.us-east1.run.app/api/mcp`. Sign in to your existing I Do Crew account through the connector's OAuth flow and approve read-only access. Disconnect or revoke access through the connector setup page when needed.

The integration cannot send messages, book vendors, process payments, delete records, or change profiles. User-provided free text returned from authorized records may contain personal information or links.

## Examples

- “Summarize my wedding preferences and vendor match status.”
- “Show up to five recommended vendors within my saved preferences and a $5,000 maximum budget.”
- “Summarize the last ten messages from one of my approved vendor matches.”

## Documentation and privacy

- [Setup and documentation](https://idocrew-connectors-85059751688.us-east1.run.app/connectors)
- [Privacy policy](https://idocrew-connectors-85059751688.us-east1.run.app/legal/privacy)
- [Support](https://idocrew-connectors-85059751688.us-east1.run.app/legal/support)
- [Terms](https://idocrew3.web.app/terms)

This is a proprietary submission candidate, not an open-source release. The repository remains private. Anthropic's directory scanned version 1.0.0 privately; version 1.0.1 adds the missing license declaration and proprietary notice. Neither scan nor this notice means the plugin is submitted, approved, or published. Submit the remote MCP connector separately, then submit this bundle from the same Claude organization. Use the same MCP URL so users who install both see one tool set.
