# Obsidian Capture

A ready-to-use Obsidian vault for work: people, meetings and projects, with a few AI commands that file your notes and write the links for you.

You write plain lines in today's note. `/capture` turns them into meeting notes, facts on each person and project, and actions, all linked. Open anyone's note and you see every meeting and project they're part of.

## Get started

1. **Download** this repository (Code > Download ZIP) and unzip it anywhere. Or `git clone` it.
2. **Open the folder in Obsidian** ([free](https://obsidian.md)): *Open folder as vault*.
3. **Open the same folder in your AI tool**: Claude Code, Codex, or GitHub Copilot in VS Code (agent mode).
4. Open **START HERE** in Obsidian and follow the three steps.

No plugins to install, no account, no script.

## Commands

| Command | What it does |
| --- | --- |
| `/capture` | Files today's notes into people, meetings, projects and actions, with links |
| `/brief <name>` | A ten-line brief on a person or project before you meet |
| `/weekly` | Your week, open actions, and projects that went quiet |
| `/tidy` | Finds duplicates, broken links and forgotten lines, and fixes them with your OK |
| `/new-skill` | Describe a new command in a sentence; the AI writes it |

## What's inside

| Path | What |
| --- | --- |
| `Home.md` | Open actions, active projects, recent meetings, people |
| `Daily/` | Where you write, one note per day |
| `People/`, `Projects/`, `Meetings/` | Filed by `/capture`; each note lists what links to it |
| `Weekly/` | Saved weekly recaps |
| `Actions.md` | Actions that don't belong to a meeting |
| `Templates/`, `Bases/` | Note templates and the live tables |
| `AGENTS.md` | The rules every AI agent follows here |
| `.agents/skills/`, `.claude/skills/` | The commands (the same skills, in the folders each tool reads) |

## Examples

A few sample notes (tagged `example`, from the starship Enterprise) show how it works on day one. Ask your AI to "delete the example notes" when you're ready.

## Make it yours

- Add a command: `/new-skill`, then describe it.
- Edit a command: change its `SKILL.md` in `.agents/skills/` and copy it to `.claude/skills/` (or ask your AI to).
- Add a property or folder: update the table in `AGENTS.md` and the template in `Templates/`.

## Privacy

Plain Markdown files on your computer. Nothing leaves it except what your AI tool reads. People notes hold work facts only.
# obsidian-capture
# obsidian-capture
# obsidian-capture
# obsidian-capture
