# DecayPlay's mods: roadmap

What's out, what's next and what's planned for each of my Minecraft mods. There are no dates: an update comes out
when it's built and tested.

Want something on this list? **[Post an idea](https://github.com/tyler919/mods/issues/new/choose)**, or give an
existing one a 👍. I look at the 👍 counts when I pick what goes in the next update.

| Word | Means |
|---|---|
| **Out now** | On CurseForge |
| **Being built** | Being made right now, for the next update |
| **Planned** | Decided, coming in a later update |
| **Ideas** | Being considered, not promised yet |

**Prefer clicking around?** The same roadmap is an [interactive board](https://github.com/users/tyler919/projects/2), with a tab for each mod.

**Want a ping when a mod updates?** Join [DecayPlay's Workshop on Discord](https://discord.gg/y6z5GpgBcr).

_Last updated: November 14, 2026_

---

## Colossal Quarry

**Out now: 2.1.0** (NeoForge, 1.21.1; the Forge file stays on 1.2.0; a beta build on CurseForge). The Pump drains a
whole lake in one trip: the first time the dig reaches a lake, a flooded cave or an aquifer, the pump head goes straight
down to the deepest spot and drains every source of that fluid joined to it, up to 32 blocks past the dig area (loaded
chunks only, never on protected land). The lake's lower layers get no more trips; water and lava on one layer are one
trip, a tank each; an ocean is still pumped a layer at a time. The quarry rechecks its hole every time it loads: gravel
that fell in, blocks placed in the hole and water that came back are dug first, then it carries on from where it was; a
finished rig does it too while its frame stands. Fixed: with the Extra Drills Upgrade a reload could end the dig early
and leave blocks behind, and a running rig with a Size upgrade came back from a world load stopped. Worlds from 2.0 and
1.x carry over.

**Planned: 3.0, the full rig**
- Bigger rigs: the Heavy Rig (7×7×7) and the Colossal Rig (9×9×9)
- Drill Heads that temper as they dig and grow into the next head
- Overdrive, kept cool with water
- Survey Scanner, and a Survey button that predicts the whole dig
- Dense Silo Casing (4× the space)
- Field Manual (an in-game guide book), advancements and a full set of sounds
- A charge slot on the generators, and optional CC:Tweaked support

**Ideas from players**
- Seal the edges of the hole so water and lava outside can't flow in ([#3](https://github.com/tyler919/mods/issues/3))
- A rig a creeper can't blow up ([#3](https://github.com/tyler919/mods/issues/3))

## Colossal Furnace

**Out now: 1.4.1** (NeoForge 1.21.1, needs Jumbo Furnace). Tiers 1 to 5 and Tier 20, the Heart slot, lava straight
from tanks and pipes (at Tier 20 one bucket of lava smelts 1,500 items), and an optional Liquid Experience tank when
XP Works is installed. New in 1.4.1: the in-game Ponder guides are now included, so they work without Create: hover a
block and hold W. Also fixes the furnace's front staying dark when only a pipe feeds it lava.

## XP Works

**Out now: 1.1.1** (NeoForge and Forge, 1.21.1). Liquid Experience, Experience Tanks that join into one big tank,
and the Experience Drain.

Nothing picked for the next update yet. Ideas welcome!

## Colossal Apiary

**Out now: 1.1.1** (NeoForge 1.21.1, needs Productive Bees). In-game Ponder guides: hold W over a Colossal Apiary
block, and animated scenes show how to build the apiary (the inside stays empty), the bigger Tier II and Tier III
shells, bees in and ore out, and the upgrades. New in 1.1.1: the guides are now included, so they work without Create.

**Ideas**
- An AE2 output port
- A Yield VI "Swarm" tier
- Breeding inside the apiary
- A gene sampler
- A guide book

## Radio Works

**Out now: 1.0.1** (NeoForge 1.21.1). Smoother muffling through walls and real 3D sound.

**Planned: 1.1**
- A Portable Radio
- AAC and HLS stations, so a lot more stations play
- A Forge version

**Ideas**
- Ogg Opus and FLAC stations

## Atomic Generation

**Out now: 0.1.0-m4** (NeoForge 1.21.1), an early beta: milestones 1 to 4 of Atomic Generation 1.0, "First
Criticality". The real nuclear fuel cycle, from uranium ore to a reactor going critical: 20 ores, radiation in sieverts
with shielding and contamination, a Geiger counter and hazmat gear; pipes with a real temperature and pressure; the
whole fuel front end, from ore through centrifuge enrichment to fuel (every gram of U-235 accounted for); the steam
power side, with a multiblock turbine, a cooling tower and an emergency diesel; and the first reactor, the Chicago
Pile: build it your own way from graphite and uranium, approach critical with a neutron source and a counter, and
control it with cadmium rods and a zip rod. Also a research tree: the pile's logs unlock the next reactors' designs.
No power reactor yet: the pile makes no power. Worlds carry forward to the next betas.

**Being built: 0.1.0-m5, Magnox, the first power reactor.** A graphite stack with fuel channels inside a steel pressure
vessel, CO2 pushed through it by gas circulators, out through gas ducts to boilers, steam to the turbine, FE out.
Refuelling while it runs, one channel at a time. Spent fuel: a pool (water shields and cools it; Magnox cans corrode in
it), a dry cask, and a fuel transfer crane that carries it. New research logs (hours at power, a refuelling cycle, a
restart through a xenon pit, a clean SCRAM); the RBMK's design will need two of them. Also the pile settles in minutes and
the recorder logs one first criticality a pile.

## Living Roads

**Coming soon.** A brand new mod: roads between villages that grow as you play, built by a new Road Builder villager.
