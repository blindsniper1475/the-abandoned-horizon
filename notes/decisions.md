# Decisions Log

A running record of story and project decisions, newest last. One entry per decision: what was decided, when, and why.

## 2026-10-05 — Project setup

- **GitHub:** Private repo `blindsniper1475/the-abandoned-horizon`, repo-local git identity (noreply email). Whole project (chapters, scenes, bible, notes) is versioned; `dist/` and story-lock files ignored.
- **Tooling:** `story` CLI at `%USERPROFILE%\.agents\skills\story-maintenance\scripts\story.js`. After every drafting session: `wordcount --write`, `reindex`, `continuity`, `links`, `validate`.

## 2026-10-05 — Chapter 2 drafting decisions

- **Time:** Chapter 2 happens the same night as Chapter 1 (loop 1, day 1, `time: night`). The group leaves the common room after the flicker to find beds; there is no time skip and no daylight.
- **POV:** Elena Hayes (per chapter registry). Her reporting voice narrates when she's frightened; she writes everything down — the notebook is the chapter's spine.
- **Ledger:** The library circulation ledger is dated **eleven days before arrival**, kept by hand in an unknown upright hand. This is Alex's maintenance/sign-in trail — planted here, not explained until the archive material surfaces (Ch 3–6). Names are copied into Elena's notebook but not recognized.
- **Five rooms:** Exactly five of fifty gallery doors are unlocked and made up — matching five respondents to a letter that went to sixty. 107 and 109 are made up, lamps left burning, no one claims them (the extra beds read as kept ready; reserved-for-Alex never stated on page). Room assignments: M+E 103, David+Sarah 105 (married couples share), Jake last door before the stair; 107 and 109 left empty.
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

## 2026-10-07 — Style sheet completed in full + repo gap audit

- **Style sheet:** every remaining stub section filled. Added: dialect pairs (toward/traveled/while/among/check/airplane), enforceable `watch-words` (wrongness, flatness, seemed, felt) with per-chapter budgets and measured Ch 1–2 baselines (2/0/0/7), `samples` pointing at chapters 1–2 so `story prose` compares against approved voice; Capitalisation rules (sentence case in prose, no emphasis capitals); expanded Hyphenation (em/en dashes, ellipsis policy, no exclamation points in narration, white-out/all-terrain/sub-basement/non-Euclidean forms); Numbers & Time (bare room numerals, conversational time estimates, relative dates, 20-years/15-years anchors); Dialogue mechanics (interruption paragraph rule, contractions as register flag, swearing budget tracked like a resource); Naming & Address rules verified against Ch 1–2 (first names only in narration; **no nicknames established** — corrected an earlier draft note that claimed Marcus says "El"; Hayes/Keller surname-drift warning); new **Terms** section codifying the locked no-explanation rule as a hard banned-word filter with on-page substitutes; POV discipline (one POV/chapter, never Alex, free indirect discourse default); Chapter Mechanics (3,000–4,500 words/chapter → ~80–95k target, frontmatter must be filled, hook lands in final third, outline beats stay as revision spine); Session Checklist; Open Style Questions (epigraphs, dinkus breaks, photo captions, real vs fictional Alaska geography, Ch 24 register).
- **Repo gaps found during audit (not yet fixed):** glossary registry empty (Buffer/De-Rez/Retention/Echo/Void/Noise/Loop/Custodian/Abscissa all need entries — invented terms belong there per style sheet); characters/_index.md relationship map empty (two marriages + Alex/class ties undefined); world overview paragraph empty; scene cards for Ch 3–24 missing POV fields; promise/clue registries list planted-in chapters (12, 3) ahead of drafts — fine, but they'll validate-fail until those chapters exist; chapter 1 frontmatter `time:` empty (should be night→arrival sequence decision); `mode:` field unused everywhere.
- **Note:** Abscissa Industries appears zero times in chapters 1–2 — consistent with the letterhead-only rule now written into the style sheet.

## 2026-10-07 — Author canon update + gap-filling pass

