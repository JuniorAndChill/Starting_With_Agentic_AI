# Mini Project (any tool): Get the Team Offsite Back on Track

## Setup (3–5 min): find your level

AI tools change names and features constantly, so find the row that matches what your tool **can do**:

| Level | Your tool can... | Examples (at time of writing) | How to set up |
|---|---|---|---|
| **A: Full agent** | open a folder on your computer and read/write files | Coding and desktop agents: GitHub Copilot agent mode in VS Code, Cursor, Gemini CLI, Codex, and similar | Open the `workspace` folder in the tool. |
| **B: Upload agent** | take uploaded files and give you files back to download | ChatGPT, Gemini, Copilot chat with file uploads | Upload `BRIEF.md` and everything in `inbox/`. |
| **C: Chat only** | only text | Most basic chat windows | Paste the contents of `BRIEF.md` and the inbox files into the chat. |

Everyone can do this exercise. Level A shows the full "agent" experience. Levels B and C show the same thinking, with you doing the file handling.

> **Check your company's AI policy** before uploading work files to any tool. The practice files here are fake, so they're safe.

---

**The scenario:** You just inherited planning for a team offsite. The last owner left you a messy `inbox` folder with meeting notes, an expense sheet, and some random files. You have 20 minutes to make sense of it.

Copy each prompt into your tool. **Level B/C adjustments are in *italics*.**

---

## Step 1: Let it look around (read-only)

> Read BRIEF.md, then look through everything in the inbox folder. Tell me what's there and what state the offsite planning is in. Don't change any files yet.

*B/C: replace "in the inbox folder" with "I've shared".*

**Notice:** it's working from all the files at once, not one question at a time.

---

## Step 2: Organize the mess

> Organize the inbox folder into subfolders that make sense (like notes, finance, and misc). Rename anything with a bad file name so it's clear. Show me the plan before you move anything.

*B/C: end with "Give me the plan as a table: current name, new name, new folder." Then do the moves yourself, or skip them.*

**Notice:** the core loop is **goal → plan → approve → act → review.** At Level A the agent acts. At B/C you act.

---

## Step 3: Pull out what matters

> Read all the meeting notes and create a file called action-items.md with every open task, who owns it, and the due date if there is one. Flag anything that conflicts between meetings.

*B: add "and give it to me as a downloadable file." C: add "and show it as a table."*

---

## Step 4: Fix the numbers

> Clean up the expenses file: fix inconsistent formatting, flag duplicates, and tell me total spent vs. the budget in BRIEF.md. Save the cleaned version as a new file and keep the original.

*B: "Give me the cleaned CSV as a download." C: "Show me the cleaned table."*

**Always double-check AI math.** Ask it: *"Show your work for the total."*

---

## Step 5: Make the deliverable

> Using everything you've found, write a one-page status update for my manager called offsite-status.md: what's done, what's at risk, the budget picture, and the top 3 decisions I need to make this week.

---

## Stretch (if you finish early)

- *"Turn the status update into a short email I can send."*
- *"What's missing from these files that I should go ask about?"*
- **Level A:** copy `templates/AGENTS.md` into the workspace and fill it in. Many tools read this file automatically.
- **Level B/C:** paste `templates/BRIEF.md` (filled in) at the start of a new chat as your "project instructions."

---

## The takeaway

1. **Give it the full context and a goal**, not a one-line question.
2. **Ask for the plan first** when it's going to change things.
3. **Say what to leave alone.**
4. **Review the output.** You're the editor, not the typist.
