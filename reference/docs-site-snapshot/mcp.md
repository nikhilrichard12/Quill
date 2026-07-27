# MCP server · Littlebird docs

Source: https://support.littlebird.ai/docs/mcp/
Fetched: 2026-07-27

---

Features

# MCP server
Give a compatible AI client access to Littlebird tools through MCP, with the same account permissions you already use.

Connect your AI client to the Littlebird MCP server to give it access to Littlebird tools, based on your account access and permissions.

Note

The Littlebird MCP server is currently available to Power & Pro users only.

## Server URL

https://mcp.littlebird.ai/mcp

Once connected, your AI client can use Littlebird tools according to your account access and permissions. Most clients use a standard OAuth flow the first time you connect - just follow the browser prompt to sign in to your Littlebird account.

## Claude Code

Run this command in your terminal:

claude mcp add --transport http littlebird https://mcp.littlebird.ai/mcp

Then authenticate by running /mcp in Claude Code and following the OAuth flow.

Use /mcp to list and manage installed MCP servers. Use /context to see current context usage, including tokens used by enabled MCP servers.

## Claude Desktop

- Open Settings → Connectors.

- Click Add Connector.

- Enter this URL:

https://mcp.littlebird.ai/mcp

- Complete the OAuth flow to connect your Littlebird account.

Note: Remote MCP servers in Claude Desktop are configured through Settings → Connectors, not the claude_desktop_config.json file.

## Cursor

- Open Cursor Settings → MCP → Add new global MCP server.

- Paste this configuration:

{
"mcpServers": {
"littlebird": {
"url": "https://mcp.littlebird.ai/mcp"
}
}
}

- Save and restart Cursor.

- When you use a Littlebird tool for the first time, complete the OAuth flow.

## VS Code (GitHub Copilot)

- Create a .vscode/mcp.json file in your workspace.

- Add this configuration:

{
"servers": {
"littlebird": {
"type": "http",
"url": "https://mcp.littlebird.ai/mcp"
}
}
}

- Open the Command Palette with Cmd+Shift+P on Mac or Ctrl+Shift+P on Windows/Linux.

- Run MCP: List Servers.

- Start the Littlebird server and complete the OAuth flow when prompted.

## ChatGPT

Custom MCP connectors require a paid ChatGPT plan (Plus, Pro, Business, Enterprise, or Edu) and must be enabled via Developer Mode.

- Go to Settings → Connectors → Advanced and turn on Developer mode.

- Return to Settings → Connectors and click Add (Create) custom connector.

- Enter this URL:

https://mcp.littlebird.ai/mcp

- Complete the OAuth flow to connect your Littlebird account.

## Windsurf

- Open Windsurf Settings with Cmd+, on Mac.

- Search for MCP.

- Click View raw config to open mcp_config.json.

- Add the Littlebird server configuration:

{
"mcpServers": {
"littlebird": {
"serverUrl": "https://mcp.littlebird.ai/mcp"
}
}
}

- Save and restart Windsurf.

- Complete the OAuth flow when prompted.

## Gemini CLI

Run this command:

gemini mcp add --transport http littlebird https://mcp.littlebird.ai/mcp

Or add this to your Gemini CLI settings.json:

{
"mcpServers": {
"littlebird": {
"httpUrl": "https://mcp.littlebird.ai/mcp"
}
}
}

Authenticate inside Gemini CLI with:

/mcp auth littlebird

Complete the OAuth flow in your browser.

## Codex

- Add the Littlebird server to your Codex configuration at ~/.codex/config.toml:

[mcp_servers.littlebird]
url = "https://mcp.littlebird.ai/mcp"

- Authenticate by running:

codex mcp login littlebird

- Complete the OAuth flow to connect your Littlebird account.

## Cline

- Open the Cline panel in VS Code.

- Open the menu in the top-right corner.

- Select MCP Servers.

- Open the Remote Servers tab.

- Enter:

