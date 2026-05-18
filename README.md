# Chess Map

## Server

Install this MCP server by adding the following JSON code to your JSON config file

```json

"mcpServers": {
    "Server": {
    "command": "uvx",
    "args": [
        "--from",
        "git+https://github.com/hebemewe/chess-map.git",
        "run",
        "chess"
        ]
    }
},

