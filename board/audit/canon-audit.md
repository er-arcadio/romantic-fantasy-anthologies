---
title: "Canon Audit of the Migrated World"
ticket: T-001
author: story-bible-keeper
date: 2026-10-18
status: delivered, awaiting author decisions
---

# Canon Audit (T-001)

Scope: all of `story-bible/` (including `eras/`, `species/`, `characters/`, `magic/`), `writing-guide/story-laws.md`, `writing-guide/gaze-guide.md`, `themes/thesis.md`, and the archive `reference/world-plan-v1.md` (history, not canon). `writing-guide/magic-system/` was not used as a source of facts. Nothing was edited except this file. Every fix below is a **proposal**; none is applied.

Path shorthand: `sb/` = `story-bible/`. Quotes are verbatim.

Severity rule used: **BLOCKER** when canon itself invites or permits a Law 1 violation, actively contradicts a story law or itself, or leaves a story that is next in line impossible to outline. Where canon merely *requires compliance* (for example "give the character a stated age of 18 or more"), I filed it SHOULD-FIX and said so.

---

> **Lead editor's verification (2026-10-18).** Checked against T-001's definition of done: met. Two corrections before this reaches the author:
> - **A4 / M3, provenance:** "raised by the fairies" is not a migration invention. The author wrote on 2026-10-16 that elves "were born from light and were raised by fairies when they arrived"; it was dropped from the plan file, not added by the bible. The age question in A4 still stands.
> - **A1, severity:** downgraded from BLOCKER to NOTE. The author decided on 2026-10-17 that fairies have no age: each is an ancient angelic mind conjured directly into an adult form, never a child at any point, which is consistent with the purpose of Law 1. Decision 2 below stays available if the author wants a stricter rule.
> Revised counts: **6 BLOCKER, 32 SHOULD-FIX, 17 NOTE.**

## 1. Summary

| Severity | Count |
|---|---|
| BLOCKER | 7 |
| SHOULD-FIX | 32 |
| NOTE | 16 |

**Blockers at a glance**

| ID | One line |
|---|---|
| C1 | Elves may reproduce with humans from Era 3, but a male elf needs a human father and Law 6 forbids male elves before the epilogue |
| A1 | Newly conjured fairies have "no age", so the stated-age test cannot protect them; Era 4 plans erotic conjuring |
| A2 | The men's aging chart has no bands: stated age 3 looks 28. "Visibly adult" is unsatisfiable for male drow, demon sons, and male elves |
| A3 | Vampires are turned by *apparent* age 18 to 30; Era 4 plans "humans seduced and converted" |
| A4 | Era 1 part two: elves are "born of light and raised by the fairies" yet are adult protagonists, with no stated age |
| G1 | Era 3 (Book 1) has no want, obstacle, climax, or decisive choice for any of its three women |
| G2 | Era 4 has no protagonist (known, ticket T-009); this blocks Book 3 |

Questions for the author are in section 9 (30 items, each with a recommended default).

---

## 2. Contradictions

### C1. Male elves versus elf-human reproduction (BLOCKER)
- `sb/reproduction.md` → "Reproduction": "Later they can also reproduce with a human or another creature." and "A male elf needs a human father, which is why male elves first appear with the epilogue's half-births."
- `sb/eras/era-3-vampires.md` → "Events": "Pushed by the upheaval, **elves begin reproducing with others**."
- `writing-guide/story-laws.md` → 6: "male elves appear only with the epilogue's half-births".
- Conflict: if Era 3 elves bear children with humans, male half-elves can be born in Era 3 to Era 7. The rule cannot hold on the biology as written. Related: `sb/species/drow.md` → "Sex and lean": "Male or female... men lean demon with slight elf traits." Male half-elves (drow) already exist from Era 2, so "no male elves" needs a definition of what counts.
- Law 6 cannot be quietly overridden. Needs an author ruling (Q1).

### C2. When elves first reproduce with others (SHOULD-FIX)
- `sb/eras/era-1-fairies-and-elves.md` → "Rules in force": "Fairies and elves **never cross with other races** in this era."
- `sb/eras/era-2-origin.md` → "Events" 7: "Demons and elves produce the **drow**." (so Era 2).
- `sb/eras/era-3-vampires.md`: "elves begin reproducing with others" (so Era 3).
- `sb/reproduction.md` → "Why elves began reproducing with others": "the elves were forced to reproduce with others to keep the balance" (era unstated).
- Three different "firsts". The word "forced" also reads as coercion in a sexual context (see A9).

### C3. Mortal, immortal, and which species use the chart (SHOULD-FIX)
- `sb/ages-and-lifespans.md` → "The aging chart": "27 | immortals stop here" and "27 to 30 (mortals only; "old")". The file never says which species are mortal. Elves (stated up to 332.5 for mortals) cannot be sorted.
- `sb/reproduction.md`: "**Demons** carry a curse: a demon's child with a **mortal** is always **male**". `sb/species/drow.md`: drow "Male or female". If elves were mortal the curse would forbid female drow, so elves must be immortal, but nothing says so.
- `sb/ages-and-lifespans.md` → "The aging chart": the chart applies to "everyone **except humans, witches, fairies, and vampires** (so elves, dark elves, drow, werewolves, demons, and others)". But `sb/species/humans.md`: "A man who becomes a werewolf, or anyone turned vampire, starts human." A bitten adult cannot also run a birth-to-maturity schedule. Fallen angels, the death god, and created demons are swept in too (see A5).
- Plan note "Mortals age slowly" (`reference/world-plan-v1.md` §3E) was replaced by "Humans age normally" and left unreconciled with the chart's "mortals".

### C4. Half-births in the epilogue versus cross-species births from Era 2 (SHOULD-FIX)
- `sb/eras/epilogue-half-births.md`: "A wave of **half-births**: half human, half something else."
- Canon already produces cross-species births long before: demon sons with mortals (`sb/reproduction.md`), drow (Era 2), "witches with demons" and "cross-species romances everywhere" (`sb/eras/era-4-settlement.md` → "Planned threads"; `sb/eras/era-3-vampires.md`).
- Nothing says why a "wave" waits until after Era 7, and `sb/eras/era-6-civil-war.md` → "Aftermath" has the elves isolating "from humans out of shame", which removes the human fathers the epilogue needs.

