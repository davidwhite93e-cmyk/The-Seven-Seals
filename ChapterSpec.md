# Chapter 2 — The First Seal

Status: **Complete**, per Design Spec 003 (v1.0).

Purpose: teach what a Seal is, teach how Guardians work, establish
that worthiness matters more than strength, player earns the First
Seal, Qadir quietly removes another obstacle (concealed from the
player — see `MYSTERY_LEDGER.md`).

## Scenes

1. Hakim's Study — the shrine is named, Yasmina joins the party.
2. Departure — farewell to Farah, leaving Zafirah.
3. The Caravan — road to the hill country, optional NPC beats (Sabiha,
   the pilgrim, Yasmina).
4. The Empty Desert (`Ch2_Desert`) — caravan drop-off, lore-only
   exploration hub (waymarker stones, carvings, campsite, dry well).
5. The Shrine Appears (`Ch2_Shrine_Appears`) — the staircase reveals
   itself once the wind dies.
6. The First Guardian (`Ch2_Guardian_Basim`) — meeting Sheikh Basim,
   who already knows Amir's name.
7. The Trial (`Ch2_Trial_Enter` through `Ch2_Trial_Threshold`) — a
   three-stage endurance sequence (Collapsed Corridor, Steep Climb,
   Narrow Ledge) built entirely from Continue/Turn-Back choices plus
   optional Observe/Yasmina/Basim beats at each stage. Turning back is
   penalty-free and always allows a fresh attempt via `Ch2_Trial_Enter`.
8. The Empty Chamber & the Seal of Resolve (`Ch2_Trial_Chamber`,
   `Ch2_Trial_Seal`) — the trial's twist (it ended attempts ago) and
   Basim entrusting the Seal.
9. Aftermath & Chapter End (`Ch2_Trial_Aftermath`, `Ch2_ChapterEnd`,
   `Ch2_ReturnHome`) — Yasmina's private foreshadowing beat with Basim,
   the "six more who remember" line, and the return to Hakim.

Chapter ends cleanly on `Ch2_ReturnHome` with an `<!-- End of Chapter 2
-->` marker and **no forward link** — this is intentional, not the
dead-end class of bug fixed earlier. Chapter 3 has no spec yet, so
nothing was invented past this point per Design Spec 002's own rule
("implement only what has been specified").

## New/expanded state (StoryInit)

- `$npc.basim` — new NPC entry, follows the existing database pattern.
- `$places.shrine` — new location entry, follows the existing pattern.
- `$trial` — new top-level object (`active`, `progress`, `attempts`),
  modeled directly on `$combat`'s shape. Justified as a recurring
  system: the Game Bible's "Seal Rhythm" implies every future Guardian
  chapter will need the same kind of trial-progress tracking.
- `$seals.first`, `$seals.total`, `$knowledge.knowsSevenSeals` — all
  pre-existing fields, now actually being set.

## Awaiting next Design Specification

Chapter 3 purpose (per the Book One roadmap): consequences, political
fallout, rumors spread, first hint of rival seekers, introduce a
recurring ally. No scene-level content exists yet — implementation
will resume once that Scene Package arrives.
