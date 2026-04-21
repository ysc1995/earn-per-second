# Money Flow

A dynamic wallpaper that shows you how much money you're earning in real time.

## Usage

1. Open `index.html` in a browser
2. Enter your annual income (USD)
3. Click **Start** — money particles float up every second, with a coin sound
4. Move your mouse anywhere on screen to spawn particles at your cursor
5. The center counter shows your total earnings for the current day, updated smoothly every frame

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

## No dependencies

Pure HTML + CSS + JavaScript. No build step, no server required — just open the file.
