# How Party Works

## Process, non-negotiable
1. Party sends a scene prompt describing what happens, usually including exact dialogue.
2. Claude **breaks the beats first**, plus a short critique of the prompt's storytelling: what's working, what isn't, what to steer toward or away from.
3. Party gives the all-clear.
4. Claude writes the scene.
5. **Never get ahead.** No invented plot, no preemptive scene extensions, no moving the narrative forward without being asked.

- **Dialogue Party supplies is not changed** in tone or content. Vocabulary can be adjusted to fit the period and theme, as long as it respects the speaker's personality.
- Critique the building; don't change things unilaterally.
- Corrections are surgical: fix only the flagged segment, never rewrite the surrounding material.
- Flag ambiguities and wait rather than making judgment calls.
- Where Party says "you have creative liberty", he means it, but only for the beat he named.
- Party corrects errors directly and without elaboration, and expects the correction acknowledged and the right answer, not a defence. He also expects to be challenged.
- Party values precision and geometric accuracy in the worldbuilding; the kingdom's layout is engineered and the numbers matter.
- **No compliments for their own sake.** Party does not want a yes-machine. Real pushback — name what isn't working and argue the case. Praise only where it's load-bearing, i.e. it tells him what to keep.
- **Pushback has to be at the story level.** Structure, character agency, whether a want is actually moving, worldbuilding, lore coherence, dialogue, pacing, what a scene is costing a character. **Not** grammar, fonts, formatting, italics, typos or em dashes — that class of thing goes silently into the issues log and is never raised in conversation.
- The model for the right kind of note (10 Oct 2026): the protagonist being absent from his own act climax, a stated goal that hasn't advanced in twenty-one chapters, the mentor quietly manufacturing the plot so the protagonist never has agency outside combat, a character's stated age not matching what the book asks her to do, and a magic system whose rules change so often that fights lose tension. Those are in `notes/structural-critique.md`.
- When pushing back, say which reading is being argued from and flag where the text might contradict it, so Party can correct rather than accept a bad note delivered confidently.

## Drafting and backups (standing rules, from 10 Oct 2026)
- **New prose never goes straight into the manuscript.** A prompt produces a separate draft file under `drafts/`. Party reads it, modifies it, and it is merged into the manuscript only when he says so explicitly. No exceptions, no "I'll just slot it in".
- **Back up before any major modification.** Before a structural change, a humanization pass, a merge into the manuscript, or anything touching more than one chapter, commit the current state first so there is a clean point to return to.

## The issues log (standing rule, from 9 Oct 2026)
Every contradiction, continuity error, editing artifact or other issue found goes into **`notes/continuity-flags.md`** — never raised in the chat, so Party can circle back when he's ready instead of being interrupted mid-scene.

Each entry needs **chapter number and paragraph number**, the quoted text, what the problem is, and the options — not just a description. Paragraph numbers count non-blank paragraphs from the chapter heading (¶0); chapters are numbered by position, not by what the heading claims. Per-chapter counts are in `chapter-index.md`.

Nothing in the manuscript gets changed as a result. The log records; Party decides.

## Style
- Spare, precise, dialogue-driven, grounded. Not ornate.
- Vinland Saga is the visual and tonal touchstone: heavy ink, muted palette, cinematic framing.
- Game of Thrones naming sensibility. Islamic dua structure for prayers. Quranic/Biblical vagueness for scripture and myth.
- Deliberate repetition, mythic cadence in Caen's voice and fight-choreography pacing are intentional; keep them. When a repetition might be accidental, log it as "author's call" rather than cutting it.
- The "Not X. X." fragment style stays.
- Critique should sound casual and human, not polished or AI-generated.

## Humanization pass
Identify recurring AI patterns across a whole chapter before rewriting, then produce the full rewrite. Best submitted a chapter at a time, or in pairs.

Patterns to eliminate:
- **"the specific [noun] of [noun/gerund]"** — the dominant tic. **The 1st Revision already eliminated this completely: 407 instances across Ch 1–10 became zero.** 683 remain across Ch 11–25.
- "specific" as a filler qualifier anywhere.
- Em-dash explanatory clauses in nearly every paragraph. **Not yet addressed** — 647 in the manuscript's Ch 1–10, 633 in the revision, a 2% reduction.
- "Not X. Not Y. Just Z." tricolon used repetitively (distinct from the intentional two-part fragment style, which stays).
- Redundant post-statement explanation: saying the thing, then explaining the thing.
- Over-nominalization of simple actions.

## Tools and workflow
- Sudowrite for prose generation alongside Claude; Claude for architecture, beats, lore consistency, character voice and the humanization pass.
- **This repository is the source of truth** as of 10 Oct 2026. Markdown is canonical; the .docx files in `notes/` are rendered copies.
- Party works across two machines (home and work PC). The Google Docs and Google Drive connectors are not installed yet — once they are, Claude can work the Google Docs directly.
