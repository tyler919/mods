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

_Last updated: November 18, 2026_

---

## Colossal Quarry

**Out now: 2.2.0** (NeoForge, 1.21.1; the Forge file stays on 1.2.0; needs DecayPlay's Guidebooks). New in 2.2.0: an
in-game guidebook, the Colossal Quarry Handbook. You get it the first time you join a world. 36 pages in 6 chapters:
Start here takes you from the first casing to the first hole one step at a time, and every build and machine has a
guided page with what you need, numbered steps with a 3D view of the build, "Done when" and "If it doesn't work". Show
in world sets a see-through ghost of the build down in your world to build into: right blocks vanish, wrong ones glow
red, and a list says what's still missing. Hold G over any Colossal Quarry item to open its page. It replaces the
hold-W guides (Ponder), so Ponder and Flywheel are no longer inside the mod and the file is smaller. Worlds and
configs from 2.1, 2.0 and 1.x carry over.

**Planned: 3.0, the full rig**
- Bigger rigs: the Heavy Rig (7×7×7) and the Colossal Rig (9×9×9)
- Drill Heads that temper as they dig and grow into the next head
- Overdrive, kept cool with water
- Survey Scanner, and a Survey button that predicts the whole dig
- Dense Silo Casing (4× the space)
- Advancements and a full set of sounds
- A charge slot on the generators, and optional CC:Tweaked support

**Ideas from players**
- Seal the edges of the hole so water and lava outside can't flow in ([#3](https://github.com/tyler919/mods/issues/3))
- A rig a creeper can't blow up ([#3](https://github.com/tyler919/mods/issues/3))

## Colossal Furnace

**Out now: 1.4.1** (NeoForge 1.21.1, needs Jumbo Furnace). Tiers 1 to 5 and Tier 20, the Heart slot, lava straight
from tanks and pipes (at Tier 20 one bucket of lava smelts 1,500 items), and an optional Liquid Experience tank when
XP Works is installed. New in 1.4.1: the in-game Ponder guides are now included, so they work without Create: hover a
block and hold W. Also fixes the furnace's front staying dark when only a pipe feeds it lava.

**Being built: 1.5.0**
- An in-game guidebook that walks you through the Colossal Furnace step by step: the Fragment Mold, Jumbo Furnace
  Fragments, the 6×6×6 build (with a Show in world hologram to build into), input, fuel and output, lava from tanks and
  pipes, Tiers 2 to 5, the Heart, Tier 20 and the Liquid Experience tank. Hold G over any Colossal Furnace item to open
  its page. It replaces the Ponder guides. Needs DecayPlay's Guidebooks.

## XP Works

**Out now: 1.1.1** (NeoForge and Forge, 1.21.1). Liquid Experience, Experience Tanks that join into one big tank,
and the Experience Drain.

**Being built: 1.2.0**
- An in-game guidebook that walks you through XP Works step by step: Liquid Experience and its bucket, the Experience
  Tank and how tanks join into one big tank, and the Experience Drain. Hold G over any XP Works item to open its page.
  Needs DecayPlay's Guidebooks. NeoForge, 1.21.1 (the Forge file stays on 1.1.1).

## Colossal Apiary

**Out now: 1.1.1** (NeoForge 1.21.1, needs Productive Bees). In-game Ponder guides: hold W over a Colossal Apiary
block, and animated scenes show how to build the apiary (the inside stays empty), the bigger Tier II and Tier III
shells, bees in and ore out, and the upgrades. New in 1.1.1: the guides are now included, so they work without Create.

**Being built: 1.2.0**
- An in-game guidebook that walks you through the Colossal Apiary step by step: the 7×7×7 build (with a Show in world
  hologram to build into, and a size picker for the 9×9×9 and 11×11×11), bees in through the Bee Port, flowers in the
  Garden, ore out through the ports, and every upgrade. Hold G over any Colossal Apiary item to open its page. It
  replaces the Ponder guides (hold W), so Ponder and Flywheel are no longer inside the jar. Needs DecayPlay's Guidebooks
  and Productive Bees.

**Ideas**
- An AE2 output port
- A Yield VI "Swarm" tier
- Breeding inside the apiary
- A gene sampler

## Radio Works

**Out now: 1.0.1** (NeoForge 1.21.1). Smoother muffling through walls and real 3D sound.

**Being built: 1.0.2**
- An in-game guidebook that walks you through the Radio Console, speakers, stations, stream links, the music library
  and how walls change the sound. Needs DecayPlay's Guidebooks.

**Planned: 1.1**
- A Portable Radio
- AAC and HLS stations, so a lot more stations play
- A Forge version

**Ideas**
- Ogg Opus and FLAC stations

## Atomic Generation

**Out now: 0.1.0-m5** (NeoForge 1.21.1; a beta build on CurseForge): milestones 1 to 5 of Atomic Generation 1.0, "First
Criticality". Everything 0.1.0-m4 had (the real nuclear fuel cycle from uranium ore to fuel, radiation in sieverts with
shielding and contamination, the steam power side, the Chicago Pile, the research tree) plus **Magnox, the first power
reactor:** a graphite stack with fuel channels inside a steel pressure vessel, natural uranium in Magnox cans, CO2 pushed
through it by gas circulators and out through gas ducts to the boilers, steam to the turbine, FE out (about 3,000 FE/t net
from a 9-across core). Run it like an operator: rods out a notch at a time, the Doppler effect levels the power, xenon
builds for the first half hour, trips and SCRAM. Refuelling while it runs, one channel at a time; elements keep their
burnup, plutonium and decay heat. Spent fuel: a pool (water shields and cools it; Magnox cans corrode under water and leak
caesium-137), a dry cask, and a fuel transfer crane on rails that carries it. New research logs on the Magnox controller
(hours at power, a refuelling cycle, a restart through a xenon pit, a clean SCRAM); the RBMK's design will need two of
them. Also the pile settles in minutes of play and the recorder logs one first criticality a pile. Worlds from 0.1.0-m4
carry forward, a running pile included.

## DecayPlay's Guidebooks

**Out now: 1.0.0** (NeoForge 1.21.1, NeoForge 21.1.200 or newer, on both client and server; JEI is optional). The
first release of the guidebook library for DecayPlay's mods: one separate mod that the CurseForge app installs for you.
On its own it adds nothing; each mod brings its own book. **Guided pages:** what you need with a live count from your
inventory, numbered steps that tick themselves off, done when, if it doesn't work, and "What do I do next?" on the first
page. Search, bookmarks, back and forward; the book remembers your page. Pictures, and 3D views of blocks, items, mobs
and whole builds: one layer at a time, building up block by block, in each size, with the list of what it takes. Recipes
on the page, with "View in JEI" when JEI is installed. **Show in world:** a hologram of a build to build against. Right
blocks vanish, wrong blocks glow red, a list shows what is missing, and "Build complete" ticks the step. Hold G over an
item to open its page. Each mod's book is given on first join and has a cheap recipe. Resource packs can change any page.

**Planned: 1.1**
- Show in world also checks which way a block faces. Today the hologram checks which block you placed, not its
  direction, so a furnace or a controller put in facing the wrong way still counts as right. Where a build needs a
  block to face a certain way, the hologram will check that too.

## Living Roads

**On hold for now.** A brand new mod: roads between villages that grow as you play, built by a new Road Builder villager. It will come back later.
