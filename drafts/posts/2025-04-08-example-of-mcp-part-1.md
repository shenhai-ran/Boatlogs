---
title: "Example of MCP, Part 1"
date: 2025-04-08T11:03:09+02:00
draft: false
tags: ["AI Generated", "MCP", "Development"]
---

# Example of MCP, Part 1

It has been a while since last post, because I have been play around with different MCP tools.
This will be the first post of a series of posts about MCP.

## MCP in Nutshell

** Give a short description of MCP, based on the information from https://www.anthropic.com/news/model-context-protocol**

## MCP in Action

Here are five MCP servers I have been using:

1. GitHub:https://github.com/modelcontextprotocol/servers/tree/main/src/github
2. Google Maps: https://github.com/modelcontextprotocol/servers/tree/main/src/google-maps
3. Playwright: https://github.com/Automata-Labs-team/MCP-Server-Playwright
4. Cloudflare: https://github.com/cloudflare/mcp-server-cloudflare
5. Fetch: https://github.com/zcaceres/fetch-mcp

** generate a detailed description of each MCP server, based on the url provided of each server.**

## Issues with MCP

### too many tools from MCP

For Cloudflare and Playwright MCP, I have encountered some issues saying that: "adding this instance would exceed max allowed tools" from Windsurf.
I think it is limited by Windsurf, however need to be confirmed.

### Network connection

I notice MCP are mostly developed by either nodejs or python. In case of python, it is often use `uvx` to run the server. However if I am within a network with proxy or self-signed certificate, it willl have network connection issues, for example, fetch MCP from this one (https://github.com/modelcontextprotocol/servers/tree/main/src/fetch).

I think it is the limitation of MCP itself without too much configurations yet. Hope it will be improved in the future.