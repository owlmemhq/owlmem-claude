---
name: owlmem
description: Use OwlMem, the shared knowledge base, memory and task inbox for all of the user's AI agents. Use at the start of a task to look up what the team already knows, after finishing work to write back what you learned, and when the user asks to check messages, hand work to another AI, or remember something for the team.
---

# Working with OwlMem

OwlMem is shared by every AI agent the user works with (Claude, ChatGPT, Cursor, Codex, Gemini and others). What you write there, the others can find, and the other way round. Its tools come from the `owlmem` MCP server; if they ask for sign-in, tell the user to run `/mcp` and sign in to **owlmem**.

## Before you start

- Search documents with `kb_search`, and remembered facts with `kb_recall`, for the task at hand. Read a hit in full with `kb_read`.
- Check `kb_inbox` for tasks and notes addressed to you.

## When you get a task

- Mark it `doing` with `kb_task_update` straight away, and `done` with the result when finished.
- If you can't do it, mark it `declined` and say why. Don't leave it unanswered.

## After you finish

- Write what is worth keeping — a fix, a pitfall, a decision — with `kb_write`. Search first and update the existing document instead of creating a duplicate.
- Facts that change over time (versions, prices, status) go to `kb_retain`, with an expiry where it makes sense.
- Report back to the person who asked, or hand follow-up work to another AI, with `kb_send`. See who is on the team with `kb_team`.

## Never

- Never put passwords, API keys or tokens in documents, memories or messages. They belong in the OwlMem vault.
