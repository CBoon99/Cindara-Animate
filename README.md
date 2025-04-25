# Doppleit Animate
*A glitch-style 2D animation playground built entirely in a single file.*

## Overview

Doppleit Animate is a lightweight, in-browser 2D animation tool focused on providing a creative and intuitive animation experience with a unique glitch-style timeline control. Built entirely within a single HTML file (Doppleit-style!), it offers basic animation capabilities, state saving/loading, and evolving export tools.

## Features

* **Glitch-Enhanced UI:** A visually engaging interface with a subtle glitch effect on the logo, matching the Doppleit Suite aesthetic.
* **Canvas-Based Animation:** Real-time rendering on a clean, responsive canvas.
* **Interactive Timeline:** Scrub through the animation using a smooth slider synced to duration.
* **Playback Controls:** **Play**, **Pause**, and **Stop** with active state visuals.
* **FPS & Duration:** Adjustable **Frames Per Second** and total animation length.
* **Dark Mode:** Toggle between light/dark themes with Doppleit Suite gradients.
* **State Management:** Save/Load current state via `localStorage`, with toast feedback.
* **Undo/Redo Scaffold:** History tracking system scaffolded (full support in v1.3).
* **Export Tools:**
  * **Export JSON:** Download your current animation parameters.
  * **Embed Export (Coming Soon):** Generate a shareable HTML version of your animation.
* **Accessibility Enhancements:**
  * `title` attributes on buttons.
  * ARIA support on timeline slider.

## Built With

- HTML5
- CSS3
- JavaScript (Vanilla)

## Getting Started

1. **Download:** Save the `index.html` file to your local machine.
2. **Open in Browser:** Open the `index.html` file in any modern web browser.
3. Start animating — no setup required!

## Usage

- **Timeline:** Use the slider to scrub through your animation.
- **Playback:** Hit **Play** to animate, **Pause** to hold, **Stop** to reset.
- **FPS & Duration:** Adjust animation speed and length in real time.
- **Dark Mode:** Toggle on/off for light-sensitive environments.
- **State:** Use **Save** and **Load** for local state persistence.
- **Undo/Redo:** Step back and forward through recent changes (early implementation).
- **Export:** Download settings as JSON. Embed HTML export coming in v1.3.

## What's Next (v1.3+)

- Full Undo/Redo functionality with multi-step history.
- Keyframe support and basic animation curve editing.
- More drawing primitives and motion styles.
- Embeddable animated viewer (HTML export).
- Enhanced accessibility and mobile refinement.

## License

[Optional: Add license details here]

## Acknowledgements

- Inspired by the simplicity of in-browser tools.
- Uses `requestAnimationFrame` for smooth, hardware-synced animation.

---

Made with love by the Doppleit Suite team. 🧡  
[ doppleit-animate.netlify.app ] — live soon.
