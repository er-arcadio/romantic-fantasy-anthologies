# CLAUDE.md — Romantic Fantasy Anthologies

This file orients an agent (or collaborator) working in this repo. Read it first. Each subfolder has its own `CLAUDE.md`; read the relevant one before writing or editing anything there.

## The one rule above all
**Adults only in adult content.** `writing-guide/story-laws.md` → 1. Maturity governs: an adult body, mind, and development (18 human years for humans and the beings made from them; a stated 18 on the 12:1 count for creatures from god). Any agent that sees a possible violation stops and raises it.

## How work is run
Run by an editorial team of agents, on the same model as *Vector Anthologies*. **Start every session as `lead-editor`** (`.claude/agents/lead-editor.md`): it is the only agent the author talks to, it owns the board in `board/`, and it delegates.

- `publishing-house/WORKFLOW.md` — stages from slate entry to published story, and the author's approval gates.
- `publishing-house/BOARD.md` — ticket and user-story conventions. All work is a ticket in `board/`.
- `publishing-house/HIRING.md` — a new agent costs tokens and needs the author's approval first.
- `publishing-house/ROSTER.md` — the team, and the bench.
- `board/audit/` — standing audits.

`story-bible/` is canon and agents never change it; canon changes are proposed to the author. `.claude/agents/board-of-advisors.md` is the critique panel; convene it, never duplicate it.

## What this repo is
Development and canon repo for an adult romantic-fantasy saga: seven eras and an epilogue on prehistoric Earth, told out of order, where **women lead and men support**, with the gazes deliberately crossed. Content is split into small single-topic files so any agent can search and cite it.

## Before outlining
1. `writing-guide/character-journey-worksheet.md`, one per POV or major character.
2. `story-bible/timeline.md`, `story-bible/chain-of-intentions.md`, and the era file.
3. `writing-guide/outline-checklist.md`. Every story needs a real point A, point B, want, and obstacle.

## Before writing prose
1. `writing-guide/story-laws.md` — hard constraints.
2. `writing-guide/style-guide.md` — the narrator is **open** and the tone ratio **provisional**; follow what the file currently says.
3. `writing-guide/gaze-guide.md`, and the `women-characters` / `men-characters` agents for scenes of desire.
4. The relevant `story-bible/` files, plus `foreshadowing-map.md` and `plot-twist-inventory.md` against the telling order.
5. Stories go in `stories/`, never in `story-bible/`.

## After a draft
1. `writing-guide/eval-checklist.md`, recorded in `eval_status`.
2. Convene the board of advisors and the two gaze agents, and present their reads alongside the draft. They flag; the author decides.

## Folder map
- `story-bible/` — canon: identity, world, chain of intentions, timeline, roster, eras, species, ages, reproduction, magic forms, foreshadowing, open questions.
- `writing-guide/` — style guide, story laws, gaze guide, checklists, worksheet, style research, and `magic-system/` (two guidelines, not canon).
- `themes/` — the thesis and its verdict per people.
- `stories/` — prose, filed by era. Empty for now.
- `reference/` — the archived world plan the bible was migrated from.
- `board/` — the project board (rendered on the private site tab).
- `scripts/` — the reading-site and board builders; deployed by `.github/workflows/pages.yml` on every push to `main`.
- `TODO.md` — tooling and process backlog only.

## Status flags
Files with open needs carry a `status:` line in their frontmatter. Everything in `story-bible/` is `draft` until the canon audit (T-001) passes. `story-bible/magic/` is deliberately blank.
