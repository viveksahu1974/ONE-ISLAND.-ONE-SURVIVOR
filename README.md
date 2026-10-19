# ONE ISLAND. ONE SURVIVOR.

## EMBER DROP — browser battle royale

A free, original 2D top-down solo survival game against bots. Built with HTML, CSS, and vanilla JavaScript. No installation, backend, API keys, or build step required.

### Play

Current hosted game: https://ember-drop-arena-vivek.foggyjelly2.chatgpt.site

The hosted Site currently requires the owner's access. To run your own copy, download this repository and open `index.html`, or serve the folder with `python -m http.server 8000` and visit http://localhost:8000.

### Three modes and maps

| Mode | Map | Bots | Enemy HP | Storm delay |
| --- | --- | --- | --- | --- |
| Easy | Emerald Island (forest) | 10 | 70 | 30 seconds |
| Medium | Dust Canyon (desert compounds) | 18 | 130 | 20 seconds |
| Hard | Iron District (city streets) | 26 | 200 | 10 seconds |

Enemy damage, accuracy, speed, firing rate, loot supply, and storm speed vary by mode. Select a mode before deploying; use Change Mode / Map from the pause or results screen to return to selection.

### Features

- Titan tank with 50% protection from enemy bullets
- 500 player HP; medkits restore up to 150 HP
- Cannon: 120 area damage; rifle: 55 damage
- 60-round magazine and 360 reserve ammunition at spawn
- Shrinking safe zone, pickups, minimap, sound toggle, pause, victory and replay
- Mobile joystick and fire controls with automatic aiming

### Controls

| Action | Control |
| --- | --- |
| Move | WASD / arrow keys |
| Aim / fire | Mouse / left click |
| Tank / rifle | T or screen button |
| Reload | R |
| Heal | E |
| Sprint on foot | Shift |
| Pause | Escape |

### Files

- `index.html`: interface and mode selection
- `style.css`: responsive styling
- `game.js`: map generation, rendering, combat, bots, and match logic

Google Fonts are optional; system font fallbacks are provided. This is a solo prototype, not online multiplayer. It is an original game inspired by the battle royale genre and is not affiliated with Garena or Free Fire.

### GitHub Pages

To host this repository on GitHub Pages, select **Settings → Pages → Deploy from a branch → main → / (root)**. GitHub Pages is not enabled by merely uploading these files.

### Verification

JavaScript syntax and simulated logic checks passed for all three modes, including spawning, armor/damage, storm timing, reload, healing, pause, mode changes, restart, victory and defeat. Live browser visual testing has not been completed.
