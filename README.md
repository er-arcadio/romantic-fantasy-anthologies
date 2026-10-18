# Romantic Fantasy Anthologies

**📖 Read the stories: [er-arcadio.github.io/romantic-fantasy-anthologies](https://er-arcadio.github.io/romantic-fantasy-anthologies/)** (live once Pages is enabled; see below)

Story development repo for an adult romantic-fantasy saga set on prehistoric Earth, in the age of Pangea. Witches, hags, fairies, light and dark elves, drow, vampires, werewolves, demons, fallen angels, and a death god, across seven eras and an epilogue, told out of order.

Two choices define it:
- **Women lead, men support.** Every protagonist is a woman; the men serve her journey.
- **The gazes are crossed.** Women are written through the male gaze, men through the female gaze.

It runs on the same structure and process as [Vector Anthologies](https://github.com/er-arcadio/vector-anthologies): an editorial team of agents, a ticket board, small single-topic canon files, and an auto-built reading site.

**Start with `CLAUDE.md`.** Every folder has its own `CLAUDE.md` too.

## Structure

```
CLAUDE.md                       Start here
story-bible/                    Canon (not prose)
├── 00-story-identity.md        Premise, principles, thesis, themes
├── 01-world.md                 Pangea, the heavens, the underworld, the elements
├── chain-of-intentions.md      The causal spine: progress vs equilibrium
├── timeline.md                 Chronology and telling order
├── roster.md                   The locked archetypes, and the cut list
├── ages-and-lifespans.md       The aging chart and its exceptions
├── reproduction.md             Births, conjuring, curses
├── eras/                       Era 1 … Era 7, and the epilogue
├── species/                    One file per kind of being
├── characters/                 Protagonists by era (unnamed so far)
├── magic/                      World and creature magic forms (blank by design)
├── foreshadowing-map.md, plot-twist-inventory.md
└── open-questions.md
writing-guide/                  Read before outlining or drafting
├── style-guide.md              Length, dialogue, the horror hum; narrator open, tone provisional
├── story-laws.md               Hard constraints, the age rule first
├── gaze-guide.md               The crossed gazes
├── outline-checklist.md, character-journey-worksheet.md, eval-checklist.md
├── fiction-style-profile.md    The author's prose-taste research (shared with Vector)
└── magic-system/               Seven Domains and Magic Management (guidelines, not canon)
themes/thesis.md                Purpose, community, health, and the verdict per people
stories/                        Prose, by era (empty for now)
reference/world-plan-v1.md      The world plan this repo was migrated from
scripts/                        Reading-site and board builders
.claude/agents/                 The editorial team, plus women-characters and men-characters
publishing-house/               Workflow, board conventions, hiring, kickoff, roster
board/                          Charter, decisions, user stories, tickets, audits
```

## Reading site
A timeline feed of every story in `stories/`, built by `scripts/build_site.py` and deployed by `.github/workflows/pages.yml` on every push to `main`.

**To turn it on (ticket T-012):** under **Settings → Pages**, set **Source** to **GitHub Actions**, then re-run the workflow.

## The private board tab
The site carries a second tab, **Board**, encrypted at rest and decrypted in the browser with a passphrase. Add it under **Settings → Secrets and variables → Actions** as a repository secret named `BOARD_PASSPHRASE` (8 characters or more). Without it, the board tab is not built; the board is never published in plaintext. The repo is public, so `board/` itself is readable on GitHub.

## Running the site locally
```bash
./scripts/preview.sh
```
Serves at <http://localhost:8000> with the board tab, passphrase `local-preview`.
