# Fumble Up

> *A Foe is just a Friend, you haven't Fumbled yet.*

A casual 3D platformer party game featuring 1v1 split-screen, head-to-head vertical races to the top. Outwit, push, and jetpack your way past your opponent in a fast-paced arcade-style showdown built for friends, foes, and anyone who enjoys a good giggle with a competitive twist.

Built in Unreal Engine 5 by **Malteada Studio** for the *Theory and Practice of Game Design and Development (GAMED) 2025* course at Aalborg University Copenhagen.

📺 **Gameplay video:** https://www.youtube.com/watch?v=fpHoQKWUYk0

---

## Gameplay

Two players race vertically up a chaotic platforming course. First to the top wins. Along the way, players can use power-ups to gain an edge - or knock their rival off a ledge.

### Core mechanics

- **Vertical platforming** — jump and time your movement to scale the level
- **Jetpack boost** — temporary 10-second propulsion power-up for quick ascents
- **Push** — knock opponents off platforms for slapstick setbacks
- **Invisibility buff** — disappear briefly for tactical plays
- **Split-screen 1v1** — direct, head-to-head competition in real time

### Design pillars

- **Challenge** — timing and strategic movement
- **Uncertainty** — physics-based movement creates surprise outcomes
- **Humor** — failures and unexpected collisions create *funstration* (slapstick comedy you keep coming back to)

---

## Built with

- **Unreal Engine 5** — render engine, physics, audio, and Behavior Trees
- **Blueprint Visual Scripting** — gameplay logic, state management, and mechanics
- **Niagara / Particle Systems** — jetpack propulsion VFX
- Arcade controller support

---

## Repository structure

This repo has three branches:

| Branch | Contents |
| --- | --- |
| `main` | Zipped Windows build — easiest way to play |
| `build` | Unzipped build folder |
| `game` | Full Unreal project source (Blueprints, assets, levels) |

### Quick start (play the game)

1. Switch to the `main` branch.
2. Download and extract the Windows build zip.
3. Run the `.exe`.
4. Plug in two controllers (recommended) or use keyboard for both players.

### Open the project in Unreal Engine

1. Switch to the `game` branch.
2. Clone or download the project files.
3. Open the `.uproject` file with Unreal Engine 5.
4. Allow shaders to compile on first launch.

---

## Development approach

The project followed a **playcentric design philosophy** (Fullerton, 2019), prioritising the player experience throughout development.

1. **Paper prototyping** - quick sketches and mock-ups to test mechanics and UI before committing to digital implementation
2. **Flowcharts** - to design the system and player interactions
3. **Acting it out** - physically simulating mechanics like the jetpack to visualise the experience
4. **Iterative playtesting** - using the think-aloud method with peers, refining mechanics each cycle
5. **Digital production** - built and balanced in Unreal Engine 5
6. **Showcase playtesting** . final round of competitive playtesting at the GAMED Game Showcase

Key balancing decisions came directly from playtesting: platform spacing was adjusted, the jetpack was rebalanced as a 10-second power-up to act as a soft rubber-banding mechanism, and invisibility was tuned to add strategic depth without feeling unfair.

---

## Team — Malteada Studio

The name *Malteada* is Spanish for "milkshake" — a [purple cow](https://www.scottrogers.dev/) name suggesting whimsical, humorous, and fun games (Rogers, 2014).


## Asset credits

Environmental assets purchased from the FAB store:

- **Deep Elder Caves** — https://www.fab.com/listings/cea534a5-0440-426c-a372-d86c474276d2
- **Stylized Nature** — https://www.fab.com/listings/1c5fb915-5e6e-483d-bfaa-d6813c130b47

---

## Future work

Features we'd add given more time:

- Dynamic difficulty balancing / rubber-banding for skill differences between players
- Adjustable game length and level scale
- More levels and varied environments
- Customisable controls and colourblind-friendly onboarding for accessibility
- Standardised playtesting metrics (e.g. Schønau-Fog's continuation desire framework)

---

## Academic context

This project was developed for the **GAMED — Theory and Practice of Game Design and Development** course at the Department of Architecture, Design and Media Technology, Aalborg University Copenhagen.

### Key references

- Fullerton, T. *Game Design Workshop: A Playcentric Approach to Creating Innovative Games* (4th ed.). CRC Press.
- Rogers, S. *Level Up! The Guide to Great Video Game Design* (2nd ed.). John Wiley & Sons.
- Schønau-Fog, H. *The Player Engagement Process — An Exploration of Continuation Desire in Digital Games*.

---

## License
 
The original code, Blueprints, level design, and documentation in this repository are licensed under the **MIT License**.
 
**Third-party assets are excluded.** The environmental assets purchased from the FAB store (*Deep Elder Caves* and *Stylized Nature*) remain under their original FAB licensing terms and are **not** redistributable. Anyone forking or reusing this project must obtain their own valid FAB licences for these assets or remove them before redistribution.
