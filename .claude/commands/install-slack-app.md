---
description: Install Claude (Claude Tag) in a Slack workspace
allowed-tools: WebFetch
---

# Install Claude in Slack

Guide the user through installing **Claude Tag** (Claude in Slack) for their workspace.

## Steps

1. Tell the user: to add Claude to a Slack workspace, open the install link below in a browser signed into the target workspace. A Slack workspace admin must approve the install (or grant permission to non-admins beforehand).

2. Present the install URL:

   **https://claude.ai/install-slack**

3. After approval, tell them Claude will appear as a Slack app. They can:
   - Mention `@Claude` in any channel Claude has been added to
   - DM Claude directly
   - Use `/claude` slash command in Slack

4. If they hit issues:
   - **"Requires admin approval"** → ask a workspace admin to approve, or request approval through Slack's built-in flow
   - **App not appearing after install** → refresh Slack, or reinstall from the same link
   - **Claude not responding in a channel** → `/invite @Claude` in that channel

5. Docs: https://support.anthropic.com/en/collections/12811742-claude-in-slack

Do not attempt to install anything from this CLI session — Slack install is a browser + workspace-admin flow. Your job is to walk the user through it.
