# The Shortsword

Dark fantasy novel. Working repository — manuscript, sources and working notes.

Private. ~182,000 words of unpublished draft.

## Layout

| Path | What's in it |
|---|---|
| `manuscript/` | The live Word documents. `The Shortsword.docx` is Ch 1–25. `1st Revision.docx` is the tightened Ch 1–10 and is **canon for those chapters**. `Prompts.docx` is the scene prompts, lore Q&A and the Ch 26 plan. |
| `sources/` | Plain-text exports of the same material. These are what git can actually diff — use them to see what changed between commits. |
| `notes/` | Working notes. Markdown is canonical; the two `.docx` are rendered copies of `continuity-flags.md` and `character-voices.md` for reading away from the repo. |
| `reference/` | `The Calamity Lore Compendium.docx` — the game lore the world is built on. Not followed to the letter and not copied; see `notes/world-and-lore.md` for what was taken and what was changed. |
| `archive/2026-09-notes/` | The September snapshot of the notes, kept whole. Superseded by `notes/` but nothing thrown away. |

## Where to start

- **`notes/continuity-flags.md`** — every contradiction, continuity error and editing artifact found so far, with chapter and paragraph references. This is the live to-do list.
- **`notes/character-voices.md`** — how each character talks and behaves, taken from a full read. Read before writing a scene.
- **`notes/story-so-far.md`** — chapter-by-chapter summary of everything written, plus the Ch 26 notes that aren't prose yet.
- **`notes/working-with-party.md`** — the process. Beats and critique first, approval, then prose. Dialogue is never changed.

## Reference convention

Issues are cited as `Ch12 ¶347` — chapter 12, the 347th non-blank paragraph after the chapter heading. **Chapters are numbered by position in the document, not by what the heading says**: the 16th chapter's heading currently reads "Chapter Fourteen". Per-chapter paragraph counts are in `notes/chapter-index.md`.

## State of the draft, 10 October 2026

- Ch 1–25 written. Ch 26 exists as notes only.
- Ch 1–10 revised. **The revision eliminated the dominant AI tic completely** — "the specific [noun] of [noun]" went from 407 instances to zero across those chapters, with the two drafts within 5% of each other on length. 683 instances remain across Ch 11–25. The em-dash clauses were not touched (647 → 633).
- Terminology sweep outstanding: 132 "mana" → arcana, 24 "life force" → anima, across Ch 8–25.
- Six chapters are set in italics nearly end to end (Ch 21 at 100%), which kills the marking of scripture, prayer and memory fragments. Formatting fix, not a writing one.

## Also stored outside the repo

The "The Shortsword" project on claude.ai mirrors `notes/`. As of 10 Oct 2026 **this repository is the source of truth** and the project docs are the mirror, not the other way round.

The three Google Docs the `.docx` files came from still exist. Once the Google Docs connector is installed, those can be worked directly.
