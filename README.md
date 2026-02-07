# Installation Steps

Add the following configuration to your MCP servers setup:

```json
{
  "mcpServers": {
    "add_tool": {
      "command": "uvx",
      "args": [
        "--from",
        "git+https://github.com/cheryl95/mcpserverexample.git",
        "mcp-server"
      ]
    }
  }
}
```

This will fetch and setp `mcp-server` from the specified github repository.