### C5. The death god's motives across eras (SHOULD-FIX)
| Source | Line |
|---|---|
| `sb/chain-of-intentions.md` → 5 | "has **always believed in neutrality**... he deludes himself that **killing all magical beings is the only way to true neutrality**" |
| `sb/eras/era-2-origin.md` → "The portal afterwards" | he visits "witches and dark elves, to seduce them"; is "accidentally seduced himself, by witches and some fire fairies" |
| `sb/eras/era-5-werewolves.md` → "The death god's stance" | "a little **ashamed of the demons**... So **he doesn't intervene**; the werewolf is serving his cause." |
| `sb/eras/era-6-civil-war.md` → "The sides" | "**The death god and the demons** approve (more death) and watch." |
| `sb/roster.md` → "Distinctions" | "the death god is certain he is neutral" |
| `writing-guide/gaze-guide.md` → table | Death god "Changes from: Detachment and certainty" |

- Questions: (a) shame over demons (Era 5) sits oddly beside "certain" and "detachment", and then he *approves* the same kind of death in Era 6. (b) He seduces and is seduced by the very beings he believes must all die. (c) He lets the werewolf kill his own demons; the plan had Dracula "does not like the demons being killed" (dropped in migration, M4), so his agent's reaction to the same event is now missing. (d) His Era 5 hope that there is "never... peace while good and evil are locked in a tug of war" is a call to abandon balance-by-adjustment, which sits against "neutrality". These may all be intended as the shape of a self-deceiving man, but canon never says the contradictions are his; Law 4 requires them to read as his rationalisation, not a verdict. Needs an author line (Q10).

### C6. Death god's mission wording changed in transit (SHOULD-FIX)
- `reference/world-plan-v1.md` §2 men's table: "Death god / reaper | Duty to souls and the underworld"; §2 distinctions: "the reaper is *neutral by nature* and bound by duty."
- `sb/roster.md` → "Men": "Balance through death"; "Distinctions to preserve": "the death god is certain he is neutral."
- "Duty to souls" is gone. Nothing in the bible says what the death god does with the dead while confined, or who reaps souls. His one soul-related act is sending a dead human's soul back as Dracula (`sb/species/vampires.md` → "Origin"). Not recorded as an author decision.

### C7. The evil witch's sequence (SHOULD-FIX)
- `sb/eras/era-2-origin.md` → "Events" 6: a coven sister "**already seduced by the death god**, goes to help, secretly meaning to win his heart and join his cause. She becomes **the evil witch**." (She is already his partisan before the demons exist.)
- Same file, 8: "the death god's view of balance through death takes hold of her; she loses faith when the demons miss; and **jealousy** tips her over." (She is converted gradually and *had* faith in the soft approach.)
- `sb/chain-of-intentions.md` → 7: "A coven sister seduced by the death god helps, secretly hoping to win his heart. She becomes the evil witch."
- `sb/plot-twist-inventory.md`: "The evil witch was the death god's lover and ally | Book 2 | Her turn must surprise."
- Mole from the start, or convert? As written she is both. Also unstated: who actually defeats her (Era 2, 9: "The coven, helped by the light elves, defeats her"), and the label "evil" in a bible subject to Law 4 (see C18).

### C8. The portal and who knows what (SHOULD-FIX)
| Claim | Source |
|---|---|
| He is confined and "cannot leave except through the evil witch's secret portal" | `sb/01-world.md` → "The powers above and below" |
| "**She opens a secret portal** to let him out... **he does not come through to save her**" | `sb/eras/era-2-origin.md` → "Events" 9 |
| He then "visit[s] people" through it | same file, "The portal afterwards" |
| "**No one knows of the portal except those he visits**" | same file |
| Demons are made by the contained death god in Era 2 (event 6) and are loose on Earth seducing elves and witches (event 7) *before* the portal exists (event 9) | same file |
| Era 5: surviving demons "retreat to the underworld with the death god"; Era 6: drow and demons travel "between Earth and the underworld" | `sb/eras/era-5-werewolves.md` 11; `sb/eras/era-6-civil-war.md` 6 |
| The first witch "keeps visiting him below" yet "never learns of the portal" | `sb/species/death-god.md` → "Confinement and the portal" |
| Unplaced Era 5 idea: "a good witch and a bad witch... visit the death god for advice (and something more)" | `sb/eras/era-5-werewolves.md` → "Open" |

Problems:
1. Demons and later drow cross between worlds freely, so the portal is neither the only exit nor secret from them.
2. If the first witch can visit the underworld she either uses a gate of her own or sees the portal from the other side. Neither is explained.
3. The coven defeated the evil witch where she opened it; it is not stated whether the portal survives, closes, or is unseen.
4. "Does not come through" (Era 2) against "visit[s] people" (afterwards) needs one line: he declined to cross *to save her*.
5. The good/bad witch visit, if placed, hands a witch knowledge of the death god's reachability.
6. `sb/01-world.md` states "He cannot leave" as fact, while the plan listed "can the death god ever leave it?" as open (`reference/world-plan-v1.md` §6C(c)). This is a quiet answer (H1).

### C9. The first witch: fate, ignorance, and lifespan (SHOULD-FIX)
- `writing-guide/story-laws.md` → 6: "the first witch never learns of the death god's portal". That binds every era she is alive in (Eras 2 to 7).
- `sb/species/witches.md` → "Age": witches "age like humans until they learn the **forbidden magic**" and then freeze. Whether a frozen witch can die of age, and whether the first witch is alive in Era 3 to Era 7, is not stated. `sb/eras/era-7-witches.md` → "Open": "who founds them (a descendant of the first coven?)".
- Hags: `sb/species/hags.md` lists eras [6, 7] and "the few hags", but any witch who skips the forbidden magic ages as a human, so aged witches exist from Era 2. Hags "ancient, formidable" (plan §2) was dropped, leaving hags as ordinary human-lifespan women. Hag age and numbers need a line.

### C10. Chain of intentions versus Era 1 and Era 2 (SHOULD-FIX)
- `sb/chain-of-intentions.md` → 4: the fallen angels "come to restore equilibrium by pulling toward **less progress**: humans' vices and hedonism."
- `sb/eras/era-2-origin.md` → "Events" 1: "Their plan: **end the fairies' and elves' involvement in human progress** and keep the groups separate."
- Two different plans (pull humans to vice; withdraw the helpers). Meanwhile `sb/eras/era-1-fairies-and-elves.md` → "Part two" has the **dark elves** already doing the vice-pulling before the angels fall, which the chain does not mention. Also chain 7: the first witch contains the death god "using the power of the two women fallen angels", but Era 2 3 says he **consumed the leader's soul** and the second woman is a sacrifice; where their power persists is not stated.

