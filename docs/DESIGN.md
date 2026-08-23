# Thread design

Implement against this file, not folklore.

## Identity

- Product: **Thread**
- Repo: `computerpets-thread`
- Idea: Pet Maze Escape
- Genre: Pathfinding puzzle
- Engine: Godot
- Surface: `Godot editor`

## Loop

Named after the mythic thread, not a stolen maze engine. Species instincts matter: frogs cut water tiles, pandas hug trees. You never possess the body — you are the architect.

## Play beats

- Daily maze seed.
- Place 8 tiles. Pet autowalks.
- Exit before patience ends.
- Par = treat. Fail = pet still home on overlay, just annoyed.

## Neighbors

- computerpets-lore
- computerpets-motion
- computerpets-sdk (custom tiles)
- computerpets (Daedalus2 is a sibling, not a dependency)

## Failure doctrine

No path → hint, not a freeze. AI loop → timeout and reset. Custom tiles cannot block exit permanently.

## Hard rules

1. Minigames cannot mint or burn NFTs by themselves (Minter is the write path).
2. Stats come from lived overlay care + Dojo caps, not cash shop.
3. Species kits stay inside Lore. Illegal hybrids never spawn.
4. Fail soft: the desktop overlay process is not this process.
