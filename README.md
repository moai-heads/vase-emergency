# Vase Emergency — First-Person Shard Repair

A small browser-based 3D physics game: walk through a workshop, find loose curved ceramic shards, carry them to the growing vase, and manually fit a matching broken seam. Press **E** only when the actual chipped edges line up. A successful fuse joins the shard to the vase with a physics constraint; it does not snap or teleport into place. Dropped shards tumble and collide. There are no ghost outlines, target slots, or piece suggestions.

## Play

Open the [GitHub Pages game](https://moai-heads.github.io/vase-emergency/) or serve this folder over HTTP.

## Controls

- **WASD** — walk; **mouse** — look around
- **Left click** — pick up / drop a shard
- **Hold right click + mouse** — rotate the held shard in pitch and yaw
- **Z / C** — roll the held shard
- **Shift + hold right click + mouse** — move the held shard sideways / up and down
- **Mouse wheel** — move the shard farther away or closer
- **E** — fuse only when a real neighboring broken edge fits
- **Shift** — sprint

Choose 10, 50, 100, 200, 500, or 1,000 shards. The Three.js and Rapier runtimes are included locally, so gameplay does not depend on third-party CDNs.