### C11. Era 2's event order and complicity (SHOULD-FIX)
- `sb/eras/era-2-origin.md` → "Events" 3 has the death god consume the leader "but doesn't find her power there, because she has already passed it on"; 4 then narrates "The leader creates the first witch, passing her power on." The cause is listed after its effect.
- Event 2: the man "convinces the other two to help kill the leader." "The other two" includes the second woman, who then sacrifices herself for the witches (4) and lends power to the containment (5). Her complicity in the murder is never addressed.
- `sb/characters/protagonists.md` says the first witch is "connected to the leader later", yet she is created by her.

### C12. Fairies: speech, naming, and mission (SHOULD-FIX)
- `sb/roster.md`: "Fae | Trickery and bargains | The fairy realm; five elements". `sb/species/fairies.md` → "Mission": "trickery and bargains (archetype); in lore, guiding humans... with hints." Lore says fairies "never speak to humans" (small form) and give "hints only"; no bargain, trick, name, iron, or promise rule survives in the bible (M1).
- `sb/species/fairies.md` → "Forms" 2: human form "speaks, integrates". Era 1 limits the silence to fairy form: "**In fairy form they never speak to humans**". The plan said they "never speak to humans" generally; the migration silently narrowed it.
- Terminology: the plan's Era 3 character was "a fae"/"The fae"; the bible uses "fairy"/"fairies" in Era 3 and everywhere. Is "fae" the roster label and "fairy" the species? Unstated.
- `sb/eras/era-1-fairies-and-elves.md`: freckles "so the reader knows she is a fairy" (plan: "so the audience knows"). In-world, can anyone tell? It matters because the human form is the one form vampires can kill.

### C13. Roster versus species files (SHOULD-FIX)
| Roster line | Species/lore | Issue |
|---|---|---|
| `sb/roster.md` Women: Dark elf and Drow both "Ambition and conquest" | `sb/species/dark-elves.md`: "pulling humans toward temptation and vice"; `sb/species/drow.md`: outcasts who join the death god | Neither lore file shows conquest. The shared mission is a leftover from the plan's single entry. |
| Drow listed under **Women**, covered by the male gaze | `sb/species/drow.md`: "Male or female"; tags "women, men" | Male drow have no gaze rule. `sb/roster.md` also lists "male dark elf" as **cut**. |
| Fallen angel: "Redemption or defiance" | `sb/species/fallen-angels.md` and `themes/thesis.md`: the survivors' purpose is "wanting their women back" | Mission and lived purpose differ. |
| `sb/roster.md` → "Distinctions": "the fallen angel is good that fell" | `writing-guide/story-laws.md` → 4 | See C18. |
| `sb/roster.md` frontmatter `status: locked` | same file: "Whether 'dark elf' and 'drow' stay one roster entry or two is open"; kitsune "placement parked" | "Locked" with open items; `sb/CLAUDE.md` says everything is `draft` until this audit. |
| Roster Witch: "Human, magic is a skill" | Law 2 / `sb/species/witches.md` tag "women" | No statement on male witches; "warlock" is on the cut list, which implies none, but only by inference. |

### C14. Population and extinction by era (SHOULD-FIX)
Checked and holding: see section 8 (checks that pass). Gaps found:
- **Dark elves in the Civil War.** `sb/eras/era-6-civil-war.md` → "The sides" lists fairies, "Elves", witches, vampires, death god. Which side the dark elves take is not given, though they are later sent "beneath the desert sand". The drow "outcast by the elves": why, and by which elves?
- **Fairy sustainability.** After fire, water, and air are extinct, no one can conjure those kinds (`sb/reproduction.md`: a fairy conjures "by immersing herself in the element she came from"). Soul fairies "rarely conjure, out of shame", and "only a few soul fairies survive". `sb/eras/era-7-witches.md` gives soul fairies a "fulfilled" verdict; their continued existence is unexplained.
- **Elves' shame.** `sb/eras/era-6-civil-war.md` → "Aftermath": survivors isolate "out of shame", but the elves considered the massacre "an overall improvement". Shame for what is not stated (the war? the hags' help if they learn of it?).
- **Hag numbers.** "the few hags" in Era 6, yet a curse made them dangerous enough to extinct three fairy kinds with the elves' war. Needs a rough size.
- **Era durations.** `sb/timeline.md` gives no years or gaps. The Era 5 elf also stars in Era 6, witches and elves may be 300-plus years old, and the chart runs on stated years. Every cross-era character question needs this.

### C15. Ages (SHOULD-FIX)
- `sb/ages-and-lifespans.md` → "Distribution": "women centre on about **24**... a very small tail is the rapidly maturing children." But the chart has immortals "stop here" at 27 and witches freeze at "21 to 27"; any long-lived population piles up at 27, not 24. And the chart gives 18 months to apparent 18 and 15 years to apparent 21, so the "smaller group" of 18 to 21 cannot be 14 percent of a population. The curve and the chart describe different things.
- Arithmetic of the women's chart checks out (1.5, 16.5, 166.5, 316.5, 331.5, 332.5).
- `sb/ages-and-lifespans.md` says "about 2" for a woman who looks 18; the chart says 1.5. Cosmetic.

### C16. Era 3 and Era 4 overlap (NOTE)
`sb/eras/era-3-vampires.md` ends with "Equilibrium returns, with cross-species romances everywhere... witches, vampires, and demons blend in with humans so well", and `sb/eras/era-4-settlement.md` is "the settlement of vampires and humans". The boundary between them is unmarked. Era 4 also lists both "Elves with elves" and "**Elves staying out of it all**, for now" (readable as "only with each other"), directly after Era 3 has them reproducing with others.

### C17. Species file that reads as an unfinished decision (NOTE)
- `sb/eras/epilogue-half-births.md` → "Open": "Whether male half-fae appear (fairies cannot conceive, so this may be impossible; to confirm)". `sb/reproduction.md`: fairies "**can never conceive** with them: the parts exist but do not work." Canon has already answered this: no. Listed in `sb/open-questions.md` as open (H1).

### C18. Moral labels in canon (NOTE)
`writing-guide/story-laws.md` → 4: "No character or faction is narrated as objectively good or evil." Canon text uses "the **evil witch**" throughout, "some good people can be infected by evil" (`sb/eras/era-2-origin.md` 6), and "good that fell" (`sb/roster.md`). These are bible labels, not prose, but they will leak into drafts. Suggest a neutral working name for the evil witch and a note that the labels are in-world slurs or POV reads.

### C19. Dangling references (NOTE)
- `sb/species/humans.md` → "Magic": "See `../magic/creature-forms/humans.md`", which does not exist (no humans or kitsune form in `sb/magic/creature-forms/`).
- `sb/01-world.md` → "Where the peoples live by the end" omits vampires, werewolves, hags, fallen angels.
- `sb/species/elves.md` → "Origin": "They carry a special kind of magic (open)". An unrecorded addition (M3).

