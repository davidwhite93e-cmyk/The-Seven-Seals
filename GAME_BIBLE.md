# Game Bible

Master vision document. Canonical unless superseded by a later Design
Specification from the Creative Director. Internal reference only —
nothing in this file should be exposed to the player through codex,
journal, or dialogue text ahead of its scripted reveal.

**Newest authoritative source: `MASTER_STORY_FILE.md`** (Book One
Master Story File, compiled by the Creative Director from the Chapter
1–9 Story Overviews) — where it conflicts with anything below, the
Master Story File wins. Its Chapter 9 materially revises prior
mythology: see the annotations on Design Specs 002/006/007/009 below.

Sources: Design Spec 002 (Book One Production Roadmap, v1.0), Design
Spec 004 (Book One Production Philosophy, v1.0), Design Spec 005 (The
Guardian Bible, Part I — Foundational Design, v1.0), Design Spec 006
(Book One Story Architecture, v1.0 — **approved in principle** by the
Creative Director with revisions recorded in its Post-Review Revisions
block; provisional elements remain non-canon), Design Spec 007 (The
Mythology Bible, v1.0 — **approved with modifications**, all folded
into its text), Design Spec 008 (The Seven Founding Oaths, v1.0 —
**approved with revisions**, all folded into its text), Design Spec
009 (Character Bible, v1.0 draft — pending review, **non-blocking**
per the Creative Direction Reset), and the **Creative Direction Reset**
(v1.0 — canonical; supersedes prior direction where they conflict, and
moves the project to chapter-driven implementation).

## Book One Goal

The player believes they are protecting the Sultanate, collecting the
Seven Seals before the servants of darkness, and preventing the return
of demons.

The truth: every Seal willingly delivered to Amir removes another
obstacle preventing Qadir's freedom. When every Seal is gathered,
Qadir takes them, breaks his prison, binds the demons to himself, and
escapes. Book One ends there — the player believes they lost. Book
Two's central conflict is not to be revealed in Book One.

*(REVISED by the Master Story File, Ch9 "The Seventh Gate," which
governs: the party themselves perform the Rite with all seven Seals;
the prison beneath the sanctuary opens; the **Black Vizier — a
distinct being, not Qadir —** steps free; Qadir kneels to the Covenant
with "I have kept my promise," revealed as its true keeper serving an
older promise; the demons answer to the Black Vizier; the Seals remain
behind, their purpose complete, reclaimed by no one; the Djinn
sacrifices himself to cover the party's escape, his fate left
unresolved. The ending emotion is loss + resolve + hope, not the
"player believes they lost" despair described above.)*

## The Heart of the Series (Creative Director note — canonical)

The Seven Seals is no longer a story about recovering magical
artifacts. It is about **inheritance — not of blood, but of
responsibility**. Every generation chooses whether the promises of the
previous generation continue. The Seals are only the physical reminder
of those promises. That is the story players should remember long
after they forget the mechanics.

## Creative Direction Reset (canonical — supersedes where conflicting)

The mythology exists to support the story; the story does not exist to
explain the mythology. Every creative decision is now evaluated
against one question: **does this make the story more engaging to
play?**

- The most important parts of Book One are people, not lore: Amir,
  Yasmina, Qadir, the people they meet, the lives they save, the
  promises they choose to keep. Character over lore, always.
- Every chapter is an adventure: memorable places, unforgettable
  people, dangerous creatures, immediate problems, a world left a
  little better. The Seals provide structure; they are not the purpose.
- Constant discovery; never two consecutive chapters visually or
  emotionally similar.
- Relationships develop through shared victories and failures,
  campfires, disagreements, quiet moments, danger, laughter. Romance
  emerges from trust, not attraction.
- Qadir stays exactly as designed — warm, helpful, patient, likable.
- Guardians appear, change Amir, entrust the Seal, and let the story
  continue. Philosophy never overshadows the living world.
- Every chapter: exploration, character interaction, at least one
  memorable set piece, meaningful choices, a satisfying climax, a
  strong emotional ending. Reveal lore through action.
- Write like a novelist: scenes begin late, end early; dialogue
  reveals character; description vivid but economical.
- **Implementation is chapter-driven, not documentation-driven.** Do
  not stop implementation to request foundational documents unless a
  true contradiction or blocker exists. Identify creative gaps clearly
  and continue with reasonable implementation. The goal is to finish
  Book One.

## Chapter Story Overviews (authoritative)

The Creative Director has issued per-chapter Story Overviews —
emotional blueprints, not passage specs. **All nine are now
consolidated in `MASTER_STORY_FILE.md`, which is the governing
document** — including the previously unseen Chapter 6 (The City of
Mirrors), Chapter 7 (The Lighthouse at the Edge of the World), Chapter
8 (The Gathering Storm), and Chapter 9 (The Seventh Gate), plus
cross-chapter trackers for Guardians/Seals, Qadir's moves, and
character arcs. Notes reconciling the shipped chapters against those
trackers:
- **Guardian naming (tracker §11.1):** the Master File treats
  Guardians 2–7 as formally unnamed, while shipped Ch4–6 gave three of
  them human names (Tariq, Amina, and the Magistrate of the Old
  Quarter). Flagged for the Creative Director; the names are humble and
  don't break the hidden-in-plain-sight theme, but renaming is a cheap
  find/replace if strict anonymity is preferred.
- **Qadir's moves (tracker §11.2):** his Ch3–5 moves match items 1–3
  exactly. **Chapter 6 deliberately gives Qadir no on-screen move** —
  the erasure is powered by the years-earlier Records Commission (see
  Mystery Ledger), so his hands stay clean, consistent with the "his
  greatest weapon is administration" note.
- **Broken-circle symbol (§11.5):** confirmed implemented in Ch5's
  aqueduct.

Received individually before consolidation: **Chapter 1 (Festival of
Lanterns)**, **Chapter 2 (The Shrine Beneath the Sands)**, **Chapter 3
(Echoes in the Dust)**, **Chapter 4 (The Fortress That Watches the
Wind)**, and **Chapter 5 (The Orchard of Forgotten Springs)** — Ch5
key beats: a fertile valley village whose ancient
springs are failing (collapsed Covenant-era aqueducts, the symbol
beneath mineral deposits); the Third Guardian living unrecognized as
the valley's oldest gardener; the trial is staying to help when
leaving would be reasonable ("You stayed"); one night encounter
protecting villagers from cavern creatures displaced by the failing
springs (environmental choices over slaughter); Yasmina's emotional
chapter — her knowledge earns the village's trust on her own name;
Qadir's concealed move is years-old infrastructure defunding that let
time do the damage; ends bittersweet: "I hope we remember places like
this." / "I don't think I could forget." Shipped Ch1–2 content was
audited against its overviews and conforms, with one tone patch
applied (the Chapter 1 ending now closes on determination and
anticipation rather than dread, per the Ch1 overview's final emotional
note). Chapters implement against their overview first, then the Spec
006 architecture; **where they conflict, the Story Overview wins.**
For Chapter 3 specifically, the overview supersedes parts of the Spec
006 sketch: there is no palace-court sequence, the
trusted-intermediary introduction is deferred beyond Ch3, and Qadir's
concealed move is revised (see the Ch3 annotation in Spec 006 and the
Mystery Ledger).

## Chapter Structure

| Chapter | Purpose | Status |
|---|---|---|
| 1 | Introduce the world, Yasmina, Qadir (no suspicion), the symbol, demons. Teach combat. End pointed at the First Guardian. | Complete |
| 2 | Teach what a Seal is and how Guardians work. Worthiness over strength. Player earns the First Seal. Qadir quietly removes another obstacle. | Complete |
| 3 | Consequences, political fallout, rumors spread. First hint of rival seekers. Introduce a recurring ally. | Not started |
| 4 | Journey turns dangerous. Rival seekers introduced. Second Guardian. Trials begin changing the player. | Not started |
| 5 | Major emotional chapter. Yasmina's personal history. First serious disagreement. Relationship deepens or strains. Third Seal. | Not started |
| 6 | Escalation. Enemies organize. The Sultan's court grows unstable. Player unknowingly advances Qadir's plan. Fourth Seal. | Not started |
| 7 | Everything becomes personal. Truth about Amir's father begins surfacing. Fifth Seal. Qadir manipulates from the shadows; player still trusts him. | Not started |
| 8 | Race accelerates. Multiple factions pursue the final Seals. Sixth and Seventh Seals acquired. Player believes victory is imminent. | Not started |
| 9 | Qadir reveals the truth, claims every Seal, breaks his prison, binds the demons, escapes. Book One ends immediately after. No final battle, no Book Two exposition. | Not started |

## Pacing Rules

Every chapter contains: opening, exploration, character interaction,
one major conflict, one mystery discovery, one emotional moment, one
resolution, one hook. Never two combat-heavy chapters in a row. Never
two exposition-heavy chapters in a row. Alternate action and discovery.

## The Seal Rhythm

Every Seal chapter follows the same underlying structure:

Travel → Mystery → Guardian → Trial → Reflection → Seal → Aftermath.

Reflection is never skipped — it's where Amir changes.

## Qadir — Golden Rule

Qadir never directly causes events on-screen. He positions people,
withholds information, encourages investigations, redirects attention,
and allows others to make bad choices. Every manipulation must read as
reasonable in the moment. The player must not suspect Qadir before
Chapter 9.

## Yasmina

Deuteragonist, not comic relief, not a sidekick, not a romance reward.
Every chapter should include new respect, new disagreement, new
understanding, and new mystery involving her. Relationship growth must
feel earned.

## Player Choice Scope

Choices affect: relationship, personality, information, reputation,
optional scenes, combat approach, dialogue.

Choices do NOT affect: main chapter outcome, Seal acquisition, story
progression, Book ending.

## Combat

Only when it serves the story. No filler fights. Every enemy teaches
something; every battle changes the player somehow.

## Exploration

Reward curiosity, never punish it. Optional content provides lore,
character moments, hidden codex entries, optional journal entries,
foreshadowing, small resources — never mandatory progression.

## Coding Standards

Continue using existing architecture: reuse widgets, reuse objects,
avoid new globals, keep passage names readable, one scene = one
gameplay purpose.

## Acceptance Criteria

Book One should read like an excellent fantasy novel with meaningful
interaction — not a branching sandbox.

---

# Production Philosophy (Design Spec 004)

Governs *how* everything below the roadmap gets written. Where this
section and an earlier one overlap, this is the more specific
statement of intent.

## Primary Design Goal

The player should finish Book One feeling they completed a great
fantasy novel that happened to be interactive — not a branching
adventure, a resource-management game, or a puzzle game. When
implementation choices compete, favor narrative quality.

## Emotional Arc by Chapter

1. Wonder, curiosity, excitement, danger, hope.
2. Humility, reflection, purpose.
3. Responsibility, growing mystery.
4. Confidence, growing danger.
5. Friendship, doubt, loss.
6. Determination, pressure.
7. Identity, revelation.
8. Triumph, momentum, confidence.
9. Shock, betrayal, failure, resolve. The ending should hurt — not
   because anyone dies, but because the player realizes every victory
   unknowingly served Qadir.

