# Templates: Start Your Own Project in 5 Minutes

1. **Make a new folder** for your project and put the files you want the agent to work with in it (use copies at first).
2. **Copy `BRIEF.md`** into that folder and fill it in. Lines starting with `<!--` are comments you can delete.
3. **Optional:** copy the instructions file your tool reads automatically:
   - Claude Cowork / Claude Code → `CLAUDE.md`
   - Most other agent tools (Copilot, Cursor, Codex, Gemini CLI, etc.) → `AGENTS.md`
   - Chat tools → paste `BRIEF.md` at the start of the chat instead.
4. **Open `PROMPTS.md`**, pick a starter prompt, and go.

| File | What it's for |
|---|---|
| `BRIEF.md` | What the project is, who it's for, what done looks like. **Start here.** |
| `CLAUDE.md` | Standing rules Claude follows every time it works in this folder. |
| `AGENTS.md` | Same idea, the cross-tool standard name. |
| `PROMPTS.md` | Copy-and-paste prompt patterns for common tasks. |

> **Tip:** `CLAUDE.md` and `AGENTS.md` hold the same kind of content. If you use more than one tool, keep them identical.
