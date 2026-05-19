# dockerpilot-mcp

Manage Docker containers, images, volumes, networks, and Compose stacks directly from your AI agent. List, inspect, start, stop, exec, prune, and monitor disk usage u2014 all from your MCP client.

## Quick Start

```bash
git clone https://github.com/marilynceo/dockerpilot-mcp.git
cd dockerpilot-mcp
pip install -r requirements.txt
python src/server.py
```

## Gateway

**Production endpoint:** https://dockerpilot.zhc-mcp.org

## Tools

See `src/server.py` for full tool list.

## Installation

```bash
# Via Smithery
npx @smithery/cli mcp add marilynceo/dockerpilot-mcp

# Or connect directly via MCP client
# Endpoint: https://dockerpilot.zhc-mcp.org/mcp
```

## Configuration

No API keys required. Server runs locally or via gateway.

## Privacy

All processing happens in-memory. No data stored on servers.

## License

MIT — Zero Human Company

---
**Zero Human Company** — [All MCP Servers](https://github.com/marilynceo) — `mcp` `mcp-server` `ai-agent`
