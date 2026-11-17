# Homebrew tap for vi-mcp

[vi-mcp](https://github.com/imoes/vi-mcp) — a VI memory as an MCP server for many AI sessions.

```bash
brew install imoes/vi-mcp/vi-mcp
vi-mcp instance "$USER" --reflexes      # prints the token once
brew services start vi-mcp && vi-mcp setup
```

The formula is written by the vi-mcp release (`deploy/release.sh`, template `deploy/macos/vi-mcp.rb.in`); edit it there, not here.
Its source archive is the release asset `vi-mcp-<version>.tar.gz`, listed in the release's signed `SHA256SUMS`.
