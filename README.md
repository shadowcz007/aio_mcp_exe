This is a collection of MCP servers that anyone can use. It provides services through packaged exe files, which can be started by simply double-clicking. Additionally, users can choose to use the stdio mode and configure it in Claude.

这是一个普通人都能使用的 MCP 服务器集合。它通过打包好的 exe 文件提供服务，用户只需双击即可开启 SSE 服务。此外，用户还可以选择使用 stdio 模式，并将其填写到 Claude 中。


[MCP UIUX](https://shadowcz007.github.io/mcp_uiux/)

[voice input](https://github.com/shadowcz007/aio_mcp_exe/releases/download/0.1/voice_input.exe)

[memory](https://github.com/shadowcz007/aio_mcp_exe/releases/download/0.1/mcp_server_memory.exe)

[chromadb](https://github.com/shadowcz007/aio_mcp_exe/releases/download/0.1/mcp_server_chroma.exe)

[use brower](https://github.com/shadowcz007/aio_mcp_exe/releases/download/0.1/mcp-use-browser.exe)


### Claude：
```json
{
    "mcpServers": {
      "chroma": {
        "command": "C:/mcp_server_chroma.exe",
        "args": [
          "--transport",
          "stdio",
          "--db-path",
          "C:/chroma_db"
        ]
      }
    }
  }
```

***

#### todo 
aio
