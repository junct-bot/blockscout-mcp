# Blockscout MCP Server

MCP server for Blockscout. Agent-ready API for Blockscout.

Hosted at [blockscout.mcp.junct.dev/mcp](https://blockscout.mcp.junct.dev/mcp). Free to use. No auth. No API key required.

Part of [Junct](https://junct.dev) — the agent-readiness layer for the crypto stack.

## Quick Start

Add to your MCP client config (Claude Desktop, Cursor, Windsurf):

```json
{
  "mcpServers": {
    "blockscout": {
      "url": "https://blockscout.mcp.junct.dev/mcp",
      "transport": "streamable-http"
    }
  }
}
```

## About

This MCP server is **deterministically generated** from the Blockscout API specification. Every tool maps 1:1 to a real API endpoint — no hallucinated endpoints, no phantom tools.

- **Protocol:** Blockscout
- **Endpoint:** `https://blockscout.mcp.junct.dev/mcp`
- **Transport:** Streamable HTTP
- **Auth:** None required
- **Documentation:** [blockscout.mcp.junct.dev/llms.txt](https://blockscout.mcp.junct.dev/llms.txt)
- **Server card:** [blockscout.mcp.junct.dev/.well-known/mcp/server.json](https://blockscout.mcp.junct.dev/.well-known/mcp/server.json)

## Links

- [Junct Dashboard](https://junct.dev/servers/blockscout)
- [llms.txt](https://blockscout.mcp.junct.dev/llms.txt)
- [agents.md](https://blockscout.mcp.junct.dev/agents.md)
- [OpenAPI spec](https://blockscout.mcp.junct.dev/openapi.json)

## Keywords

Blockscout, MCP server, DeFi, AI agent, agent-ready API, crypto tools, Model Context Protocol, hosted MCP
