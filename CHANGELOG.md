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
- Drafted Design Spec 006 (Book One Story Architecture) into
  `GAME_BIBLE.md` at the Creative Director's request: chapter-by-chapter
  breakdown for Ch3-9 (objective, Guardian, mystery, emotional theme,
  relationship progression, what the player learns/misunderstands,
  Seal progression, ending hook), the Seven Seals' virtue/shrine
  assignments, a Seal-cost escalation track, and per-chapter Qadir/
  Black Vizier presence notes. Marked explicitly DRAFT, pending
  Creative Director review and approval -- no Chapter 3 implementation
  has begun.
- Design Spec 006 approved in principle by the Creative Director with
  six revisions, now recorded in an authoritative Post-Review
  Revisions block: Guardian virtues 2-7 reduced to placeholders,
  Guardian names 2-7 provisional, "Karim" redefined as a narrative
  role (trusted intermediary inside Qadir's circle), the rival
  faction's name/identity/history left open, Yasmina's Ch5 backstory
  intentionally deferred to its own future spec, and "the Covenant"
  retained as the Ancient Order's proper noun.
- Drafted Design Spec 007 (The Mythology Bible) into `GAME_BIBLE.md`
  at the Creative Director's request: the Black Vizier's history, the
  Covenant's counter-pact binding, what Seals/Guardians/entrusting
  actually are, the lost rite of renewal, the metaphysical cost of
  carrying Seals, Qadir's Book One goal, the central lie/truth pair,
  the rival faction's fragment of true doctrine, the
  hidden-until-later-books list, and consistency rules for all future
  implementation. Marked DRAFT with twelve sections and six flagged
  open questions -- no chapter implementation until approved.
- Design Spec 007 approved with modifications, all folded into its
  text so it reads as clean canon: counter-pact, entrusting
  ("responsibility, not power; the burden is inherited, not the
  Seal"), Rite of Renewal, and Seals-measure ("revealing him, not
  changing him") approved; "audible to demonkind" modified to
  Covenant-disturbance sensed as storm-pressure; the lie-binding
  metaphysics rejected and replaced with Qadir's One Rule (a
  voluntary, absolute refusal to speak deliberate falsehood); freed
  Guardians canonically return to natural mortality ("not dying --
  finally allowed to live again").
- Drafted Design Spec 008 (The Seven Founding Oaths) at the Creative
  Director's request: full texts of the seven Oaths and the Closing,
  the founders-are-the-Guardians proposed reading, sigil lore
  unifying the shipped unbroken-circle Seal symbol with the shipped
  broken-circle ward-sign, folk echoes already present in shipped
  Chapters 1-2, and on-page usage rules. Marked DRAFT with five open
  questions. All chapter implementation suspended until approved.
- Logged the partial Design Spec 008 review (transmission arrived
  truncated mid-sentence): core philosophy, promises-not-virtues, and
  farewells-as-worn-Oaths approved; oath language approved with a
  brevity/timelessness revision owed; founders-are-the-First-Guardians
  now CANON. The oath-text tightening pass and rulings on the
  Closing-in-Ch9, folk labels, and the sole-successor asymmetry await
  the remainder of the review.
- Received the complete Design Spec 008 review and folded all rulings
  in: executed the brevity/timelessness pass on all seven Oaths,
  rewrote the Closing ("Seven made one promise. / Let it hold while we
  hold. / Let it end in better hands."), logged three NEW CANON
  sections (the Oaths cannot be destroyed; every Trial ends with
  silence; the Seals are ordinary -- the Oaths are the treasure, with
  its guiding principle), replaced the rejected Closing-in-Ch9 beat
  with Qadir's impossible-familiarity beat in the Chapter 9
  architecture, added the second-playthrough rule for
  farewells-as-worn-Oaths, and recorded the Creative Director's
  inheritance-of-responsibility theme as "The Heart of the Series."
- Drafted Design Spec 009 (Character Bible) at the Creative Director's
  request: arc-level entries (core wound, desire, fear, flaw,
  strength, Book One arc, mutual change with Amir, end-of-book
  secrets, non-implementable Book Two trajectory) for Amir, Yasmina,
  Qadir, Sultan Rashid, Hakim Nadir, Farah, and Basim. Yasmina's
  biographical specifics and all father/river content stay behind
  their standing deferrals. Marked DRAFT with four open questions;
  implementation resumes from Chapter 3 upon approval.
