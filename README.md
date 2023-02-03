# RVP-Test-Builds
## Introduction
RVP is a mispelled acronym of a game idea which I refer to as "Reverse Vampire Survivors" but the right definition of it would be is : "It is a  cookie clicker rogue-like". This repo contains the test builds and proof of concepts before I go into production with my game.

Builds in V0.01 branch are all abstraction builds meant to explore the systems and features which might make it to the prototype later.

## Build V0.01.2
- Updated UI for better visual hierarchy and readbility.
- Swapped out health text with a health bar for a bit more visual juice.
- Added a console log instead of changing text to make incoming data more readable.
- Some more balancing to make player death a possibility.
- Reduced the probability of finding health potions from 16% to 10%.

## Build V0.01.1
- Updated some aspects of UI.
- Added exp bar for some visuals.
- Flattened out the scaling curves for player and enemy to test for new balance.
- Fixed bug twhere the slider value didn't rightly scale enemy level.

## Build V0.01.0
- Player UI with buttons for spawning, automating spawns and buying upgrades.
- Text to inform player of what's going on.
- Added GUI text for player health.
- Added GUI text to display play time.
- Added GUI text to display character stats.
- Added GUI text to display enemy stats.
- Added GUI text to log updates.
- Added a slider to adjust enemy's current level.
- Using a linear curve that is an additive of current level(both for player and enemy).
