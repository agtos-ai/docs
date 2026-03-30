# agtOS Documentation

Documentation site for [agtOS](https://github.com/agtos-ai/agtos) — a voice-native AI agent platform.

Powered by [Mintlify](https://mintlify.com). Auto-deploys from this repo via the Mintlify GitHub App.

## Local Development

```bash
npm i -g mint
mint dev
```

Preview at `http://localhost:3000`.

## Structure

| Directory | Content |
|-----------|---------|
| `*.mdx` (root) | Getting started pages |
| `configuration/` | Authentication, providers, environment |
| `features/` | Voice pipeline, chat, memory, MCP |
| `api-reference/` | REST API, WebSocket, MCP tools |
| `architecture/` | System overview, ADR index |

## Contributing

Edit `.mdx` files and push to `main`. Changes deploy automatically.

See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.
