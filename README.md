# Installation

1. Prerequisite
    - Git must be installed.

2. Add the following server entry to your MCP servers config (e.g., `mcp-servers.json`):

```json
{
  "mcpServers": {
     "testServer": {
        "command": "uvx",
        "args": [
          "--from",
          "git+https://github.com/bartpotrykus1/mcpserverexample.git",
          "mcp-server"
        ]
     }
  }
}
```

3. Install / run the test server (example):

uvx --from git+https://github.com/bartpotrykus1/mcpserverexample.git mcp-server

4. Verify the server started and consult logs / stdout for any errors.
