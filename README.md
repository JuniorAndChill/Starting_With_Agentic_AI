# Starting with Agentic AI: Brown Bag

A 30–45 minute hands-on intro. You'll give an AI agent a folder and a goal, and watch it **plan, work through files, and produce real output** instead of just chatting.

## Chat vs. agent, the short version

| Chat AI | Agentic AI |
|---|---|
| You paste text in, copy answers out | It opens, reads, and writes files itself |
| One question, one answer | One goal, many steps |
| You do the work, it advises | It does the work, you review |

## 1. Get the files

Go to **https://github.com/JuniorAndChill/Starting_With_Agentic_AI**, click the green **Code** button, then **Download ZIP**. Unzip it somewhere easy, like your Desktop.

*Comfortable with git?* `git clone https://github.com/JuniorAndChill/Starting_With_Agentic_AI.git`

## 2. Pick your path

| If you use... | Go to |
|---|---|
| **Claude** (desktop app, Cowork) | [claude-version/](claude-version/PROJECT.md) |
| **Anything else** (ChatGPT, Copilot, Gemini, Cursor, etc.) | [any-tool-version/](any-tool-version/PROJECT.md) |

Both paths use the same `workspace/` folder and the same exercise. Only the setup and a few words in the prompts differ.

## 3. Start your own project

The [templates/](templates/) folder has fill-in-the-blank files you can copy into any folder and start using right away. See [templates/README.md](templates/README.md).

Stuck? See **[HELP.md](HELP.md)**.

## What's in here

```
Starting_With_Agentic_AI/
├── README.md            ← you are here
├── HELP.md              ← tips, prompt patterns, troubleshooting (any tool)
├── claude-version/      ← setup and prompts for Claude Cowork
├── any-tool-version/    ← setup and prompts for any other AI tool
├── templates/           ← starter files for your own project
└── workspace/           ← the practice folder you give the agent
    ├── BRIEF.md         ← context the agent reads
    └── inbox/           ← messy files to work on
```

> Only give an agent folders you're OK with it reading and changing. That's the habit to build from day one.
