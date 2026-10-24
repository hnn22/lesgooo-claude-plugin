# lesgooo for Claude Code

Plan things with friends from Claude Code. [lesgooo.fun](https://lesgooo.fun/) is a free group planner without accounts: one link holds the group's dates and exact free hours, places with votes, the agreed event with RSVPs, a checklist and shared costs. Friends answer in any browser, without Claude or an account.

This plugin connects Claude Code to the hosted lesgooo MCP server (`https://lesgooo.fun/mcp`). It contains no code, only the connection settings.

## Install

```
/plugin marketplace add hnn22/lesgooo-claude-plugin
/plugin install lesgooo@lesgooo
```

Or add the MCP server directly:

```bash
claude mcp add --transport http lesgooo https://lesgooo.fun/mcp
```

No API key or sign-in is needed.

## Try it

- “Use lesgooo to create a plan called Cabin weekend. I’m Alex. In Europe/Prague, mark me free next Saturday and Sunday.”
- “Open https://lesgooo.fun/ab12/when and tell me which evening works for most people.”
- “Add Bring sleeping bags and Buy groceries to the checklist.”
- “I paid 1,200 CZK for groceries for all four of us. Record it and show who owes whom.”

## What it can and can’t do

It can create and read plans, save availability, RSVPs, places and votes, checklist items, event details and shared costs. It can’t book places, send invitations or messages, or move money; recording a repayment only records it.

Don’t put passwords, payment-card details, health data or other sensitive information into a plan: anyone with the plan link can read it.

## Links

- Guide: https://lesgooo.fun/agents/claude/
- Tools: https://lesgooo.fun/agents/tools/
- Privacy: https://lesgooo.fun/cookies · Terms: https://lesgooo.fun/terms
- Support: lesgooofun@gmail.com

The MIT license covers the files in this repository only, not the lesgooo service.
