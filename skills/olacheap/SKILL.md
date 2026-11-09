---
name: olacheap
description: Use when the user wants to use their OlaCheap account (domains, business email, hosting, VPS) through the OlaCheap MCP server. Requires sign-in with an OlaCheap account or a personal API key.
license: MIT
---

Tools from the `olacheap` MCP server (https://olacheap.com/api/mcp):

The server requires sign-in; it lists its tools after the user signs in.

Rules:
- The server requires sign-in: an OlaCheap account (OAuth) or a personal API key sent as `Authorization: Bearer ocp_...`. Without it every request returns 401.
- Use only the tools the server lists after sign-in, and follow their descriptions.
- Do not infer availability or prices from pages marked coming soon or from a waitlist. Current prices and availability are on olacheap.com.
- Contact: support@olacheap.com.
