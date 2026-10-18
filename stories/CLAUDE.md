# CLAUDE.md — stories/

Where prose lives. Empty for now.

## Before writing a story here
Read, in order:
1. `../writing-guide/story-laws.md` (the age rule first)
2. `../writing-guide/style-guide.md` and `../writing-guide/gaze-guide.md`
3. `../writing-guide/character-journey-worksheet.md` and `../writing-guide/outline-checklist.md`
4. `../story-bible/timeline.md`, the era file, and the species files the story touches
5. `../story-bible/foreshadowing-map.md` and `../story-bible/plot-twist-inventory.md`

## Filing convention
Folders are named by **chronology**; the site shows each story's era.

```
stories/
├── era-01/ … era-07/       one folder per era
├── epilogue/
└── spinoffs/
    └── witch-school/      adult academy only (recruits are 18+)
```

## Frontmatter

```markdown
---
title: "Story Title"
tags: [story, era-3, witches]
story_type: arc-advancing | single-beat
canon_status: draft | canon | non-canon
eval_status: unreviewed | passed | flagged
date: YYYY-MM-DD
---

<!-- story shape
POV:
Want:
Need:
Point A (starting state):
Point B (ending state):
Obstacle (external | interpersonal | internal):
Resolution and its cost:
Narrator tried:
-->
```

`date` is the real-world date written, and drives the site's timeline. `story_type`, `canon_status`, `eval_status`, and the optional `publish` and `order` fields work exactly as in *Vector Anthologies*: see `../writing-guide/style-guide.md` → Length and `../writing-guide/eval-checklist.md`. `Narrator tried:` is extra here, while the narrator is still being researched.

## Sidecars
Reviews are saved beside the story with names ending in `-review.md`, which keeps them off the public site: `<slug>.board-review.md`, `<slug>.women-review.md`, `<slug>.men-review.md`, `<slug>.line-review.md`.

## Publishing
`../scripts/build_site.py` publishes every story file here on each push to `main`, unless `publish: false` or the build's publish policy withholds it. **Treat "written" as "published"** unless the story is deliberately withheld.
