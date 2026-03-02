# MCP Connection Test Evidence

This file documents proof that each configured MCP server is connected and responding in Claude Desktop.

> Put screenshots in `/screenshots` and link them here.

---

## 1) Rolldice — Connection Test
**Status:** ✅ Connected / Working  
**Test performed:** Asked Claude to call the Rolldice tool (example: “roll a d20”).  
**Expected result:** Tool returns a numeric roll and Claude displays it.

**Evidence:**
- Screenshot: `screenshots/mcp-rolldice-working.png`
- Prompt used: *(paste your prompt)*
- Result summary: *(paste what happened / outcome)*

---

## 2) GitHub — Connection Test
**Status:** ✅ Connected / Working  
**Test performed:** Used GitHub MCP to interact with this repository (example: list repository files or read README).  
**Expected result:** GitHub MCP returns repository data without errors.

**Evidence:**
- Screenshot: `screenshots/mcp-github-working.png`
- Prompt used: *(paste your prompt)*
- Result summary: *(paste what happened / outcome)*

---

## 3) Bootcamp AI Agent — Not Connected
**Status:** ❌ Not configured  
**Evidence:** Not available (server not in `claude-desktop-config.json`).

---

## 4) Calendar Booking — Not Connected
**Status:** ❌ Not configured  
**Evidence:** Not available (server not in `claude-desktop-config.json`).

---

## Overall MCP Status
- Connected servers: **2**
- Missing (required by rubric): **2**