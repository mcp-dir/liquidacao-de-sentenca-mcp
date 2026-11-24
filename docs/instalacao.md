# Instalação detalhada

Liquidação de Sentença é um servidor MCP remoto. Aponte seu cliente pra `https://api.mcp.ai/p_liquidacao-de-sentenca`. Snippets rápidos: [INSTALL.md](../INSTALL.md).

| Cliente | URL | Auth |
|---|---|---|
| Claude Desktop | `https://api.mcp.ai/p_liquidacao-de-sentenca` | nenhuma (grátis) |
| Cursor | `https://api.mcp.ai/p_liquidacao-de-sentenca` | nenhuma |
| VS Code (Copilot) | `https://api.mcp.ai/p_liquidacao-de-sentenca` | nenhuma |

A config JSON é a mesma em todos: só a URL, sem headers.

## Desinstalar

Remova o bloco `mcpServers.liquidacaodesentenca` (ou `servers.liquidacaodesentenca` no VS Code) do config do cliente e reinicie.
