# St. Joe Time Machine

Claude setup for Danielle's local-history page about St. Joseph, Missouri
([Facebook](https://www.facebook.com/Stjoetimemachine), TikTok, Instagram).

Preston keeps this repository up to date. Danielle's Claude reads from it in two ways.

## 1. Project knowledge (works in the phone app)
`knowledge/` holds the files her Claude Project reads:

| File | What it is |
|---|---|
| `project-instructions.md` | Paste this into the Project's instructions box |
| `what-works.md` | Her page numbers and what her audience responds to |
| `best-videos.md` | Transcripts of her best videos, as examples of her voice |
| `sources-and-rules.md` | Where to find old St. Joseph papers, the no-invented-facts rule, copyright |
| `prompts.md` | Eight prompts to copy and paste |

**Connect it once, in a browser (claude.ai), signed in to her Claude account:**
1. Open the **St. Joe Time Machine** Project.
2. In the Project knowledge section, click **+** then **GitHub**. If asked, sign in to GitHub.
3. Paste `https://github.com/pmcgaughy98/St-Joe-Time-Machine` and select the `knowledge` folder.
4. Paste `knowledge/project-instructions.md` (below the line) into the Project instructions.

**When Preston updates the files:** open the Project and click **Sync** on the GitHub files. The phone app
then uses the new version.

## 2. Her skill, as a plugin (claude.ai web and Claude Desktop)
`plugins/st-joe-time-machine/` packages her skill: her voice, her two video formats, and the rules.
It works in any chat, not only inside the Project.

1. claude.ai → Settings → Capabilities → turn on **Code execution and file creation**.
2. Customize → **Plugins** → **Add** → **Add marketplace** → enter `pmcgaughy98/St-Joe-Time-Machine`.
3. Find **st-joe-time-machine** in that marketplace and click **Add**.

## Layout
```
.claude-plugin/marketplace.json          marketplace "time-machine-tools"
plugins/st-joe-time-machine/
  .claude-plugin/plugin.json
  skills/st-joe-time-machine/SKILL.md
  skills/st-joe-time-machine/references/her-best-videos.md
knowledge/                               files for the Project
```

This repository is public. Keep it to public material: her published videos and posts, and public
sources. No personal details, logins, or private messages.
