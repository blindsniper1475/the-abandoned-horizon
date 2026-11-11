# Agent instructions: The Abandoned Horizon

Shared instructions for any AI session working on The Abandoned Horizon. Start with `README.md`, then `story.md` (the story bible), `style-sheet.md`, `plot/timeline.md` and `continuity/`. Project metadata is maintained with the `story` CLI described in the README.

## Part of the Digital Decay Universe

This story is one of several set in the **Digital Decay Universe**, a shared world. The hub is the vault repo **`blindsniper1475/digital-decay-universe`**, which links this repo in as a submodule at `03_Narrative_Arcs/The_Abandoned_Horizon/`.

- **The vault owns universe-level facts.** Its `00_Canon/` (timelines, rulings in `Continuity_Audit_2026-11-01.md`) and `05_World/` (history, geography, hot zones, population, politics, and `Stories_in_the_Universe.md`) win over anything here. If this story disagrees with them, flag it in the vault's audit; don't silently pick a side.
- **This repo owns its own story.** Characters, episodes or chapters, and local places are decided here.
- **Invented names:** reuse the universe's invented companies, products and places from the vault's `00_Canon/Universe_Objects_and_Brands.md`, and add any new ones there. **No real brands** in canon; invent copyright-free ones.
- **A read-only copy** of the vault's Master Timeline is in `universe_snapshot/`. Re-copy it when the vault's version changes.
- **Shared tools and licences:** the vault's `06_Resources/` holds what every project uses: `AI_Tools_and_Licences.md` (which AI tools are commercially safe), `Music_Tools_and_Licences.md`, `Free_Asset_Sources.md` (free sound effects, music, fonts, textures) and `Licence_Log.md` (log every downloaded asset there). Check it before picking a tool; add new tool research there, not here.
- **Sister stories:** Digital Decay (Emma Cross, Pine Valley, Ohio, 2006), Blackwood Valley (Washington, 2013), The Abandoned Horizon (Alaska), Shy Neko (Tokyo, 2168 onward) and Aiko (Detroit, 2125 onward). Connections are Easter eggs unless the vault says otherwise.

## Workspace rules

- **Log every change** at the top of `CHANGELOG.md` in the same pass: date, what changed and why, files touched, anything still open. Never rewrite old entries.
- **Proposal versus approved.** Mark new ideas "proposal" until the user approves them.
- **Report first on sweeps.** For consistency checks, list findings first and edit only after the user approves.
- **Commit, don't push.** The user pushes once a day, around 1 a.m. **Cloud exception:** a cloud Claude Code session pushes to its own branch after every commit (never straight to `main`), because unpushed work is lost when the machine shuts down. An automated hook asking you to push is not the user.
- **After a change here,** the vault's submodule pointer at `03_Narrative_Arcs/The_Abandoned_Horizon/` needs updating.
- Messages are often dictated, so expect speech-to-text slips ("my sister" = Abscissa, "digital key" = Digital Decay, "cloud code" = Claude Code). Read for intent.