## Design Pillars

Every scene should strengthen at least one:

- **Wonder** — places, ideas, traditions, people that feel older than
  the current civilization. The world should always feel larger than
  what's shown.
- **Mystery** — questions should outnumber answers; every answer
  creates a new question; never explain mythology immediately.
- **Character** — players remember people more than lore. When
  exposition competes with character interaction, character wins.
- **Momentum** — every chapter moves forward; no scenes that exist
  only to deliver information. Information emerges through action.
- **Hope** — never cynical, even in dark moments. People generally
  want to help. Goodness still exists — that's why Qadir's betrayal
  will matter.

## The World

The Sultanate should feel lived in through small, specific detail:
vendors, children playing, pilgrims, travelers, old customs, shared
sayings, food, architecture, music, prayer, markets, caravans.

## The Guardians

Not bosses, not quest givers, not exposition machines — living
embodiments of the virtue their Seal represents. Each should feel like
someone Amir wishes he'd known longer. Players should regret leaving.

## The Seals

Symbols of trust, never trophies, never magical loot, never rewards
for winning. Every Seal is freely entrusted. Central to Book One.

## Qadir

Patient, measured, intelligent, never theatrical, never cruel for its
own sake, never openly threatening. Everything he says stays true —
he only allows others to misunderstand it.

## Yasmina

A protagonist, never a love interest, comic relief, mission companion,
or objective marker. Her own convictions, fears, intelligence,
disagreements. She challenges Amir when appropriate and grows because
of him. Their relationship runs on mutual respect; romance (if any)
grows from friendship and shared hardship, never forced.

## Player Choice Philosophy

Choices should answer *who Amir is becoming, how he treats people,
what kind of leader he is, what he values* — rarely *which ending,
which faction, which route*. Book One is a guided narrative: choice
shapes the journey, not the destination.

## Combat Philosophy

Combat exists because violence has consequences, not because players
expect frequent fights. Every encounter should accomplish at least two
of: advance character, reveal lore, teach gameplay, create tension,
change relationships, reveal enemy behavior. If a fight accomplishes
none of these, remove it.

## Exploration Philosophy

Curiosity is always rewarded — never with power, only with stories,
history, optional dialogue, codex entries, journal entries, character
moments, foreshadowing. Players should feel smarter for exploring, not
stronger.

## Dialogue Philosophy

Dialogue should sound spoken. Avoid exposition disguised as
conversation — characters already know their world and shouldn't
explain obvious facts to each other. Prefer implication over
explanation.

## Writing Style

Primary inspirations: Brandon Mull, Robin McKinley, Lloyd Alexander,
Patricia McKillip. Hopeful, adventurous, emotionally sincere. Avoid
grimdark, modern sarcasm, self-aware humor, contemporary slang.

## Implementation Standards (supplements Coding Standards above)

Prefer extending existing systems over duplicate mechanics. Only touch
`StoryInit` when introducing a genuinely new *reusable* system. Reuse
widgets whenever possible. Maintain passage-naming and variable-naming
consistency. Treat Codex, Journal, Objectives, and Relationship
tracking as first-class systems throughout — not chapter-1-only
scaffolding.

## Chapter Acceptance Test

"If this chapter were removed, would Book One lose an important piece
of Amir's emotional journey?" If no, redesign rather than expand.

## Retroactive Foreshadowing Rule

