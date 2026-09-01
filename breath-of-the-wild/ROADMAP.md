# Great Plateau — Roadmap

What is left to build, in the order it should be built.
Tick items off as they land.

---

## Phase 1 — felt every second of play

- [ ] **1. Animation** — a real skeletal system with authored poses.
      Right now everything is rigid boxes rotating. This is the single biggest
      improvement per second of playtime, and every character, enemy, NPC and
      boss inherits it. It is also a foundation: building it later means
      redoing the work.
- [ ] **2. Art pass 2** — proper character, enemy and building models on top of
      that skeleton. Pairs naturally with #1; doing them together avoids
      modelling everything twice.
- [ ] **3. Music** — a real multi-instrument score with per-region themes.
      Cheap to build, and you hear it constantly.

## Phase 2 — the biggest missing chunk of actual game

- [ ] **4. Divine Beast interiors** — four dungeons with rotate and tilt
      mechanics, terminals and control units.
- [ ] **5. Blights** — four boss fights. The stat table already has them at
      800 HP each.
- [ ] **6. Hyrule Castle interior** — plus a proper Ganon fight inside it.

Roughly nine hours of new game content that does not exist today.

## Phase 3 — the moment the data arrives

- [ ] **7. Shrine layouts** from the rest of the shrine atlas.
      120 shrines are a huge share of playtime, so this is high value, but it
      is blocked on pasted data. It interrupts whatever is in progress the
      moment it lands.
- [ ] **8. Korok coordinates → terrain.** 900 more elevation anchors would
      largely close the gap between the 136 shrine anchors.

## Phase 4 — a world that feels inhabited

- [ ] **9. NPCs** with names, daily schedules, real conversations and quests.
- [ ] **10. Memories + Champion story.**
- [ ] **11. Side quests and shrine quests** (76 + 42).

## Phase 5 — depth, in descending value

- [ ] **12. Boss mechanics** — climb a Talus to its ore, the Hinox necklace,
      mounting a Lynel.
- [ ] **13. Missing enemies** — Skywatchers, Turrets, Cursed enemies,
      Master Kohga.
- [ ] **14. Weapon modifiers** — attack up, durability up, critical rolls.
- [ ] **15. Weather** — snow, fog, heat haze.
- [ ] **16. Trial of the Sword.**
- [ ] **17. Sheikah Sensor, Hero's Path, map stamps.**
- [ ] **18. Horse registration, horse gear, Epona.**
- [ ] **19. Lost Woods fog maze.**
- [ ] **20. Content density** — more of everything, everywhere.
- [ ] **21. Fishing** — held back deliberately; say the word and it goes in.

---

## Why this order

**Animation before art.** The skeleton determines what the models can be.
Reverse it and everything gets modelled twice.

**Dungeons before quests.** A dungeon is self-contained playable content.
Quests need NPCs to be interesting first.

**Shrine data is the highest value per unit of effort**, but waiting on it
would idle everything else, so it interrupts rather than blocks.

**The long tail goes last** because each item is small and independent. No
order dependency, so it is pure cleanup.

---

## What needs outside input

Everything above is self-contained except three items:

| Item | What is needed |
| --- | --- |
| #7 | The rest of the shrine atlas — it cut off partway through Lanayru. Roughly 87 shrines still need their real room layout and chest rewards. |
| #8 | Korok seed coordinates, a Hyrule heightmap, or coordinates for the towers, stables and villages. |
| #21 | A yes or a no on fishing. |

Optional: a side quest list would make #11 exact rather than reconstructed.
Voice acting stays text-to-speech — Nintendo's audio is not an option.

---

## Already done

The world uses Breath of the Wild's own coordinate system. All 136 shrines sit
at their real coordinates, and the terrain is anchored to their real altitudes
(mean error 26 m, none over 100 m). Region positions are derived from real
shrine centroids rather than estimates.

260 terrain sculpting passes · 120 shrines, 33 with their real mechanic and
rewards · 900 Korok seeds · four Divine Beasts · Calamity Ganon and Dark Beast
Ganon · 108 armour pieces placed where they are really found · 97 NPCs, shops
and rupees · 30 wild horses · four Great Fairies · the real enemy HP and damage
tables · the 1000-unit stamina wheel · a 24-minute day.