---

## 3. Age-rule pass (Law 1)

Method: each species, era thread, and planned thread walked against `writing-guide/story-laws.md` → 1. Test for BLOCKER: canon structurally permits, invites, or cannot prevent a non-adult (by stated age) in sexual or romantic content. Where canon only needs a stated age to be written down, SHOULD-FIX.

### 3.1 Species walk

| Species | Verdict | Finding |
|---|---|---|
| Humans | Pass | Stated age equals years lived (`sb/species/humans.md`: "age normally"). |
| Witches | SHOULD-FIX | A6 |
| Hags | Pass | Age visibly; no frozen appearance. |
| Fairies | **BLOCKER** | A1 |
| Elves | **BLOCKER** (Era 1) / SHOULD-FIX | A4, A8; eligible only from stated 18, apparent just over 21 (`sb/ages-and-lifespans.md`). |
| Dark elves | As elves | Same chart; A4/A8 apply. |
| Drow | **BLOCKER** (male) | A2 |
| Vampires | **BLOCKER** | A3; plus A7 |
| Werewolves | NOTE | A11 |
| Demons | SHOULD-FIX | A5, A2 (sons) |
| Fallen angels | SHOULD-FIX | A5 |
| Death god | SHOULD-FIX | A5 |
| Kitsune | NOTE | A10 |

### 3.2 Findings

**A1. Newly conjured fairies (BLOCKER).**
- `writing-guide/story-laws.md` → 1: "Fairies are conjured as adults and have no age; they are ancient, angelic minds. They are always written as unmistakably adult." Same file: "A character may appear in sexual or romantic content **only if her or his stated age is 18 or older**." The fairy carve-out removes any minimum.
- `sb/reproduction.md`: the new fairy is "an **adult from the start**, a **mental clone**". A fairy conjured an hour ago has the body and mind of an adult but is, by any count, new. The Law's own principle ("A character who looks 18 but is stated as 2 is a child in the text") would apply if she had an age.
- Planned thread: `sb/eras/era-4-settlement.md`: "Fairies taking pleasure in conjuring more fairies (depicting only the adult fairy)". The Law permits depicting the adult parent. But the thread eroticizes the act that makes the newcomer, and the newcomer then appears in Era 4's "Fairies with demons, vampires, and witches" with no rule on how soon.
- Proposed rule (Q2): a conjured fairy takes part in sexual or romantic content only once 18 years have passed since conjuring, and the conjuring scene itself shows only the parent.

**A2. The men's chart (BLOCKER).**
- `sb/ages-and-lifespans.md`: "Men follow the same chart, except maturity takes **36 months** and arrives at apparent age **28**. How the later bands run for men is open."
- A male on the chart is therefore a fully adult-looking 28-year-old at stated age 3, with no 18 to 21 band, no adolescent look, and no visible signal of youth for the next 15 years. The Law's requirement "visibly so on the page" cannot be met for any male who is on the chart and under 18 stated.
- Who this reaches: male drow (`sb/species/drow.md`); sons of demons and mortals (`sb/reproduction.md`: "must be **male**"); male half-elves in the epilogue (`sb/eras/epilogue-half-births.md`); any male half-born child. The female gaze (`writing-guide/gaze-guide.md`) has no guard against a 28-looking stated-10 man.
- Also: women chart species pass only because the chart shows a visible adolescent look; men do not.
- Proposed fix (Q3): give men the same visible stages (apparent 18 at stated 3; apparent 28 at stated 18), and add a line that any male under stated 18 is described as a boy and is never in such content. This preserves "men need more time" and makes eligibility visible.

**A3. Vampire turning by apparent age (BLOCKER).**
- `sb/ages-and-lifespans.md`: "**Vampires** are turned by another vampire between apparent **18 and 30** and stay at that age forever." `sb/species/vampires.md` → "Age": same.
- Law 1: "Stated age governs, not apparent age." A human of stated 16 who looks 18 satisfies the rule as written.
- Era 4 plans "Humans seduced and converted to vampires and demons" (`sb/eras/era-4-settlement.md`), a romantic-and-sexual scene in which the turned person must be stated 18 or more. The rule must say so. (Related to Law 1 bullet: "a vampire turned young must still read as clearly adult".)
- Fix (Q4): "turned only at stated 18 or older, appearing 18 to 30."

**A4. Era 1 part two: elves "born of light and raised by the fairies" (BLOCKER).**
- `sb/eras/era-1-fairies-and-elves.md` → "Part two": "They are born of light and raised by the fairies when they arrive." Also: "A second group of women angels... come down as **elves**". The two readings differ: angels arriving as adults, or children arriving to be raised.
- "Raised by the fairies" does not appear in the plan (`reference/world-plan-v1.md` §4B). It is a bible addition (M3).
- Two elves "lead the march" and are "main protagonists". Elves on the chart look adult by stated 1.5 and eligible at stated 18. With no stated ages and a rapid-childhood species, Era 1 part two could be drafted with protagonists whose stated age is under 18 in romantic scenes, and the later male angels' longing for "their women" (`sb/eras/era-2-origin.md`, "The male fallen angels") points at them.
- Fix (Q5): the first elves arrive as adult angels with stated ages of 18 or more; "born of light" applies to the generations they bear.

**A5. Created and ancient beings are swept onto the chart (SHOULD-FIX).**
`sb/ages-and-lifespans.md` exempts only "humans, witches, fairies, and vampires". That leaves fallen angels, the death god, and created demons on a birth-to-maturity schedule that makes no sense for them, and for demons made "male beings" in Era 2 gives no stated age (a demon made last year is "stated 1"?). Law 1 needs a stated age for everyone. Propose: angels, the death god, and created demons are exempt, with stated age counted from arrival or creation; only demon-born children use the chart.

**A6. Witch-making and the schools (SHOULD-FIX).**
- `writing-guide/story-laws.md` → 1: "Would-be witches are recruited only after they turn 18, so every student is an adult." Fine as far as it goes.
- Gaps: `sb/eras/era-2-origin.md` 4 "an avenue for more witches to be created" has no age condition; recruiting at 18 does not stop a child with leaking magic being taught or sheltered; students who are not human (half-births, elves) have a chart age, not "turn 18" in human years; `sb/magic/world-form.md` leaves "Awakening: Leaks out / Found by practice / Must be taught" open. Suggest: witch-making and teaching only of stated 18 or more, for every kind of student.

