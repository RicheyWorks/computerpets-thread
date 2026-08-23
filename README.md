# Thread

**Pet Maze Escape** — Puzzle: guide a lost pet home. You shape the maze; their AI walks it.

Part of the [ComputerPets](https://github.com/RicheyWorks/computerpets) universe. Map: [computerpets-ecosystem](https://github.com/RicheyWorks/computerpets-ecosystem).

> Status: **design scaffold**. Gameplay contract is frozen. Engine choice is the one in the brief. Implementation comes next.

## Loop

Named after the mythic thread, not a stolen maze engine. Species instincts matter: frogs cut water tiles, pandas hug trees. You never possess the body — you are the architect.

## Genre & engine

- Genre: **Pathfinding puzzle**
- Engine: **Godot**
- Stack: Godot 4 · A* / flow fields · you paint walls, pet instincts bias the path
- Default surface: `Godot editor`

## How you play

1. Daily maze seed.
2. Place 8 tiles. Pet autowalks.
3. Exit before patience ends.
4. Par = treat. Fail = pet still home on overlay, just annoyed.

## Talks to

- computerpets-lore
- computerpets-motion
- computerpets-sdk (custom tiles)
- computerpets (Daedalus2 is a sibling, not a dependency)

## Failure doctrine

No path → hint, not a freeze. AI loop → timeout and reset. Custom tiles cannot block exit permanently.

Canon rules that never yield:

- 210 living kinds. No illegal hybrids.
- Overlay pets can get tired, sick, or hide. Tokens are not burned by a minigame.
- Desktop walk stays the main quest. Closing Thread must leave Rui walking.

## Layout

```
computerpets-thread/
  README.md
  LICENSE
  docs/DESIGN.md
  src/                implementation lands here
```

## Run (Windows)

```powershell
godot --path . ; F5
```

Meet Rui first via the [flagship start-here](https://github.com/RicheyWorks/computerpets/blob/main/docs/START-HERE.md). This game is optional.

## License

MIT. See [LICENSE](LICENSE).

---

*Two hundred ten living kinds. Keep them so a line does not go quiet.*
