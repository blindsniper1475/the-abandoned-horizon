---
type: style-sheet
dialect: american
preferred:
  - use: gray
    avoid: grey
  - use: color
    avoid: colour
  - use: realize
    avoid: realise
  - use: recognize
    avoid: recognise
  - use: behavior
    avoid: behaviour
  - use: yards
    avoid: metres
  - use: floors (of a building)
    avoid: storeys
  - use: toward
    avoid: towards
  - use: traveled
    avoid: travelled
  - use: while
    avoid: whilst
  - use: among
    avoid: amongst
  - use: check (verb)
    avoid: cheque
  - use: airplane
    avoid: aeroplane
watch-words:
  - wrongness
  - flatness
  - seemed
  - felt
allow-words: []
samples:
  - chapters/chapter-01.md
  - chapters/chapter-02.md
---

# Style Sheet

The book's house decisions, kept the way a copyeditor keeps them. Read this before drafting or revising prose. `story prose` enforces the lists in the frontmatter: `dialect` (british, american, or unspecified) flags the other dialect's common spellings, each `preferred` entry flags its `avoid` form, `watch-words` are counted in every chapter, and `allow-words` silences a built-in filter word or adverb. Add a `samples` list of your own prose (`../book-one`, approved chapters) and `story prose` compares each chapter with it instead of fixed limits.

## Voice

**The register is King over Lovecraft — a picture between the two.** The foreground is Stephen King: ordinary midlife people, marriage friction, jobs, small talk, brand names and trade talk when it fits, humor that dies mid-joke; dread arrives through character and place, one domestic wrongness at a time. The background is Lovecraft: vast indifferent architecture, geometry that doesn't compute, the sense of a scale the characters cannot hold in their heads and will never be able to explain. The rule for blending them: **the King layer speaks, the Lovecraft layer is only ever seen.** Dialogue, interiority, and the concrete sensory world stay warm, colloquial, specific; the uncanny stays impersonal, wordless, and never anthropomorphized. No eldritch vocabulary (no *cyclopean*, no *blasphemy*, no *indescribable*), no capital-G Evil, no explanation of what the school actually is. The horror is loss of resolution, not a monster with intentions. One borrowed device from each side, both already visible in chapters 1–2: King's habit of letting narration digress into the character's real life (jobs, marriages, the yearbook photo) before returning to the room; Lovecraft's slow arithmetic of wrongness (counting distances, checking dates, finding the numbers refuse to close).

Narrative distance: third-person limited, tight on the chapter's POV character, past tense. Their professional habits are the narration's habits — Elena documents and maps and writes the numbers down, Marcus reads hazards and counts doorframes, David thinks in logs — so the weird registers first as a measurement or a count that refuses to sit still.