- **Canon (author-stated):** Two marriages only — Marcus & Elena (Texas), David & Sarah (Oregon). Marcus is a **cop** (not a Ranger); Elena is a **reporter/investigator**; David is an **analyst**; Sarah is a **fashion model**. Applied to character sheets and style sheet.
- **Ch 1 fix:** The firelit-conversation paragraph previously said Sarah and David were married "once, briefly, years ago" — contradicts current canon. Rewritten: they are three years into their marriage. (Interpretation adopted: the Kellers remarried each other later in life; if the author means something different, this line is the one to revisit.)
- **Occupation sweep:** "Texas Ranger"/"ranger" removed from marcus-hayes.md and style-sheet.md; Marcus's sample line using nickname "El" deleted (contradicts the no-nicknames address rule). British spellings in bible files normalized to American (grey/color/floors etc.).
- **Glossary filled:** 15 entries created (Buffer, De-Rez, Retention, Echoes, Loops, Void, Noise, Rot, Custodian, White-Out, Synthesis, Abscissa Industries, Archive School, Clock Tower, Key Ring) — each with bible definition + on-page usage rule enforcing the no-explanation prose law. Registry table populated.
- **Character registry:** Relationship Map filled (both marriages, friend web, Alex-as-adversary per person, the sixty→five summons link) + Family Trees section (households, no children on page, do-not-invent guardrails).
- **World overview:** written in worldbuilding/_index.md.
- **Scene cards:** POV + location fields filled for Ch 3–24 from chapter frontmatter rotation.
- **Chapter 1 frontmatter:** `time: night` set (arrival through firelight is one night). Word counts recomputed after edits (ch1 ~3120, ch2 see frontmatter).

## 2026-10-07 — Canon reconciliation pass (rethink of Ch 1–2 against new details)

**Note:** the previous session's summary claimed a commit (`52490a6`) applying Chris/Ranger/five-year canon; that commit does not exist in this repo's history and the files never contained those changes. This pass applies the full canon for real, from the current file state.