Server Name: littlebird
Server URL: https://mcp.littlebird.ai/mcp
Transport Type: Streamable HTTP

- Click Add Server.

- If Cline shows Authentication required, click Authenticate and complete the OAuth flow in your browser.

Advanced configuration:

{
"mcpServers": {
"littlebird": {
"url": "https://mcp.littlebird.ai/mcp",
"type": "streamableHttp",
"disabled": false
}
}
}

## Zed

- Open Zed Settings.

- Add Littlebird under context_servers:

{
"context_servers": {
"littlebird": {
"url": "https://mcp.littlebird.ai/mcp"
}
}
}

- Save the settings file.

- Zed will prompt you to authenticate with the standard MCP OAuth flow when needed.

## Amp

Run:

amp mcp add littlebird https://mcp.littlebird.ai/mcp

Or add this to your Amp settings file:

{
"amp.mcpServers": {
"littlebird": {
"url": "https://mcp.littlebird.ai/mcp"
}
}
}

Amp starts the OAuth flow in your browser for remote MCP servers that require authentication. See the Amp MCP documentation for more.

## OpenCode

Add Littlebird to your opencode.json configuration:

{
"$schema": "https://opencode.ai/config.json",
"mcp": {
"littlebird": {
"type": "remote",
"url": "https://mcp.littlebird.ai/mcp",
"enabled": true
}
}
}

Authenticate with:

opencode mcp auth littlebird

Complete the OAuth flow in your browser.

## JetBrains AI Assistant

- Open Settings → Tools → AI Assistant → Model Context Protocol (MCP).

- Click Add.

- Choose HTTP.

- Paste this JSON configuration:

{
"mcpServers": {
"littlebird": {
"url": "https://mcp.littlebird.ai/mcp"
}
}
}

- Choose whether the server should be available globally or only for the current project.

- Click OK, then Apply.

See the JetBrains MCP documentation for more.

## Amazon Q Developer CLI

Add Littlebird to your Amazon Q Developer CLI agent configuration:

{
"mcpServers": {
"littlebird": {
"type": "http",
"url": "https://mcp.littlebird.ai/mcp"
}
}
}

Start Q Developer CLI with that agent, then use:

/mcp

If authentication is required, Q will provide a browser URL. Open it, complete the OAuth flow, and return to the CLI. See the Amazon Q Developer MCP documentation.

## Kiro

- Open the Command Palette.

- Run Kiro: Open user MCP config (JSON) for a global setup, or Kiro: Open workspace MCP config (JSON) for a project setup.

- Add:

{
"mcpServers": {
"littlebird": {
"url": "https://mcp.littlebird.ai/mcp"
}
}
}

- Open Settings with Cmd+, on Mac or Ctrl+, on Windows/Linux.

- Search for MCP and make sure MCP support is enabled.

- Open the Kiro panel and check the MCP Servers tab for connection status.

## Goose

For a one-off session, run:

goose session --with-streamable-http-extension "https://mcp.littlebird.ai/mcp"

For a persistent setup:

- Run:

goose configure

- Select Add Extension.

- Select Remote Extension (Streamable HTTP).

- Enter the Littlebird MCP URL:

https://mcp.littlebird.ai/mcp

- Follow the remaining prompts.

## Antigravity

- Follow the Antigravity instructions for connecting custom MCP servers.

- Add this configuration to your mcp_config.json:

{
"mcpServers": {
"littlebird": {
"serverUrl": "https://mcp.littlebird.ai/mcp"
}
}
}

- Save the configuration.

- Complete the OAuth flow when prompted.

## LM Studio

- Open LM Studio.

- Switch to the Program tab in the right sidebar.

- Click Install → Edit mcp.json.

- Add:

{
"mcpServers": {
"littlebird": {
"url": "https://mcp.littlebird.ai/mcp"
}
}
}

- Save the file.

See the LM Studio MCP documentation for more.

← Previous
Hummingbird
Next →
Glance: your day at a glance

esc

↑ ↓ navigate↵ openesc close
