# Chapter 3 — Echoes in the Dust

Status: **Complete**, implemented against the Chapter 3 Story Overview
(authoritative) with the Spec 006 architecture as secondary reference.
The overview superseded the earlier Spec 006 sketch: no palace-court
sequence, the trusted-intermediary introduction is deferred beyond
Ch3, and Qadir's concealed move is records-into-the-wrong-hands (see
`MYSTERY_LEDGER.md`).

## Scenes

1. Opening (`Ch3_Opening`) — the story outgrows Amir; Zafirah rumor
   texture; Farah's "the fishmonger bowed to me."
2. Rumors hub (`Ch3_Rumors_Hub` + Bilal / pilgrim / guard captain
   optionals) — the world pushes back: exaggeration, veneration,
   skepticism. Contains the Black Vizier idle-curse texture line
   (unremarked, per the Spec 006 presence requirement).
3. The pattern (`Ch3_Study`) — the symbol recurs across generations of
   travelers' accounts; the accounts converge on the Sunken Library.
4. The road east (`Ch3_Road`) — campfire scene, three-way relationship
   choice; seeds the Amir-listens arc.
5. The Sunken Library (`Ch3_Library_Arrival` + hub with reading hall /
   map room / scriptorium optionals) — beauty in decay; signs of prior
   visitors; the charcoal "WHICH OF THE SEVEN?"; Yasmina's joy scene
   (scriptorium); a Third-Oath folk echo (child's copybook,
   unremarked); the survey fragment (optional, pays off in scene 9).
6. The gray scholars (`Ch3_Scholars` → `Ch3_Scholars_Fight` →
   `Ch3_Scholars_Fight2` → `Ch3_Scholars_End`) — debate first (with a
   let-Yasmina-answer growth option), then the first human conflict:
   two rounds, choice-driven, no fatalities; some surrender, some
   flee; the youngest always escapes with copied pages ("Not to
   them!").
7. The damaged journal (`Ch3_Journal`) — written by someone who
   personally knew a Guardian; final pages cut, not rotted; the intact
   line: "the fortress that watches the wind."
8. Aftermath (`Ch3_Aftermath`) — the used, pitiable scholars
   (recruited by faceless learned letters); mercy choice
   (release/hand over).
9. Night camp + return (`Ch3_NightCamp`, `Ch3_Return`) — Yasmina lays
   out the whole pattern; "we" stops needing saying; Hakim confirms
   three independent sources for the Fortress; urgency hook; End of
   Chapter 3 (no forward link — Chapter 4 next).

## New/expanded state

- `$places.sunkenLibrary` — new location entry.
- Key item "Damaged Journal"; codex entries (places, lore, items).
- New `$choices` flags: `ch3RumorsHubSeen`, `sawRumorBilal/Pilgrim/
  Captain`, `ch3CampTalk`, `ch3LibraryHubSeen`, `sawReadingHall/
  MapRoom/Scriptorium`, `ch3Debate`, `ch3FightFirst`, `ch3FightEnd`,
  `ch3ScholarsFate`.
- Reuses `$combat` for the two-round human conflict; all state
  mutation through existing widgets.

## Flagged creative gaps (filled with reasonable implementation, per the Reset)

- **"The Sunken Library"** — name coined here; easy to rename.
- **The gray scholars** — deliberately NOT identified with the
  protective rival-faction concept; their patron is faceless. The
  Unseen Searcher's identity stays open per the overview ("the answer
  should remain hidden").
- **The escaped scholar** — uncast and unnamed ("thin, young"); the
  overview says he becomes important, so casting is left fully open.
- **Trusted-intermediary introduction** — deferred beyond Ch3 by the
  overview; needs a landing spot in a future chapter.

## Next

Chapter 4 — The Fortress That Watches the Wind (Story Overview
received and logged in `GAME_BIBLE.md`; implementation next).
