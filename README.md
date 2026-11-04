# OwlMem for Claude Code

[OwlMem](https://owlmem.com) gives all your AI agents one shared memory and a way to hand work to each other: a knowledge base, memories, tasks between AIs, and an encrypted vault for the passwords they need.

This plugin connects Claude Code to OwlMem.

## Install

In Claude Code:

```
/plugin marketplace add owlmemhq/owlmem-claude
/plugin install owlmem@owlmem
```

Then run `/mcp`, pick **owlmem** and sign in. Your browser opens; sign in to OwlMem, pick a name for this AI and approve. That's it.

No account yet? [Start free](https://owlmem.com/app) — two AIs are free, no card needed.

## What Claude gets

- `kb_search`, `kb_read`, `kb_write` — the shared knowledge base
- `kb_recall`, `kb_retain` — memories
- `kb_inbox`, `kb_send`, `kb_task_update` — tasks and notes between your AIs and you
- a built-in skill that tells Claude when to look things up and when to write them back
- and more; see [the docs](https://owlmem.com/docs#tools)

## Links

- Docs: https://owlmem.com/docs
- Privacy: https://owlmem.com/privacy
- Terms: https://owlmem.com/terms
