# Decisions Log

A running record of story and project decisions, newest last. One entry per decision: what was decided, when, and why.

## 2026-10-05 — Project setup

- **GitHub:** Private repo `blindsniper1475/the-abandoned-horizon`, repo-local git identity (noreply email). Whole project (chapters, scenes, bible, notes) is versioned; `dist/` and story-lock files ignored.
- **Tooling:** `story` CLI at `%USERPROFILE%\.agents\skills\story-maintenance\scripts\story.js`. After every drafting session: `wordcount --write`, `reindex`, `continuity`, `links`, `validate`.

## 2026-10-05 — Chapter 2 drafting decisions

- **Time:** Chapter 2 happens the same night as Chapter 1 (loop 1, day 1, `time: night`). The group leaves the common room after the flicker to find beds; there is no time skip and no daylight.
- **POV:** Elena Hayes (per chapter registry). Her reporting voice narrates when she's frightened; she writes everything down — the notebook is the chapter's spine.
- **Ledger:** The library circulation ledger is dated **eleven days before arrival**, kept by hand in an unknown upright hand. This is Alex's maintenance/sign-in trail — planted here, not explained until the archive material surfaces (Ch 3–6). Names are copied into Elena's notebook but not recognized.
- **Five rooms:** Exactly five of fifty gallery doors are unlocked and made up — matching five respondents to a letter that went to sixty. 107 is made up, lamp left burning, no one claims it (reserved for Alex; never stated on page yet). Room assignments: M+E 103, David 105, Sarah 109, Jake last door before the stair.
- **Duress first step:** Elena's post-greenhouse symptoms (chest warmth, ache behind the eyes) are logged as symptoms, attributed to travel, told to no one. Stage names and percentages are never spoken in prose — sensation only, per the locked prose rule.
- **Chapter hook:** Question — *How did they know it would be five?*

## 2026-10-06 — Chapter 1→2 continuity pass

- **Seam reinforcement:** Ch 2's opening now names the flicker's location (thirty yards, near the east-wing door) and echoes Marcus's "bad lightbulb" line and Jake's toast from Ch 1's closing scene, so the same-night handoff is explicit.
- **Fixes:** Removed Elena's "as of four hours ago" snow measurement in Ch 2 (she had no way to know; David's radar already covers the storm forecast). Corrected "she had driven nine hours" → "ridden nine hours in the cab of a truck" (Marcus drives; established in Ch 1).
- **Metadata:** Ch 2 `word-count` updated to 3496 after edits.
- **Note:** Dialect drift found between chapters (Ch 1 uses American spellings: color, yards; Ch 2 uses British: colour, metres, realise/recognise). Style sheet dialect is `unspecified`; flagged for an author decision, not yet normalized.
## 2026-10-07 — Dialect decision + style sheet filled in
- **Dialect:** Author chose **American English** as house dialect. Style-sheet frontmatter set to `dialect: american` with variant pairs (gray/grey, color/colour, realize/realise, recognize/recognise, behavior/behaviour) and imperial-units rule (yards/feet/miles; floors, not storeys).
- **Sweep:** Ch 2 normalized to American (colour→color, metres→yards ×4, storeys→floors ×3, realised→realized, recognise→recognize); Ch 1's two stray `grey` → `gray`. Both chapters now grep-clean for British variants. Ch 2 `word-count` updated to 3558 (prose section only).
- **Voice register:** Author defined the target style as **Stephen King foreground over Lovecraft background** ("a picture between the two"). Codified in the style sheet Voice section: King layer speaks (dialogue, interiority, domestic detail), Lovecraft layer is only seen (architecture, geometry, scale); no eldritch vocabulary, no explanation of the mechanism. Samples quoted from ch 1–2.
- **Style sheet:** Filled all empty sections (voice, spelling/usage, hyphenation, numbers, dialogue/punctuation, character voices, watch list). Character voice entries verified against character sheets (Marcus = Texas Ranger, Elena = journalist, David = systems analyst, Sarah = brand/modeling, Jake = photographer).