**A7. Vampire feeding on half-born children (SHOULD-FIX).**
`sb/eras/epilogue-half-births.md`: half-births "can be fed on by vampires". `writing-guide/story-laws.md` → 1: "Violence against children is never framed as erotic." Canon's vampire appeal is "The devoted predator" with seduction as the bite (`sb/roster.md`), so the framing is the risk. Rule: feeding on a child is never seduction and never from an erotic POV.

**A8. The Era 5 three-way and the Era 5 and 6 elf (SHOULD-FIX; BLOCKER if the elf is under stated 18).**
- `sb/eras/era-5-werewolves.md` 1: "The witch and the elf want **a man they can share**. In the woods, they turn a **human man**... in a three-way."
- No stated age is given for the witch, the elf, or the man. For the elf, apparent 21 to 27 spans stated 16.5 to 332; an elf who *looks* adult may be 17. The elf "bullied" by dark elves (`sb/eras/era-5-werewolves.md` → "Protagonists") suggests a past that may be an under-18 childhood or adolescence; those scenes must not be romantic or sexual. Write stated ages into the character worksheets before outlining.

**A9. Law wording and species rules that make compliance unclear (SHOULD-FIX).**
1. Law 1 says "visibly [adult] on the page" and "adult-looking body" cannot be used to eroticize youth, but the chart's whole design is that youth is adult-looking (men: 28 at stated 3).
2. Fairy carve-out has no minimum (A1).
3. "Romantic content" is undefined: does a crush, a mentor's longing, or a chaperoned courtship of a maturing elf count?
4. "Forced": `sb/reproduction.md` → "Why elves began reproducing with others": "the elves were forced to reproduce with others". Consent must be legible (`writing-guide/gaze-guide.md` → "Limits on both gazes"). Reword.
5. "Chosen or frozen youthful appearance" is covered only by "clearly adult"; no stated-age floor for the freeze.
6. Law 1 omits the plan's affirmation (`reference/world-plan-v1.md` §5) that rapidly maturing characters "can still be rich, important, non-sexual characters". Useful guard-rail; restore.

**A10. Kitsune (NOTE).** `sb/species/kitsune.md` has no age system. Tail-count lore ages in centuries; whichever placement the author picks, assign a stated age rule first (T-008).

**A11. Werewolf bites (NOTE).** `sb/species/werewolves.md`: "turned by his bite", victims "human men". A bite-as-seduction scene needs a stated age of 18 or more; none is stated.

---

## 4. Gaps that block drafting

Test: protagonist, want, obstacle, resolution (and, per Law 2, a decisive choice by her). `CLAUDE.md` (root): "Every story needs a real point A, point B, want, and obstacle."

| Era (telling) | Protagonist | Want | Obstacle | Resolution | Verdict |
|---|---|---|---|---|---|
| 3 (Book 1) | Three women: witch; turned vampire; fairy | Partial: witch fights prejudice "because she is in love"; vampire "likes what is happening"; fairy "looking for justice and truth" | Prejudice; vampires; demon lord | "Equilibrium returns" (a state, not a choice) | **BLOCKER G1** |
| 2 (Book 2) | Leader; first witch | Leader: end elf and fairy involvement. Witch: contain him | Death god; evil witch | Coven defeats the evil witch | Draftable; see W2 |
| 1 / 4 (Book 3) | Era 1: fairy; two elves. Era 4: none | Era 1: guide, then help | Hints insufficient; over-help | Era 1: God lets it be, angels cast out. Era 4: none | **BLOCKER G2** (Era 4); G3 (Era 1) |
| 5 (Book 4) | Witch and elf | A shared man; to stand against evil, and against bullies | The werewolf's loss of control | Fairies strike the final blow | Draftable with G4 |
| 6 (Book 5, proposed) | Elf (from Era 5); a fairy | Opposed positions on the werewolves | The war itself | Open | G5 |
| 7 (Book 6) | "Witches, with side stories" | Protect fairies and humans | Hags; death god's pull | Hags defeated; uneasy balance | G6 |
| Epilogue | None | n/a | n/a | n/a | G7 |

### G1. Era 3 (BLOCKER)
- `sb/eras/era-3-vampires.md` → "Protagonists (decided)": "A **witch** who fights for what is right despite the prejudice against witches, because she is in love with a woman who was turned."; "A **human woman turned vampire**, who likes what she has become"; "A **fairy**, in a side story: a woman looking for justice and truth."
- Missing, in order of importance:
  1. **No climax and no decisive choice.** Era 3 events are world events (demon lord, Dracula, prejudice, "Equilibrium returns"). No woman does anything that ends the book.
  2. **The fairy's injustice and truth are unnamed.** What was done to whom? How does her side story meet the others? ("three separate stories that come together" has no meeting point.)
  3. **The vampire's want.** "Likes what she has become" is a state. What does she risk? Who turned her, and with what consent (turning is presented elsewhere as killing: "made for **sheer killing**")?
  4. **The beloved's turning.** Both ages and consent are required (A3).
  5. **The demon lord** is created and never used (no scene, no goal, no fate in Era 3; killed only in Era 5). Antagonists in `sb/characters/protagonists.md` are collective ("Demons, the demon lord, the vampires").
  6. **The death god's role.** `sb/eras/era-3-vampires.md`: "The death god supports their journeys and leads none of them." Yet in the same file he creates the vampires who are the threat. A supportive man who engineered the problem needs a defined face in Book 1 (see F3).
  7. **Time.** The gap since Era 2 is unstated; so is how far the public knows Era 2 (F2).
- Why a blocker: it is told first and sets the reader's contract. A story shape is needed before outline; the worksheet and outline checklist cannot be filled from this file.

### G2. Era 4 (BLOCKER for Book 3)
- `sb/eras/era-4-settlement.md` → "Open": "**Protagonist not yet chosen** (skipped for now by the author)." Ticket T-009 exists. "Planned threads" are activities, not a story; "How it braids with Era 1" is open. It is the saga's densest adult-content zone and has no woman at its center, which would also put it at odds with Law 2. A1 and A3 apply directly to its threads.

### G3. Era 1 (SHOULD-FIX)
Protagonists and a mission exist, but the part-two elves have no named want beyond "help", and "Proposed reading, to confirm: they are the two whose beliefs split the elves" is unconfirmed. Part one ends with "Not enough" and no choice by the fairy leader. Which woman chooses what, so the story can end? A4 also binds.

