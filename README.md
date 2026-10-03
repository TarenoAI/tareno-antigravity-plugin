# Tareno for Google Antigravity

Plugin bundling the Tareno remote MCP connector and `tareno-social-ops` skill. Supports connected account discovery, analytics, content strategy, media, draft creation, and approval-backed scheduling and publishing.

## Install locally

Clone this repository and install its directory through Antigravity's plugin manager (`/plugin install <local-path>`) or `agy plugin install <local-path>`. For workspace installation, use `.agents/plugins/tareno/`.

Authenticate the Tareno server in Settings → Customizations when prompted. Tareno supports OAuth with dynamic client registration; no API key or credential is bundled. A Tareno account with MCP access is required.

After authentication, ask “List my connected Tareno accounts” and “Analyze my social performance this month.” Create drafts before publishing; consequential actions provide a Tareno approval URL and must be checked for success.

## Compatibility and marketplace status

The package follows Google's documented `plugin.json`, `mcp_config.json` and skill format. OAuth and tool execution in Antigravity are not yet verified end to end. Public GitHub distribution and marketplace review are separate from approval and public listing.

MCP: https://tareno.co/api/mcp  
Documentation: https://tareno.co/docs/mcp  
Privacy: https://tareno.co/legal/privacy  
Support: support@tareno.co
