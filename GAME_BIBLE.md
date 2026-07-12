# Game Bible

Master vision document. Canonical unless superseded by a later Design
Specification from the Creative Director. Internal reference only —
nothing in this file should be exposed to the player through codex,
journal, or dialogue text ahead of its scripted reveal.

Sources: Design Spec 002 (Book One Production Roadmap, v1.0), Design
Spec 004 (Book One Production Philosophy, v1.0), Design Spec 005 (The
Guardian Bible, Part I — Foundational Design, v1.0), Design Spec 006
(Book One Story Architecture, v1.0 — **approved in principle** by the
Creative Director with revisions recorded in its Post-Review Revisions
block; provisional elements remain non-canon), and Design Spec 007
(The Mythology Bible, v1.0 draft — **pending review and approval**; no
chapter implementation until approved).

## Book One Goal

The player believes they are protecting the Sultanate, collecting the
Seven Seals before the servants of darkness, and preventing the return
of demons.

The truth: every Seal willingly delivered to Amir removes another
obstacle preventing Qadir's freedom. When every Seal is gathered,
Qadir takes them, breaks his prison, binds the demons to himself, and
escapes. Book One ends there — the player believes they lost. Book
Two's central conflict is not to be revealed in Book One.

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
revisions below.** Architecture only. No dialogue, no passages, no
implementation. The chapter skeleton (objectives, emotional themes,
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
- **The Mythology Bible** (Design Spec 007, drafted below — needed
  before Chapter 3 implementation and before virtues 2–7 can be
  finalized).

---

# The Mythology Bible (Design Spec 007)

**Status: DRAFT — awaiting Creative Director review and approval. No
chapter implementation proceeds until this document is approved.**

Once approved, this is the single source of truth for every
supernatural element in the series. Where earlier documents touch the
same ground, this document is the deeper, governing statement. It is
entirely backstage: player-facing reveals remain governed by the
Mystery Ledger's schedule, and nothing here is license to surface lore
early. Drafted by the Implementation Lead; every mechanism below is a
proposal built to fit all shipped content and prior specs without
contradiction, and each section the Creative Director should
particularly scrutinize is flagged.

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
   raise his hand against a Guardian. And — this is proposed as the
   mythological root of his defining trait — **he cannot speak a
   lie**. The Covenant was made of true promises; its prisoner is held
   to truth. Everything he says must be true. He has had centuries to
   master the art of letting the truth deceive.

*Design intent: Design Spec 004's rule that "everything Qadir says
remains true — he simply allows others to misunderstand" stops being a
stylistic choice and becomes a chain he wears. This is flagged for
Creative Director scrutiny because it retroactively converts a voice
rule into hard metaphysics — a strong move, but one that binds all
future Qadir dialogue everywhere in the series.*

Across the centuries since, the bound man has worn many names and
lived many quiet, exemplary public lives. **"Qadir ibn Salim" is only
the latest.** No records connect the names, because the man who
manages the records has always, eventually, been him.

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

When a Guardian freely places their Seal in a successor's hands:

1. **The oath ends — fulfilled, not broken.** This distinction
   matters; the Covenant does not punish its keepers.
2. **The lent time ends.** The Guardian becomes ordinary: they resume
   aging from where they stand and live out a natural remainder.
   (Proposed: they do *not* die upon entrusting — Design Spec 004's
   Hope pillar argues for Basim still tending his shrine, mortal and
   content, and freed Guardians are a Book Two resource.)
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
   virtue — not as judgment but as presence, the way carrying a
   sleeping child changes how you walk. This is the mythological basis
   for the trials changing Amir permanently, and for the escalating
   interiority of Chapters 4–8. The weight is formative, never
   corrupting: the Seals are made of promises, and nothing about them
   tends toward darkness.
2. **They are audible.** To demonkind, an unbound Seal is a struck
   bell that never quite stops ringing. One Seal is a rumor. Three are
   a trail. Seven gathered in one place are a beacon — which is why
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

## XII. Open Questions for Creative Director Review

1. The lie-binding (Section II) — canonize Qadir's truthfulness as
   metaphysics, or keep it as characterization only?
2. The fallen empire — named now, or left unnamed through Book One?
3. Freed Guardians live out natural lives (proposed) vs. die upon
   entrusting — affects Basim's availability as early as Chapter 3.
4. The rite of renewal — permanently lost, or does a fragment survive
   somewhere as Book Two's hope? (This document assumes lost *as far
   as Book One knows*, which keeps both options open.)
5. The Black Vizier's series-scale want (Section VII) — accept,
   revise, or defer entirely.
6. With this mythology in place, the seven virtues can now be derived
   from the seven founding oaths — should the Implementation Lead
   propose that derivation as a follow-up for review, or will the
   Creative Director specify the virtues directly?

Awaiting review. No Chapter 3 implementation until approved.