### G4. Era 5 (SHOULD-FIX)
After step 3 the protagonists cease to act: steps 4 to 11 are the werewolf's, Dracula's, the fairies', and the death god's. `sb/eras/era-5-werewolves.md` 8: "The witches hunt for the man in human form and can't find him." The era's weakness ("Their weakness is **beautiful women**") is never used on the page. See W1 for the proposal.

### G5. Era 6 (SHOULD-FIX)
Ticketed (T-011 for placement; the ending is open in `sb/eras/era-6-civil-war.md` → "Open": "How the war ends"). Two women on opposite sides with no decisive choice. Wants exist; the resolution does not.

### G6. Era 7 (SHOULD-FIX)
`sb/eras/era-7-witches.md` → "Protagonists (decided)": "**Witches**, with a few side stories." No named want, obstacle, or choice for any woman; the hags' defeat has no actor. The ending ("the death god **quietly winning**") puts the final move with a man (W1 below).

### G7. Epilogue (NOTE)
`sb/eras/epilogue-half-births.md` has no protagonist; Law 2 says "Every story's protagonist is a woman." As a "coda" it may need none. Confirm (Q25).

---

## 5. Women-lead check (Law 2)

Law 2: "her choice resolves the climax. No man rescues her from her own story."

| Era | Man who drives or resolves | Does the era file give a woman the decisive choice? |
|---|---|---|
| 2 | Death god (kills the leader; "does not come through to save" the evil witch) | **Partly.** The leader chooses to pass her power on; the first witch chooses to contain him and to make the demons. But the defeat of the evil witch is credited to "The coven, helped by the light elves", and the man's refusal to cross is what decides it. **W2** |
| 3 | Death god (sends Dracula); Dracula | **No.** No woman's decision is named at all (G1). |
| 5 | The first werewolf (drives steps 2 to 9); Dracula; death god's inaction | **No.** The witch and elf choose at the start. The final blow is struck by "The fairy leaders of each element" (not the protagonists), and the era's lead antagonist is the man they made. G4 |
| 6 | Death god and demons "watch" | Not yet decided (ending open, G5). |
| 7 | Death god: "quietly winning" | **No.** The saga's final state is a man's win beneath "uneasy balance". **W1** |
| 1 | None | Fairy leader and elves: yes in structure (G3). |
| 4 | None | n/a (no protagonist). |

**W1 (SHOULD-FIX).** `sb/eras/era-7-witches.md` → "How the saga ends (decided)": "the death god **quietly winning** beneath it." This is the author's decision. It stands against Law 2 only if no woman is shown choosing the balance. Proposal (Q27): the last scene is a witch's choice to sustain the uneasy balance knowing what lies beneath; the death god's win is her cost, not his achievement.

**W2 (SHOULD-FIX).** Era 2: name who delivers the blow to the evil witch. Proposal: the first witch, deciding, with the portal-refusal as the man's non-act that she reads as abandonment.

**Era 5 proposal (Q26).** Give the witch and elf the decisive act at the climax. The unused "Weakness: beautiful women" and the unanswered "why the curse never takes women" (`sb/open-questions.md`) point one way: the protagonists choose to give the fairies the means to end him, at a cost to themselves.

---

## 6. Migration check

`reference/world-plan-v1.md` is history. This section lists what did not carry over, what changed, and what was added.

### 6.1 Changed in transit (see main findings)
| Plan | Bible | Note |
|---|---|---|
| §2: death god "Duty to souls and the underworld"; "neutral by nature and bound by duty" | `sb/roster.md`: "Balance through death"; "certain he is neutral" | C6 |
| §2: demon "*evil by nature*"; fallen angel "*good that fell*" | `sb/roster.md`: "the demon is made, and made to seduce"; fallen angel kept "good that fell" | Demon reframed (compatible with Law 4); fallen angel not (C18) |
| §3E: "apparent age" for the 18-to-21 band; Law §5 "adult in apparent age, behavior, mind, development" | `writing-guide/story-laws.md` → 1 uses **stated** age | Improvement; but `sb/ages-and-lifespans.md` vampire rule still apparent (A3) |
| §3E: "Mortals age slowly" | `sb/species/humans.md`: "Humans age normally" | C3 |
| §4B: fairies "never speak to humans" | `sb/eras/era-1-fairies-and-elves.md`: "**In fairy form** they never speak" | C12 |
| §4D: "A **fae** with a side story" | "A **fairy**" | C12 |
| §6C: "the cursed hags remain a threat... defeated by the witches near its end" (Resolved) | `sb/species/hags.md` → "End" | Preserved |

### 6.2 Dropped
| ID | Plan item | Severity |
|---|---|---|
| M1 | §2 Fae: "strict rules (names, iron, promises); Seelie/Unseelie split available". Not in `sb/roster.md`, `sb/species/fairies.md`, or any era file | SHOULD-FIX (supports the "trickery and bargains" mission, C12) |
| M2 | §2 Appeal-type detail: "seduction, elegance, eternal devotion"; "raw physicality, loyalty, a wild side"; "dominance, confidence, being chosen"; "beauty with a wound; the one who sees him"; "calm, mysterious, the exception he breaks rules for". `sb/roster.md` and `writing-guide/gaze-guide.md` keep only the short label | SHOULD-FIX (the men-characters agent needs them) |
| M4 | Minor: hags "ancient, formidable, often works in trios or covens" (only "trios or covens" kept; C9). Elf "Visual anchor; graceful, long-lived, otherworldly". Vampire "seduction and elegance". Era 5: Dracula "does not like the demons being killed". Era 6: "(No succubi are made.)". Era 5 note "The succubus is dropped from the world." Era 7: "(seduction, not hunting)". Plan §6C: "drow... need not relate to the epilogue half-births" | NOTE |
| M5 | §5: "Rapidly-maturing characters can still be rich, important, non-sexual characters"; "For humans, witches, and vampires, stated age equals years lived" | NOTE (A9) |
| M6 | §6B: "Are queer relationships and female friendships part of the world?" and §6A tone/heat. Era 3 answers the first (a taboo-then-partnership love between two women); the tone and heat questions live in tickets T-004 and T-005. Not recorded as answered | NOTE |
| M7 | `sb/01-world.md` omits the plan's per-people locations for vampires, werewolves, hags, fallen angels | NOTE (C19) |

### 6.3 Added in the bible with no source in the plan (unmarked as proposed)
| ID | Addition | Where | Severity |
|---|---|---|---|
| M3 | Elves "raised by the fairies when they arrive" | `sb/eras/era-1-fairies-and-elves.md` → "Part two" | SHOULD-FIX (A4) |
| M3 | Elves "carry a special kind of magic (open)" | `sb/species/elves.md` | included |
| M3 | Kitsune placement options: "a fire fairy's legacy after their extinction; a dark-elf or drow offshoot; a creation of the death god sent through the portal; or cut" | `sb/species/kitsune.md` | included (these are proposals; label them so; T-008) |
| M3 | "Dr. Sato on the board watches this" | `sb/species/kitsune.md` | included |

