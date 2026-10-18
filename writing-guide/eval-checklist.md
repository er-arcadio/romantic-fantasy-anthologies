---
title: "Draft Eval Checklist"
tags: [writing-guide, eval, checklist, quality-gate]
---

# Draft Eval Checklist

A quality gate, not a style opinion. Run this against a finished draft in
`stories/` before treating it as done — after `outline-checklist.md` has
already done its job at the outline stage, this is the equivalent pass on
actual prose. Manual (human or agent), run once per draft. Not automated,
and not meant to be: the checks below are judgment calls a script can't
reliably make, and this repo has exactly one author whose voice is the
thing being protected, not a team that needs a bot to enforce a house
style.

**This gate flags, it doesn't block.** A draft can be filed with open
flags — see `eval_status` below. But a story can't move from
`canon_status: draft` to `canon_status: canon` (i.e. its facts get folded
back into `story-bible/`) with unresolved flags in Sections 2 or 3 — those
are the sections that protect continuity for everything written after it.

Record the outcome in the story's own frontmatter (`eval_status:
unreviewed | passed | flagged` — see `stories/CLAUDE.md`) and, if anything
is flagged, leave a short `<!-- eval notes -->` HTML comment block at the
bottom of the story file itself: what was flagged, and whether it was
fixed, accepted as an intentional exception, or left for later. Keep the
record with the story, not in a separate report file — it's one author,
one file per decision.

---

## 0. Length and Shape

First: check `story_type` in the frontmatter, because it decides which
checks below apply (`style-guide.md` → Length).

**If `story_type: arc-advancing`:**

- [ ] Word count falls in the **3,000–5,000 word** band. Outside it isn't an
  automatic fail, but it isn't a silent pass either: **write the rationale
  into the eval notes.** A piece under the floor with no rationale recorded
  is a flag.
- [ ] It came in short and is now being relabelled `single-beat` — **that's a
  flag, not a reclassification.** A piece conceived as arc-advancing that
  landed at 1,600 words has a problem the label won't fix.
- [ ] The `<!-- story shape -->` block (`stories/CLAUDE.md`) is filled in:
  POV, want, need, point A, point B, obstacle (external / interpersonal /
  internal), and what the resolution costs. Point A and B are concrete
  states, not abstract lessons. If any field is vague or can't be answered
  from the actual text, the story doesn't have a clear A-to-B yet — a flag,
  and usually a sign `outline-checklist.md` got skipped rather than run.

**If `story_type: single-beat`:**

- [ ] No word floor applies and no A-to-B is required — don't flag either.
- [ ] The compression is doing real work: would this be *worse* at 3,000
  words? If the honest answer is "no, it just stopped," it isn't a
  single-beat piece.
- [ ] One line recorded on the effect it's going for, in place of the full
  story-shape block.

**Either way:**

- [ ] The slate is still weighted toward arc-advancing pieces overall. These
  are meant to be the majority; a run of single-beat pieces is worth noticing.

## 1. Style Guide Compliance (`style-guide.md`)

- [ ] **Tone blend** reads roughly like the provisional ratio in
  `style-guide.md` (romance and desire / grounded drama / horror-hum). It is
  provisional while the author tunes it against sample passages, so record
  how the draft actually landed rather than forcing the ratio.
- [ ] **Narrative voice:** present tense is the default register. Any
  past-tense passage has a real in-scene reason (the narrator stepping
  back into explicit reflection, or telling a story within the story) —
  not a scheduled "big moment" that could just as easily be present tense.
- [ ] **Present-tense break:** if a past-tense passage exists, its most
  overwhelming beat snaps back to present tense. A past-tense passage that
  never breaks is a flag.
- [ ] **Dialogue — sparse AND sustained, not either/or.** This is the
  single most common failure mode to check for explicitly: read any
  dialogue-heavy scene and count how often narration interrupts between
  lines. If narration steps in on *nearly every line*, that's a violation
  of the sustained-exchange default even if each individual line is
  appropriately terse — the two axes (line length, interruption frequency)
  are independent and both need to pass.
- [ ] **Horror register** stays a background hum: planted without
  follow-up explanation in the same scene, absence over performed grief,
  no ambiguous thread over-confirmed. If a wrong detail gets explained
  immediately, or a loss gets a full mourning scene, flag it.
- [ ] **Magic on the page** (if applicable): every spell or creature power
  visibly costs or affects something, consistent with the filled-in
  `story-bible/magic/world-form.md` and the creature's form in
  `story-bible/magic/creature-forms/`. Flavor text standing in for a rule
  the world has not settled is a flag.
- [ ] **Sex and desire** (if on the page): it serves character arc, not
  decoration; it is written to the gaze rules in `gaze-guide.md`; desire is
  active on both sides; consent is legible.
- [ ] **Narrator voice** matches whatever `style-guide.md` → Narrative voice
  currently settles. (The narrator is still being researched; until it is
  settled, note which voice the draft tried.)

## 2. Story Laws Compliance (`story-laws.md`) — hard constraints

- [ ] **Age rule.** Every character in sexual or romantic content is
  past maturity (Law 1: 18 human years, or a stated 18 on the 12:1
  count for creatures from god) and adult on the page. No ages given in
  human years for creatures from god. No exceptions. A violation here is a stop, not a flag.
- [ ] **Women lead, men support.** The protagonist is a woman and her
  choices drive the climax. No man rescues her from her own story.
- [ ] **The two gazes.** Women are written through the male gaze without
  losing agency or interiority; men are written through the female gaze.
  Run the matching agent checklists (`.claude/agents/women-characters.md`,
  `.claude/agents/men-characters.md`).
- [ ] **No moral framing.** Judgment comes from POV only. Outside a POV
  filter, competing philosophies are presented, not verdicts. This matters
  most for the factions that are "neither right nor wrong" (light and dark
  elves, fairies and elves in the Civil War, the death god's neutrality).
- [ ] **Chain of intentions.** Nothing in the story contradicts
  `story-bible/chain-of-intentions.md` (who pushes progress, who pulls
  toward equilibrium, and why).
- [ ] **Era discipline.** Species, populations, and who knows what all
  match the era the story is set in (`story-bible/timeline.md` and the era
  file). No later-era fact borrowed early: for example, no succubi (dropped
  from the world), no extinct fairy kinds after Era 6, no portal knowledge
  for the first witch.
- [ ] **Telling order.** The story does not spoil a reveal that the telling
  order (`story-bible/timeline.md`) holds back for a later book.

## 3. Canon Cross-Check

- [ ] Checked against the relevant `story-bible/eras/`, `species/`, and
  `characters/` files: no invented canon that is not flagged as proposed.
- [ ] Checked against `story-bible/open-questions.md`: the story does not
  silently answer a question the author has not settled.
- [ ] If `canon_status: canon` (or heading there): the relevant
  `story-bible/` file(s) have been updated to match what the story
  establishes, with the author's approval.

## 4. Board of Advisors

- [ ] Convened the board (`.claude/agents/board-of-advisors.md`) and have
  its report ready to present *with* the draft, not instead of it. It is a
  perspective check, not a second style gate.
- [ ] Nothing from the board has been acted on unilaterally. Record any
  flags adopted, and any consciously declined, in the eval notes.
- [ ] The report is saved as a sidecar next to the story
  (`<story-slug>.board-review.md`, see `../stories/CLAUDE.md`). Canon or
  consistency errors it caught go into the story's own `<!-- eval notes -->`;
  craft and perspective flags stay in the sidecar.

## 5. Final Call

- [ ] Set `eval_status` in the story's frontmatter: `passed`, `flagged`
  (Section 2 or 3 issue found, which needs a decision before this can be
  `canon_status: canon`), or leave `unreviewed`.
- [ ] If anything is flagged, add the `<!-- eval notes -->` comment block
  at the bottom of the story file.
