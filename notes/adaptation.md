---
title: "Adaptation Roadmap"
type: note
status: active
created: 2026-10-07
updated: 2026-10-07
---

# Adaptation Roadmap

Purpose: keep the book-first pipeline **adaptation-ready** without letting adaptation concerns distort the prose. Decisions here are reversible until Act II is drafted; nothing in this file overrides `style-sheet.md` or `notes/decisions.md`.

## Target formats (author-stated, priority order)

1. **Audiobook** — single-narrator, the cheapest and earliest win.
2. **Audio drama** — full cast + sound design; the natural second step.
3. **YouTube series** — likely motion-comic / narrated-visual format first; live action only much later, if ever.
4. **TV series** — long-shot; treat as a pitch asset, not a production plan.

All generation may be AI-assisted (voices, music, SFX, visuals), but every output gets an author pass before shipping. The bible stays the single source of truth for all of it.

## Why the book is already adaptation-friendly

- **Locked 5-beat scene structure** per chapter = clean act breaks for episodic formats.
- **Strict single-POV discipline** = narrator/casting is unambiguous per chapter; POV rotation (Ch 1–3: Marcus → Elena → Sarah) gives each episode a lead.
- **Dialogue-forward King register** = scenes play with voices alone; almost no interior monologue that resists audio.
- **The no-explanation law** (mechanism never stated on page) = audio drama can't cheat either; dread lives in sound design gaps, which suits the medium.
- **Contained setting** (one brutalist school, twelve towers) = one standing set/location package.

## Canon anchors that must survive every adaptation

| Anchor | Book rule | Adaptation consequence |
|---|---|---|
| Chris, 13, off-stage at Texas summer camp | Referenced by parents, never appears live (relationship-map guardrail) | Never cast him; his absence is load-bearing |
| Alex Voss mentioned-only until Ch 6 | No face, no voice before Ch 6 | Audio formats: no Custodian voice/SFX signature earlier than Ch 6 |
| Jake's folder unread (Ch 3 planted) | Payoff reserved | Don't leak his dossier art/audio in promo material |
| Retention scores locked (88/85/84/81/79/73/100) | Canon numbers | Any on-screen document inserts must match exactly |
| American dialect + imperial units | Style sheet | Voice artists read American; no metric conversions in props |
| King speaks / Lovecraft is only seen | Style sheet voice rule | Audio: human warmth in dialogue, coldness in ambience. Visuals: vast indifferent architecture, never a monster close-up |

## Format notes

### Audiobook (Phase A)
- Single narrator; differentiate POVs via pacing, not accents (matches dry understated tone).
- Chapter frontmatter `word-count` ≈ runtime math (~9,300 wpm finished prose → ~1 hr per 5–6 chapters at current lengths).
- Preserve em-dash rhythm; instruct narrator to beat-and-hold short declarative landings ("Not wind down. Stop.").

### Audio drama (Phase B)
- Cast: six principals (five respondents + Alex from Ch 6), ensemble ≤3 (camp phone call, Echoes handled by FX, not voices — Echoes are not characters).
- Sound-design bible to write when drafting starts: Buffer flicker = power hum drop-out, white-out = pressure change, Clock Tower = mechanical heartbeat. All rules from glossary usage constraints apply to FX too: never let sound *explain* the mechanism.
- One chapter ≈ one 25–35 min episode at current word counts.

### YouTube / visual series (Phase C)
- Motion-comic beats live action on budget and matches the "seen, not described" Lovecraft layer.
- Standing asset list: the Sanctuary exterior (twelve towers, brutalist, amber lighting), library/common room, archive vaults, map prop (the one that fails), dossier inserts (must match locked canon numbers).
- No signal on-site = diegetically perfect excuse for offline-recorded, post-produced audio.

### TV pitch (Phase D)
- Only after the book exists complete. Series bible derives from this repo: logline from `story.md`, season map from `plot/timeline.md` loops, character sheets as-is.

## Writing-for-adaptation rules (already in style, keep them)

These cost the prose nothing and save rework later:

1. **Keep scenes single-location, single-time.** (Already enforced by scene cards.)
2. **Keep props nameable and drawable.** Dossiers, key ring, ledger, map — they'll become insert shots/asset pages. When a prop gets invented mid-chapter, add it to `worldbuilding/artifacts/`.
3. **Avoid uncastable constructions.** Long silent stretches, paragraphs of pure written-text quotation, mirrors-heavy blocking. Chapter 3's dossier reads work because Sarah speaks/reacts while reading — keep that pattern.
4. **Tag every new named thing to the glossary immediately.** Continuity state is the master asset registry for every format.

## What NOT to do now

- Do not shorten sentences, simplify vocabulary, or add "cinematic" description for future formats. The book serves readers first; every other format adapts from a strong draft.
- Do not generate promo/AI assets featuring Alex, Chris, or Jake's dossier before those payoffs exist on page.
- Do not branch the repo into per-format scripts yet. When Phase A/B actually starts, derive script folders from finished chapters (`adaptations/audio/` etc.), never the reverse.

## Next steps (when we get there)

1. Finish the manuscript (current status: Ch 1–3 drafted, Ch 4–24 stubbed).
2. Compile a read-through pass for audiobook fluency (tongue-twister/rhythm check).
3. Write `adaptations/sound-bible.md` derived from glossary usage rules.
4. Build the visual asset list from continuity state + artifacts.