### 6.4 Carried faithfully (spot-checked)
The chain of intentions, the era sequences (Eras 1 to 7), the telling order, the thesis verdicts per people, the aging chart numbers, the reproduction rules, the cut list, and the open items. No other omissions found.

---

## 7. Foreshadowing and telling-order integrity

Telling order from `sb/timeline.md`: Book 1 = Era 3, Book 2 = Era 2, Book 3 = Era 1/4, Book 4 = Era 5, Book 5 = Era 6 (proposed), Book 6 = Era 7, Epilogue.

| Entry (`sb/foreshadowing-map.md` / `sb/plot-twist-inventory.md`) | Check | Result |
|---|---|---|
| Evil witch's turn: seed and payoff both Era 2 (Book 2) | Same book | Holds; but see C7 (mole vs convert) |
| Portal: seed Era 3 (Book 1), payoff Era 2 (Book 2) | Seed before payoff in telling order | Holds. Book 1 must not show the portal or name its opener. |
| Death god's shame: seed Era 2, payoff Era 5 | Book 2 before Book 4 | Holds |
| **Fairy vulnerability: seed "Era 1: the human form has no magic"; pays off "Era 3 onward"** | Era 1 is Book 3, **after** Era 3 (Book 1) | **F1: inverted** |
| Hags' hunger: seed and reveal both Era 6 | Same book (Book 5) | Holds, but the "seed" is the reveal's own lead-in |
| Elves' isolation: seed Era 6, payoff Era 7 | Book 5 before Book 6 | Holds |
| Twist: cursed hags helped the elves, "Book 5 (Era 6)" | Era 6 is telling "5th (proposed)" | Holds only if Era 6 stays 5th (T-011) |
| Twist: death god quietly winning, "Book 6 (Era 7)" | | Holds; no seed listed (F5) |

**F1 (SHOULD-FIX). Fairy vulnerability is seeded after it pays off.** Book 1 (Era 3) already uses the rule (`sb/eras/era-3-vampires.md`: "only in her magic-less human form"), and its fairy protagonist stands inside it. The "seed" in Book 3 is a reminder, not a seed. The seed must live in Book 1.

**F2 (SHOULD-FIX). Era 3 text leaks a Book 2 reveal.** `sb/eras/era-3-vampires.md` → "Events": "the prejudice [against witches] is **partly justified by the evil witch and the demons**." `sb/plot-twist-inventory.md`: "The first witch had the demons made | Book 2 (Era 2) | Recontextualizes the witches' prejudice in Book 1." If Book 1's characters know the demons came from witches, the Book 2 reveal is gone. Decide what the public of Era 3 knows: that an evil witch spread death (known), that witches made demons (hidden).

