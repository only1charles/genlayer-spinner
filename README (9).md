# GenLayer Spinner

An animated loading spinner designed for the GenLayer Portal, submitted for the [Design the GenLayer Spinner](https://portal.genlayer.foundation/mission/12) mission.

## Preview

Open `preview.html` in a browser to see the spinner on light and dark backgrounds at three sizes (24px, 48px, 96px).

## Design

- **Format:** self-contained SVG with embedded CSS animation, no dependencies
- **Colors:** built from GenLayer's official brand palette — Kinetic Cobalt (`#110FFF`) for the rotating arc and bracket, Success green (`#00FF66`) for the blinking cursor accent, Asphalt (`#606060`) at low opacity for the track
- **Identity:** the center mark echoes GenLayer's ">_" terminal bracket, with the underscore rendered as a blinking cursor to reinforce the "loading" motif
- **Loop:** smooth, infinite, eased arc animation combined with a rotating ring (no jank on start/stop)
- **Legibility:** tested down to 24px, holds up on both light and dark backgrounds

## Usage

Drop `genlayer-spinner.svg` directly into any HTML page:

```html
<img src="genlayer-spinner.svg" width="48" height="48" alt="Loading">
```

Or inline the SVG markup directly to allow the CSS animation to run without extra requests.

## Files

- `genlayer-spinner.svg` — the spinner, ready to use
- `preview.html` — a demo page showing the spinner on light/dark backgrounds at multiple sizes
