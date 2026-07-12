# Game Bible

Master vision document. Canonical unless superseded by a later Design
Specification from the Creative Director. Internal reference only —
nothing in this file should be exposed to the player through codex,
journal, or dialogue text ahead of its scripted reveal.

Sources: Design Spec 002 (Book One Production Roadmap, v1.0) and
Design Spec 004 (Book One Production Philosophy, v1.0).

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
