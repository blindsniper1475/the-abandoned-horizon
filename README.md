# The Abandoned Horizon

A 24-chapter digital-decay / liminal-space survival horror novel.

Five alumni return to their abandoned arctic boarding school after a 20-year reunion letter — only to find the building maintained, the storm wrong, and one of them already inside.

## Structure

- `story.md` — the story bible (premise, themes, structure)
- `chapters/` — chapter drafts (24 planned)
- `scenes/` — scene cards
- `characters/` — character sheets
- `worldbuilding/` — locations, systems, factions, artifacts
- `plot/` — plot arcs, timeline
- `continuity/` — continuity state, questions, promises, clues
- `glossary/`, `style-sheet.md`

## Tooling

Project metadata is managed with the `story` CLI (story-maintenance skill):

```powershell
node "$env:USERPROFILE\.agents\skills\story-maintenance\scripts\story.js" <command> <path>
```

Useful commands: `validate`, `wordcount --write`, `links`, `continuity`, `prose`, `next`.

## Shared Universe

The Abandoned Horizon is part of the **Digital Decay Universe**, a shared world whose hub is the vault repo `blindsniper1475/digital-decay-universe` (this repo is linked there as `03_Narrative_Arcs/The_Abandoned_Horizon/`). Sister stories:
- **Digital Decay** (survival horror game — Emma Cross, Pine Valley, Ohio, 2006)
- **Blackwood Valley** (analog-horror web series — Washington, 2013)
- **Shy Neko** (web series — Tokyo, 2168 onward)
- **Aiko** (live AI VTuber — Detroit, 2125 onward)

**The tie (settled 2026-11-10):** the town was one of Abscissa Industries' early tests of the **Archive**, processed around 2006-07. In 2035 Abscissa does the same to most of humanity (the Holistic Integration). The five get out in **2031**, four years before the Collapse. Universe-level facts live in the vault's `00_Canon/` and `05_World/`; see `AGENTS.md`.
