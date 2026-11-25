# OwlMem for Claude Code

One shared memory, knowledge base, task handoff and encrypted vault for all your AI agents — Claude Code, Codex, Cursor, Gemini CLI and more.

<!-- screenshot: Claude Code asking OwlMem for a project decision made last week, and getting the answer from shared memory -->

## Quick start — 30 seconds

In Claude Code:

```
/plugin marketplace add owlmemhq/owlmem-claude
/plugin install owlmem@owlmem
```

Then run `/mcp`, pick **owlmem** and sign in. Your browser opens; sign in to OwlMem, pick a name for this AI and approve. That's it.

No account yet? [Start free](https://owlmem.com/app) — two AIs are free, no card needed.

## Why OwlMem

- **Claude remembers across sessions.** What it learns is saved to shared memory and the knowledge base, so the next session picks up where this one stopped.
- **It hands work to other AIs.** Leave a task for Codex, Cursor or Gemini CLI; they pick it up in the same shared space.
- **It uses secrets without seeing them.** Passwords and keys live in an end-to-end encrypted vault and go into commands, never into messages.
- **One memory for every AI you run.** Claude isn't the only one with access — every AI you connect reads and writes the same place, each under its own name.

## What Claude gets

- `kb_find` — search everything at once: knowledge base, files and memory, by meaning and keywords
- `kb_read`, `kb_write` — the shared knowledge base
- `kb_recall`, `kb_retain` — memories
- `kb_inbox`, `kb_send`, `kb_task_update` — tasks and notes between your AIs and you
- a built-in skill that tells Claude when to look things up and when to write them back
- and more; see [the docs](https://owlmem.com/docs#tools)

## OwlMem vs Mem0

| | OwlMem | Mem0 |
| --- | --- | --- |
| What it is | Hosted service for teams: knowledge base, memory and vault | Open-source memory SDK and hosted platform |
| Shared across AI apps | Yes — Claude, ChatGPT, Claude Code, Codex, Cursor, VS Code, Gemini CLI, Windsurf, any MCP client | Yes, via its MCP |
| Knowledge base with history | Yes — plain Markdown in git; every write is a commit you can diff and revert | Change history per memory; audit logs on Enterprise |
| Secrets vault for AIs | Yes — end-to-end encrypted | Not described in Mem0's docs |
| Extracts memories automatically | No — your AIs save what matters, in their own words | Yes — an LLM extracts memories from chats |
| Starting price | Free for 2 AIs; from $12/month | Free (bring your own LLM key); Custom for higher limits |

Details: [owlmem.com/compare](https://owlmem.com/compare)

## Links

- Website: [owlmem.com](https://owlmem.com)
- Docs: [owlmem.com/docs](https://owlmem.com/docs)
- Pricing: [owlmem.com/pricing](https://owlmem.com/pricing) — start free, two AIs free, no card
- Privacy: [owlmem.com/privacy](https://owlmem.com/privacy)
- Terms: [owlmem.com/terms](https://owlmem.com/terms)
