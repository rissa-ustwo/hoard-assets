# hoard-assets

3D models for Hoard, loaded at runtime by the game.

| File | What it is |
|---|---|
| `models/dragon.glb` | Felt dragon, 2048px texture, 1 unit tall, standing on y = 0, facing +Z. From v4: two nodes, `Body` and its child `Head`, whose origin is the neck pivot, so the game can turn or nod the head |
| `models/dragon_rigged.glb` | Same dragon with an auto-generated rig (no animations) |
| `models/tree.glb` | Felt pine tree, static mesh, 1024px texture, 1 unit tall, standing on y = 0 (from v2) |
| `models/banner.glb` | Felt banner on a pole, static mesh, 1024px texture, 1 unit tall, standing on y = 0 (from v3) |
| `models/rock_tall.glb` | Painted cardboard rock, tall, static mesh, 1024px texture, 1 unit tall, standing on y = 0 (from v5) |
| `models/rock_short.glb` | Painted cardboard rock, low and wide, static mesh, 1024px texture, 1 unit wide, 0.69 tall, standing on y = 0 (from v5) |

Use a tagged link, e.g. `https://cdn.jsdelivr.net/gh/rissa-ustwo/hoard-assets@v1/models/dragon.glb`.
