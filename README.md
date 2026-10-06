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
