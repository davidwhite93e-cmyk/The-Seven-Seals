# Changelog

## 2026-07-12

- Fixed Ch1 -> Ch2 dead end, missing `<<reputation>>` widget, and
  `$npc.qadir.met` not being set at the Ceremony scene.
- Pre-declared `$combat.observedFire`, standardized hub passages,
  renamed the source file to `TheSevenSeals.twee`.
- Logged Design Spec 002 (Book One Production Roadmap) into
  `GAME_BIBLE.md` as canon. Updated `ChapterSpec.md` with Chapter 2's
  purpose and implementation status.
- Implemented Design Spec 003 (Chapter 2, Scenes 4-9): The Empty
  Desert, The Shrine Appears, the First Guardian (Sheikh Basim), the
  three-stage Trial of Resolve, the Seal of Resolve, and the chapter's
  close. Chapter 2 is now complete. Added `$trial` state object,
  `$npc.basim`, and `$places.shrine`. Recorded Qadir's concealed
  shrine-funding move in `MYSTERY_LEDGER.md`.
- Logged Design Spec 004 (Book One Production Philosophy) into
  `GAME_BIBLE.md` as canon: emotional arc, design pillars, and voice
  rules for Qadir, Yasmina, the Guardians, and the Seals across all of
  Book One. No new scene content -- this is a style/philosophy
  reference, not a Chapter 3 spec.
- Logged Design Spec 005 (The Guardian Bible, Part I) into
  `GAME_BIBLE.md` as canon: the Ancient Order's true nature, common
  Guardian traits, trial/shrine/farewell design rules, and the
  acceptance criteria for future Guardians.
- Patched two retroactive gaps in Basim's already-shipped farewell
  (`Ch2_ChapterEnd`): added his specified philosophy line ("The heart
  always reaches its destination before the feet"), which Design Spec
  003 commissioned but the implementation never delivered, and a
  single subtle, unexplained physical cue reflecting that his
  unnatural longevity ended the moment he entrusted the Seal. Recorded
  a new project-wide **Retroactive Foreshadowing Rule** in
  `GAME_BIBLE.md` governing how this class of fix should be handled
  going forward: one or two sentences, no exposition, never explained
  on the page.
