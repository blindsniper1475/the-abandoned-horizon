---
type: continuity-state
story: the-abandoned-horizon
current-chapter: 1
character-state:
  - character: marcus-hayes
    location: the-archive-school
    physical: healthy
    emotional: wary, holding it together for the others
  - character: elena-hayes
    location: the-archive-school
    physical: healthy
    emotional: unsettled, already taking notes
  - character: sarah-keller
    location: the-archive-school
    physical: healthy
    emotional: quiet, watchful
  - character: david-keller
    location: the-archive-school
    physical: healthy
    emotional: restless, suspicious of the calm
  - character: jake-mercer
    location: the-archive-school
    physical: healthy
    emotional: calm, unbothered, photographing everything
object-state:
  - artifact: alexs-key-ring
    owner: alex-voss
    location: the-archive-school
    status: hidden
knowledge-state:
  - character: elena-hayes
    knows: almost nobody from the class came; only five answered the letter
    learned-in: chapter-01
  - character: david-keller
    knows: the storm is not behaving like weather
    learned-in: chapter-01
---

# Continuity State

## Current Story State

Five classmates have arrived at the Archive School during the first White-Out. The building is pristine. Nobody has noticed anything wrong yet. Alex Voss — the Custodian — is present but not visible, and has begun his first re-boot.

## Character State

| Character | Location | Physical State | Emotional State | Knowledge |
|-----------|----------|----------------|-----------------|-----------|
| marcus-hayes | the-archive-school | Healthy | Wary; holding it together for the others | Believes this is just a reunion |
| elena-hayes | the-archive-school | Healthy | Unsettled; already taking notes | Noticed almost nobody came |
| sarah-keller | the-archive-school | Healthy | Quiet, watchful | Not yet aware anything is wrong |
| david-keller | the-archive-school | Healthy | Restless, suspicious of the calm | Thinks the storm is abnormal |
| jake-mercer | the-archive-school | Healthy | Calm, unbothered | Feels at home in a way that unsettles the others |

## Object State

| Artifact | Owner | Location | Status |
|----------|-------|----------|--------|
| alexs-key-ring | alex-voss | the-archive-school | hidden |

## Knowledge State

| Character | Knows | Learned In |
|-----------|-------|------------|
| elena-hayes | Only five of the graduating class answered the reunion letter | chapter-01 |
| david-keller | The blizzard is not behaving like weather | chapter-01 |

## Upkeep

Re-run `story wordcount . --write`, `story reindex .`, and `story continuity .` after every drafting session. Keep this file describing the state **as of `current-chapter`** — nothing from later chapters belongs here.