- **Chris confirmed by author:** Marcus & Elena's son is named **Chris, 13**, off at summer camp in Texas with another family's kids — the reason the Hayeses could say yes to Alex's letter. Added to Ch 1's firelit-conversation paragraph (the only safe on-page slot: Ch 2's POV scenes have no natural opening, and Marcus's dialogue there is about the school). Family-tree guardrail rewritten: Chris may be referenced by parents, never introduced live, no plot hinges on him until the author decides. The old "Alex is mentioned-only until Ch 6" rule is unaffected — Chris is a different character; the bible's "Alex" remains the Custodian.
- **Marcus = Texas Ranger restored** (author's correction): character sheet backstory + timeline + style-sheet voice entry now say Ranger — small posts, trail crews/detail work, training cadre; working practically since high school. His shoulder scar given an in-canon origin (horse accident on the trail).
- **Marriage math fixed everywhere:** Hayes ~15 years (married the summer after graduation), Keller ~5 years. Ch 1: both "twenty years of marriage" → "fifteen years"; firelit paragraph now says fifteen/five (was three). Ch 2: Elena's research files twenty → fifteen years (×2). Character timelines rebuilt: David married five years ago (recruited practically out of high school); Sarah started modeling right after high school, married five years ago; Jake clean ~5 years ago, eleven months sober by his own chip count (author-approved reading: rehab stints through most of the drift years, final sobriety recent).
- **Elena's career** dated: started a little after the wedding (~14 years in); her ghost-wound/location lines reworded so "twenty years" no longer implies a twenty-year career.
- **Jake** backstory now carries the rehab-centers history explicitly (drugs and alcohol), matching Ch 1's new on-page mention.
- **Continuity state:** new "Off-Stage Facts" section locks Chris, marriage lengths, Jake's sobriety, and all four occupations as reference-only canon.
- **Word counts recomputed:** Ch 1: 3,295 / Ch 2: 3,513 (prose sections).


## 2026-10-07 — Chapter 3 drafted (The Archive Vaults, Sarah POV) per author direction

- **Author brief:** dossiers carry post-graduation info — relationship status, address, work status, notable events, family ties. Reading order locked by author: Jonas → David → Marcus → Elena → Sarah (second to last) → Alex (last). The J-name classmate is named **Jonas Fells** (author couldn't recall; flagged for confirmation).
- **Retention scores locked** (clue file): Fells 88 (never came), Jake 85 (pre-existing Ch 21 canon), Sarah 84, Marcus 81, David 79, Elena 73, Alex 100. Band 73–88 preserved; several classmates scored higher than any of them and never came — planted as foreshadowing in-bible only.
- **On-page handling of banned terms:** *retention* appears only inside diegetic artifacts (Sorensen's blackboard word, dossier column headers via numbers); no character or narration uses it. *Custodian* arrives through a document (Alex's occupation line), per style-sheet rule — Ch 6's formal naming stays intact. *Abscissa* appears once, on a brass property plate at chapter end, never spoken.
- **Jake's folder deliberately unopened** — his number stays off-page; Ch 21 payoff protected.
- **Chris Hayes** appears in Marcus's dossier as a family-tie line item (document context only; off-stage rule intact). Beats the parents hardest; kept one sentence, no speech about it.
- New facts planted: Elena's *survived exposure event, site unknown, age 16* (hooks her Ch 2 greenhouse eye-ache; payoff owned by later drafts — flag for author); Sarah photographed annually since nineteen, marked *holds well*; Amarillo bar fight — never reported to any precinct — is on file anyway; fixed mid-draft from an impossible four-days-ago date because dossiers were updated pre-arrival; Alex's stack dated yesterday, red 100%.
- Registry/state updated: chapters/_index (draft, 3,039 words), continuity state advanced to current-chapter 3 with knowledge rows, question evidence added, scene card filled (purpose/beats/continuity notes). Watch-words all zero in Ch 3 prose. Length 3,039 — low end of band; expansion pass optional.

## 2026-10-07 — Adaptation roadmap added (author intent: audiobook/audio drama/YouTube/TV, AI-assisted)

- **Author statement (off-topic note):** after the book is finished, wants to adapt it — TV series or YouTube series, and/or audiobook/audio drama; plans AI generation for assets. Recorded in `notes/adaptation.md` as a phased plan (A: audiobook, B: audio drama, C: visual/motion-comic YouTube, D: TV pitch), priority order per author's phrasing.
- **Decision:** book stays first; no prose changes made to serve future formats. The roadmap file documents which existing craft rules already make the manuscript adaptation-friendly (5-beat scenes, single POV, dialogue-forward register, contained setting) and which canon anchors must survive every adaptation (Chris never on-page, Alex voiceless/faceless before Ch 6, Jake's dossier unleaked, locked retention numbers, American dialect/imperial units).
- Repo structure unchanged; script folders (`adaptations/`) will be derived from finished chapters only when production actually starts.

## 2026-10-07 — Room-sharing arrangement (author directive)
- Married couples share rooms: Marcus+Elena in 103, David+Sarah in 105. Motive is comfort/safety, not trust in the building — "familiar place, but not familiar place." Jake keeps his own room at the end before the stair.
- The two leftover made-up rooms are now 107 AND 109 (lamps burning, unclaimed). Five beds for five people still holds; two spare rooms instead of one — deepens the "kept ready" wrongness.
- Chapter 3 opening adjusted ever so slightly per author note: Sarah's cold coffee moved from desk/outside-the-door to the nightstand between the two beds in 105. New implication: whoever left it came INTO the room while they slept. Sarah's "did not say that part downstairs" beat preserved and sharpened.
- Scene card, continuity state, and this log updated accordingly.

## Session note — Ch 3 opening revised (author direction)
- Sarah wakes ALONE in 105; David is already downstairs by the dead fire talking with Elena about what they found yesterday.
- The coffee on the nightstand was brought by DAVID (he carried it up during the night). Sarah does not know this and never asks. Old implication (unknown intruder entered the room) replaced with a warmer-but-oddly-specific one: mug ring says it sat steaming a long time, thermos poured to her exact line, David's bed made up tight, no sign he slept.
- Downstairs beat adjusted: Elena and David break off mid-sentence when Sarah enters — small shared-secret texture, POV-safe (Sarah infers, states nothing).
- Word count updated: 3205.
