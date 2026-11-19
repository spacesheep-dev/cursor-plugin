# Spacesheep for Cursor

Publish pages from your agent to a private, shareable link on [spacesheep.dev](https://spacesheep.dev): reports, plans, docs, designs, dashboards and decks that people open on any device, comment on and come back to.

## What's in it

| Part | What it does |
|---|---|
| `mcp.json` | Connects Spacesheep's MCP server, `https://mcp.spacesheep.dev/mcp`. Nothing to install: it runs on Spacesheep. |
| `skills/spacesheep` | Tells the agent when to use Spacesheep and which tool does what. |

## Use

1. Install the plugin from the marketplace.
2. The first time the agent uses Spacesheep, Cursor asks you to sign in. Sign in with your Spacesheep account (or make one) and approve the connection. There is no key to paste.
3. Ask for a page: "publish this report as a page", "make a one-pager for the launch", "update my plan at spacesheep.dev/@you/plan".

New pages use your account's default audience: private, unless you've changed it.

## Configuration

None. The MCP server signs you in with OAuth.

## Develop locally

Copy this folder to `~/.cursor/plugins/local/spacesheep`, then run **Developer: Reload Window** and check **Customize** for the `spacesheep` skill and the `Spacesheep` MCP server.

## License

MIT
