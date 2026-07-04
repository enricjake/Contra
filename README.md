# CONTRA — Jungle Run & Gun

A browser-based tribute to Konami's classic 1987 run-and-gun **Contra**.

![CONTRA](https://img.shields.io/badge/-CONTRA-e84020?style=for-the-badge&logo=arcade&logoColor=white)
![HTML5 Canvas](https://img.shields.io/badge/HTML5-Canvas-e34c26?style=for-the-badge&logo=html5&logoColor=white)
![No Dependencies](https://img.shields.io/badge/No%20Dependencies-zero%20npm-green?style=for-the-badge)

## Play

Open `index.html` in any modern browser, or play online at:
**https://enricjake.github.io/Contra/**

## Controls

| Key | Action |
|-----|--------|
| Arrow Keys / WASD | Move & Aim |
| Space / W / Up | Jump |
| Z / J | Shoot |
| Down + S | Crouch (prone) |
| Up | Aim Up |
| Up + Left/Right | Aim Diagonal |
| P | Pause |
| Enter | Start / Continue |

## Features

- **8-directional aiming** — shoot up, down, diagonally, and in any direction while jumping or prone
- **5 weapon types**: Rifle (R), Machine Gun (M), Spread Gun (S), Laser (L), Fireball (F)
- **One-hit death** — authentic Contra difficulty; stay sharp or lose a life
- **3 lives** with respawn invincibility frames
- **Power-up capsules** — shoot flying capsules to reveal weapon upgrades
- **Enemy soldiers** that chase and shoot at the player
- **Turrets** that track and fire at the player
- **Multi-level platforms** — jungle ledges at varying heights for vertical combat
- **Side-scrolling camera** that follows the player through the jungle
- **3 stages** of increasing length
- **Parallax background** — distant mountains and layered jungle foliage
- **Screen shake & flash** effects on explosions and weapon pickups
- **High score** persistence via localStorage

## Weapons

| Code | Name | Description |
|------|------|-------------|
| R | Rifle | Default weapon — single shot, reliable |
| M | Machine Gun | Rapid fire rate |
| S | Spread Gun | 5-way fan shot — clears crowds |
| L | Laser | Long piercing beam — cuts through enemies |
| F | Fireball | Spiraling piercing projectile |

## Enemy Types

| Type | HP | Points | Description |
|------|-----|--------|-------------|
| Soldier | 1 | 100 | Runs toward player, fires periodically |
| Turret | 3 | 500 | Stationary, tracks and shoots at player |
| Capsule | 1 | 300 | Flies across screen, drops weapon power-up |

## Technical Details

- Pure HTML5 Canvas + vanilla JavaScript — zero dependencies
- Single `index.html` file
- 60 FPS game loop with `requestAnimationFrame`
- AABB collision detection
- Procedurally drawn pixel-art graphics (no external image assets)
- Parallax scrolling backgrounds
- Works on desktop browsers

---

## Disclaimer

**This is an unofficial fan project created purely for personal enjoyment and educational purposes.**

- **Contra** is a registered trademark of **Konami Digital Entertainment, Inc.**
- This project is **not affiliated with, endorsed by, sponsored by, or approved by Konami**
- No copyright infringement is intended
- This project is **free and non-commercial** — no revenue is generated
- All game logic, graphics, and code are **original implementations** drawn from scratch using HTML5 Canvas — no original Konami assets, sprites, or code are used
- The game design concept (side-scrolling run-and-gun shooter) is attributed to Konami's original 1987 arcade game
- This project exists solely as a personal tribute and coding exercise

If Konami or any rights holder wishes for this project to be removed, it will be taken down immediately.

## License

This project is released for personal/educational use only. Not for commercial distribution.
