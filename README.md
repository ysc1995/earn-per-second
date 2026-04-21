# Earn Per Second

A dynamic wallpaper that shows you how much money you're earning in real time.

## Usage

### Browser
1. Open `index.html` in a browser
2. Enter your annual income (USD) and click **Start**
3. Money particles float up every second with a coin sound
4. Move your mouse to spawn particles at your cursor position

## Controls

| Control | Action |
|---|---|
| 🔊 button | Toggle sound on/off |
| Reset button | Return to the input screen |
| Mouse on screen | Particles spawn at cursor position |
| Mouse off screen | Particles spawn at random positions |

## How earnings are calculated

- **Per second** = Annual income ÷ (365 × 24 × 3600)
- **Earned today** = Seconds elapsed since midnight × per-second rate

## Files

| File | Purpose |
|---|---|
| `index.html` | Main app |
| `project.json` | Wallpaper Engine config |
| `*.mp3` | Coin sound effect |

## No dependencies

Pure HTML + CSS + JavaScript. No build step, no server required.