Sentence rhythm: long additive paratactic sentences built with *and* and em-dashes for rooms, weather, and wrongness (King's run-ons), then short declarative sentences for the beat that lands ("It wasn't." "Stop."). Triplets for description, two items for the turn. Concrete nouns dominate; adjectives do light work. Repeated anaphora (*"The first was locked. The second was locked."*) is welcome in moderation, as are direct addresses of the wrongness in plain words — *wrongness*, *flatness* — because the characters have nothing more precise.

Never does this prose: explain the mechanism (the Buffer, De-Rez, retention, loop mechanics stay out of the pages entirely); editorialize or wink at the reader; use Gothic stock phrases; let the POV character articulate the theme. Quote three sentences that sound exactly right (all from chapters 1–2):

> It was a fortress: high walls, few windows on the lower floors, everything designed as much to keep things in as to keep things out.

> Everything you looked at directly was in shadow. Everything in the corner of your eye was bright.

> Not wind down. Stop. Like a held breath.

## Spelling And Usage

American English throughout — `dialect: american` in the frontmatter, enforced by `story prose`. Chapters 1 and 2 were swept to American spellings on 2026-10-07; keep every new draft in the same dialect. The established variants are in the frontmatter list (`gray`, `color`, `realize`, `recognize`, `behavior`). Units are imperial: **yards, feet, miles, Fahrenheit** — the setting is Alaska and the cast is American. Never metres, kilometres, or Celsius in narration or dialogue. Building levels are *floors*, not storeys.

## Capitalisation

- **Sentence case everywhere in prose.** No emphasis capitals for effects: *the storm*, not *the White-Out*; *a re-boot*, not *a Re-boot*. The in-world machinery is never capitalized on the page because it is never named on the page (see Terms).
- **Proper nouns only:** character names (Marcus Hayes, Elena Hayes, Alex Voss), places as named facilities (*the school*, *the library*, *the greenhouse* are lowercase common nouns in narration; *Archive School* appears capitalized only in formal/document contexts — letterhead, signets, official records), institutions (*Abscissa Industries* — but see Terms: the name appears only on paperwork, never in speech).
- **Chapter titles** are title case in registries and headings (*The Arrival*, *The Sanctuary*), never referenced inside prose.
- **Document text quoted inline** keeps whatever capitalization the document has — the ledger's upright hand, the letter's courteous phrasing. That is diegetic, not house style.
- Job titles are lowercase unless used as a direct address or formal signature (*the cop said*; a letter signed *Custodian* is the document's choice, not narration's).

## Hyphenation And Compounds

- **Em-dashes spaced** (word — word), never closed up; they carry the appositional, additive rhythm of the long sentences. No en-dash parentheticals in narration; em-dash or comma only.
- Ranges and dates use *en* dashes (`2026–2027`, `Ch 7–9`) — that's registry/bible style; in prose, characters say ranges in words (*ten to twelve times*).
- **Ellipses are unspaced with a closing quote/period as needed** (*…*) only in fading voices and text artifacts; three typed periods with spaces is not house style. In print prose prefer the full stop and a new short sentence — the rhythm does the fading.
- **No exclamation points in narration**; sparingly in dialogue, mostly Jake's forced jokes (a joke that lands an exclamation point is a joke that isn't landing).
- Compound modifiers hyphenated before the noun (*white-out*, *bad-lightbulb energy*), open after. *White-out* is hyphenated as noun and modifier (never *whiteout*); *all-terrain*, *hand-crank*, *dehydrated* stay as chapters 1–2 have them.
- Prefixes: *re-boot* is hyphenated (Alex's register; the mechanism is never named on the page anyway); *sub-basement* closed; *non-Euclidean* hyphenated with capital E — bible/notes only, never narration.
- Never split infinitives anxiously, but don't legislate against them; King splits them when the rhythm wants it.

## Numbers, Dates, And Time

- **Spelled out in narration and dialogue:** one through twenty (*five respondents*, *nine hours*, *twelve towers*). Measurements, ages-as-units, and money stay numeric when precision is the point (*two hundred yards*, *sixty letters*, *thirty-eight years old*).
- **Numbers above twenty** spelled out in casual speech and thought, numeric when someone is counting or measuring for real. Elena writes digits; Jake says *thirty seconds*; nobody says *twenty-three* aloud unless the exact number matters.
- **Room numbers are numerals**, always bare, never "Room" before them in narration: *103*, *105*, *107*. Ledger entries reproduce as digits with periods, as artifacts: *101. 102. 103.*
- **Times of day** are conversational estimates — *an hour before dark*, *the small hours*, *somewhere past midnight*. No digital-clock readouts in narration; no watch in this cast keeps reliable time (established Ch 1–2). Frontmatter `time:` fields use the plain names: `night`, `day`, `dawn`.
- **Dates** in prose are relative (*eleven days before arrival*, *twenty years ago*); absolute calendar dates appear only inside documents, formatted as the document has them. The reunion letter's date, if it ever shows, is Alex's format: handwritten, courteous, faintly administrative.
- **Ages and decades:** *twenty years after graduation*, *fifteen years abandoned* — keep these two anchors exact; they are load-bearing facts (see continuity state).
- Ordinals in prose: *first, second, third* spelled out; higher ordinals numeric in documents only.

## Dialogue And Punctuation

- **Double quotation marks**; commas and periods inside the quotes (American convention). Question marks and exclamations go inside when they belong to the quoted speech, outside when they belong to the frame.
- **Paragraphs:** new speaker, new paragraph — except deliberate overlaps, where an interruption is rendered by closing one quote with an em-dash and opening the next speaker's quote in the *same* paragraph (*"You don't think I—"* *"I think we should talk about—"*). This is the only exception; stress scenes should use it, calm scenes never do.
- **Tags are plain** — *said*, occasionally *asked*; never *exclaimed*, *muttered*, *replied*, *retorted* as tag verbs. Beat-action replaces tags freely (David checked his phone again. "It says no signal for eleven miles."). Attributed first line of a scene, then unattributed exchange is fine once the speakers' rhythms make them identifiable.
- **Italics** for a single stressed word in dialogue or thought (*Stuttered.*), and for artifacts quoted inline (*out*, *101. 102. 103.*). Never whole paragraphs of italic thought; interiority runs unquoted and unitalicized at narrative distance, so a character's thought reads like narration until its diction gives it away.
- **Contractions in all speech and close third-person** — this cast talks contracted (*don't, wasn't, it's*) and the narration sits tight enough to think contracted too. Uncontracted speech is a flag: someone is formal, frightened, or performing (Alex's letter register, strangers on the phone).
- **No semicolons in dialogue.** Narration may use one only if the rhythm demands; usually an em-dash or full stop does.
- Characters talk past each other under stress: interruptions, non-sequiturs, jokes that die mid-joke, trade shorthand nobody explains to the reader. Marcus speaks in inspections and counts; David in logs and timestamps; Sarah in careful questions; Elena in measurements she refuses to round; Jake in camera language he knows is a defense mechanism.
- **Swearing:** King-scale mild is available (*hell, damn, son of a bitch* for Marcus) but rare before Act II; the five are polite people whose politeness erodes measurably as the loops accumulate — track it like a resource.

## Character Voices

One entry per POV character or major speaker: vocabulary, sentence length, verbal tics, and words they never use.

- **Marcus Hayes** (POV 1): cop, twenty years in Texas — precinct work, then state detail, then the training cadre. Short declaratives, procedure vocabulary, counting compulsions, held lines. Says *load*, *rating*, *egress*, *not right*. Never says *haunted*; he says *someone signed off on this*.
- **Elena Hayes** (POV 2): reporter and investigator — bylines on paper, but the real work is records, files, and local histories everyone else gave up on. Medium-long sentences with embedded clauses; documents everything, writes the numbers down, then underlines the number that fails. Voice words: *record*, *verify*, *when*. Avoids *probably fine* like a landmine. Never uses mystical language for space.
- **Sarah Keller** (POV 3+): fashion model turned brand work — funds artists now, lives in Oregon with David. Poised, precise, asks the question everyone avoided in a flat voice. Describes everything visually, feels nothing about it on the page. Deflects with competence.
- **David Keller** (POV 4+): systems and security analyst in Oregon ("a firewall with a payroll"), married to Sarah. Speaks in diagnostics: he doesn't ask how someone feels, he asks what changed. Timestamps, self-corrections mid-sentence, narrates probabilities out loud when rattled. Dryly funny without trying.
- **Jake Mercer** (POV 5+): freelance photographer. Frames things — *composition*, *light*, *thirty seconds* — jokes to dissolve dread; the jokes get thinner as the book goes on. The sharpest memories of the five, and the emptiest life.
- **Alex Voss** (never POV, mentioned until Ch 6): letter register — formal, dated, oddly courteous, faintly administrative. His warmth reads as *scripted*.

### Naming And Address Rules

Verified against chapters 1–2 and locked from here forward:

- **Narration:** first names only — Marcus, Elena, Sarah, David, Jake, Alex. Surnames appear only in documents (the ledger, the letter, class records) and in formal register moments. No middle names exist; never invent one.
- **Spouses:** the two married couples are Marcus & Elena Hayes and David & Sarah Keller. Spouses address each other by full first name, exactly as established in chapters 1–2 — no nicknames have been used yet, and none should be introduced casually; if Marcus ever starts calling her something else, it is a scene-worthy change of register, not a stylistic freebie. Nobody shortens Sarah or David. Jake is *Jake* to all.
- **Couple shorthand in notes/bibles:** "the Hayeses" and "the Kellers" — but avoid collective references in prose; the five are always counted individually (counting is the house rhythm).
- **Last-name drift watch:** both couples share surnames internally (Hayes/Hayes, Keller/Keller), so mis-tagging a surname is the most likely continuity error in dialogue tags. `story prose` can't catch this; check every new draft by hand.
- **Abscissa:** no character has said the word aloud yet, and none should until paperwork forces it into speech (Ch 3+, at most once, flatly). The name lives on letterhead and forms.
- **Pronunciation note for read-aloud copy:** Abscissa = ab-SISS-uh; Voss rhymes with "loss."

## Terms — Bible Vocabulary That Must Not Appear In Prose

The locked rule from story.md, restated as a hard filter. These words belong to the world's own taxonomy; the characters have no access to it, so the narration doesn't either. **Never in dialogue or narration:** *Buffer*, *De-Rez*, *retention*, *Echo* (as a noun for the phenomena), *the Void*, *the Noise*, *the Rot*, *Custodian* (until the role is named obliquely in Ch 6 — see chapter registry hook "The Custodian is named"; even then, the naming scene must arrive at the word through a document, not a mouth), *loop* (they do not know they repeat), *re-boot*, *resolution* (in its technical sense — "low resolution" as camera talk from Jake is allowed and encouraged as cover), *Archive* (lowercase *archive* as an ordinary noun for the vaults is fine; capitalized as a system name is not).

**On-the-page substitutes** (what they actually say when the phenomenon presses): *flat*, *wrong*, *washed out*, *unfinished*, *stuttered*, *the light was the wrong color*, *the hallway took four steps longer*. Sensation only, measurement only, arithmetic only. If a draft needs one of the banned nouns to make sense, the draft is telling instead of showing — cut and re-stage as a count or a distance.

## POV And Tense Discipline

- Third-person limited, past tense, tight on the chapter's registered POV (see chapters/_index.md). One POV per chapter, never more; rotating across the five friends in registry order.
- **Never Alex's POV.** Not even a cold open, not even the epilogue.
- Head-hopping is banned inside scenes; POV shifts happen only at chapter breaks. A non-POV character's face is external data the POV character reads — and can be wrong about.
- Free indirect discourse is the default interior mode: no *he thought that* framing tags unless distancing is wanted for irony or comfort.

## Watch List

Why each `watch-words` entry is in the frontmatter, and what a rising count means. `story prose` counts these per chapter; the budgets below are Act I numbers — tighten them again when Act II drafts exist.

- **wrongness** — load-bearing in chapters 1–2 (the flicker, the maze). Budget: ≤2 per chapter. It names the uncanny in plain words exactly once per appearance; a third use means the narration is explaining instead of showing. Current baseline: Ch 1 + Ch 2 combined = 2. ✓
- **flatness** — story.md's sanctioned sensation word for decay. Not yet used on the page; reserved. When decay accelerates (Act II+), *flat* as adjective stays preferred over the noun. Budget: ≤1 per chapter. Current: 0. ✓
- **seemed** — hedge-word. The five measure; they don't seem. If a sentence needs *seemed*, it usually needs a number instead (*took four steps longer*). Budget: ≤2 per chapter. Current: 0. ✓✓
- **felt** — King's own crutch and this book's most likely slip (*felt the old weight*, *felt the wrongness*). Emotion should arrive through action and body-sensation, not *felt*. Budget: ≤4 per chapter (some literal touch-use is fine — *felt the doorframe*). Current: Ch 1–2 combined = 7; acceptable for Act I warmth scenes, but watch it drop from Ch 3 onward.
- **uncanny** — deliberately NOT on the list yet because it has never appeared; if it ever does, that's a red flag by inspection, not by count. Keep out of prose entirely (it's critic vocabulary, not character vocabulary).

