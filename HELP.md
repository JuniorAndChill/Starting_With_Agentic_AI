# Help & Cheat Sheet

## A good agent prompt has 4 parts

| Part | Example |
|---|---|
| **Goal:** what done looks like | "Create a one-page status update…" |
| **Inputs:** where to look | "…using the notes in the inbox folder…" |
| **Rules:** what to avoid | "…don't edit the originals…" |
| **Output:** name and format | "…save it as status.md." |

## Handy phrases

- **"Show me the plan first."** Use it before anything that moves, renames, or edits.
- **"Don't change anything yet."** Keeps it in read-only mode.
- **"Keep the original."** It saves a new file instead of overwriting.
- **"Ask me if anything is unclear."** Lets it check with you instead of guessing.
- **"What did you change?"** Gives you a quick recap to review.

## Troubleshooting

| Problem | Try |
|---|---|
| It can't see my files | Make sure you opened or added the **workspace** folder, not a parent or child folder. In chat tools, upload or paste the files. |
| My tool can't create files | Ask it to "show the result as a table" or "give me the text to copy," then save it yourself. |
| It asks permission a lot | That's normal and good. Approve when it makes sense. |
| It did something I didn't want | Tell it: *"Undo that and put the files back where they were."* |
| The answer is too long or vague | Be specific: *"one page"*, *"bullet points"*, *"top 3 only"*. |
| It went off track | Stop it, then restate the goal more narrowly. |
| It says it can't delete files | Also normal. Most agents need your explicit approval to delete. |
| The math looks off | Ask it: *"Show your work."* Always check numbers yourself. |

## Make it remember your rules

Put a `CLAUDE.md` (Claude) or `AGENTS.md` (most other agent tools) in your project folder. See `templates/`.

## Good habits

- Start **read-only**, then let it act.
- Use a **copy** of real files until you trust the workflow.
- **Never** give it folders with passwords, HR files, or customer data unless your company policy allows it.
- Always **skim the output** before sending it to anyone.
