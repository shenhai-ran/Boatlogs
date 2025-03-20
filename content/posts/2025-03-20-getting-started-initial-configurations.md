---
title: "Getting Started: Initial Configurations of Boat/-Logs"
date: 2025-03-20T14:46:10+01:00
draft: false
tags: ["Hugo", "Cloudflare", "GitHub", "AI Generated"]
author: "Shenhai Ran"
showToc: true
TocOpen: false
hidemeta: false
comments: false
description: "The beginning of Boat/-Logs - setting up a personal blog with AI assistance"
canonicalURL: "https://boatlogs.pages.dev/posts/getting-started-initial-configurations"
---

# Getting Started: The Initial Journey

As the saying goes, "A journey of a thousand miles begins with a single step." In this case, our journey began with a single prompt. This post chronicles the first steps in creating Boat/-Logs, a blog that's not just about content, but about the process of creating it through AI-powered development.

## The Beginning: Project Initialization

The adventure began in Windsurf, where I asked Cascade (the AI assistant) to set up a personal blog website using Hugo. The experience was unlike traditional development - no manual installation, no lengthy setup procedures. Instead, just a conversation:

"I'd like to create a personal blog using Hugo."

And off we went! Cascade suggested the commands needed to initialize the Hugo project, and I simply reviewed them before execution. Within minutes, the basic structure was in place - a feat that would have taken significantly longer if done manually.

## Overcoming Challenges: Theme Selection

The journey wasn't without its challenges. After initialization, I asked for a "modern and fancy theme" and received three recommendations. I chose "Toha," but it turned out there were compatibility issues with our Hugo setup. 

Despite multiple attempts to resolve these issues, we kept hitting roadblocks. Like changing direction when faced with obstacles, I pivoted and asked for a "modern and simple theme" instead. This led us to "PaperMod," which integrated seamlessly with our setup.

This experience highlighted an important lesson: sometimes simplicity is the best approach, especially when exploring new territory.

## Finding Direction: MCP Servers

For those unfamiliar, MCP (Multi-Cloud Provider) servers are powerful tools that facilitate cloud service management. While my Windsurf license doesn't include MCP support, I found a workaround by using the Cline extension.

This arrangement worked perfectly for our needs:
- Windsurf's Cascade handled all local development commands
- MCP through Cline extension managed GitHub interactions
- Cloudflare operations were initially planned through MCP but required manual intervention

I encountered some issues with the Cloudflare MCP (identical to [this GitHub issue](https://github.com/cloudflare/mcp-server-cloudflare/issues/12)), which will be addressed in future updates.

## Progress with Cloudflare

Deploying to Cloudflare Pages was straightforward, albeit manual due to the MCP issues mentioned above. The only significant hurdle was the outdated Hugo version on Cloudflare Pages, which was easily resolved by adding an environment variable.

The site was live within minutes of deployment - a testament to the efficiency of modern hosting solutions and AI-assisted development.

## Planning Ahead

For future content, I've established a workflow that leverages AI assistance. My approach involves:

1. Creating draft ideas in markdown files (stored in `./drafts/posts/`)
2. Having Windsurf Cascade generate the full posts based on these drafts
3. Publishing the polished content to the website

This post itself was created using this exact workflow, based on [this draft file](https://github.com/shenhai-ran/Boatlogs/blob/main/drafts/posts/2025-03-20-setups.md).

## Summary

This journey represents just the beginning of exploring AI-powered development tools. The process has been remarkably efficient - what would typically take days of research, installation, configuration, and troubleshooting was accomplished in a fraction of the time.

As we continue with Boat/-Logs, I'm excited to discover more ways that AI can enhance the development experience. The possibilities are vast, and we're just getting started!

Stay tuned for more adventures as we explore both content creation and the evolving landscape of AI-assisted development.