**Filter words to keep out without tooling help:** *eerie, eerie silence, dread settled, spine tingled, cold blood, unspeakable, ancient evil, shadow moved*. Gothic stock — banned outright in the Voice section; add any that recur to `watch-words` rather than arguing with them in notes.

**Baseline counts recorded 2026-10-07** (prose sections of chapters 1–2): wrongness 2, flatness 0, seemed 0, felt 7. Re-measure after every revision pass so drift is visible against the budget, not against memory.

## Chapter Mechanics

House rules for the chapter files themselves, so every draft is built the same way:

- **Length target:** 3,000–4,500 words of prose per chapter (current baseline: Ch 1 = 3,067; Ch 2 = 3,558). Twenty-four chapters at that band lands the book around 80–95k. One scene card per chapter currently — a chapter may hold more scenes than its card lists if the beats demand it, but update `scenes/` to match before drafting.
- **Frontmatter:** fill every field before drafting; no empty strings left behind. `time:` takes one of `dawn`, `day`, `dusk`, `night`; `date:` stays empty in-loop (the characters don't track calendar dates) unless a document pins one; `mode:` is unused — delete it or define it, don't leave blanks spreading. `hook:` takes `question` or `revelation` and the hook must land in the final third of the chapter.
- **Outline section:** the numbered beat list stays in the file after drafting — it's the revision spine, not scaffolding to delete. Beat tags (`[Location:] [Character:] [Theme:] [Arc beat:] [Foreshadowing:]`) are required per beat and must match what the prose actually contains.
- **End-of-chapter contract:** every chapter ends on its registered hook and on the group's physical position changing (they move, decide, or are moved). No chapter may end in static conversation — that's how serial momentum dies.
- **Word count maintenance:** update `word-count:` (prose section only, excluding frontmatter/outline headings) in the same commit as the edit; registry totals in `chapters/_index.md` come from `story wordcount . --write`.

## Session Checklist

What "done" means after any drafting or revision session, in order:

1. `story validate` — schema and links clean.
2. `story wordcount . --write` — registry and per-file counts agree.
3. `story continuity` — then hand-update `continuity/state.md`: character/object/knowledge state as of `current-chapter` only, nothing later.
4. `story prose` — dialect pairs, watch-word budgets vs. the Watch List baselines, sample comparison against Ch 1–2.
5. New clues/questions/promises get their own files + registry rows; resolved ones get closed, not deleted.
6. Decisions logged in `notes/decisions.md` (what, when, why — newest last).
7. Commit with a message naming the chapter(s) touched.

## Open Style Questions

Deliberately unsettled; each needs an author decision, not a guess:

- **Epigraphs:** should chapters open with quoted fragments (ledger lines, letter excerpts, Abscissa paperwork)? Strong King habit, and this book has the artifacts for it — but it risks pre-explaining. Recommendation: allow only *after* Ch 6, never for POV-critical reveals. Decide by Act II.
- **Section breaks inside chapters:** asterism/dinkus vs. running continuous prose (current practice: continuous). If chapters grow past ~4,000 words with location changes, adopt `* * *`.
- **Jake's photographs:** do images ever appear as described captions set off from prose? Currently everything is narrated. If captioned artifacts enter, they need their own formatting rule here first.
- **Alaska place names:** keep real geography (Anchorage, the coast road) or fictionalize alongside the school? Chapters 1–2 stay vague (*nine hours north*, *the coast*). Lock one way before Ch 6's gatekeepers bring outsiders into range.
- **Chapter 24 register:** Re-Stabilization is epilogue-shaped — does it keep the full voice discipline (still King/Lovecraft blend, still no explanation) or is a slight warmth shift allowed after they escape? Decide before outlining it; recommend keeping the bans and letting only the weather change.
