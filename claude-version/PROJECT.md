# Mini Project (Claude version): Get the Team Offsite Back on Track

## Setup (3 min)

1. Open the **Claude desktop app** and switch to **Cowork**.
2. Click **Add folder** and pick the `workspace` folder.
3. That's it. Nothing to install.

---

**The scenario:** You just inherited planning for a team offsite. The last owner left you a messy `inbox` folder with meeting notes, an expense sheet, and some random files. You have 20 minutes to make sense of it.

Instead of doing it by hand, you'll hand it to an agent, one step at a time. Copy each prompt into Cowork.

---

## Step 1: Let it look around (read-only)

> Read BRIEF.md, then look through everything in the inbox folder. Tell me what's there and what state the offsite planning is in. Don't change any files yet.

**Notice:** it opened and read several files by itself. You didn't paste anything.

---

## Step 2: Organize the mess (it changes files)

> Organize the inbox folder into subfolders that make sense (like notes, finance, and misc). Rename anything with a bad file name so it's clear. Show me the plan before you move anything.

**Notice:** it proposes a plan, you approve, and then it does the work. That's the core loop: **goal → plan → approve → act → review.**

---

## Step 3: Pull out what matters (it creates a file)

> Read all the meeting notes and create a file called action-items.md with every open task, who owns it, and the due date if there is one. Flag anything that conflicts between meetings.

**Notice:** it's combining information across multiple files, the tedious part you'd normally do yourself.

---

## Step 4: Fix the numbers (it works with data)

> Clean up the expenses file: fix inconsistent formatting, flag duplicates, and tell me total spent vs. the budget in BRIEF.md. Save the cleaned version as a new file and keep the original.

**Notice:** "keep the original" matters. Tell the agent what *not* to touch.

---

## Step 5: Make the deliverable

> Using everything you've found, write a one-page status update for my manager called offsite-status.md: what's done, what's at risk, the budget picture, and the top 3 decisions I need to make this week.

---

## Stretch (if you finish early)

Pick one:

- *"Turn the status update into a short email I can send."*
- *"Make a simple day-of schedule for the offsite from the notes."*
- *"What's missing from these files that I should go ask about?"*
- Copy `templates/CLAUDE.md` into the workspace, fill it in, and see how it changes the agent's behavior.

---

## The takeaway

1. **Give it a folder and a goal**, not a copy-pasted question.
2. **Ask for the plan first** when it's going to change things.
3. **Say what to leave alone.**
4. **Review the output.** You're the editor, not the typist.
