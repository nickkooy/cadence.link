---
title: "Known Issues"
menu:
  main:
    parent: "general"
    weight: 20
---

A list of issues that are good to be aware of as they might result in softlocks, crashes or unexpected behaviour.

## Ganon & Shrine of Peace Softlock

Activating Shrine of Peace in Future Hyrule Castle will currently break the ice block logic in the Ganon fight, preventing you from finishing the fight as intended.
This is caused by the Shrine of Peace incorrectly downgrading the hitbox entity into a skulltula cocoon.
If this glitch is in effect when you start the fight you'll see spiderweb graphics by the characters feet inside the ice blocks.

To fix this you will have to deactivate the shrine. This can be done by saving and quitting, luting, or dying.

## Fire Keese & Glass Flail Crash

I'm pretty sure this still crashes the game in some situations? Does not always happen, not sure about specifics.
Does it apply to other keese as well?

## Unreliable Permadeath Leaderboards

There is a glitch which allows one to submit any character (even co-op), to any permadeath leaderboard, making the boards unreliable for now.
As an example, it's possible to submit a PD co-op barrier skip run to the single player PD story mode board.
This also applies to Dungeon Mode.

## Infinite Bounce Trap Crash

If two bounce traps are facing each other, attempting to step onto one crashes the game instantly as it moves you back and forth infinitely, trying to figure out where to place you.