**F3 (SHOULD-FIX). The death god in Book 1.** `sb/eras/era-3-vampires.md`: he "supports their journeys". `sb/plot-twist-inventory.md`: "The death god made the vampires | Book 1 or 2 | Open: how much Book 1 reveals"; "The death god was once an angel | Book 2 and Book 3". Also `sb/foreshadowing-map.md`: Book 1 seeds "unexplained visits, people who know him too well". The author must decide what Book 1 shows him to be before any scene with him is drafted. (An open question is not canon: the "Book 1 or 2" line is open, and Era 3's file already states he sent Dracula as event.)

**F4 (NOTE). Reveals not in the inventory.** Dracula's identity as the death god's agent (see F3); the first witch's ignorance of the portal (dramatic irony); the Era 5 elf and witch as the werewolf's makers; fairy extinction (Book 1 and Book 3 show fire, water, and air fairies alive and unthreatened before Book 5 takes them; the Era 1 fairy leader's element is unstated and she may be among the dead).

**F5 (NOTE). Threads with no entry in the map.** The death god quietly winning (no seed); the dark elves who bullied the Era 5 elf (no seed); Dracula's reaction to the demon massacre; the elves' first births with others; the beautiful-woman weakness (a seed with no payoff, see below).

**F6 (NOTE). Seed with no payoff.** `sb/species/werewolves.md` → "The rest of the kind": "Their weakness is **beautiful women**." Never used in `sb/eras/era-5-werewolves.md` or `sb/eras/era-7-witches.md` except as lure for love affairs. Open question: "Why the werewolf curse never takes women" is tied to it in the plan.

**F7 (NOTE). Book 3 braid.** Era 1 (told in two parts) and Era 4 (no protagonist) are braided with no plan for the braid (open). Whatever the braid does, Book 3 must not reveal Era 5 to Era 7 facts, including fire, water, and air fairy extinction.

### Open-questions hygiene

**H1 (SHOULD-FIX). Quietly answered, still listed open (or answered without a decision).**
- *Can the death god leave the underworld?* `sb/01-world.md`: "He cannot leave except through the evil witch's secret portal." The plan's question (§6C(c)) is no longer in `sb/open-questions.md`.
- *Can male half-fae exist?* `sb/reproduction.md` says fairies "can never conceive"; `sb/open-questions.md` → "Eras" still lists it (C17).
- *Dark elf and drow one entry or two?* `sb/roster.md` has two rows, `sb/open-questions.md` still lists it.
- *Queer relationships and female friendships?* Answered in Era 3, not recorded.
- *Elves "raised by the fairies"* and *elf magic* were added without a record (M3).

**H2 (NOTE). Dropped from `sb/open-questions.md`.** Why hags refuse or lose the glamour (plan §6D); whether the death god or other men look different from the bell curve (kept in `sb/ages-and-lifespans.md` → "Open", missing from `sb/open-questions.md`); whether fairies bargain or trick (M1); the heat level (ticketed as T-004). Tickets T-008, T-009, T-010, T-011 correspond to listed open questions.

---

## 8. Checks that pass

| Check | Source | Result |
|---|---|---|
| Fire, water, air fairies extinct after Era 6 | `sb/eras/era-6-civil-war.md` 9; `sb/species/fairies.md`; `sb/eras/era-7-witches.md` | Era 7 mentions only forest and soul fairies. No species file or Era 7 line uses the extinct three after Era 6. Fire fairies appear only in Era 2 portal visits (`sb/species/death-god.md`), which is before the extinction. |
| No succubi | `sb/roster.md` → "Cut"; `writing-guide/story-laws.md` → 6 | No succubus, no female demon in any file. (The hags' feeding on fairies is a different mechanism; the plan's "(No succubi are made.)" note was lost, M4.) |
| Women's chart arithmetic | `sb/ages-and-lifespans.md` | 1.5, 16.5, 166.5, 316.5, 331.5, 332.5 all sum correctly |
| Fairies cannot conceive vs events | `sb/reproduction.md`; `sb/eras/era-2-origin.md`: "tragic... because fairies never conceive" | Consistent; no event gives a fairy a child |
| Werewolves never turn women | `sb/species/werewolves.md`; `sb/eras/era-5-werewolves.md` | Consistent |
| Witches did not exist before Era 2 | `sb/species/witches.md`; Era 1 | Consistent |
| Hags only in Eras 6 and 7 | `sb/species/hags.md` | Consistent with the cursed-hag arc (but see C9 on non-cursed aged witches) |
| Thesis verdict table | `sb/eras/era-7-witches.md`; `themes/thesis.md` | The same eight rows and readings |
| Telling-order table | `sb/timeline.md` | Matches the plan and each era file's `telling:` frontmatter |

---

## 9. Decisions for the author

Each answerable in one line. Recommended default in bold.

**Blocker-clearing**
1. *Elf births before the epilogue (C1, C2).* Which elf births are canon before the epilogue? **Default: Era 3's "reproduce with others" means elf with demon (drow) and elf with elf-by-choice; human-fathered elf births, and so male elves, begin only with the epilogue, and the Era 3 line is reworded to "begin openly choosing others".**
2. *Conjured fairies (A1).* **Default: no sexual or romantic content for a fairy until 18 years after conjuring; conjuring scenes show only the parent.**
3. *Men's chart (A2).* **Default: men show the same visible stages as women (apparent 18 at stated 3, apparent 28 at stated 18); any male under stated 18 is a boy on the page.**
4. *Vampire turning age (A3).* **Default: turned only at stated 18 or older, appearing 18 to 30.**
5. *Era 1 first elves (A4).* **Default: they arrive as adult angels of stated age 18 or more; "born of light" describes only their daughters.**
6. *Era 3 shape (G1).* Will you give each of the three women a want, a decisive act, and a point where the stories meet? **Default: commission a story-shape pass on Era 3 before any outline; the keeper proposes three options.**
7. *Era 4 (G2, T-009).* **Default: stay parked, and do not outline Book 3 until a woman is chosen.**

**Canon fixes**
8. *Mortal and immortal (C3).* **Default: elves, dark elves, drow, demons, angels are immortal; humans, witches, half-births, and werewolves are mortal; the "mortal" in the demon curse means "not immortal".**
9. *Chart scope (A5).* **Default: angels, the death god, and created demons are exempt from the chart; their stated age counts from arrival or creation.**
10. *Death god's contradictions (C5).* Are the shame, the approval, and the seductions his self-deceptions, shown through a POV? **Default: yes; add one line to his file.**
11. *Death god's mission (C6).* **Default: restore "bound to souls and the underworld" beside "balance through death", and say who reaps souls while he is confined.**
12. *Evil witch (C7).* **Default: she is a convert; she is seduced at the start but not yet his; rewrite Era 2 event 6 to match the three steps.**
13. *Portal (C8).* **Default: demons cross by the first witch's own gate; the portal is a second, secret exit for the death god alone; the first witch's visits use her gate; "no one knows" means no one but visitors and the demons and drow who traffic through it.**
14. *First witch (C9).* **Default: frozen witches can still be killed; the first witch is alive or dead as the stories need, and Law 6 binds her only while she lives.**
15. *Chain wording (C10).* **Default: edit chain item 4 to "withdraw the helpers and let vice weigh on the other side".**
16. *Era 2 order (C11).* **Default: reorder events 3 and 4; the second woman did not take part in the murder.**
17. *Fae vs fairy (C12, M1).* **Default: "fairy" is the species and "fae" the roster label; restore bargains, names, iron, and promises for the later conjured generations; first-generation fairies stay silent.**
18. *Dark elf and drow (C13).* **Default: two entries; give each its own mission (dark elves: temptation as counterweight; drow: belonging); male drow allowed with their own gaze note; update the roster `status` to `draft`.**
19. *Era 6 loose ends (C14).* **Default: dark elves side with the elves; the drow are outcast after the war's first elf victory; give the elves' shame a cause (the cost of the war itself).**
20. *Era durations (C14, C15).* **Default: add rough year spans and gaps to `sb/timeline.md`.**
21. *Bell curve (C15).* **Default: treat it as the look of characters met on the page, not a population, and say so.**
22. *Half-births (C4).* **Default: the wave is a result of Era 7's merging of peoples; one sentence explains why earlier births stayed rare.**
23. *Humans converted to demons (Era 4 thread).* **Default: cut "and demons" from the thread unless a mechanism is decided.**
24. *Witch-making and teaching (A6).* **Default: stated 18 or older, for every kind of student.**
25. *Epilogue protagonist (G7).* **Default: none; the epilogue is a coda.**
26. *Era 5 climax (G4).* **Default: the witch and elf choose to give the fairies the means to end him, using the "beautiful women" weakness.**
27. *Saga ending (W1).* **Default: a witch's choice to sustain the balance, knowing what lies beneath, is the last scene.**
28. *Era 3 and the telling order (F1, F2, F3).* **Default: Book 1 seeds fairy vulnerability on the page; the public knows an evil witch spread death but not that witches made the demons; the death god appears as an ally of unclear motive and is not named a fallen angel.**
29. *Law 1 wording (A7, A9).* **Default: add four lines: vampire feeding on children is never erotic; "forced" is struck; "romantic content" is defined; restore the "rich non-sexual characters" sentence.**
30. *Labels (C18).* **Default: use a neutral working name for the evil witch; mark "good" and "evil" labels as in-world views.**

---

## Counts

| Severity | Count | IDs |
|---|---|---|
| BLOCKER | 7 | C1, A1, A2, A3, A4, G1, G2 |
| SHOULD-FIX | 32 | C2 to C15 (14); A5 to A9 (5); G3 to G6 (4); W1, W2 (2); M1, M2, M3 (3); F1, F2, F3 (3); H1 (1) |
| NOTE | 16 | C16 to C19 (4); A10, A11 (2); G7 (1); M4 to M7 (4); F4 to F7 (4); H2 (1) |

**Author decisions needed:** all 30 in section 9; items 1 to 7 are required before Book 1 (items 1 to 6) or Book 3 (item 7) can be outlined.
