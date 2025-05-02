# mcp
MCP server that provides tools for interacting with the Fluidattacks API. 

- Complete documentation [here](https://dev.fluidattacks.com/components/interacts/)
- MCP server code [here](https://gitlab.com/fluidattacks/universe/-/tree/trunk/interacts?ref_type=heads)

## Configuration 
If you don't know how to generate the API_TOKEN, please refer to the [documentation](https://dev.fluidattacks.com/components/interacts/#setup) 

```json
{
  "mcpServers": {
    "fluidattacks-mcp": {
      "command": "npx",
      "args": [
        "-y",
        "@fluidattacks/mcp"
      ],
      "env": {
        "API_TOKEN": "your_api_token_here"
      }
    }
  }
}
```
