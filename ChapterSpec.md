# Chapter 4 — The Fortress That Watches the Wind

Status: **Complete**, implemented against the Chapter 4 Story Overview
(authoritative). The overview superseded parts of the Spec 006 sketch:
on-page enemies are hired desert raiders (not the rival faction, which
stays unseen), and there is no intermediary relay.

## Scenes

1. The road runs out (`Ch4_Road`, `Ch4_Camp`) — broken cliffs, the
   rope bridge (three-approach choice), cold camp, the
   comfortable-silence beat.
2. Hours behind (`Ch4_Signs`) — fresh rope, boot prints, a
   professionally cold fire; Amir's frustration (with a
   read-the-signs listening option). Rival never shown.
3. Arrival (`Ch4_Fortress`) — built to endure; prayer banners at
   impossible heights; lonely, not haunted.
4. The man at the wall (`Ch4_Wall`, `Ch4_Wall_Work`) — Tariq
   (provisional name), mason's cadence; asks for help before names;
   the trial begins unannounced (`$trial.progress` tracks
   responsibility choices invisibly). His unexplained Yasmina beat
   (handing her the next stone).
5. Inside (`Ch4_Hub` + carvings / training yard / watchtower
   optionals) — the Standing People; "Fear stands in the line too"
   (Second-Oath folk echo, unremarked); the visitors who "asked
   nothing."
6. Shelter (`Ch4_Travelers`, `Ch4_Travelers_Work`) — guide, herder
   Khalid, daughter Noor, two pilgrims; storm coming; Yasmina becomes
   the fortress's quartermaster on her own merits.
7. The raiders (`Ch4_Raiders` → two combat rounds → `Ch4_Raiders_End`)
   — desperate hired men from the drought country; parley option;
   uncomfortable victory; Salt-beard's "He didn't say they were kept."
8. The storm (`Ch4_Storm`, `Ch4_Storm_Rescue`) — the collapse, "You
   already know what matters," Salt-beard going in ahead of Amir for
   his own boy, Yasmina calling the collapse patterns from the
   doorway. Everyone lives.
9. After (`Ch4_Storm_After`) — the raiders leave changed; the
   handshake.
10. The Seal (`Ch4_Seal`, `Ch4_Farewell`) — the canonical
    trial-ends-in-silence beat at the wall; "Courage is rarely loud";
    entrusting with no ceremony; Tariq's unexplained parting line to
    Yasmina; the lingering image (stone by stone).

## New/expanded state

- `$npc.tariq` (provisional name), `$places.windFortress`.
- `$seals.second = true`, `$seals.total = 2`; key item "The Second
  Seal"; codex entries.
- `$trial` reused as the invisible responsibility tracker; `$combat`
  reused for the two-round raider fight.
- New `$choices` flags: `ch4HubSeen`, `sawCarvings/TrainingYard/
  Watchtower`, `ch4Parley`, `ch4FightFirst`, `ch4FightEnd`.

## Flagged creative gaps (filled per the Reset, easy to revise)

- **"Tariq"** — provisional Guardian name per standing ruling; a
  rename is a find/replace plus the NPC entry.
- **"The Second Seal"** — deliberately NOT given a virtue label
  in-game, since virtues 2–7 are placeholders pending the folk-label
  ruling; the key item can be renamed (e.g. "Seal of Courage") when
  the Creative Director rules.
- **Salt-beard and the boy raider** — uncast minor characters; the
  overview's "one risks his own life to save another" beat is
  fulfilled by Salt-beard. He offers a drought-country door that a
  future chapter could pay off or ignore.

## Next

Chapter 5 — The Orchard of Forgotten Springs (Story Overview received
and logged in `GAME_BIBLE.md`; implementation next).
