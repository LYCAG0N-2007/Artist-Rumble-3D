# Artist-Rumble-3D
Artist Rumble 3D: a rhythm-based 3D arcade fighting game that runs in a single HTML file. 12 musician fighters, combos, parries, combo breakers and cinematic special moves. Built with Three.js.  Topics: game fighting-game threejs webgl javascript html5-game browser-game rhythm-game arcade single-file
# Artist Rumble 3D 🎤

A 3D rhythm-fighting arcade game that runs in your browser from a single HTML file. Pick a headliner, land hits on the beat, and win best of three rounds on a neon concert stage.

## Features

- **12 original fighters**, each with their own look and special move (shockwave, beam, rush, spin, slam, note barrage, skyfall columns and more)
- **Beat system:** hits landed on the beat deal +25% damage while the stage lights, crowd and LED wall pulse with the music
- **Combos:** a 3-hit jab chain ending in an uppercut, plus a roundhouse finisher
- **Ways to break free of combos:**
  - **Parry:** tap guard just before a hit lands to stun the attacker
  - **Counter strike:** block, then press jab or kick
  - **Combo breaker:** press Shift while being hit (costs 40 guard, 2s cooldown)
- **Knockdowns:** tumbling falls, bounces and get-up animations after finishers and specials
- **Cinematic specials:** slow-motion, speed lines, charge-up effects and screen shake
- **Modes:** VS CPU (Easy, Normal, Hard) or 2 players on one keyboard
- **Controls for everyone:** keyboard, touch buttons for phones and tablets, gamepad support
- **Accessibility:** an Effects toggle that reduces flashes and camera shake

## Play

Open `Artist_Rumble_3D.html` in a modern browser. No build step or install.
An internet connection is needed to load Three.js and fonts from a CDN.

## Controls

| Action | Player 1 | Player 2 |
|---|---|---|
| Move / dash | A D (tap twice to dash) | Arrow keys |
| Jump / guard | W / S | Up / Down |
| Jab / Kick | J / K | , / . |
| Special (full hype) | L | / |
| Combo breaker | Shift | Right Shift |

Gamepad: stick or d-pad to move, X jab, A kick, Y special, B break.
Pause with Esc.

## Tech

- Three.js (r128), WebGL, plain JavaScript
- Procedural fighters, stage and crowd (no external assets)
- Web Audio API for music and sound effects, all synthesized in code

## Roadmap

- Online play
- Arcade mode with a boss
- Training mode with hitbox display
- Unique move sets per fighter and more stages
- Key remapping and replays
