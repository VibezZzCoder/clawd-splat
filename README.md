# Clawd Splat

`Clawd Splat` is a small, single-file browser game prototype. Open
`index.html` in a browser and play a turf-war match with orange and teal teams —
out-paint your rivals before the timer hits zero. Everything (graphics, particles,
music, and sound) is generated at runtime on an HTML canvas with the Web Audio API.

## Play

- https://vibezzzcoder.github.io/clawd-splat/
- Modes: Desktop 1P vs CPU or local 2P; Mobile 1P vs CPU.
- Goal: cover more of the arena floor in your team's ink than the other team
  before time runs out. Splatting an opponent sends them back to spawn.
- Runtime: self-contained `index.html`, no external scripts, CDNs, images,
  audio files, or build step. Progress (lifetime record + badges) is saved
  locally in your browser via `localStorage`.

## Controls

- Player 1: `WASD` to move, mouse aim + click (or `Space`) to fire, `Shift` to
  submerge/swim in your own ink (faster movement + ink recharge).
- Player 2 (local 2P): Arrow keys to move, `/` `.` or `Enter` to fire, `Ctrl` to
  submerge.
- Mobile: on-screen joystick to move, fire/swim touch controls.
- Hold fire at a full ink tank to charge a **Super Splat** heavy shot.

## Match Setup

- Weapon classes: Blaster (balanced), Spreader (wide spray), Charger (long-range
  line), Roller (melee paint roller).
- Difficulty: Easy / Medium / Hard CPU.
- Arenas: Pillars (classic), Ring (moving walls), Split (conveyor belts).
- Timer: 60 / 90 / 120 seconds.

## License

The game code is released under the MIT License. See `LICENSE`.

See `NOTICE.md` for fan-project, third-party rights, and non-affiliation
notices. This is an independent, unofficial fan project and is not affiliated
with, endorsed by, sponsored by, approved by, or otherwise associated with
Anthropic, Claude, OpenAI, Nintendo, or any other third-party rights holder.
