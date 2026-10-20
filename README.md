# Override: Facility 9

A retro first-person shooter built entirely in a single HTML file (vanilla JS + Canvas). No dependencies, no build step — just open it and play.

**Play live:** [Open the game](https://meliapatrick214-jpg.github.io/override-facility-9/)  
*(GitHub Pages will be available shortly after the first push.)*

## Story

A rogue ASI has seized Facility 9. Shut down its robots and clear the station.

## Controls

### Desktop / Keyboard
| Action | Key / Input |
|--------|-------------|
| Move | `W` `A` `S` `D` or Arrow keys |
| Look / Turn | Mouse or Arrow Left/Right |
| Fire | Left Click, `Space`, `Ctrl`, or `Enter` |
| Switch weapon | `1` (Blaster) / `2` (Scatter Gun) |
| Run | `Shift` |
| Toggle minimap | `M` |
| Start / Retry | Click or `Enter` |

### TV Remote (Rocky TV, Android TV, Fire TV, Google TV, Roku, etc.)
| Action | Remote Button |
|--------|---------------|
| Move forward / back | D-Pad **Up** / **Down** |
| Turn left / right | D-Pad **Left** / **Right** |
| Fire | **OK / Select / Enter** (center button) |
| Switch weapon | Number keys `1` / `2` (if available) |
| Toggle minimap | `M` or Info |
| Start / Retry | **OK / Enter** |

The game auto-detects TV environments and shows the matching on-screen instructions.

### Gamepad / Bluetooth Controllers (including many TIC-style remotes)
- Left stick or D-pad → move
- Right stick → look / turn
- A / Cross / R2 → fire
- L1 / R1 → switch weapon
- L2 → run
- Start → begin / retry

### Touch / Mobile
- Left side of screen → move
- Right side of screen → look
- **FIRE** button → shoot
- **GUN** button → switch weapons

## Features

- Classic raycasting engine (Wolfenstein / Doom style)
- Procedural wall, floor & ceiling textures
- Animated robot enemies (walk, attack, pain, death poses)
- Two weapons: rapid-fire Blaster + wide Scatter Gun
- Health packs, ammo cells, and weapon pickup
- Enemy projectiles
- Dynamic lighting & screen flash effects
- Minimap
- Web Audio SFX + procedural background music
- Title, death, and victory screens
- Fully playable on desktop, mobile, **and smart TVs with remote**

## How to run locally

Just open `index.html` in any modern browser.  
No server required (though some browsers restrict `file://` audio — a simple local server works best).

```bash
# Optional quick local server
python -m http.server 8000
# then visit http://localhost:8000
```

## License

Free to play, share, and modify. Have fun clearing Facility 9.
