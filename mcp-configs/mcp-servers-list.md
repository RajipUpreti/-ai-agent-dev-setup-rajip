# MCP Servers List

This repo currently has **2 MCP servers connected** in Claude Desktop.

## Connected Servers

### 1) Rolldice
- **Type:** HTTP MCP server
- **Endpoint:** https://rolldice.ausbizconsulting.com.au/api/mcp
- **Purpose:** Simple tool server used to validate MCP connectivity and tool calling.
- **What it does:** Returns dice roll results (useful for confirming tool invocation works end-to-end).

### 2) GitHub (Copilot MCP)
- **Type:** HTTP MCP server
- **Endpoint:** https://api.githubcopilot.com/mcp/
- **Purpose:** Enables Claude/Copilot tool access for GitHub-related workflows (repo interactions, file operations, etc., depending on the enabled tools in your environment).
- **What it does:** Supports GitHub-integrated actions through MCP in supported clients.

## Required by rubric but NOT connected yet
These are required by the assignment criteria but are **not present** in my current Claude Desktop MCP configuration:
- Bootcamp AI Agent — **Not connected**
- Calendar Booking — **Not connected**

> Status summary: **2/4 connected** (Rolldice + GitHub).