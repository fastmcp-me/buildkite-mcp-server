[![Add to Cursor](https://fastmcp.me/badges/cursor_dark.svg)](https://fastmcp.me/MCP/Details/1620/buildkite)
[![Add to VS Code](https://fastmcp.me/badges/vscode_dark.svg)](https://fastmcp.me/MCP/Details/1620/buildkite)
[![Add to Claude](https://fastmcp.me/badges/claude_dark.svg)](https://fastmcp.me/MCP/Details/1620/buildkite)
[![Add to ChatGPT](https://fastmcp.me/badges/chatgpt_dark.svg)](https://fastmcp.me/MCP/Details/1620/buildkite)
[![Add to Codex](https://fastmcp.me/badges/codex_dark.svg)](https://fastmcp.me/MCP/Details/1620/buildkite)
[![Add to Gemini](https://fastmcp.me/badges/gemini_dark.svg)](https://fastmcp.me/MCP/Details/1620/buildkite)

# buildkite-mcp-server

[![Build status](https://badge.buildkite.com/79fefd75bc7f1898fb35249f7ebd8541a99beef6776e7da1b4.svg?branch=main)](https://buildkite.com/buildkite/buildkite-mcp-server)

> **[Model Context Protocol (MCP)](https://modelcontextprotocol.io/introduction) server exposing Buildkite data (pipelines, builds, jobs, tests) to AI tooling and editors.**

Full documentation is available at [buildkite.com/docs/apis/mcp-server](https://buildkite.com/docs/apis/mcp-server).

---

## Library Usage

The exported Go API of this module should be considered unstable, and subject to breaking changes as we evolve this project.

---

## Security

To ensure the MCP server is run in a secure environment, we recommend running it in a container.

This image is built from [cgr.dev/chainguard/static](https://images.chainguard.dev/directory/image/static/versions) and runs as an unprivileged user.

---

## Contributing

Development guidelines are in [`DEVELOPMENT.md`](DEVELOPMENT.md).

---

## License

MIT © Buildkite

SPDX-License-Identifier: MIT