Project-wide storytelling rule, not a one-off: whenever later canon
reveals that an already-shipped scene *should* have contained
foreshadowing, prefer adding a single subtle, emotionally natural
detail over exposition or dialogue. One or two sentences at most — a
hesitation, a lingering touch, a breath held a moment too long, a
flash of weight or years the character doesn't otherwise show. The
POV character notices but cannot explain it, does not ask about it,
and the other character does not comment on it either. On a first read
it should pass as ordinary human behavior; only in hindsight does it
read as the truth arriving early. (Precedent: Basim's farewell in
`Ch2_ChapterEnd`, after the Guardian Bible established that entrusting
a Seal ends a Guardian's unnatural longevity.)

Governing principle: **the truth is almost always visible before it is
understood.**

---

# The Guardian Bible, Part I — Foundational Design (Design Spec 005)

Canonical design language for all seven Guardians. Supersedes prior
brainstorming on the topic.

## Core Distinction

Guardians protect the *decision to entrust* the Seal, not the Seal
itself. The Seal has little value in the wrong hands — its power
comes from the trust between Guardian and successor. Every Guardian
understands this.

## The Ancient Order (backstage lore — reveal gradually, never dump)

Seven men and women were entrusted with the Seals after the
imprisonment of the Black Vizier, long before the Sultanate existed.
They founded no kingdom, raised no army, built no religion — only
quiet stewardship. Most people believe them myths; most rulers believe
them long dead; scholars disagree on whether they existed at all. All
are wrong.

Each Seal preserves its Guardian's life until a worthy successor is
found — they are not immortal, they are waiting. **The moment a
Guardian entrusts their Seal, their unnatural longevity ends and they
become ordinary again.** This is why every Guardian quietly hopes Amir
is worthy: he isn't merely taking a burden, he's releasing them from
one. No Guardian knows the full story — each understands only the
virtue they protect, the Seals' responsibility, and that the Black
Vizier must never possess all seven. None of them know Qadir has
already escaped his prison in every meaningful way but the physical
one, which is why none of them warn Amir about him.

## Common Traits

Calm, patient, observant, emotionally mature. Never arrogant, never
eager to prove themselves, never impressed by violence. Centuries of
waiting means nothing Amir says surprises them.

## How They Speak

Direct answers. Never manipulate Amir, never test him through
deception, never speak in riddles just to sound wise — if they won't
answer something, they say why. Players should trust every Guardian
immediately; this is a deliberate contrast with Qadir. The honest
people appear mysterious. The dishonest man appears trustworthy.

## Relationship with Amir

No Guardian immediately believes Amir worthy, and none dismiss him
either — each approaches with quiet curiosity. By trial's end, each
should genuinely admire him for a different reason: not because he's
exceptional, but because he chooses virtue despite uncertainty.

## Relationship with Yasmina

Every Guardian recognizes her as extraordinary and none explain why.
Each has a unique interaction with her that Amir doesn't fully
understand — subtle Book Two foreshadowing. Never explain these in
Book One.

## Visual Language

Simple clothing, no jewelry beyond personal keepsakes, no ceremonial
armor, no elaborate magical effects. Shrines are places of peace, not
power. Seals should read as almost disappointingly ordinary — players
should realize the *people* are remarkable, not the objects.

## Shrine Design

Every shrine reflects its Guardian, not its virtue in the abstract
(Basim's is quiet and humble because *he* values simplicity — not
because "Resolve" abstractly implies humility). Future shrines:
library, abandoned fortress, thriving orchard, lighthouse,
observatory, cliffside monastery. Environment communicates personality
before dialogue starts.

## Trial Design

The player always understands the physical objective; the true test
is moral or emotional, and should only be recognized as such after the
trial ends. Combat may appear but should never be the point. Failure
should almost never be a game over — it teaches. Players retry because
they understand themselves better, not because they memorized a
puzzle. **Avoid repeating trial structures between Guardians** — the
tunnel-endurance format used for Basim (Continue / Pause / Turn Back)
should not be reused verbatim for the Second Guardian.

## The Farewell

Every Guardian gets a memorable final conversation — never a plain
"good luck." Each farewell leaves Amir with one sentence that becomes
a recurring touchstone in later chapters. (Basim's: "The heart always
reaches its destination before the feet.")

## Implementation Standards

Introduce each Guardian through environment before dialogue. Give each
a distinct speech rhythm and vocabulary. Avoid repeated trial
structures. Reinforce philosophy through gameplay, not exposition.
Codex the Guardian immediately on meeting them. Journal each completed
trial in terms of Amir's personal growth, not just plot progression.

## Acceptance Criteria

By Book One's end, players should recall each Guardian by name,
personality, and philosophy without confusing them. If two Guardians
could be swapped between chapters without noticeably changing the
story, the design has failed and must be revised before implementation
continues.

---

# Book One Story Architecture (Design Spec 006)

**Status: Approved in principle by the Creative Director, with the
revisions below — but its Chapters 6–9 are now SUPERSEDED by the
Master Story File** (`MASTER_STORY_FILE.md`), which changes them
substantially: Ch6 is "The City of Mirrors" (trade city, magistrate
Guardian, erased Covenant-descendant families, the burning archive,
**the Djinn introduced**); Ch7 is "The Lighthouse at the Edge of the
World" (Keeper Guardian, sea-siege — the Amir's-father storyline is
**dropped from Book One entirely**, held behind its Book 2 Ledger
flags); Ch8 is "The Gathering Storm" (observatory + cliff monastery,
the rival faction met face-to-face, no Qadir move needed); Ch9 is "The
Seventh Gate" (see the revision note under Book One Goal). The Spec 006
chapter sections below are retained for the ideas that still apply
(and for Chapters 1–5, which shipped), but where they conflict with
the Master Story File, the Master Story File wins.

Architecture only. No dialogue, no passages, no implementation. The
chapter skeleton (objectives, emotional themes,
mystery/answer/raise structure, Seal pacing, Qadir's per-chapter
moves, the escalation track) is canon. The revisions below override
anything in the chapter text that conflicts with them.

## Post-Review Revisions (Authoritative — Creative Director)

1. **Guardian virtues are placeholders.** Only Resolve (Seal 1) is
   canon, locked by shipped Chapter 2 content. Virtues 2–7 must emerge
   from the completed Ancient Order mythology, not read as a
   predefined list of RPG attributes. Do not finalize until the
   Mythology Bible (Design Spec 007) is approved.
2. **All Guardian names are provisional.** Working labels only, listed
   in the Awaiting Approval section at the end of this spec. A name
   does not become canon merely because implementation needs one.
3. **"Karim" is a role, not a character.** The canon element is the
   narrative function: *a trusted intermediary inside Qadir's circle
   who unknowingly provides Amir with information.* Whether that role
   belongs to a new character, several people, or someone already
   introduced is a future Creative Director decision. Where the
   chapter text below says "Karim," read the role.
4. **The rival faction's name, identity, and history are open.** The
   story function is canon: a believable rival faction that appears to
   oppose Amir while actually trying to prevent something much worse.
   "The Veiled Hand" is a working label only.
5. **Yasmina's Chapter 5 backstory is intentionally deferred.** She is
   an emotional pillar of the series; her history gets its own Design
   Specification and is not to be finalized inside this architecture.
6. **"The Covenant" is retained** as the proper noun for the Ancient
   Order, unless future lore requires otherwise.

Wherever the chapter architecture below uses a provisional name
(Tariq, Amina, Idris, Zahra, Hassan, Rania, Karim, "the Veiled Hand")
or a placeholder virtue, it is shorthand for readability — not canon.

## Continuity Notes

- **"The Covenant"** is used throughout as the proper noun for what
  Design Spec 005 calls "the Ancient Order" — the founding pact of the
  seven original Guardians. This pays off the existing
  `$knowledge.knowsCovenant` flag in `StoryInit`, present since the
  project's first commit but never yet written toward.
- **Chapter 3's central mystery is built to satisfy a pre-existing,
  previously unaddressed commitment**: the Mystery Ledger already
  lists "Ghūl Symbol" with Reveal: Ch3. This architecture treats that
  reveal as "the Zafirah attack wasn't isolated — the same
  ward-disturbance pattern has appeared at other forgotten shrines" —
  which also doubles as the first hint of the rival faction Design
  Spec 002 calls for in the same chapter.
- **The Seven Seals**, one per Seal chapter. Per Post-Review Revision
  1, virtues 2–7 are placeholders pending the Mythology Bible; per
  Revision 2, names 2–7 are provisional working labels. What IS canon
  in this table: the shrine assignments (drawn verbatim from Design
  Spec 005's own list), the chapter pacing, and Seal 1 as shipped.

  | # | Virtue (placeholder) | Guardian (provisional) | Shrine (canon) | Chapter (canon) |
  |---|---|---|---|---|
  | 1 | Resolve *(canon — shipped)* | Sheikh Basim *(canon — shipped)* | Desert shrine | Ch2 |
  | 2 | "Courage" | "Tariq" | Abandoned fortress | Ch4 |
  | 3 | "Loyalty" | "Amina" | Thriving orchard | Ch5 |
  | 4 | "Justice" | "Idris" | Library | Ch6 |
  | 5 | "Truth" | "Zahra" | Observatory | Ch7 |
  | 6 | "Sacrifice" | "Hassan" | Lighthouse | Ch8 |
  | 7 | "Wisdom" | "Rania" | Cliffside monastery | Ch8 |

  Ch8 carries two Guardians, matching Design Spec 002's own language
  ("Sixth and Seventh Seals acquired" in one chapter) and the roadmap's
  compressed, race-against-rivals pacing at that point in the book.
  The proposed trial shapes attached to Chapters 4–8 are likewise
  contingent on the final virtues and should be re-validated once
  those are locked.

## The Cost of the Seals — Escalation Track

Design Spec 006 requires the cost of carrying the Seals to increase
every chapter. Rather than a mechanical drain, this is a narrative
throughline:

1. **Ch2 (1 Seal):** Private, internal. Nothing external changes yet.
2. **Ch4 (2 Seals):** The party becomes an active target — the rival
   faction engages directly for the first time.
3. **Ch5 (3 Seals):** Personal cost. The quest becomes inseparable
   from Yasmina's own history, not just Amir's.
4. **Ch6 (4 Seals):** Civic cost. The quest now visibly affects the
   whole Sultanate, not only the party.
5. **Ch7 (5 Seals):** Identity cost. The quest reaches into Amir's own
   family history — no longer separable from who he is.
6. **Ch8 (6–7 Seals):** Existential cost. Completing the set removes
   whatever the rival faction believed was still holding the worst
   outcome back — win condition and danger peak simultaneously.
7. **Ch9:** Total cost. Everything gathered is taken at once, by the
   one person no one suspected.

## Chapter-by-Chapter Architecture

### Chapter 1 — *(shipped; documented here for completeness)*

- **Primary objective:** Survive the Festival of Lanterns; establish
  Zafirah and home.
- **Guardian encountered:** None.
- **Central mystery introduced:** The seven-fold broken-circle
  ward-symbol burned into the flagstones by the ghūl.
- **Core emotional theme:** Wonder, curiosity, excitement, danger,
  hope.
- **Relationship progression:** Meets Yasmina (mutual respect,
  sparked). Sees Qadir for the first time — no suspicion.
- **What the player learns:** Demons are real and can breach the
  mortal world; an old symbol ties the attack to "guardians."
- **What the player still misunderstands:** Believes this is an
  isolated, local incident. No concept yet of Seals, the Covenant, or
  Qadir's nature.
- **Seal progression:** 0/7.
- **Ending hook:** Hakim identifies the symbol as a guardian ward-sign
  and points Amir toward the shrine.
- **Answers:** "What was that creature and symbol?" (partially —
  "guardian-related.")
- **Raises:** "What is a Guardian?" / "Why did Father fear the river?"

### Chapter 2 — *(shipped; documented here for completeness)*

- **Primary objective:** Reach the Shrine of the First Guardian and
  earn his trust.
- **Guardian encountered:** Sheikh Basim, Guardian of Resolve.
- **Central mystery introduced:** The Covenant exists; Guardians
  entrust rather than guard by force.
- **Core emotional theme:** Humility, reflection, purpose.
- **Relationship progression:** Yasmina becomes a true equal partner;
  first shared hardship (the trial).
- **What the player learns:** Seals are entrusted, not taken;
  worthiness matters more than strength.
- **What the player still misunderstands:** Believes collecting Seals
  simply means "stopping the servants of darkness." No knowledge of
  Qadir's involvement.
- **Seal progression:** 1/7 (Resolve).
- **Ending hook:** "Six more who remember" — Hakim's research toward a
  lead on the Second Guardian.
- **Answers:** "What is a Seal, and how is it earned?"
- **Raises:** "Who are the other six Guardians?" / "What did Basim
  mean about Yasmina's road asking different things?"

### Chapter 3 — Consequences

*(Superseded in part by the Chapter 3 Story Overview "Echoes in the
Dust," which governs: no palace-court sequence; the
trusted-intermediary introduction is deferred beyond Ch3; the chapter
centers on rumor fallout in Zafirah, a ruined library predating the
city, corrupted scholars as the first human conflict, a damaged
journal proving the Guardians real, and the "Fortress That Watches the
Wind" lead. Qadir's concealed move is revised: he ensured the right
records became available to the wrong people, and the escaping
scholar's incomplete copies will eventually reach him.)*

- **Primary objective:** Navigate political fallout in Zafirah after
  news of the ghūl attack and the shrine expedition spreads; secure
  standing and information for the road ahead.
- **Guardian encountered:** None — deliberately, per pacing rules
  (never two Seal-heavy chapters in a row; Ch2 and Ch4 bracket a
  breather).
- **Central mystery introduced:** The ward-disturbance pattern from
  Ch1 has been showing up at other forgotten shrine sites recently —
  the Zafirah attack wasn't isolated. First hint of the rival faction
  (working label: "the Veiled Hand" — name/identity/history open per
  Post-Review Revision 4) already searching for the Seals. *(Fulfills
  the Mystery Ledger's existing Ch3 commitment for "Ghūl Symbol.")*
- **Core emotional theme:** Responsibility, growing mystery.
- **Major relationship progression:** Introduces the *trusted
  intermediary inside Qadir's circle* — a canon narrative role, not
  yet a canon character, per Post-Review Revision 3 (working label:
  "Karim") — as an information source; Amir's standing with the court becomes
  concretely trackable via `$reputation.city`; Yasmina begins visibly
  splitting attention between Amir and her obligations to Hakim
  (quiet setup for Ch5).
- **What the player learns:** The court has competing interests;
  someone already knows about the Seals; being "the one who fought the
  ghūl" carries public cost as well as benefit.
- **What the player still misunderstands:** Assumes the Veiled Hand is
  the book's central threat. Assumes Qadir's household is simply
  generous and well-run — has no reason to connect the Ch2 shrine-fund
  redirection to any person.
- **Seal progression:** Still 1/7 — no Seal this chapter.
- **Qadir's move (concealed):** "Reluctantly" grants Amir access to
  restricted archive texts about the Seals — generous on its face —
  while ensuring the one volume that would expose the Covenant's full
  history is "still being catalogued." Nothing withheld is ever a lie.
- **Black Vizier presence:** A court official uses "when the Black
  Vizier wakes" as an idle curse. Dismissed by everyone, including
  Amir, as superstition.
- **Ending hook:** Karim quietly reveals someone else requested the
  same restricted texts, days before Amir did — first concrete
  evidence of a rival seeker.
- **Answers:** "Was the ghūl attack an isolated incident?" (No.)
- **Raises:** "Who is behind the Veiled Hand?" / "Why do they want the
  Seals?"

### Chapter 4 — The Fortress

*(Superseded in part by the Chapter 4 Story Overview "The Fortress
That Watches the Wind," which governs: the on-page enemies are
desperate desert raiders hired through collectors — not the rival
faction, which stays unseen and unrevealed; no intermediary relay; the
Guardian is met repairing the outer wall, the trial is responsibility
and a sandstorm crisis, the farewell line is "Courage is rarely loud,"
and Qadir's concealed move is ensuring old fortress maps reached
collectors whose greed hired the raiders, forcing the Seal's
entrusting earlier than the Guardian intended.)*

- **Primary objective:** Reach the Second Guardian's shrine while the
  Veiled Hand actively pursues the same goal.
- **Guardian encountered:** Tariq, Guardian of Courage (abandoned
  desert fortress).
- **Central mystery introduced:** The Veiled Hand is glimpsed as
  organized and resourced, not a mob. Tariq is the first to say "the
  Covenant" aloud on-page.
- **Core emotional theme:** Confidence, growing danger.
- **Major relationship progression:** Amir and Yasmina's partnership
  tested under real physical danger for the first time. Karim relays
  intelligence remotely — the recurring-ally relationship deepens
  without requiring him to travel.
- **What the player learns:** Someone with real resources is racing
  Amir for the Seals. Tariq subverts the "warrior guardian" cliché
  (consistent with Design Spec 005's "never impressed by violence"):
  courage isn't the absence of fear, it's protecting something
  breakable while still afraid.
- **What the player still misunderstands:** Believes the Veiled Hand
  is the book's central antagonist. Qadir, dispatching supplies and an
  escort from the capital, appears more helpful than ever.
- **Seal progression:** 2/7 (Courage) at chapter's end.
- **Qadir's move (concealed):** "Generously" sends a small Sultan's
  escort to protect the party from the Veiled Hand. Its unstated real
  effect: keeps the party on a slow, public, predictable route rather
  than a fast, quiet one — exactly how Qadir wants Amir's movements
  managed.
- **Black Vizier presence:** Tariq mentions, plainly, that his trial
  exists because "something was imprisoned, once, that must never be
  whole again" — first explicit (if incomplete) Guardian reference to
  the imprisonment itself.
- **Ending hook:** The Veiled Hand's masked leader is glimpsed
  watching the party leave, without engaging — a wordless promise of
  confrontation to come.
- **Proposed trial shape (distinct from Basim's endurance format):** a
  fear-confrontation trial — the correct choice is never to suppress
  fear, only to act honestly afraid.
- **Answers:** "Are the rival seekers actually dangerous?" (Yes.)
- **Raises:** "Who leads the Veiled Hand?" / "What did Tariq mean by
  'must never be whole again'?"

### Chapter 5 — The Orchard

- **Primary objective:** Reach the Third Guardian while Yasmina's own
  history complicates the journey.
- **Guardian encountered:** Amina, Guardian of Loyalty (thriving
  orchard).
- **Central mystery introduced:** Yasmina's personal connection to
  this region or Guardian becomes the chapter's emotional core. Its
  content is **intentionally deferred** per Post-Review Revision 5 —
  her history gets its own dedicated Design Specification and must not
  be improvised during Chapter 5 implementation.
- **Core emotional theme:** Friendship, doubt, loss.
- **Major relationship progression:** Book One's first serious
  disagreement between Amir and Yasmina — Amir wants to press on for
  the mission, Yasmina needs to stop for her own unfinished business.
  Relationship deepens or strains based on `$npc.yasmina.relationship`
  and how the player handles it, per existing tracking.
- **What the player learns:** Yasmina has her own stakes and grief,
  not borrowed from Amir's journey. Amina teaches that loyalty is
  tested exactly when it's inconvenient, never when it's easy.
- **What the player still misunderstands:** Still frames the conflict
  as "stop the Veiled Hand" — doesn't realize every day spent on
  Yasmina's history is a day Qadir doesn't have to work around Amir's
  presence in the capital.
- **Seal progression:** 3/7 (Loyalty) at chapter's end.
- **Qadir's move (concealed):** Reassigns Karim to different duties
  "for his advancement" while Amir is away — reduces the density of
  Amir's court-side intelligence exactly as tensions in Zafirah begin
  rising, without ever looking like anything but routine promotion.
- **Black Vizier presence:** A small, unsettling detail at the orchard
  — a ring of withered trees, animals that avoid one spot — hints the
  Black Vizier's old influence touched this ground once, long before
  the Covenant existed.
- **Ending hook:** Word reaches the party that Zafirah's political
  situation has worsened in their absence.
- **Proposed trial shape:** a divided-attention trial — repeatedly
  choosing whom to help first among people with real, competing needs,
  probably involving Yasmina directly.
- **Answers:** "What has Yasmina been carrying?" (Revealed, at least
  in part.)
- **Raises:** "What did Qadir's Karim reassignment actually cost the
  party?" (invisible to Amir, visible to the player as dramatic irony)
  / "What else don't I know about the people I trust?"

### Chapter 6 — The Unstable Court

- **Primary objective:** Return to a destabilized Zafirah, then pursue
  the Fourth Guardian.
- **Guardian encountered:** Idris, Guardian of Justice (library).
- **Central mystery introduced:** The Veiled Hand escalates to open
  action in the capital itself; the Sultan leans on Qadir's counsel
  more than ever — a visible, entirely reasonable-looking increase in
  Qadir's formal authority.
- **Core emotional theme:** Determination, pressure.
- **Major relationship progression:** Amir must weigh spending his own
  reputation/resources stabilizing the city against continuing the
  quest. Karim resurfaces in a reduced role, testing whether the
  earlier investment in him still matters.
- **What the player learns:** The Sultanate's stability is fragile;
  the race for the Seals has real civic cost. Idris teaches that
  Justice isn't punishment — it's accurate seeing, weighed carefully,
  before acting.
- **What the player still misunderstands:** Reads Qadir's expanding
  authority as the Sultanate correctly leaning on its most capable
  servant during a crisis — exactly as intended.
- **Seal progression:** 4/7 (Justice) at chapter's end.
- **Qadir's move (concealed):** Proposes "centralizing crisis
  response," gratefully approved by the Sultan — its structural effect
  routes nearly all Seal- and Veiled-Hand-related intelligence through
  Qadir's office first.
- **Black Vizier presence:** Idris's library holds a fragment naming
  "the Black Vizier" as historical fact, not myth — the first
  confirmation the phrase is literal. Idris still won't say more than
  the text does.
- **Ending hook:** The party leaves for the Fifth Guardian carrying
  information Qadir already possesses before they act on it.
- **Proposed trial shape:** an incomplete-information trial — render
  judgment on a historical dispute using only fragments of evidence.
- **Answers:** "Is the crisis real, or overblown?" (Real.)
- **Raises:** "Why does everything seem to run through Qadir now?"
  (dramatic irony for the player) / "Is the Black Vizier actually
  real?"

### Chapter 7 — The Father's Road

- **Primary objective:** Follow a lead — plausibly the Broken Compass,
  if taken in Ch1 — toward the Fifth Guardian, discovering it's tied
  to Amir's father's own forgotten history with the Covenant.
- **Guardian encountered:** Zahra, Guardian of Truth (observatory).
- **Central mystery introduced:** Amir's father had prior, unexplained
  contact with the Covenant or a Guardian — deepens, but deliberately
  does not resolve, the existing Mystery Ledger threads "Broken
  Compass" and "Father's Fear of the River" (both already flagged
  Reveal: Book 2 — this chapter should not jump that gun).
- **Core emotional theme:** Identity, revelation.
- **Major relationship progression:** Amir confides in Yasmina about
  his father in a way he hasn't before — the chapter where their bond
  stops being "companions who respect each other" and becomes
  load-bearing for the rest of the book. Romance, if any, continues to
  grow from this, never forced.
- **What the player learns:** Amir's family has a real, specific
  history with the Covenant predating this journey. Zahra teaches that
  Truth isn't certainty — some truths can only be approached, never
  fully possessed (a quiet echo of Yasmina's own scholarly humility
  from the Ch2 caravan scene).
- **What the player still misunderstands:** Believes this closes a
  loop about his father. Doesn't realize this is exactly the kind of
  leverage Qadir has been managing for years — left deliberately
  unresolved whether Qadir knew Amir's father directly.
- **Seal progression:** 5/7 (Truth) at chapter's end.
- **Qadir's move (concealed):** When the palace archive is asked about
  Amir's father's old associations, Qadir ensures the answer is true
  but incomplete — a real, minor fact confirmed, the one connection
  that would raise suspicion omitted.
- **Black Vizier presence:** Zahra's observatory records a chart of
  "the year the stars went briefly wrong," dated to roughly when the
  Covenant first bound the Black Vizier — establishes scale without
  naming Qadir.
- **Ending hook:** Amir now has a personal, not just civic, reason to
  finish this. Hakim's continued research identifies the Sixth and
  Seventh Guardians as unusually close together, setting up Ch8's
  compressed pacing.
- **Proposed trial shape:** a perception/interpretation trial —
  distinguishing real signs from false ones, learning truth-seeking is
  a discipline, not a single act of seeing clearly.
- **Answers:** "What is Amir's father's connection to all this?"
  (Deepened, deliberately not resolved.)
- **Raises:** "What does Qadir actually know about Amir's father?" /
  "Why are the last two Guardians so close together?"

### Chapter 8 — The Race

- **Primary objective:** Race the now openly hostile, increasingly
  desperate Veiled Hand to secure the final two Seals.
- **Guardians encountered:** Hassan, Guardian of Sacrifice
  (lighthouse), **and** Rania, Guardian of Wisdom (cliffside
  monastery) — both in one chapter, matching the roadmap's compressed
  pacing at this point in the book.
- **Central mystery introduced:** The Veiled Hand's true goal is
  narrower and stranger than "stop Amir" — they don't want the Seals
  for themselves. They want to prevent anyone, including Amir, from
  completing the set, because they believe (correctly, though the
  player won't know it yet) that gathering all seven in one place is
  exactly what must never happen. Reframes the villains as possibly
  right, for reasons no one yet understands.
- **Core emotional theme:** Triumph, momentum, confidence.
- **Major relationship progression:** The full support network (Amir,
  Yasmina, Karim, echoes of Tariq/Amina/Idris/Zahra) operates at its
  most cohesive point in the book — the emotional high before the
  fall. Must feel earned, not hollow.
- **What the player learns:** Hassan teaches that sacrifice is usually
  quiet and unthanked, not dramatic or witnessed. Rania teaches that
  wisdom is knowing which questions are still open, not having every
  answer — a deliberate tease that not even the last Guardian claims
  full understanding.
- **What the player still misunderstands:** Believes completing the
  set of Seven Seals *is* the victory condition — exactly the belief
  Qadir has spent seven chapters cultivating, and exactly what the
  Veiled Hand was actually trying to prevent.
- **Seal progression:** 6/7, then 7/7 (Sacrifice, then Wisdom) — Book
  One's Seal collection completes at the end of this chapter.
- **Qadir's move (concealed):** Ensures the Sultan formally declares
  the Seals' delivery a state occasion — a public ceremony, announced
  in advance, guaranteeing all seven Seals will be gathered in one
  place, publicly, with Qadir present by unquestionable right as Grand
  Vizier. He never asked for this. It was the obvious, generous thing
  to arrange.
- **Black Vizier presence:** The Veiled Hand's leader, cornered, says
  just enough before escaping to plant real doubt: "You still don't
  understand what you're carrying." A red flag the player may not
  fully register until Ch9.
- **Ending hook:** All seven Seals in hand, the party turns home for
  the ceremony Qadir arranged — triumphant, unaware they're walking
  toward the trap the whole book has been building.
- **Proposed trial shapes:** Hassan — an offer of a genuine, unwitnessed
  sacrifice with no way to know in advance if it mattered. Rania — an
  opportunity to learn more than Amir should (about Qadir, unconfirmed)
  and the choice of restraint instead.
- **Answers:** "Can Amir actually collect all seven Seals?" (Yes.)
- **Raises:** "What did the Veiled Hand's leader mean?" / "Why does
  completing the set feel like the end of the story rather than the
  middle of one?"

### Chapter 9 — The Black Vizier

- **Primary objective:** Attend the public ceremony delivering the
  Seven Seals — which becomes the site of Qadir's true reveal and
  escape.
- **Guardian encountered:** None — all seven already met. This chapter
  is the payoff, not a new trial.
- **Central mystery introduced and resolved:** Qadir ibn Salim is the
  Black Vizier, imprisoned generations ago by the Covenant and bound
  in mortal guise — unable to touch a Seal himself, consistent with
  the existing Mystery Ledger's "corrupted by infernal pacts," because
  a Seal will not be taken by the hand it was made to guard against.
  Every "generous" act across Book One (fund redirection, the slow
  escort, Karim's reassignment, the information bottleneck, the public
  ceremony) is revealed, in sequence, as the same plan wearing
  different faces.
- **Core emotional theme:** Shock, betrayal, failure, resolve.
- **Major relationship progression:** Yasmina's reaction anchors the
  player's — she should be as blindsided and as angry at herself as
  Amir is, never framed as someone who "should have known." The seven
  Guardians' farewell touchstones (Basim's "the heart always reaches
  its destination before the feet" among them) should each
  recontextualize here — what Amir collected turns out to be exactly
  what's left once certainty is gone.
- **What the player learns:** Everything — the true shape of the
  conflict, Qadir's nature, the cost of trust freely given.
- **What the player still misunderstands:** Nothing left about Qadir
  specifically — but the Marid, the Black Vizier's true demonic
  nature, and Book Two's actual conflict stay unknown, per "no Book
  Two exposition."
- **Seal progression:** 7/7 collected, then 0/7 in Amir's possession —
  Qadir takes them all. (Mechanically: a new flag such as
  `$seals.stolen = true` is recommended over resetting the individual
  Seal booleans, so the game still remembers Amir legitimately earned
  all seven even though he no longer holds them. Implementation detail
  only — not to be built yet.)
- **Qadir's move:** Openly revealed at last — takes the Seals, breaks
  his own imprisonment, binds the demons (the Marid among them, per
  the existing `$npc.marid` entry) to himself as his own power, and
  escapes. No final battle, per spec.
- **Impossible familiarity (canon, per the Spec 008 review):** during
  the ceremony and reveal, Qadir quietly recognizes the Covenant's
  ritual shape without ever claiming ownership of it — small,
  unremarked competences no living person should have. He never
  speaks the Closing (explicitly rejected). The design target is the
  post-book realization: "How could he have known that?"
- **Black Vizier presence:** Total — this is his chapter.
- **Ending hook:** Book One ends immediately after the escape. Amir
  has nothing left but the Guardians' words, Yasmina beside him, and a
  Sultanate that just watched this happen in public. No resolution
  offered — Book Two begins from this wound.
- **Answers:** Every mystery on the Mystery Ledger reaches its
  scheduled reveal chapter except the two already flagged "Book 2"
  (Broken Compass, Father's Fear of the River), which stay open by
  design.
- **Raises:** Only what Book Two needs, deliberately nothing more.

## Awaiting Approval (non-canon until the Creative Director signs off)

- **Guardian names 2–7:** "Tariq," "Amina," "Idris," "Zahra,"
  "Hassan," "Rania" — provisional working labels only.
- **Guardian virtues 2–7:** "Courage," "Loyalty," "Justice," "Truth,"
  "Sacrifice," "Wisdom" — placeholders until the Ancient Order
  mythology is complete (Design Spec 007).
- **Rival faction:** name ("the Veiled Hand"), identity, and history
  all open; only the story function is canon.
- **Trusted-intermediary role:** casting open (new character,
  multiple people, or someone already introduced); only the function
  is canon.
- Whether Amir's father's Covenant connection should hint at anything
  more specific by Ch7 (beyond "prior contact, unexplained") — current
  draft keeps it as vague as the existing Ledger entries require.
- Whether Qadir personally "knowing" Amir's father should be confirmed
  or left ambiguous through the end of Book One.

## Intentionally Deferred (to dedicated future Design Specs)

- **Yasmina's personal history** (needed before Chapter 5
  implementation).
- **The Seven Founding Oaths** (Design Spec 008, drafted below — all
  chapter implementation is suspended until it is approved; virtues
  2–7 and the Guardians' final characterization derive from it).

---

# The Mythology Bible (Design Spec 007)

**Status: APPROVED with modifications — but now PARTIALLY SUPERSEDED
by the Master Story File, pending a Creative Director rewrite.** The
Master File's Chapter 9 establishes that **Qadir is NOT the Black
Vizier.** They are distinct beings: the Black Vizier is the imprisoned
one who steps free at the Seventh Gate; Qadir is the Covenant's true
keeper, serving an older promise for centuries ("I have kept my
promise" — spoken kneeling to the Covenant, not to the Vizier). Any
passage below that identifies the two as one person no longer holds
as written and must not be used for implementation.

What still stands: the counter-pact concept, the entrusting mechanics,
Guardian longevity / lent time, the trial / silence / farewell rules,
the Seals-measure / Seals-disturb mechanics, Qadir's One Rule (every
word he ever spoke stays true — the Master File §11.5 explicitly
re-affirms this), and the escalation track.

Newly open questions for the Creative Director: what exactly was
Qadir's older promise, to whom, and when; why he cannot claim a Seal
himself (the Ledger's "corrupted by infernal pacts" answer may need
revision); who the Black Vizier was before imprisonment; and how
"Qadir has already escaped his prison in every meaningful way except
physically" (Design Spec 005) reconciles — e.g., whether Qadir's
"prison" is his centuries of bound service rather than the Vizier's
cell.

--- *(original approval note, retained for the parts still in force)* ---

**Status: APPROVED by the Creative Director, with modifications — all
folded into the text below.**

Review outcomes: counter-pact — approved. Entrusting — approved
(responsibility transfers, never power; the burden is inherited, not
the Seal). Rite of Renewal — approved. Seals measure their bearers —
approved (they reveal Amir, they do not change him). Seals "audible"
to demonkind — modified (infernal beings sense disturbances in the
Covenant, like pressure before a storm — never literal sound).
Lie-binding metaphysics — rejected; replaced with Qadir's voluntary
absolute rule (Section II). Freed Guardians return to ordinary
mortality — approved. Virtues — deliberately unfinalized, to emerge
from the Seven Founding Oaths (Design Spec 008).

This is the single source of truth for every supernatural element in
the series. Where earlier documents touch the same ground, this
document is the deeper, governing statement. It is entirely backstage:
player-facing reveals remain governed by the Mystery Ledger's
schedule, and nothing here is license to surface lore early.

## I. Before the Covenant — the Making of the Black Vizier

Long before the Sultanate, another power ruled these lands. Its name
is deliberately left unset here — naming a fallen empire is a
worldbuilding decision with Book Two consequences (see Open
Questions).

Its last great vizier was, by every honest account, the most brilliant
servant the empire ever had: patient, measured, indispensable. He did
not set out to become a monster. He set out to be *necessary* — and
the pacts came the way debt comes, one reasonable bargain at a time.
A drought ended. A border held. A plague passed over. Each bargain was
struck with the demonkind on terms that seemed, in the moment,
obviously worth paying. By the time anyone understood what he had
become, the distinction between the empire's power and his pacts had
dissolved — and so, shortly after, did the empire.

He is remembered — where he is remembered at all — as **the Black
Vizier**. That is a title, not a name. His true name is one of the
things the pacts took first.

*Design intent: his corruption must mirror Qadir's Book One method —
never a single dramatic fall, always a sequence of individually
reasonable steps. The player who later learns this history should
recognize, uncomfortably, that they watched the same pattern happen to
themselves across nine chapters.*

## II. The Binding — Why He Was Imprisoned, Not Killed

He could not be killed. The pacts had mortgaged even his death:
destroying the vessel would have released everything bound through it.
The demonkind he had chained would have come loose all at once, with
no chains at all.

So seven ordinary people — not heroes, not royalty; history kept their
titles and lost their names — did the only thing stronger than a
bargain: they made a promise. His power was pact-born, built from
terms and interests and clauses. What held him could not be walls. It
was a **counter-pact**: seven oaths, freely sworn, each staked on a
life, woven together into a binding the original texts call **the
Covenant**.

The Covenant did three things:

1. **It unmade his power** — the demonkind bound to him were sealed
   away beyond his reach, each seal anchored by one oath.
2. **It bound him into mortal shape** — alive, ageless in the same
   lent-time way as his jailers (the prison persists exactly as long
   as its keepers do, and so does the prisoner), but stripped to a
   man: no sorcery, no dominion, nothing but a mind.
3. **It bound his hands** — he cannot act directly against the
   Covenant's work. He cannot touch an oath-bound Seal. He cannot
   raise his hand against a Guardian.

**Qadir's One Rule (canon — characterization, not metaphysics).** The
Creative Director rejected making truthfulness a supernatural law; it
is something better. Qadir has *voluntarily* adopted one absolute
rule: he never speaks a deliberate falsehood. He omits. He redirects.
He frames. He answers different questions than the one asked. He
allows others to reach incorrect conclusions. But every factual
statement he makes is true. His honesty is a choice, made and kept for
centuries — which is considerably more frightening than a chain. All
future Qadir dialogue, in every book, is audited against this rule.

Across the centuries since, the bound man has worn many names and
lived many quiet, exemplary public lives. **"Qadir ibn Salim" is only
the latest.** No records connect the names, because the man who
manages the records has always, eventually, been him.

> **SUPERSEDED — see the status note at the head of this Spec.** This
> section identifies "the bound man" (the Black Vizier) with Qadir.
> The Master Story File separates them: the Black Vizier is the
> imprisoned being freed at the Seventh Gate, while Qadir is the
> Covenant's centuries-old *keeper*, not its prisoner. The imagery here
> — the many names, the always-managing-the-records — likely transfers
> to whichever of the two the Creative Director's rewrite assigns it
> to; do not treat "Qadir = the bound man" as canon in the meantime.

## III. The Seven Seals — What They Actually Are

Each Seal is **an oath made object**: the physical anchor of one of
the seven promises. They look ordinary — a white stone disc, warm from
carrying a life — because the object was never the power. The trust
is. A Seal is to its oath what a wedding ring is to a marriage:
evidence, not essence, and yet not nothing.

While its oath holds, a Seal is absolute in one narrow way: **it
cannot be taken.** Not by force, not by theft, not by the Black
Vizier, not by anyone. It can only be *given* — freely, by its sworn
keeper, into freely open hands. This is why the Guardians never guard
the object. There has never been any need. What they guard is the
decision.

## IV. The Guardians — Why They Live So Long

An oath cannot outlive its keeper. So the Covenant lends its keepers
time — not stopped, *lent*, the way a lamp is kept burning until
someone arrives to carry the flame onward. Guardians age, feel every
year, and can be hurt like anyone; they simply do not run out of time
until their oath is fulfilled. They are not immortal. They are
unfinished.

The seven oaths are woven together, and the weave has properties the
Guardians use without fully understanding:

- Guardians sense movement along it — arrivals, intentions, names.
  (Basim knowing Amir's name, shipped in Chapter 2, is the weave, not
  omniscience. His own explanation — "names travel faster than feet,
  out here, if you know how to listen" — is true, as far as he knows.)
- Shrines rest half inside it. They are found when their Guardian
  chooses to be found ("If the Guardian wishes to meet you, you
  will"), which is why the First Shrine surfaced from the sand only
  when it did.

**What the Guardians know:** the virtue they keep, the responsibility
of the Seals, and that the Black Vizier must never possess all seven.

**What the Guardians do not know:** who the Black Vizier is now, that
he walks free in mortal shape, that the renewal rite has been lost
(Section V), and therefore that entrusting their Seals — the thing
each of them has waited centuries and hopes to do — is, without the
rite, quietly dismantling the prison. They cannot warn Amir about
Qadir because they have nothing to warn him *with*.

## V. Entrusting — What Actually Happens

Canonical language, to be kept consistent throughout the series: **the
Guardians never transfer power. They transfer responsibility. The Seal
is not inherited. The burden is.**

When a Guardian freely places their Seal in a successor's hands:

1. **The oath ends — fulfilled, not broken.** This distinction
   matters; the Covenant does not punish its keepers.
2. **The lent time ends.** (Canon, per Creative Director review.) The
   Guardian becomes ordinary: they resume aging from where they stand
   and live out whatever natural life remains to them — a month or a
   decade, as their body decides. They do not die of entrusting.
   Canonical framing, per Design Spec 004's Hope pillar: **the
   Guardians are not dying. They are finally allowed to live again.**
   Basim is now mortal, aging naturally, and presumably still tending
   his shrine; freed Guardians are a Book Two resource.
3. **The successor receives the anchor — but not the oath.** The Seal
   in Amir's satchel is real, and really his, and holds real meaning.
   But it no longer anchors the prison. It is a lock carried out of
   its door.

The founders knew succession would someday be necessary, and built for
it: a **rite of renewal** by which the seven successors, together,
could swear the Covenant anew. Two things about it are canonically
true in Book One: it requires all seven Seals and all seven successors
gathered in one place, and **the knowledge of it has been lost** — not
dramatically, but the way Qadir does everything: archives flooded by
generously re-routed rivers, shrines defunded for compassionate
reasons, the one scholar who knew promoted to a distant post. Centuries
of it. (The Chapter 2 shrine-funding redirection already shipped in
the Mystery Ledger is one instance of this program, not an isolated
move.)

This is the tragic engine of Book One: **the gathering that could save
everything and the gathering that ends everything are the same
gathering.** The only difference is whether anyone present knows the
rite. No one will.

## VI. The Cost of Carrying — the Metaphysical Price

Unbound Seals do two things to their bearer:

1. **They measure.** A Seal continuously holds its bearer against its
   oath — not as judgment but as presence, the way carrying a sleeping
   child changes how you walk. This is the mythological basis for the
   trials changing Amir permanently, and for the escalating
   interiority of Chapters 4–8. Canonical distinction, per the
   Creative Director: **the Seals are not changing Amir. They are
   revealing him.** The weight is formative, never corrupting: the
   Seals are made of promises, and nothing about them tends toward
   darkness.
2. **They disturb.** (Modified from "audible" per Creative Director
   review.) Infernal beings do not hear the Seals; they sense
   *disturbances in the Covenant* — a change in pressure, the way the
   air turns before a storm. An entrusted Seal moving through the
   world is weather to them. One Seal is a shift too small to name.
   Three are a front building somewhere beyond the horizon. Seven
   gathered in one place are the storm itself, arrived — which is why
   the rival faction's inherited doctrine, "the seven must never be
   gathered," is *correct*, and why the public ceremony Qadir arranges
   in Chapter 8 is not merely a trap but a summons.

The escalation track in Design Spec 006 (private → hunted → personal →
civic → identity → existential → total) is the narrative surface of
these two mechanics.

## VII. What He Actually Wants

**What Qadir wants in Book One (canon-level, required by Spec 002):**
the seven anchors unbound by entrusting, gathered in one place, in
public reach. At that moment the Covenant has nothing left holding it;
the binding fails; his hands are free. He claims the Seals and inverts
them — a lock is a lock; it does not care what it closes — using the
anchors that once sealed the demonkind *away from him* to bind the
demonkind *to him*. Then he walks out. No battle, because he has
outgrown the need for one and the Covenant's collapse leaves nothing
to fight him with.

**What the Black Vizier wants beneath that (proposed, series-scale,
flagged for Creative Director decision):** the pacts that made him
have creditors, and eight centuries in a cell built of other people's
promises have taught him exactly what he thinks of being owned. The
title "Black Vizier" is what the pacts made of him; the man underneath
wants to owe no one — not the Covenant, and not the demonkind either.
Book One shows him escaping the first chain. What he intends about the
second is the seam Book Two opens, and this document deliberately
defines it no further.

## VIII. The Central Lie and the Central Truth

**The lie the player believes through Book One:** *The Seals are the
last defense against the darkness — gather them before its servants
do.* Every good character honestly believes some version of this.
Hakim believes it as a scholar, the Guardians believe their pieces of
it, Yasmina believes it, the player is never once lied to by anyone
except Qadir — and Qadir never lies at all.

**The truth revealed at the end of Book One:** *The Seals were the
prison.* The race was real, but Amir was the only runner; the finish
line was the trap. He couldn't gather them — every Seal had to be
freely given to worthy hands, and his were the worthiest available.
Qadir didn't steal the Seals from Amir. He waited while everyone
honest handed them forward, one trust at a time.

The ending hurts precisely because no trust was betrayed except the
one at the center: the Guardians chose truly, Amir was truly worthy,
the entrusting was truly earned — and all of it served the prisoner.

## IX. The Rival Faction's Fragment (concept-level, name/identity open)

The rival faction (per Design Spec 006 Post-Review Revision 4)
inherits a corrupted fragment of the true doctrine: **"the seven must
never be gathered."** They are right. They do not know why, they do
not know about the rite of renewal, and they have concluded the safest
bearer of the Seals is no one. Their opposition to Amir is therefore
sincere, almost correct, and tragically aimed at the wrong man. Their
origin — whether they descend from the Covenant's founders, from the
fallen empire, or from something else — is deliberately open.

## X. Hidden Until Later Books (do not resolve in Book One)

- The Broken Compass — what it is, why it never points north, why it
  reacts near Covenant matters (already Ledger-flagged Book 2).
- Amir's father — his contact with the Covenant, his fear of the
  river (already Ledger-flagged Book 2).
- Yasmina — what the Guardians recognize in her, what "your road will
  ask different things" means (deferred to her own Design Spec).
- The Marid (`$npc.marid`) — nature, allegiance, and role.
- Whether any record of the rite of renewal survives.
- The fates and future usefulness of the freed, now-mortal Guardians.
- The rival faction's origin and what becomes of it after Chapter 9.
- The pacts' creditors, and what the freed Black Vizier owes them.

## XI. Consistency Rules for All Future Implementation

1. Reveals surface only on the Mystery Ledger's schedule; this
   document never leaks to the page ahead of it.
2. Qadir never speaks a falsehood anywhere in the series — audit every
   line of his dialogue against this.
3. No Guardian may warn Amir about Qadir, hint at his identity, or
   sense him through the weave — they don't know, and the weave holds
   the prisoner *inside* it, invisibly, not as a signal on it.
4. Seals are never taken by force by anyone, anywhere, until Ch9 — and
   even then Qadir takes only what entrusting has already unbound.
5. The Retroactive Foreshadowing Rule applies: when this mythology
   makes an already-shipped moment newly meaningful, patch with one or
   two unexplained, emotionally natural sentences — never exposition.

## XII. Remaining Open Questions

Resolved by the Creative Director's review: the lie-binding (rejected
— replaced by Qadir's One Rule, Section II); freed Guardians (approved
— natural mortality, Section V); the virtues (to emerge from the Seven
Founding Oaths — Design Spec 008, commissioned).

Still open:

1. The fallen empire — named now, or left unnamed through Book One?
2. The rite of renewal — permanently lost, or does a fragment survive
   somewhere as Book Two's hope? (This document assumes lost *as far
   as Book One knows*, which keeps both options open.)
3. The Black Vizier's series-scale want (Section VII) — accept,
   revise, or defer entirely.

---

# The Seven Founding Oaths (Design Spec 008)

**Status: APPROVED by the Creative Director, with revisions — all
folded into the text below. The oath texts reflect the required
brevity/timelessness pass; earlier drafts live in git history.**

## Review Rulings (complete — canon)

1. **Core philosophy — APPROVED.** The Seven Oaths are now the oldest
   surviving words in the setting. Everything else descended from
   them: the Covenant, the Guardians, the Trials, the Seals, Amir's
   journey. They are the spiritual foundation of the series.
2. **Never RPG virtues — APPROVED.** The Oaths are promises. Every
   Guardian embodies one promise, and every Trial asks one question:
   *"Will you freely make this promise yourself?"* The player is never
   asked to recite an Oath — they prove it through action.
3. **Language — APPROVED WITH REVISION (executed below).** Timeless,
   inevitable, simple, memorable. Children should be able to remember
   them; old people should still discover new meaning in them. One
   unforgettable sentence over four beautiful ones — brevity creates
   permanence.
4. **The Founders ARE the First Guardians — CANON.** Basim did not
   inherit the First Oath; he spoke it, chose it, helped bind the
   Covenant. Every Guardian still living is one of the original Seven,
   waiting centuries for successors worthy enough to release them.
   Players are unknowingly speaking with living history.
5. **Farewells as worn Oaths — APPROVED.** Each Guardian's most
   memorable line should eventually be recognizable as their own Oath
   transformed by a lifetime of experience — and the player should
   only realize this on a second playthrough.
6. **Yasmina echoing the Fifth Oath — APPROVED.** Leave it completely
   unexplained. No one ever comments on it. Book One does not answer
   why.
7. **The Closing — MODIFIED (executed below).** Retain the meaning;
   rewrite until it feels carved into stone. It should become the
   single most recognizable quotation in the entire series.
8. **Qadir speaking the Closing in Ch9 — REJECTED.** Instead: Qadir
   quietly recognizes the ritual without claiming ownership of it —
   impossible familiarity with the Covenant, noticed only in
   hindsight. The post-book question "How could he have known that?"
   is more powerful than any direct reveal. (Folded into the Chapter 9
   architecture in Design Spec 006.)
9. **NEW CANON — The Oaths cannot be destroyed.** (Section below.)
10. **NEW CANON — Every Trial ends with silence.** (Section below.)
11. **NEW CANON — The Seals are intentionally ordinary; the Oaths are
    the true treasure.** (Section below, with the guiding principle.)

The deepest layer of the mythology. Everything above it hangs from
this document: **the Oaths create the Guardians. The Guardians embody
the Oaths. The Seals preserve the Oaths. The trials reveal the Oaths.**
And ultimately Amir himself — what the trials find in him, chapter by
chapter, is his unknowing capacity to have sworn each one.

The oath texts below are the deliverable. Everything else in this
spec exists to serve them. Per the Creative Director's instruction,
these should read like promises capable of holding back darkness for
centuries — quoted by generations that no longer remember what they
are quoting. They are presented for review, not as settled scripture:
the texts deserve iteration, and revision of any line is expected and
welcome.

## How the Covenant Was Spoken

Once, in seven voices, at the binding of the Black Vizier. Not a
ceremony — there was no one left to perform one for. Seven ordinary
people stood in a circle around a man who could not be killed, and
each in turn said what they were prepared to stake, and the saying
held.

They were not chosen. They were simply the ones who stayed.

The original tongue is lost; what the mythology preserves is the sense
of it, worn smooth by translation the way Basim's staff is worn smooth
by his grip. **Canon (per Creative Director ruling): the seven who
swore are the seven who keep.** The current Guardians are not
successors of the founders — they *are* the founders, still keeping
the promises they made, on time lent to them for exactly that purpose.
This follows Design Spec 005 ("centuries of waiting," "the title of
Guardian became inseparable from the individual") and makes every
farewell in the series the end of an eight-hundred-year sentence.
Basim did not inherit the First Oath. He spoke it. He chose it. He
helped bind the Covenant.

## The Oaths

### The First Oath
*(kept at the desert shrine — the Seal of Resolve; canon-anchored by
shipped Chapter 2)*

> When my reasons fail, I will keep walking.
> When my hope fails, I will keep walking.
> My heart will arrive before my feet.

What it holds: the refusal that cannot be bargained with. The Black
Vizier's power was made of terms — and there are no terms to offer
someone who has already agreed to lose everything and continue.

Already on the page: Basim's farewell touchstone — "the heart always
reaches its destination before the feet" — is his own oath, worn down
to a saying. He has been quoting himself for centuries, and no one
alive knows it.

### The Second Oath
*(kept at the abandoned fortress)*

> I will stand between the harm and the harmed.
> My fear will stand with me.
> We will not move.

What it holds: the shield that does not require courage to exist
before it works. The oath does not banish fear — it enlists it. The
trial built on it should never reward suppressing fear, only acting
honestly while afraid.

### The Third Oath
*(kept at the thriving orchard)*

> What I loved in the light,
> I will not leave in the dark.
> I will be found where I said I would be.

What it holds: presence. The orchard grows because someone has kept
showing up for eight hundred years. "I will be found where I said I
would be" is short enough for a parent to say at a doorway, heavy
enough for a deathbed. (The series' single most recognizable
quotation is reserved, by ruling, for the Closing.)

### The Fourth Oath
*(kept at the library)*

> I will see before I judge.
> If the scales fall against me, I will not touch them.

What it holds: honest measure. The last two lines are the teeth: a
judge who accepts a verdict that ruins them. The trial built on it
should make the fair reading of evidence personally costly.

### The Fifth Oath
*(kept at the observatory)*

> I will not dress my wishes as knowledge.
> I will say "I do not know," and I will keep looking.

What it holds: truth as a discipline rather than a possession.

Already on the page, unexplained: Yasmina's caravan-scene credo —
"I'd rather tell you 'I think' and be right twice as often than tell
you 'I know' and be wrong once where it costs someone something" — is
the Fifth Oath in a living girl's mouth, unprompted, untaught. This is
proposed as part of what the Guardians recognize in her. Per standing
canon, no Guardian explains it and neither do we.

### The Sixth Oath
*(kept at the lighthouse)*

> I will pay what the keeping costs, though no one sees the paying.
> Let the light be remembered and the keeper forgotten.

What it holds: the sacrifice that does not curdle into resentment
because it never asked for witnesses. A lighthouse keeper's whole
theology in four lines.

### The Seventh Oath
*(kept at the monastery in the cliffs)*

> I will not open every door my key fits.
> Some things I will carry and never look inside.

What it holds: restraint — the wisdom that knows the difference
between what can be done and what should be. Note the resonance with
the entire book: Amir will spend nine chapters carrying locks without
looking inside. The Seventh Oath is the one the whole story secretly
runs on.

### The Closing
*(spoken together, once, at the end)*

> Seven made one promise.
> Let it hold while we hold.
> Let it end in better hands.

Rewritten per the review toward something carved into stone: three
short lines, no ornament. This is intended to become the
single most recognizable quotation in the entire series; further
iteration remains welcome until it feels inevitable.

"Let it hold while we hold" is the tragedy stated in advance: the
Covenant's strength and its expiration are the same clause. And "let
it end in better hands" is Chapter 9 in six words — it *did* end in
better hands. Amir's hands were exactly as good as the founders prayed
for. That is precisely how Qadir wins. Nothing in the Covenant failed;
it was fulfilled to the letter, and the letter was the trap.

## The Sigil Lore

Already shipped and now unified: each individual Seal bears **a single
unbroken circle** (the Seal of Resolve, Chapter 2) — one oath, whole
in itself. The Covenant entire is drawn as **a circle broken in seven
places** — seven arcs, seven oaths, closing one ring (the ward-sign
burned into the flagstones in Chapter 1, and Hakim's "a broken circle,
seven divisions"). The full ring appearing where something dies or
leaks through is the signature of the binding under strain.

## Folk Echoes (already shipped — the Oaths hiding in plain sight)

The Oaths survive in the culture as degraded quotation, which shipped
Chapters 1–2 already contain — unplanned then, canon now:

- The Ch1 storyteller's tale: a treasure broken into seven pieces,
  each charged to a guardian who tests seekers "not with steel, but
  with character" — the Covenant, remembered as entertainment.
- Sabiha's hospitality law ("any traveler who shares your fire is owed
  protection until dawn... some laws don't need soldiers to enforce
  them") — descendant custom of the Second and Third Oaths.
- The pilgrim's proverb, "Hospitality repaid is hospitality
  understood."
- Basim's farewell saying (First Oath, self-quoted).
- Yasmina's caravan credo (Fifth Oath, unknowing).

Future chapters should continue this pattern: the Oaths should be
audible in proverbs, lullabies, market sayings, and prayers long
before any character learns what they are quoting.

## On-Page Usage Rules

1. **Fragments before wholes.** Through most of Book One the Oaths
   surface only as echoes and worn sayings. The full text of an
   individual Oath may appear at most once per book.
2. **Each Guardian may speak or closely paraphrase their own Oath
   exactly once — at their farewell.** This *is* the Design Spec 005
   touchstone-line requirement, now unified with the mythology:
   Basim's farewell already conforms retroactively. Per ruling, the
   player should only realize the farewell-is-the-Oath pattern on a
   second playthrough — never signal it.
3. **The Closing is never spoken aloud in Book One. No exceptions.**
   (The Qadir-speaks-it proposal was rejected.) In Chapter 9, Qadir
   instead quietly recognizes the ritual without claiming ownership —
   impossible familiarity, legible only in hindsight, so the finished
   player asks: "How could he have known that?"
4. Never annotate an echo. When Yasmina speaks like the Fifth Oath, no
   character notices on the page, per the Retroactive Foreshadowing
   Rule: the truth is visible before it is understood.

## What the Oaths Are Not

Not commandments — no one is punished by them. Not magic words — 
reciting an Oath does nothing; keeping it does everything. Not virtues
from a list — the shorthand names people later gave them ("Resolve"
is the only shipped example) are folk labels, and the remaining six
labels are left for the Creative Director to derive from these texts,
or to request as a follow-up proposal.

## The Oaths Cannot Be Destroyed (canon)

Even if every written copy vanished, every Guardian remembered them.
Now Amir remembers them. Ideas survive — that is why the Covenant
survives, and it is one of the central themes of the series: darkness
can destroy walls; it cannot erase freely chosen promises.

## Every Trial Ends with Silence (canon)

Not applause. Not magical spectacle. Not dramatic music. Silence. The
Guardian waits. The player reflects. Only then is the Seal entrusted —
reflection is part of the Trial. This extends Design Spec 005's trial
rules and binds every future Guardian scene. (The shipped Chapter 2
trial already conforms: Amir stands alone in the empty chamber "long
enough that it stops feeling like a delay and starts feeling like an
answer" before Basim speaks or the Seal appears.)

## The Seals Are Ordinary; the Oaths Are the Treasure (canon)

The Seals are intentionally ordinary objects. The Oaths are the true
treasure. Guiding principle for every remaining chapter, verbatim from
the Creative Director:

> "The important thing was never collecting the Seals. It was becoming
> the kind of person the Seals would be entrusted to."

Shipped Chapter 1 already whispers this: the storyteller by the
fountain, asked whether the scattered treasure was gold, laughs and
says treasure is never gold — not really — and refuses to explain what
he means.

## Remaining Open Questions

Resolved by the complete review: the oath texts (revision pass
executed above); founders-are-the-Guardians (canon); the
Closing-in-Ch9 proposal (rejected — replaced by the
impossible-familiarity beat, folded into Design Spec 006's Chapter 9).

Still open:

1. **The rite and the sole successor** — the rite of renewal
   contemplates seven successors; Book One delivers every Seal to one.
   Whether that asymmetry is Qadir's deepest manipulation of all, a
   Book Two door, or both, is deliberately left undecided here.
2. **Folk labels for Oaths 2–7** — derived by the Creative Director
   directly, or proposed by the Implementation Lead as a follow-up?
   (Blocks finalizing the placeholder virtues in Design Spec 006's
   Seal table.)
3. **The Closing's final wording** — the rewrite above is offered
   toward "carved into stone"; iterate until inevitable.

---

# Character Bible (Design Spec 009)

**Status: DRAFT — submitted for review. Non-blocking per the Creative
Direction Reset: implementation proceeds chapter-driven while review
is awaited, and these entries serve as working reference rather than
locked canon until approved.**

Arcs, not biographies, per the commission. Constraints honored
throughout: Yasmina's entries are arc-level only — her biographical
specifics remain deferred to her own future spec (Design Spec 006,
Post-Review Revision 5). Farah's and the father-related entries stay
inside the Mystery Ledger's Book 2 reveal flags. Every **Book Two
trajectory is non-implementable** — one paragraph, never to be used,
hinted at, or foreshadowed by implementation without a future spec.

## Amir

- **Core wound:** He grew up inside an unanswered question — a father
  no one would explain, a pendant no one would discuss, a river his
  mother won't name. Home was full of love and empty of answers.
- **Core desire:** To matter to something larger than the street he
  grew up on — and, beneath that, to finally understand where he
  comes from.
- **Greatest fear:** At the start: that he is ordinary. By the end:
  that the people who believe in him will pay for having done so.
  (Chapter 9 makes both fears come true in one stroke.)
- **Fatal flaw:** He believes trust, once earned, is settled — that
  worthiness proven is worthiness permanent. He audits enemies, never
  friends. Qadir's entire plan is built on exactly this.
- **Greatest strength:** He keeps walking (the First Oath lives in
  him before he ever hears it). His care for ordinary people is
  genuine, not performed — the trials keep finding it real.
- **Relationship arc across Book One:** From a baker's son with a
  training sword to the sole bearer of seven promises — moving through
  each Guardian's admiration, Yasmina's partnership, the court's
  regard, and Qadir's counterfeit mentorship.
- **How he changes because of others:** Each Guardian leaves one
  permanent mark (per the Seal rhythm); Yasmina teaches him honest
  uncertainty; Farah's steadiness becomes the floor under his Resolve;
  Qadir teaches him — at the very end — that goodness without
  discernment is a door left open.
- **How others change because of him:** See each entry below; the
  common thread is that Amir makes people braver about what they
  already believed.
- **What he still hides at the end of Book One:** The compass and what
  it does near Covenant matters (told no one; Yasmina has only seen
  fragments). His growing, unspoken certainty that his father is
  somewhere inside this story. And — after Chapter 9 — his private
  belief that the betrayal was somehow his fault.
- **Book Two trajectory (non-implementable):** From collector to
  keeper. The rite contemplates seven successors; there is one of him.
  Book Two's Amir must decide whether the Covenant is re-sworn,
  re-founded, or replaced — and what his father's road has to do with
  his own.

## Yasmina
*(arc-level only; biographical specifics deferred by standing ruling)*

- **Core wound:** She has spent her life being almost-believed —
  brilliant in a world that finds her brilliance charming rather than
  load-bearing. Her father is the only one who ever weighed her
  conclusions instead of her age.
- **Core desire:** To truly know — and to be trusted with the knowing
  when it matters, not after.
- **Greatest fear:** That the first time she is wrong will be the time
  it costs someone she loves (her caravan credo is this fear spoken
  aloud — and, unknown to all, the Fifth Oath).
- **Fatal flaw:** Self-sufficiency. She would rather carry a doubt
  alone than hand anyone an unverified fear — which means the moment
  she begins suspecting something is wrong, her instinct is silence
  until proof. (This flaw should cost the party visibly at least once
  before Chapter 9.)
- **Greatest strength:** Intellectual honesty as a way of life. She is
  the only major character who never once deceives herself on the
  page.
- **Relationship arc across Book One:** Companion → equal partner
  (Ch2, canonized by the trial) → co-protagonist. The Guardians keep
  marking her, unexplained. First serious disagreement with Amir in
  Ch5; the bond becomes load-bearing in Ch7; her reaction anchors the
  player's in Ch9.
- **How she changes because of Amir:** She learns to act on "I think"
  — to move before certainty when someone needs it, because she has
  watched Amir do it and live.
- **How Amir changes because of her:** He learns that saying "I do not
  know" out loud is strength; her discipline of doubt becomes the only
  tool he has left after Chapter 9.
- **What she still hides at the end of Book One:** What Basim told her
  ("your road will ask different things") and every Guardian moment
  like it since — she has been collecting them, privately, and has
  not told Amir. Whatever she has begun to suspect they mean.
- **Book Two trajectory (non-implementable):** Her own road begins
  asking. The deferred history spec defines what the Guardians
  recognized; Book Two makes her a protagonist of her own journey
  rather than a partner in Amir's.

## Qadir ibn Salim

> **UNDER REVISION per the Master Story File:** Qadir is not the Black
> Vizier. The wound / desire / fear entries below were written on the
> superseded identification and must be re-derived once the Creative
> Director rewrites the mythology. What survives unchanged: his One
> Rule, his patience, his flaw's shape (trust read only as leverage),
> his Book One surface arc, and the requirement that every kindness he
> ever showed was textually genuine (Master File §11.5).

- **Core wound:** He was once genuinely the greatest servant his
  empire ever had — and everything he built was consumed by what he
  paid to build it, including his own name. Eight centuries of
  imprisonment in politeness followed.
- **Core desire:** To owe no one. Freedom from the Covenant first;
  beyond that (non-implementable, per the Mythology Bible's flagged
  seam) freedom from the pacts' creditors too.
- **Greatest fear:** Being owned again — any cage, anyone's terms,
  ever.
- **Fatal flaw:** He cannot conceive of freely given trust as anything
  but leverage. Promises, to him, are terms; love is a clause. He can
  predict everything people do for advantage and almost nothing they
  do for a promise's own sake. (Book One never punishes this flaw.
  That is the point. Later books exist because of it.)
- **Greatest strength:** Patience measured in centuries, and his One
  Rule — the discipline of never speaking a deliberate falsehood,
  kept voluntarily for eight hundred years.
- **Relationship arc across Book One:** Static on the surface — the
  trusted Vizier — while the mentor-shaped trap closes by degrees:
  benefactor (Ch1), quiet enabler (Ch3), protector (Ch4), the court's
  indispensable center (Ch6), and finally the man everyone is glad is
  standing beside the Sultan at the ceremony (Ch9).
- **How he changes because of Amir:** Barely — and the barely matters.
  Amir keeps passing trials in ways Qadir's model of humanity says
  should not happen. He files each anomaly away rather than learning
  from it. (Seed, never sprouted in Book One.)
- **How Amir changes because of him:** Chapter 9. The wound that ends
  the book and forges whoever Amir becomes next.
- **What he still hides at the end of Book One:** Nearly everything —
  the creditors, his next intention, and whatever he knows of Amir's
  father (deliberately unresolved, per standing open question).
- **Book Two trajectory (non-implementable):** The second chain. He
  escaped the Covenant; the pacts remain. Deliberately undefined
  further, per the Mythology Bible's open question.

## Sultan Rashid

- **Core wound:** He inherited a throne he privately suspects belongs
  to a better man, and has spent his reign compensating with sincerity
  what he fears he lacks in brilliance.
- **Core desire:** To be a good ruler in the eyes of ordinary people —
  the festival, the lanterns for the poor quarter, light shared.
- **Greatest fear:** Failing the city through his own inadequacy —
  which is precisely the fear Qadir tends, waters, and directs.
- **Fatal flaw:** He delegates his judgment. Knowing Qadir is the
  most capable man in the room, he has quietly stopped weighing
  Qadir's counsel — the one mind in the Sultanate that never gets
  audited.
- **Greatest strength:** Genuine humility and real love for his
  people. There is no vanity to flatter, which is why Qadir works
  through his fears instead.
- **Relationship arc across Book One:** Benevolent background (Ch1) →
  increasingly Qadir-dependent under crisis (Ch6) → proud patron of
  Amir's success (Ch8) → the man who unknowingly hosts the end of the
  world's oldest protection (Ch9), betrayed in front of his own city.
- **How he changes because of Amir:** Late in Book One he begins to
  see in Amir the kind of counsel he wishes he had — someone who tells
  him true things without managing him.
- **How Amir changes because of him:** Rashid is Amir's mirror and
  warning: goodness without discernment is exploitable. Amir does not
  understand the lesson until Chapter 9 makes it autobiography.
- **What he still hides at the end of Book One:** His shame — and a
  growing private list of decisions (shrine funds among them) that he
  signed because Qadir made them easy, and now cannot stop re-reading.
- **Book Two trajectory (non-implementable):** Rebuilding a betrayed
  Sultanate, and deciding what a throne owes the truth.

## Hakim Nadir

- **Core wound:** He found threads of the Covenant decades ago — and
  let a respectable career talk him into calling them myth. The ghūl
  in the square proved him right thirty years too late.
- **Core desire:** The truth — and his daughter safe. Book One slowly
  turns these into the same desire pulling in opposite directions.
- **Greatest fear:** That his research is the thing that gets Yasmina
  killed.
- **Fatal flaw:** Caution disguised as method. He hedges, verifies,
  waits for one more source — and the delay keeps costing exactly the
  time the story cannot spare.
- **Greatest strength:** Intellectual integrity. He taught Yasmina the
  Fifth Oath's way of thinking without ever knowing what he was
  teaching — the Covenant survived partly in a scholar's habits.
- **Relationship arc across Book One:** Gatekeeper (Ch1) → reluctant
  quartermaster of the quest (Ch2) → the fixed point the expanding
  journey keeps returning to — maps, fragments, leads — while each
  return costs him another goodbye to his daughter.
- **How he changes because of Amir:** He learns to trust Amir with
  Yasmina — the hardest peer review of his life — and, through Amir's
  example, to publish his convictions before they are fully proven.
- **How Amir changes because of him:** Hakim is the first adult who
  answers Amir's questions instead of deflecting them — a
  father-shaped figure whose honesty makes the silence around Amir's
  real father newly loud.
- **What he still hides at the end of Book One:** *(Proposal, flagged
  for Creative Director decision.)* A fragment he has not shared —
  something found while researching the Guardians that he is still
  verifying, contents unspecified here. If accepted, this is a hook
  whose payload the Creative Director defines later; if rejected,
  Hakim hides only his fear.
- **Book Two trajectory (non-implementable):** The scholar of the
  aftermath — whether any record of the rite survives is a question
  shaped exactly like him.

## Farah

- **Core wound:** She lost her husband to something he never explained
  — and was left with a son, a bakery, and questions she decided,
  deliberately, to stop asking. (All specifics remain behind the
  Mystery Ledger's Book 2 flags.)
- **Core desire:** To keep Amir safe — and in her experience, safe
  and *ordinary* are the same word.
- **Greatest fear:** That the thing that took her husband has finally
  come back for her son. She has never said this aloud, and will not.
- **Fatal flaw:** Silence as protection. She believes not naming a
  danger starves it — so she deflects ("Your father hated that river.
  Never told me why."), and every deflection leaves Amir less prepared
  than the truth would have.
- **Greatest strength:** Practical love. She packs bread instead of
  weeping; her farewell blessing is logistics. Steadiness is her
  native language, and Amir inherited it as Resolve.
- **Relationship arc across Book One:** The home Amir leaves (Ch2) →
  the reason word-from-home matters in the middle chapters → one of
  the few people in Zafirah whose world Chapter 9 does not upend,
  because she never trusted the palace to begin with.
- **How she changes because of Amir:** She converts protection into
  blessing — learns to let him go without pretending it costs
  nothing.
- **How Amir changes because of her:** Her steadiness is the floor
  under everything the trials find in him. The First Oath, when he
  finally hears it, sounds like his mother.
- **What she still hides at the end of Book One:** What she actually
  knows or suspects about the river, the pendant, and why her husband
  feared what he feared — contents reserved to the Book 2 reveal
  schedule, not to be specified or hinted beyond the Ch1 deflection
  already shipped.
- **Book Two trajectory (non-implementable):** When the father
  mysteries surface, Farah stops being background and becomes a
  primary source — and has to answer for the silence.

## Sheikh Basim

- **Core wound:** Eight hundred years of outliving everyone he loved —
  the unlisted price of the First Oath. He never calls it a wound. It
  is one.
- **Core desire:** Fulfilled in Chapter 2 — worthy hands. What
  remains is smaller and human: to see a little of how the story ends
  before his natural time does.
- **Greatest fear:** It ended the day he handed over the Seal. For
  centuries it was choosing wrongly after so long waiting. What is
  left is fear *for* Amir, not of anything for himself — a man whose
  own fear has finally retired.
- **Fatal flaw:** Patience complete enough to border on passivity. He
  waited at his shrine while the world forgot the Covenant — keeping
  his oath perfectly and letting everything around it erode. (He
  would say the flaw and the oath were the same thing. He might be
  right. That tension is worth keeping.)
- **Greatest strength:** Resolve embodied — and the peace of a man
  with nothing left to prove, which is what makes players trust him
  instantly (per the Guardian Bible's design contrast with Qadir).
- **Relationship arc across Book One:** The first meeting (Ch2) — and
  therefore the template every later Guardian is measured against.
  Now mortal, aging naturally, tending a shrine that no longer needs
  guarding.
- **How he changes because of Amir:** Released. Not dying — finally
  allowed to live again (canonical framing).
- **How Amir changes because of him:** First proof that strength has
  little to do with force. His worn-smooth saying becomes Amir's
  touchstone in every later dark moment, exactly as Design Spec 005's
  farewell rule intends.
- **What he still hides at the end of Book One:** Only what he said to
  Yasmina — and he does not know Qadir's identity, so he cannot hide
  it (consistency rule: no Guardian knows). He hides nothing with
  intent; he simply answers only what is asked.
- **Book Two trajectory (non-implementable):** A mortal witness of
  the founding — the only firsthand account of the binding that is
  also running out of natural time. Priceless, and perishable.

## Open Questions for Creative Director Review

1. **Hakim's withheld fragment** — accept as a hook (payload yours to
   define later), or reject so Hakim hides only his fear?
2. **Amir's fatal flaw** — "trust once earned is settled" is proposed
   as the flaw Qadir exploits; confirm, or redirect before Chapter 3
   dialogue begins encoding it.
3. **Yasmina's flaw costing the party** — the draft proposes her
   proof-before-warning instinct should visibly cost something once
   before Ch9 (so her Ch9 self-recrimination has a referent). Confirm
   placement (Ch5 or Ch6 seem natural) or reject.
4. **Qadir's "anomaly file"** — his flaw never punished in Book One,
   only seeded; confirm this stays entirely subtextual.

Awaiting review; non-blocking. Implementation proceeds chapter-driven
per the Creative Direction Reset.
