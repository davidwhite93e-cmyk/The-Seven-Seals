# Chapter 5 — The Orchard of Forgotten Springs

Status: **Complete**, implemented against the Chapter 5 Story Overview
(authoritative — the emotional heart of Book One).

## Scenes

1. The valley (`Ch5_Valley`, `Ch5_Village`) — water heard before
   seen; Three Springs ("only two still run"); hospitality; nobody
   here has heard of the hero — Amir puts down a pack he forgot he was
   carrying. Amina seeded casually as "the old gardener."
2. The trouble (`Ch5_Trouble`) — the dead east spring, the failing
   middle one, the fear nobody says in front of the children. Nobody
   asks for help; Amir offers (first trial beat, untelegraphed).
3. Days in the green (`Ch5_Life_Hub` + four optionals) — the happy
   middle: Yasmina owns the waterworks and earns *muhandisa* on her
   own name; an afternoon among Amina's figs (the trial disguised as
   easy questions); music in the threshing court (Yasmina's
   throat-back laugh; Amir notices, says nothing); the walk about
   nothing (optional father's-ledgers confidence — deepest
   relationship beat in the game so far, still behind the Book 2
   flags).
4. The aqueduct (`Ch5_Aqueduct`) — the collapse; the broken circle
   under the mineral crust; the valley is *built on* a Covenant place.
5. The temptation (`Ch5_News`) — gray strangers on the north road;
   every day here is a day lost; stay-vs-leave choice (choosing
   "leave in three days" is honored, then overtaken by events —
   failure teaches, per canon; both paths converge on staying).
6. The night encounter (`Ch5_Creatures` ×2) — blind, starving things
   driven up from the failing deep; protector combat: torch-lines /
   barricades / evacuation, then holding the ravine path by presence
   rather than slaughter. Everyone lives, including (mostly) them.
7. The mending (`Ch5_Repair`) — twelve days of mud and rope; the dead
   spring talks again; the valley goes joyfully out of its mind.
   Amina's silent visit to the mark (unremarked; legible on reread).
8. The reveal (`Ch5_Reveal`) — arrival, not surprise; the silence at
   the head-spring (canonical trial-ends-in-silence); "You stayed.";
   "I had begun to wonder if you would ever stop trying to leave.";
   the Third Seal entrusted like a seed packet; her worn-Oath
   farewell ("I was found where I said I would be... now go and be
   the same") and the pruning line.
9. Departure (`Ch5_Departure`) — sunrise, children, both fountains
   running, the gardener not looking up; the long full silence;
   "I hope we remember places like this." / "I don't think I could
   forget."

## New/expanded state

- `$npc.amina` (provisional name, per standing ruling),
  `$places.orchardValley` ("Three Springs Valley" — name coined here,
  easy to change).
- `$seals.third = true`, `$seals.total = 3`; key item "The Third Seal"
  (virtue label withheld pending the folk-label ruling, same policy as
  Seal 2).
- New `$choices` flags: `ch5HubSeen`, `ch5SawIrrigation/Amina/Evening/
  Walk`, `ch5Wavered`, `ch5NightPlan`.
- `$trial` reused invisibly; `$combat` reused for the night encounter.

## Flagged creative gaps (filled per the Reset)

- Village/valley name ("Three Springs"), host (Umm Salma), and the boy
  Faris — coined minor characters, no NPC-database entries (matches
  the Bilal/Umm Layla pattern).
- The pale creatures are deliberately unnamed and un-codexed as
  monsters — they read as displaced animals, not a bestiary entry,
  matching the protector framing.
- Amina's farewell speaks her own Oath once, worn ("found where I
  said I would be"), per Spec 008's usage rule 2.

## Next

**Blocked at the edge of authoritative story direction** — awaiting
the Chapter 6 Story Overview. (Spec 006's Ch6 architecture exists but
every chapter so far has been superseded in part by its overview, so
implementing Ch6 from architecture alone would risk redoing it.)
