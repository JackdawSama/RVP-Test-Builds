# RVP-Test-Builds
## Introduction
RVP is a mispelled acronym of a game idea which I refer to as "Reverse Vampire Survivors" but the right definition of it would be is : "It is a  cookie clicker rogue-like". This repo contains the test builds and proof of concepts before I go into production with my game.

Builds in V0.01 branch are all abstraction builds meant to explore the systems and features which might make it to the prototype later.

## Note
Check branches for builds and their details.

### Notes on the Current State
The project is currently called Souls++ and that's how it'll be referred to throughout from here onwards until I choose to change the title again.

## Build V0.5.0
This is a feature complete build and later additions would be extremely minor features that won't largely affect gameplay but only add to it.

### Current Features
- Auto-attacking Avatar
- Spawn button to spawn waves
- Automation to automate spawning
- Avatar respawn button
- Avatar corruption
- Corrupted Avatar spawning for a mini-boss fight

### Changes from V0.01.2
- UI set up largely remained the same except for the addition of the play area which visualises the avatar vs player units combat.
- The corruption system and avatar respawn has been put in place
- New scaling curves as it is no longer one unit vs avatar but many units vs avatar
- Spawn Button cooldown added
- Spawn Button cooldown displayed
- Auto-attacking visualised
- Enemy spawner imeplemented
- Enemy spawning made more organic so units spawned swarms avatar from all sides instead of set spawn points that are cycled(for more info on this check Wiki)

### Known Bugs
- After the avatar gets corrupted or dies the respawn of avatar requires hitting the respawn avatar button twice instead of once. Still debugging this. 
- The spawned corrupted unit fails to pull refernce from the previous avatar and set its stats, also fails to take damage and die after its HP is depleted.
